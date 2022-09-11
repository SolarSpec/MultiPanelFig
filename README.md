<div id="top"></div>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/SolarSpec/MultiPanelFig">
    <img src="MultiPanelFig_resources/logo.png" alt="SolarSpec" width="160" height="120">
  </a>

<h3 align="center">MultiPanelFig GUI</h3>

  <p align="center">
    A Graphical User Interface 
    <br />
    <a href="https://github.com/SolarSpec/MultiPanelFig"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/SolarSpec/MultiPanelFig">View Demo</a>
    ·
    <a href="https://github.com/SolarSpec/MultiPanelFig/issues">Report Bug</a>
    ·
    <a href="https://github.com/SolarSpec/MultiPanelFig/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![MultiPanelFig Screenshot][product-screenshot]](https://solarspec.ok.ubc.ca/)
Format multiple figures at once to your liking
<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [MATLAB](https://www.mathworks.com/products/matlab.html)
* [Image Processing Toolbox](https://www.mathworks.com/help/images/)
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To begin using this app is very simple. Just verify you have the necessary prequisites and follow the installation instructions.

### Prerequisites

Make sure MATLAB is installed. It is available for download in the Software Distribution section under the Help tab after you log into [Canvas.](https://canvas.ubc.ca/)
Click on the "Add-Ons" dropdown menu of your MATLAB Home screen. Then click on "Manage Add-Ons" and ensure you have the 'Image Processing Toolbox.' If not, click on "Get Add-Ons" button instead and search for the aforementioned products.

### Installation

1. Clone the repo to your PC
   ```sh
   git clone https://github.com/SolarSpec/MultiPanelFig.git
   ```
2. Install the application 
   ```
   Click on the .mlappinstall file in your repository to open and install in MATLAB
   ```
3. Browse the APPS header
   ```
   You will find the recently installed application and can add it to your favourites
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage
To begin, multiple external plots (from a general script/command) is needed. Multiple plots can be opened at once but the most recent/current figure will be focused on first. At the top of the middle panel, the figures dropdown object will display all figures currently opened but will not automatically update when a new plot is created and so the update button at the bottom of the left panel can be pressed to fix this issue. 

The left panel handles most of the multii-panel layout properties such as the spacing, flow, labels and padding. The user can manually input the arrangement they want their figures in or let the GUI automatically move around each tile in a "flow" state. There are also "Update" and "Export" buttons that do what one would think: they update the multi-panel back into the "flow" state while finding any new figures to add to the layout. The middle panel is the figure that is exported and the finished product of the combined tiles. The right panel handles tile selecition, location (the app can insert any tile selected to a specified location), and span (how many rows and columns the tile takes up). It also allows the user to change individual labels and font size, while also toggling other properties such as an axes box, legend, xtick labels and minor ticks, and grid lines.

_For more information on any of the internal functions, please refer to the [MATLAB Documentation](https://www.mathworks.com/help/matlab/)_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [X] Format multiple axes to a standard
- [X] Change tile labels and orientation easily
- [X] Change spacing and padding of tiles
- [X] Manually input grid size or go by a "flow" state
- [X] Individual axes properties and labels
- [X] Update with new figures or export current tile layout

See the [open issues](https://github.com/SolarSpec/MultiPanelFig/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the BSD 3-Clause License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

SolarSpec - [SolarSpec Website](https://solarspec.ok.ubc.ca/) - vidihari@student.ubc.ca

Project Link: [https://github.com/SolarSpec/MultiPanelFig](https://github.com/SolarSpec/MultiPanelFig)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Group Leader - Dr. Robert Godin](https://solarspec.ok.ubc.ca/people/)
* [The Entire SolarSpec Team](https://solarspec.ok.ubc.ca/people/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/SolarSpec/MultiPanelFig.svg?style=for-the-badge
[contributors-url]: https://github.com/SolarSpec/MultiPanelFig/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/SolarSpec/MultiPanelFig.svg?style=for-the-badge
[forks-url]: https://github.com/SolarSpec/MultiPanelFig/network/members
[stars-shield]: https://img.shields.io/github/stars/SolarSpec/MultiPanelFig.svg?style=for-the-badge
[stars-url]: https://github.com/SolarSpec/MultiPanelFig/stargazers
[issues-shield]: https://img.shields.io/github/issues/SolarSpec/MultiPanelFig.svg?style=for-the-badge
[issues-url]: https://github.com/SolarSpec/MultiPanelFig/issues
[license-shield]: https://img.shields.io/github/license/SolarSpec/MultiPanelFig.svg?style=for-the-badge
[license-url]: https://github.com/SolarSpec/MultiPanelFig/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/haris-vidimlic-06730019b/
[product-screenshot]: MultiPanelFig_resources/Screenshot.png