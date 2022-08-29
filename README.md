<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** github_username, repo_name, twitter_handle, email, project_title, project_description
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/maragraziani/miccaihackathon_shifts">
    <img src="images/logo.jpeg" alt="Logo" width="800">
  </a>

  <h3 align="center">Domain Shifts Between Clinical Annotators</h3>

  <p align="center">
    Task 1 at the MICCAI Hackathon 2022
    <br />
    Mentored by: »
    <a href="mailto:mara.graziani@hevs.ch">Mara Graziani</a>
    &
    <a href="mailto:henning.mueller@hevs.ch">Henning Müller</a>
  </p>
</p>

<!-- ABOUT THE PROJECT -->
## Task Overview

Medical imaging datasets are known to be highly heterogeneous, being often collected at multiple institutions and resulting in so-called domain-shifts between institutions. At the level of manual segmentations, annotators trained in one institution may follow slightly different annotation procedures, e.g. over- and under-segmenting, and this may bias the learning process. 

In this task, you will investigate the domain shifts in white matter (WM) lesion segmentation:
<ol>
<li> Discuss, identify and quantify the impact of *multiple sources of shift* within the multiple sclerosis dataset of WM lesions in the Shifts 2.0 publicly available [dataset](https://shifts.ai/dataset#white-matter-multiple-sclerosis-lesion-segmentation).
<li>Quantify the impact of multiple annotators as opposed to a single annotator in terms of model uncertainty. How does model uncertainty vary against the number of annotations considered to create the “golden reference”? Does the uncertainty decrease if more annotators are used?
<li>How many annotators in the given dataset over-segment the “golden reference”? How many undersegment? What is the observed bias introduced by each of the annotators?
 
## About the Shifts Project and the Upcoming Shifts 2.0 Challenge 
 
  The [Shifts Project](https://shifts.ai) is an international collaboration of academic and industrial researchers dedicated to studying distributional shift — one of the biggest challenges in applying machine learning to high-stakes real-world tasks.
   A second iteration of the [Shifts Challenge](https://shifts.ai/challenges) is foreseen very soon. The competition will consist of two new tracks, each corresponding to a high-risk application affected by distributional shift: marine cargo vessel power estimation and White Matter Multiple Sclerosis lesion segmentation in 3D Magnetic Resonance Imaging of the brain. Both tasks are strongly affected by distributional shift and have strict requirements on robustness. Furthermore, both applications are socially relevant: the former in terms of lowering carbon emissions of supply chains and the latter in terms of alleviating a widespread, incurable and degenerative illness.

<!-- GETTING STARTED -->
# Getting Started
 
## Dependencies

* [Python 3.8](www.python.org)
* [PyTorch 1.12.0](www.pytorch.org)
* [Monai 0.9.0](www.monai.io)

### Baseline Models Repo and Installation
  
  T
 https://github.com/Shifts-Project/shifts/tree/main/mswml
  
This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/github_username/repo_name/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* []()
* []()
* []()





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/maragraziani/miccaihackathon_shifts.svg?style=for-the-badge
[contributors-url]: https://github.com/maragraziani/miccaihackathon_shifts/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/maragraziani/miccaihackathon_shifts.svg?style=for-the-badge
[forks-url]: https://github.com/maragraziani/miccaihackathon_shifts/network/members
[stars-shield]: https://img.shields.io/github/stars/maragraziani/miccaihackathon_shifts.svg?style=for-the-badge
[stars-url]: https://github.com/maragraziani/miccaihackathon_shifts/stargazers
[issues-shield]: https://img.shields.io/github/issues/maragraziani/miccaihackathon_shifts.svg?style=for-the-badge
[issues-url]: https://github.com/maragraziani/miccaihackathon_shifts/issues
[license-shield]: https://img.shields.io/github/license/maragraziani/miccaihackathon_shifts.svg?style=for-the-badge
[license-url]: https://github.com/maragraziani/miccaihackathon_shifts/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/mara-graziani-878980105/
