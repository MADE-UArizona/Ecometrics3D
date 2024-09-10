<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
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


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/hbudinoff/Ecometrics3d">
    <img src="stockimages/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Ecometrics3D</h3>


  <p align="center">
    An plugin to estimate how much energy your 3D print will use.
    <br />
    
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
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
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://github.com/hbudinoff/Ecometrics3d)


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Here are some basic instructions for how to use this plugin for Cura.

### Prerequisites

You will need to install Cura before using our tool. You can download and install the latest verion [here](https://ultimaker.com/software/ultimaker-cura/). Note: we've only tested for compatibility with Cura 5.3.1.

### Installation

1. Above the list of files in this repo, click <> Code.
2. Click Download Code as a compressed folder.
3. Extract All of the contents in the compressed folder.
4. Open the Plugin folder located in the following location:
* On windows: %APPDATA%\cura\<Cura version>\ 
* On OSX: $USER/Library/Application Support/cura/<Cura version>/ 
5. Move the now uncompressed folder contents to the Plugin folder.
6. Open Cura as usual. The plugin should load automatically.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

Upload an STL file as usual. Once the part is sliced, the plugin will provide estimates of how much energy your print will consume. The estimate will automatically update as you make changes to the part, orientation, and process parameters, so you can find a process plan that lowers the energy consumption. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>





<!-- LICENSE -->
## License

Distributed under the  GNU Lesser General Public License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Hannah Budinoff - [Website](https://sites.arizona.edu/made-lab/) - hdb@arizona.com

Project Link: [https://github.com/hbudinoff/Ecometrics3D](https://github.com/hbudinoff/Ecometrics3D)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* This plugin uses [Cura-PauseBackendPlugin](https://github.com/fieldOfView/Cura-PauseBackendPlugin)
* Thanks to [vasmov](https://github.com/vasmov) for coding our initial ideas for this plugin.
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/hbudinoff/Ecometrics3D.svg?style=for-the-badge
[contributors-url]: https://github.com/hbudinoff/Ecometrics3D/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/hbudinoff/Ecometrics3D.svg?style=for-the-badge
[forks-url]: https://github.com/hbudinoff/Ecometrics3D/network/members
[stars-shield]: https://img.shields.io/github/stars/hbudinoff/Ecometrics3D.svg?style=for-the-badge
[stars-url]: https://github.com/hbudinoff/Ecometrics3D/stargazers
[issues-shield]: https://img.shields.io/github/issues/hbudinoff/Ecometrics3D.svg?style=for-the-badge
[issues-url]: https://github.com/hbudinoff/Ecometrics3D/issues
[license-shield]: https://img.shields.io/github/license/hbudinoff/Ecometrics3D.svg?style=for-the-badge
[license-url]: https://github.com/hbudinoff/Ecometrics3D/blob/master/LICENSE.txt
[product-screenshot]: stockimages/screenshot.png
