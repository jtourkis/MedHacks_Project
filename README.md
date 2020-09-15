
  [![MIT License][license-shield]][license-url]
  [![LinkedIn][linkedin-shield]][linkedin-url]

<br />

<p align="center">
  <a href="https://github.com/jtourkis/MedHacks_Project">
    <img src="logo.png" alt="AB" width="800" height="300" style="border:5px solid black">
  </a>
 
  <p align="center">
  <h3 align="center">John Hopkins MedHacks Project</h3>
    <b>Goal:</b> The project aggregates average cost data from 300 individual CA OSHPD hospital submissions of 25 medical procedures, cleans that data, and uses Tableau to visualize data in an easy to navigate format.
    <br />
    <a href="https://github.com/jtourkis/MedHacks_Project"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/jtourkis/MedHacks_Project">View Demo</a>
    ·
    <a href="https://github.com/jtourkis/MedHacks_Project/issues">Report Bug</a>
    ·
    <a href="https://github.com/jtourkis/MedHacks_Project/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

Project uses CA OSHPD data w/ avg charge for 25 common hospital outpatient procedures under AB 1045. Avg charge incl. all related services and procedures (e.g., supplies, drugs, lab, use of operating room, etc.).

### Built With

* [Python](https://www.python.org) / [Jupyter Notebook](https://jupyter.org)


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

List of required packages.

* pandas



### Installation
 
1. Clone the repo

```sh
git clone https://github.com/jtourkis/MedHacks_Project.git
```
2. Install packages
```sh
pip install package
```


<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

**Goal:** Our team compiled 2019 common hospital procedure average cost information submitted to California's OSHPD into a single dataset. This code attempts to systematically clean the cost information.

**Main Challenges Overcome:**

1) Hospitals submitted data in different formats. Some observations included: $ , ; - etc
2) Some hospitals included more than one value per cell
3) Some hospitals included cents and some did not. Since working with strings, we have to be cautious not lose this information



See the [open issues](https://github.com/github_username/repo/issues) for a list of proposed features (and known issues).



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

Note: The intial README Template was distributed under the MIT License. Copyright (c) 2018 Othneil Drew. [LICENSE](https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt)  for more information. 



<!-- CONTACT -->
## Contact

James Tourkistas - jmtourkistas@suffolk.edu

Project Link: [https://github.com/jtourkis/MedHacks_Project](https://github.com/jtourkis/MedHacks_Project)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Best-README-Template](https://github.com/othneildrew/Best-README-Template/blob/master/BLANK_README.md) 
* [MedHacks](https://devpost.com/software/medsearch-xrw2v6)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/jtourkis/MBTA-Ridership-Model/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/james-tourkistas-7127ba167/
[product-screenshot]: images/screenshot.png
