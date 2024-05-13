<p align="center">
  <a href="https://changie.dev">
    <img alt="Changie Logo" src="./docs/static/logo.svg" height="256" />
  </a>
  <h3 align="center">Changie</h3>
  <p align="center">Separate your changelog from commit messages without conflicts.</p>
</p>

[![GitHub release](https://img.shields.io/github/v/release/miniscruff/changie?style=for-the-badge&logo=github)](https://github.com/miniscruff/changie/releases)
[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/miniscruff/changie/test.yml?event=push&style=for-the-badge&logo=github)](https://github.com/miniscruff/changie/actions/workflows/test.yml)
[![Go Packge](https://img.shields.io/badge/Go-Reference-grey?style=for-the-badge&logo=go&logoColor=white&label=%20&labelColor=007D9C)](https://pkg.go.dev/github.com/miniscruff/changie)
[![Awesome Go](https://img.shields.io/badge/awesome-awesome?style=for-the-badge&logo=awesomelists&logoColor=white&label=%20&labelColor=CCA6C4&color=494368)](https://github.com/avelino/awesome-go#utilities)

![quick_start](./examples/quick_start.gif)

## Features
* File based changelog management keeps your commit history and release notes separate.
* Track changes while you work while the knowledge is fresh.
* Extensive [configuration options](https://changie.dev/config) to fit your project.
* Language and framework agnostic using a single go binary.

## Getting Started
* User documentation is available on the [website](https://changie.dev/).
* Specifically, the [guide](https://changie.dev/guide/) is a good place to start.
* There is also a [Changie GitHub Action](https://github.com/miniscruff/changie-action) available.
* Changie's [Changelog](CHANGELOG.md) is generated by itself.
* [Examples](./examples) contains a few configurations and video examples.

## Need help?
Use the [discussions page](https://github.com/miniscruff/changie/discussions) for help requests and how-to questions.

Please open [GitHub issues](https://github.com/miniscruff/changie/issues) for bugs and feature requests.
File an issue before creating a pull request, unless it is something simple like a typo.

## Want to Contribute?
If you want to contribute through code or documentation, the [Contributing guide](CONTRIBUTING.md) is the place to start.
If you need additional help create an issue or post on discussions.

## Semantic Version Compatibility
Changie is focused around the CLI and its configuration options and aims to keep existing CLI commands and options suported in major versions.
It is possible to use Changie as a dependent package but no support or compability is guaranteed.

## License
Distributed under the [MIT License](LICENSE).
