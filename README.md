<div id="top"></div>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Commits][commit-shield]][commit-url]
[![GPL License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<div align="center">
  <!-- <a href="https://github.com/itflow-org/itflow">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a> -->

  <h3 align="center">ITFlow</h3>

  <p align="center">
    IT documentation, ticketing and accounting system for small MSPs.
    <br />
    <br />
    <a href="https://demo.itflow.org"><strong>View demo</strong></a>
    <br />
    Username: <b>demo@demo</b> | Password: <b>demo</b>
    <br />
    <br />
    <a href="https://itflow.org/#about">About</a>
    ·
    <a href="https://docs.itflow.org">Docs</a>
    ·
    <a href="https://forum.itflow.org/">Forum</a>
    ·
    <a href="https://github.com/itflow-org/itflow/issues">Report Bug</a>
    ·
    <a href="https://forum.itflow.org/t/features">Request Feature</a>
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About

<b>A comprehensive, free & open-source documentation, ticket management, and accounting platform.</b>

[![ITFlow][product-screenshot]](https://itflow.org)


### The Problem
- You're a busy MSP with 101 things to do. 
- Information about your clients is unorganised and unstructured: scattered in random tickets or folders - when you do eventually find it, it's out of date. 
- For some issues, you spend longer looking for the relevant documentation than actually working the ticket. 
- On top of the technical day to day, you also have to take care of the financial side of the business - consistent pricing, quotes/invoicing, and accounting. 

### The Solution: ITFlow
- ITFlow consolidates common MSP needs (IT Documentation, ticketing and billing) into one system

### In Beta
* This project is in beta with many ongoing changes. Updates may unintentionally introduce bugs/security issues. Writing functional, secure code is very difficult.
* Whilst we are confident the code is safe, nothing in life is 100% safe or risk-free. Use your best judgement before deciding to store highly confidential information in ITFlow.
* We are hoping to have a stable 1.0 release by July 2023.

<!-- BUILT WITH -->
### Built With

* Backend / PHP libs
  * PHP
  * MariaDB
  * PHPMailer
  * HTML Purifier
  * PHP Mime Mail Parser

* CSS
  * Bootstrap
  * AdminLTE
  * fontawesome

* JS Libraries
  * chart.js
  * moments.js
  * jQuery
  * pdfmake
  * Select2
  * TinyMCE
  * FullCalendar.io

<!-- GETTING STARTED -->
## Getting Started / Installation

ITFlow is self-hosted. There is a full installation guide in the [docs](https://docs.itflow.org/installation), but the main steps are:

1. Install a LAMP stack (Linux, Apache, MariaDB, PHP)
   ```sh
   sudo apt install git apache2 php libapache2-mod-php php-intl php-imap php-mailparse php-mysqli php-curl mariadb-server
   ```  
2. Clone the repo
   ```sh
   git clone https://github.com/itflow-org/itflow.git /var/www/html
   ```
3. Create a MariaDB Database
4. Point your browser to your HTTPS web server to begin setup

<!-- FEATURES -->
## Key Features
* Client documentation - assets, contacts, domains, docs, files, passwords, and more 
* Accounting / Billing - finance dashboard, quotes, invoices, accounting, expenses, etc
* Client Portal - self service quote/invoice/ticket management for clients
* Alerting - account balance, invoices, domain/SSL renewals
* Completely free & open-source alternative to ITGlue and Hudu
  
<!-- ROADMAP -->
## Roadmap / Future to-do
* Comprehensive API to allow custom third party integration
* CalDAV to integrate with 3rd party calendars
* CardDAV to integrate with 3rd party Address books
* Recent caller toast alerts to click and bring up the clients account right away
* FIDO2 WebAuthn Support for passwordless auth (TPM Fingerprint), (USB Hardware keys such as Yubikey)

See the [forum](https://forum.itflow.org/d/11-road-map) and the [open issues](https://github.com/itflow-org/itflow/issues) for a full list of proposed features & known issues.


<!-- CONTRIBUTING -->
## Support & Contributions

### Forum
For help using ITFlow, feature requests, and general ideas / discussions please use the community [forum](https://forum.itflow.org).
For bugs, please raise an [issue](https://github.com/itflow-org/itflow/issues).

### Contributing
If you are able to make a contribution that would make ITFlow better, please fork the repo and create a pull request. Please make sure you're following our [code standards](https://docs.itflow.org/code_standards). 
For large changes / new features, please discuss the issue with other contributors first.

#### Contributors
<a href="https://github.com/itflow-org/itflow/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=itflow-org/itflow" />
</a>

<!-- LICENSE -->
## License

ITFlow is distributed "as is" under the GPL License, WITHOUT WARRANTY OF ANY KIND. See [`LICENSE`](https://github.com/itflow-org/itflow/blob/master/LICENSE) for details.


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/itflow-org/itflow.svg?style=for-the-badge
[contributors-url]: https://github.com/itflow-org/itflow/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/itflow-org/itflow.svg?style=for-the-badge
[forks-url]: https://github.com/itflow-org/itflow/network/members
[stars-shield]: https://img.shields.io/github/stars/itflow-org/itflow.svg?style=for-the-badge
[stars-url]: https://github.com/itflow-org/itflow/stargazers
[issues-shield]: https://img.shields.io/github/issues/itflow-org/itflow.svg?style=for-the-badge
[issues-url]: https://github.com/itflow-org/itflow/issues
[license-shield]: https://img.shields.io/github/license/itflow-org/itflow.svg?style=for-the-badge
[license-url]: https://github.com/itflow-org/itflow/blob/master/LICENSE
[commit-shield]: https://img.shields.io/github/last-commit/itflow-org/itflow?style=for-the-badge
[commit-url]: https://github.com/itflow-org/itflow/commits/master
[product-screenshot]: .github/readme.gif

<!-- https://github.com/othneildrew/Best-README-Template -->
