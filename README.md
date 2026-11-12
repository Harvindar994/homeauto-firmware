# HomeAutomation Firmware Releases

This repository contains **compiled HomeAutomation firmware releases only**.

It intentionally does not contain application source code.

## Release assets

Each release may contain:

- compiled controller and satellite firmware images
- a signed release manifest
- manifest signature
- SHA-256 checksums
- release metadata

## Stable manifest

The app will read the stable manifest from the latest release:

`https://github.com/Harvindar994/homeauto-firmware/releases/latest/download/manifest-stable.json`

## Source

Application and firmware source is maintained in a private repository.

## Security

Only download firmware through the app or from a release published here.
Compiled firmware is not source code, but it can still be analyzed; no
confidential information or device credentials are embedded in release images.
