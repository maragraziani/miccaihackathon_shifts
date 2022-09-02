# Data Access and File Structure

The full dataset of Shifts 2.0 Track 1 on Multiple Sclerosis lesion segmentation can be used for this Track. The data can be accessed upon completion of this [form](https://forms.gle/3n2tkYQcW18Z3f5i7), which includes a Data User Agreement to ensure the privacy protection and compliance of the data sharing to the requirements set by some of our data providers. 

<strong>[! IMPORTANT] You can only obtain the data for this track if you successfully fill in the Data User Agreement. Please follow  the instructions reported in the [form](https://forms.gle/3n2tkYQcW18Z3f5i7). After our  approval of your request, you will be granted access to the data download page.</strong>

The dataset includes the following datasets:
<ul>
<li>MSSEG  [Commowick et al., 2018],
<li>ISBI  [Carass et al., 2017],
<li>PubMRI  [Lesjak et al., 2017]
<li>Lausanne (private, not released for privacy reasons), provided by the Swiss universities of Lausanne and Basel
</ul>

In the specific content of the hackathon, you will be working with the annotated subset of the MSSEG collection. 

## Sign the DUA
A DUA is a Data Use Agreement. This is required under the Privacy Rule to work with the MSSEG data and must be accepted before we can provide you with any portion of the dataset. To accept the DUA you can follow the instructions in the [Zenodo](#), providing your 
<ul>
<li> Full Name
<li> Affiliation 
<li> institutional email address 
</ul>

We will verify the validity of the information and, after our approval, you will be redirected to the data download link. 

## File Structure

In the dataset, there are separate directories for each location of the the scanners (one source of shift):
- best
- msseg (consists of multiple locations including lyon, bordeaux and rennes)
- ljubljana

Within each of these directory, the data is split according to the canonical partitioning for the Shifts 2.0 challenge. Splits must be one of the following:
- train
- dev_in
- dev_out
- eval_in

Within each of the canonical splits, the following images are provided - note, not all locations have all the modalities:
- flair: FLAIR modality input images 
- t1: T1 modality input images
- pd: Proton Density (PD) weighted input images
- t2: T2 modaility inputi images
- t1ce: T1 contrast enhanced modaility (enhancement due to Gadolinium injection) 
- gt: The ground-truth masks to identify locations of lesion voxels
- fg_mask: The foreground masks to identify the brain area (i.e. necesaary for calculation error retention curves in only the brain area)

<strong> The MSSEG directory contains the data that you need to participate to the hackathon task, namely the annotations of 7 individual annotators.</strong> These files were used to generate a consensus map (by majority voting) used as the golden reference in our baseline model. Note that in the Best directory of the repo there are also two individual annotators (one more experienced than the other). The golden reference is in this case the expert annotator. 

