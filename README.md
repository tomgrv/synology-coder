<!-- @format -->

# Coder Synology Package

## Description

This repository builds a Synology package for [coder/coder](https://github.com/coder/coder) using [tomgrv/synology-package-builder](https://github.com/tomgrv/synology-package-builder), following the structure used in [tomgrv/synology-github-runner](https://github.com/tomgrv/synology-github-runner).

## Installation

1. Download the package from the [Releases](https://github.com/tomgrv/synology-coder/releases) page.
2. Open Synology Package Center.
3. Click **Manual Install** and select the downloaded `.spk` file.
4. Follow the installation instructions.

**The package will go in error state initially, but this is expected as it needs to be elevated to run properly.**

5. Elevate the package by following the instructions from the [Synology Package Builder](https://github.com/tomgrv/synology-package-builder/blob/main/doc/elevated.md).
6. After elevation, the package creates and manages a `coder` container that exposes Coder on port `7080`.

## License

This package is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

This work is not affiliated with Synology Inc. in any way. It is an independent project that aims to facilitate the development of Synology packages using GitHub Actions. It is not an official Synology product and does not have any official support from Synology Inc. Use at your own risk.
