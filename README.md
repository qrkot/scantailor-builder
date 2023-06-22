# ScanTailor builder for Ubuntu 22
This repo is a Github Action workflow to build a `.deb` package of [ScanTailor Advanced](https://github.com/4lex4/scantailor-advanced) on Ubuntu 22.04

[ScanTailor](https://scantailor.org/) is no longer maintained and [its Github repo](https://github.com/scantailor/scantailor) is archived.

The latest original ScanTailor was in Ubuntu 18 repo. As of now, it's no longer possible to simply `apt-get install` it on Ubuntu 22.

## Usage
Fork, manually run the build action, download and install the resulting deb package.

On Ubuntu 22 install the additional dependencies: `sudo apt-geet install libqt5opengl5 libqt5xml5`.
