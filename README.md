<div align="center">
<h1>KeeWeb Favicon CDN ☁️</h1>
<br />
<p>

Used in combination with the [KeeWeb Favicon Service](https://services.keeweb.info/favicon/) to store favicons for various websites.

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
- [Self-Hosted Ports](#self-hosted-ports)
- [Contributors ✨](#contributors-)

<br />

---

<br />

## About

The [KeeWeb Favicon Service](https://services.keeweb.info/favicon/) allows users of KeeWeb to download favicons for the websites within their vault. 

This repo serves as a content delivery network to override certain website favicons that are either difficult to see, or may implement measures which disallow grabbing the favicon from their website.

<br />

Icons can be fetched from the KeeWeb favicon service with the following syntax:
```
https://services.keeweb.info/favicon/{DOMAIN}/{ICON_SIZE}
```

<br />

A working example using the above syntax:
```
https://services.keeweb.info/favicon/reddit.com/64
```

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
- Each icon should not exceed `80kb`
- Icon should be placed in a parent folder which starts with the first letter of the service
  - Ex: `/r/reddit.com.ico` for Reddit
  - If you are providing a favicon for a subdomain, the folder name should start with the first letter of the subdomain, not the base domain.
    - Ex: `/f/forum.libriv.ox.org.ico`
  - Domains with dashes should be labeled with the same character.
    - Ex: `/r/random-website.com.ico`
  - Anything after the TLD _(top-level domain : .com, .org, .net, etc.)_ is ignored.
    - Ex: https://subdomain.my-domain-example.com/example/page/file.html should have a favicon in `/s/subdomain.my-domain-example.com.ico`
  
<br />

If you need an easy solution for converting icons to `.ico` with the proper sizes, you can install:
- [Simple File Icon Maker](https://github.com/TheJoeFin/Simple-Icon-File-Maker)

<br />

<p align="center"><img style="width: 45%;text-align: center;border: 1px solid #353535;" src="https://github.com/keeweb/favicon-cdn/assets/118329232/497b72d2-2228-46dc-87e6-b6117e7b7eda"></p>

<br />

---

<br />

## Self-Hosted Ports
This repo supports fetching icons for locally hosted web-apps. However, keep in mind that some applications conflict and may share the same port. 

In order to fetch the icon, you will need to chnage your web-app port to the same port assigned to the icon in this repo.

| App | Default Port | Repo Port |
| --- | --- | --- |
| [Gitea](https://github.com/go-gitea/gitea) | 3000 | `3000` |
| [Uptime Kuma](https://github.com/louislam/uptime-kuma) | 3001 | `3001` |
| [Gogs](https://github.com/gogs/gogs) | 3000 | `3002` |
| [Linkwarden](https://github.com/linkwarden/linkwarden) | 3000 | `3003` |
| [Duplicacy](https://github.com/gilbertchen/duplicacy) | 3875 | `3875` |
| [ShellInABox](https://github.com/shellinabox/shellinabox) | 4200 | `4200` |
| [OpenGist](https://github.com/thomiceli/opengist) | 6157 | `6157` |
| [qBittorrent](https://github.com/qbittorrent/qBittorrent) | 8081 | `8081` |
| [Duplicati](https://github.com/duplicati/duplicati) | 8200 | `8200` |
| [Swizzin](https://github.com/swizzin/swizzin) | 8333 | `8333` |
| [Sonarr](https://github.com/Sonarr/Sonarr) | 8989 | `8989` |
| [TheLounge](https://github.com/thelounge/thelounge) | 9000 | `9000` |
| [Jackett](https://github.com/Jackett/Jackett) | 9117 | `9117` |
| [Portainer](https://github.com/portainer/portainer) | 9443 | `9443` |
| [Prowlarr](https://github.com/Prowlarr/Prowlarr) | 9696 | `9696` |
| [Webmin](https://github.com/webmin/webmin) | 10000 | `10000` |
| [Netdata](https://github.com/netdata/netdata) | 19999 | `19999` |
| [FileBrowser](https://github.com/filebrowser/filebrowser) | 22534 | `22534` |

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

</div>

<br />

---

<br />

<!-- prettier-ignore-start -->
[link-repo-main]: https://github.com/keeweb/keeweb
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
