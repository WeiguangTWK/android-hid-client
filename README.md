<div id="top"></div>
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
[![GPL-3.0 License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Arian04/android-hid-gadget">
    <img src="images/logo-placeholder.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Android HID Client</h3>

  <p align="center">
    Android app that allows you to easily use your phone as a keyboard
    <br />
    <a href="https://github.com/Arian04/android-hid-gadget/wiki"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Arian04/android-hid-gadget/issues">Report Bug</a>
    ·
    <a href="https://github.com/Arian04/android-hid-gadget/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
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

[<img src="images/main-screenshot.png"
    alt="Main Screen"
    height="350">](images/main-screenshot)

This Android app allows you to use your phone as a keyboard by communicating with `/dev/hidg0`, a character device that allows your phone to send keys to a connected host device. It presents itself as a standard hardware input device and therefore doesn't require any additional software to be installed on the computer. It is also completely functional within the connected computer's BIOS/UEFI. This app supports most standard keyboard keys, including a-z, 0-9, `~!@#$%^&*()_+{}|:"><,.;'[]\=-, function keys, SysRq/Print Screen, and several more. Supports sending a string all at once or sending each key as they are pressed in real-time.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* Android Studio

### Installation

Clone the repository and import into [Android Studio](https://developer.android.com/studio)
   ```sh
   git clone https://github.com/Arian04/android-hid-gadget.git
   ```
   
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://github.com/Arian04/arian/android-hid-gadget/wiki)_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [X] Keyboard support
- [ ] Touchpad support
- [ ] Ability to send string all at once

See the [open issues](https://github.com/Arian04/android-hid-gadget/issues) for a full list of proposed features (and known issues).

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

Distributed under the GNU GPLv3 License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Arian Baishya - arian.baishya2004@gmail.com

Project Link: [https://github.com/Arian04/android-hid-gadget](https://github.com/Arian04/android-hid-gadget)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Best-README-Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Arian04/android-hid-gadget.svg?style=for-the-badge
[contributors-url]: https://github.com/Arian04/android-hid-gadget/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Arian04/android-hid-gadget.svg?style=for-the-badge
[forks-url]: https://github.com/Arian04/android-hid-gadget/network/members
[stars-shield]: https://img.shields.io/github/stars/Arian04/android-hid-gadget.svg?style=for-the-badge
[stars-url]: https://github.com/Arian04/android-hid-gadget/stargazers
[issues-shield]: https://img.shields.io/github/issues/Arian04/android-hid-gadget.svg?style=for-the-badge
[issues-url]: https://github.com/Arian04/android-hid-gadget/issues
[license-shield]: https://img.shields.io/github/license/Arian04/android-hid-gadget.svg?style=for-the-badge
[license-url]: https://github.com/Arian04/android-hid-gadget/blob/master/LICENSE.txt
[product-screenshot]: images/main-screenshot.png