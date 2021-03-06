# Navasota Brewing Company

This is the entry point for all the software documentation belonging to the Navasota Brewing Company (NBC). All software is maintained under the `NavasotaBrewing` github account.

## What is NBC?
The [Navasota Brewing Company](https://navasotabrewing.com) is a brewery based in Navasota, Texas. It was started by David Sweeney, a long time homebrewer.

## The Brewery Control System
As we scale up NBC, we need greater control and automation over the brewing hardware. The software packages here, the "brewery control system" or "BCS", are our best effort to do just that.

There are several software packages under the `NavasotaBrewing` account that make up the BCS. Each package contains its own specific documentation.

### Architecture
See the [architecture page](architecture.md) for information about the layout of this project.

### Hardware
See the [hardware](hardware/readme.md) pages for information about the hardware we use.

## Versioning and Releases
Each package has it's own version, and versions will not line up between packages (eg. `network v0.4.1` and `cli v1.1.0` are meant to be used together). 

The [Github releases](https://github.com/NavasotaBrewing/readme/releases/) within this repository will be "BCS releases", which are soft releases specifying which versions of each of the packages are meant be to used together.

Each release of this repository will have instructions on how to set up each release of the other packages.

### Latest Release

See the [releases page](https://github.com/NavasotaBrewing/readme/releases/) for the latest release.

## About this repository
This repository contains documentation for everything that doesn't fit neatly inside one of those repos. This includes, but is not limited to:

 * [Release instructions](https://github.com/NavasotaBrewing/readme/releases/)
 * [Software architecture overview](architecture.md)
 * [Hardware specifications](hardware/index.md)
 * Setup guides
 * Brewing recipes
 * and more...

