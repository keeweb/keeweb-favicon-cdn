<div align="center">
<h1>KeeWeb Favicon CDN ☁️</h1>
<br />
<p>

Used in combination with the [KeeWeb Favicon Service](https://services.keeweb.info) to store favicons for various websites.

</p>

<br />

<!-- prettier-ignore-start -->
[![Last Commit][badge-commit]][badge-commit]
[![Size][badge-size]][badge-size]
[![All Contributors][all-contributors-badge]](#contributors-)
<!-- prettier-ignore-end -->

</div>

---

<br />

- [About](#about)
- [Contributing](#contributing)
- [Contributors ✨](#contributors-)

<br />

---

<br />

## About

The [KeeWeb Favicon Service](https://services.keeweb.info) allows users of KeeWeb to download favicons for the websites within their vault. 

This repo serves as a content delivery network to override certain website favicons that are either difficult to see, or may implement measures which disallow grabbing the favicon from their website.

<br />

---

<br />

## Contributing

If you have attempted to grab an icon within KeeWeb for a certain website that is either difficult to see, or will not properly capture; you may submit an override icon to this repo. However, ensure the following:

<br />

- Submissions MUST be a proper `.ico` icon
- Icons must include the following sizes:
  - 64 x 64
  - 48 x 48
  - 32 x 32
  - 24 x 24
  - 20 x 20
  - 16 x 16
- All sizes need to be combined into a single `.ico` file
- Each icon should not exceed 100kb
- Icon should be placed in a parent folder which starts with the name of the service
  - Ex: `/r/reddit.ico` for Reddit

<br />

If you need an easy solution for converting icons to `.ico` with the proper sizes, you can install:
- [Simple File Icon Maker](https://github.com/TheJoeFin/Simple-Icon-File-Maker)

<br />

<p align="center"><img style="width: 45%;text-align: center;border: 1px solid #353535;" src="https://github.com/Aetherinox/keeweb-favicon-cdn/assets/118329232/fd5ab52f-8d5c-4abe-9c62-7478c6b1b1d6"></p>

<br />

---

<br />

## Contributors ✨
We are always looking for contributors. If you feel that you can provide something useful to KeeWeb, then we'd love to review your suggestion. Before submitting your contribution, ensure you read the policy in the section [Contributing](#contributing).

<br />

The following people have helped get this project going:

<div align="center">

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://gitlab.com/antelle"><img src="https://avatars.githubusercontent.com/u/633557?v=4?s=40" width="40px;" alt="Antelle"/><br /><sub><b>Antelle</b></sub></a><br /><a href="https://github.com/keeweb/favicon-cdn/commits?author=antelle" title="Code">💻</a> <a href="#projectManagement-antelle" title="Project Management">📆</a> <a href="#fundingFinding-antelle" title="Funding Finding">🔍</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://gitlab.com/Aetherinox"><img src="https://avatars.githubusercontent.com/u/118329232?v=4?s=40" width="40px;" alt="Aetherinox"/><br /><sub><b>Aetherinox</b></sub></a><br /><a href="https://github.com/keeweb/favicon-cdn/commits?author=Aetherinox" title="Code">💻</a> <a href="#projectManagement-Aetherinox" title="Project Management">📆</a> <a href="#fundingFinding-Aetherinox" title="Funding Finding">🔍</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://gitlab.com/HarlemSquirrel"><img src="https://avatars.githubusercontent.com/u/6445815?v=4?s=40" width="40px;" alt="HarlemSquirrel"/><br /><sub><b>HarlemSquirrel</b></sub></a><br /><a href="https://github.com/keeweb/favicon-cdn/commits?author=HarlemSquirrel" title="Code">💻</a> <a href="#projectManagement-HarlemSquirrel" title="Project Management">📆</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

</p>

<br />

---

<br />

<!-- prettier-ignore-start -->
[link-npm]: https://npmjs.com
[link-node]: https://nodejs.org
[link-npmtrends]: http://npmtrends.com/keeweb
[link-license]: https://github.com/keeweb/favicon-cdn/blob/master/LICENSE
[link-package]: https://npmjs.com/package/keeweb/favicon-cdn
[link-coverage]: https://codecov.io/github/keeweb/favicon-cdn
[link-build]: https://github.com/keeweb/favicon-cdn/actions/workflows/build.yaml?query=workflow%3Abuild.yml
[link-tests]: https://github.com/keeweb/favicon-cdn/actions/workflows/tests.yaml?query=workflow%3Atests.yml

[badge-commit]: https://img.shields.io/github/last-commit/keeweb/favicon-cdn?color=b43bcc
[badge-size]: https://img.shields.io/github/repo-size/keeweb/favicon-cdn?label=size&color=59702a
[badge-build]: https://img.shields.io/github/actions/workflow/status/keeweb/favicon-cdn/build.yml?logo=github&label=Build&color=%23278b30
[badge-tests]: https://img.shields.io/github/actions/workflow/status/keeweb/favicon-cdn/tests.yml?logo=github&label=Tests&color=%23278b30
[badge-coverage]: https://img.shields.io/codecov/c/github/keeweb/favicon-cdn?token=MPAVASGIOG&logo=codecov&logoColor=FFFFFF&label=Coverage&color=354b9e
[badge-version]: https://img.shields.io/npm/v/keeweb/keeweb
[badge-downloads]: https://img.shields.io/npm/dm/keeweb.svg
[badge-license]: https://img.shields.io/npm/l/keeweb.svg
[all-contributors]: https://github.com/all-contributors/all-contributors
[all-contributors-badge]: https://img.shields.io/github/all-contributors/keeweb/favicon-cdn?color=de1f6f&label=contributors
<!-- prettier-ignore-end -->