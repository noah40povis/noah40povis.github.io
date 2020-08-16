# Use Github Pages to Get Free Hosting
> Create your own version of lilyxsu.com. GitHub Pages are public web pages for users, organizations, and repositories, that are freely hosted on GitHub’s github.io domain or on a custom domain name of your choice. 


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://lilyxsu.com">
    <img src="header.png" alt="Logo" width="711" height="400">
  </a>

  <h3 align="center">Set Up Github Pages</h3>

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

[It is recommended to start here in the official Jekyll Ruby Page, which offers links that point to all related info on Github pages and background information.](https://jekyllrb.com/docs/github-pages/)

### Installation

If you would like to run the website locally so it updates faster, follow this guide on how to set up the Ruby on Rails gem. Please be aware that there is no support for runniing on Windows at this time. [Installation Instructions](https://jekyllrb.com/docs/step-by-step/01-setup/)

This step is not necessary for developing the site, but makes the update time much faster to see changes. 


<!-- USAGE EXAMPLES -->
## Usage

### Setup

Create a repository that ends in ```github.io```. This will be the inital domain of your site ie. ```octocat.github.io```.

### _layouts/front.html

Jinga template where you can indicate which sections ie contacts, casestudies, footer, to include in which order. 

#### Files used in lilyxsu.com

*   head.html
*   nav.html
*   header.html
*   skills.html 
*   casestudies.html
*   portfolio.html
*   modals.html
*   doc.html 
*   contact.html
*   footer.html
*   insta.html
*   scripts.html

### _includes/nav.html

Which sections and their corresponding names appear in the navbar. On click, the user will autoscroll to the indicated section.

### _includes/portfolio.html

Images route to modals

### _includes/modals.html

Pop up modals that correspond to a div id from ```portfolio.html```. 

### css/main.scss

```$theme-primary: #aca79e;```
Changes the overall theme color of the site. 
More custom changes can be applied by doing a search and replace of the existing colors versus the colors to change to in ```css/styles.css```

### CNAME

Specify your custom domain here. You will also need to route to this site from your account where you purchased your domain. 
[More info on how to set up a custom domain on the domain provider side.](https://docs.github.com/en/github/working-with-github-pages/about-custom-domains-and-github-pages)



<!-- LICENSE -->
## License

Distributed under the Apache-2.0 License. See `LICENSE` for more information.


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

This site could not have been made without the work that Harsh put in to create pop up modals in the portfolio section that allow Youtube video previews: 
* [See Harsh's github pages repo](https://github.com/hurshd0/hurshd0.github.io)
* [The Jekyll Github Pages Project](https://jekyllrb.com/docs/github-pages/)
