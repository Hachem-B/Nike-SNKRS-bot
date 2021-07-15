

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
[![LinkedIn][linkedin-shield]][linkedin-url]




<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/mosuswalks/snkrs-bot">
    <img src="./images/snkrs.svg" alt="Logo" width="150" height="100">
  </a>

  <h3 align="center">snkrs-bot</h3>

  <p align="center">
    This is a simple bot using Node.js / puppeteer that buys a Nike shoe when it drops.
    <br />
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




<!-- ABOUT THE PROJECT -->
## About The Project
A fully automated sneaker bot for purchasing exclusive sneakers on the Nike SNKR's site.



### Built With

* [Node.js](https://nodejs.org/en/)
* [Puppeteer](https://github.com/puppeteer/puppeteer)
* [Node Cron](https://github.com/node-cron/node-cron)





<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

You must already have a valid [Nike](https://nike.com) account and credit card tied to the account. 


* yarn
```sh
yarn upgrade --latest
```
* npm 
```sh
npm install npm@latest -g
```


### Installation
 
1. Clone the repo
```sh
git clone https://github.com/mosuswalks/snkrs-bot.git
```
2. Install NPM packages
```sh
yarn install
```
or
```sh
npm install
```

<!-- USAGE EXAMPLES -->
## Usage

1. You'll need to reate a .env file and add the following variables.

```sh
EMAIL=youremail@example.com
PASS=yournikeaccountpassword
CVC=yourcreditcardcvc
```

2. In the bot.js file, edit the following lines.

<img src="./images/carbon.svg">

3. Run the script like you normally would or by invoking the Cron Job (currently set to 6am)

```sh
node bot.js
```

or 

```ch
node cron.js
```


<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/mosuswalks/snkrs-bot/issues) for a list of proposed features (and known issues).








<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/mosuswalks/snkrs-bot.svg?style=flat-square
[contributors-url]: https://github.com/mosuswalks/snkrs-bot/contributors
[forks-shield]: https://img.shields.io/github/forks/mosuswalks/snkrs-bot.svg?style=flat-square
[forks-url]: https://github.com/mosuswalks/snkrs-bot/network/members
[stars-shield]: https://img.shields.io/github/stars/mosuswalks/snkrs-bot.svg?style=flat-square
[stars-url]: https://github.com/mosuswalks/snkrs-bot/stargazers
[issues-shield]: https://img.shields.io/github/issues/mosuswalks/snkrs-bot.svg?style=flat-square
[issues-url]: https://github.com/mosuswalks/snkrs-bot/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/mosuswalks/snkrs-bot/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/mohamedaabdi
[product-screenshot]: images/screenshot.png
[botjs-code]: ./images/snkr-bot.svg
