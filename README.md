[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<!-- PROJECT HEADER -->
<br />
<p align="center">
  <!-- https://github.com/stefanjudis/github-light-dark-image-example -->
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.github.com/Good-Games-Munich/assets/main/logos/GGM_logo_white.png">
    <img alt="Logo" src="https://raw.github.com/Good-Games-Munich/assets/main/logos/GGM_logo_black.png" height="150">
  </picture>

  <h3 align="center">🔒 Vpn-Server</h3>

  <p align="center">
    ·
    <a href="https://github.com/Good-Games-Munich/vpn-server/issues">Report Bug</a>
    ·
    <a href="https://github.com/Good-Games-Munich/vpn-server/issues">Request Feature</a>
    ·
  </p>
</p>

<!-- ABOUT THE PROJECT -->

## About The Project

A VPN server to connect some stuff for Good Games Munich.

## Setup

### Production

1. Follow [Creating a release](https://github.com/Good-Games-Munich/.github/wiki/workflows#creating-a-release).

### Development

tbd

### Customization

Create a environment file `touch .env`. Override variables in the `{variable name}={variable value}` format. All required variables need to be overridden for the respected environment.

| Variable         | Description              | Required in dev | Required in prod | Default value |
| ---------------- | ------------------------ | --------------- | ---------------- | ------------- |
| `HOST`           | Host url of the service. | `true`          | `true`           | none          |
| `ADMIN_PASSWORD` | Password for the admin.  | `false`         | `true`           | `admin`       |

<!-- CONTRIBUTING -->

## Contributing

Follow [contributing](https://github.com/Good-Games-Munich/.github/wiki/workflows#contributing).

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/Good-Games-Munich/vpn-server.svg?style=flat-square
[contributors-url]: https://github.com/Good-Games-Munich/vpn-server/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Good-Games-Munich/vpn-server.svg?style=flat-square
[forks-url]: https://github.com/Good-Games-Munich/vpn-server/network/members
[stars-shield]: https://img.shields.io/github/stars/Good-Games-Munich/vpn-server.svg?style=flat-square
[stars-url]: https://github.com/Good-Games-Munich/vpn-server/stargazers
[issues-shield]: https://img.shields.io/github/issues/Good-Games-Munich/vpn-server.svg?style=flat-square
[issues-url]: https://github.com/Good-Games-Munich/vpn-server/issues
