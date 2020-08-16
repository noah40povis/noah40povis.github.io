# Github Pages
> Create your own version of lilyxsu.com. GitHub Pages are public web pages for users, organizations, and repositories, that are freely hosted on GitHub’s github.io domain or on a custom domain name of your choice. 


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://lilyxsu.com">
    <img src="header.png" alt="Logo" width="711" height="400">
  </a>

  <h3 align="center">Get Github Pages Working</h3>

  <p align="center">
    Here are instructions on getting Github Pages to do web hosting for you.
    <br />
    <a href="https://jekyllrb.com/docs/github-pages/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="http://jmcglone.com/guides/github-pages/">Background Info</a>
    ·
    <a href="https://docs.github.com/en/github/working-with-github-pages/getting-started-with-github-pages">View Documentation</a>
    ·
    <a href="https://pages.github.com/versions/">Dependencies</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
* [Usage](#usage)
* [License](#license)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

[Here are Getting Started Intros to What Github Pages Is](https://pages.github.com/)

GitHub Pages are public web pages for users, organizations, and repositories, that are freely hosted on GitHub’s github.io domain or on a custom domain name of your choice.


<!-- GETTING STARTED -->
## Getting Started

[It is recommended to start here](https://jekyllrb.com/docs/github-pages/)

### Installation

If you would like to run the website locally so it updates faster, follow this guide on how to set up the Ruby on Rails gem. Please be aware that there is no support for runniing on Windows at this time. [Installation Instructions](https://jekyllrb.com/docs/step-by-step/01-setup/)

This step is not necessary for developing the site, but makes the update time much faster to see changes. 


<!-- USAGE EXAMPLES -->
## Usage

### Setup
Create a repository that ends in github.io. This will be the inital domain of your site ie. octocat.github.io.

### _layouts/front.html
Jinga template where you can indicate which sections ie contacts, casestudies, footer, to include in which order. 

### _includes/nav.html
Which sections and their corresponding names appear in the navbar. On click, the user will autoscroll to the indicated section.

### _includes/portfolio.html
Images route to modals

### _includes/modals.html
Pop up modals that correspond to a div id from portfolio.html. 

### css/main.scss
```$theme-primary: #aca79e;```
Changes the overall theme color of the site. 
More custom changes can be applied by doing a search and replace of the existing colors versus the colors to change to in css/styles.css

### CNAME
Store your custom domain
[More info on how to set up a custom domain on the domain provider side](https://docs.github.com/en/github/working-with-github-pages/about-custom-domains-and-github-pages)



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)
* [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* [Sticky Kit](http://leafo.net/sticky-kit)
* [JVectorMap](http://jvectormap.com)
* [Font Awesome](https://fontawesome.com)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=flat-square
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=flat-square
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png