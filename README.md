# CartfileDiff 
[![Build Status](https://travis-ci.org/YPlan/CartfileDiff.svg?branch=master)](https://travis-ci.org/YPlan/CartfileDiff)

A simple tool for comparing two `Cartfile.resolved` files and printing a list of dependencies in the latter which are new or differ in pinned version.

## Installation

See [Releases](https://github.com/YPlan/CartfileDiff/releases) for prebuilt `pkg` installers.

Alternatively, clone this repository and run `make install`.

## Usage

`cartfilediff <old Cartfile.resolved> <new Cartfile.resolved>`

The tool prints a list of dependencies which need bootstrapping. If nothing needs bootstrapping, the tool prints nothing.

## License

CartfileDiff is released under the [MIT License](LICENSE.md).

## Acknowledgements

[Carthage](https://github.com/Carthage/Carthage), for providing the Carthage tool and for portions of source code used in this project.
