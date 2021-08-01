<div align="center">
    <a href="https://github.com/KatsuteDev/Desktop-Flick#readme">
        <img src="https://raw.githubusercontent.com/KatsuteDev/Desktop-Flick/main/banner.png" alt="Desktop Flick">
    </a>
    <h3>Desktop Flick - Japanese flick keyboard for desktop.</h3>
    <a href="https://github.com/KatsuteDev/Desktop-Flick/actions/workflows/npm_ci.yml"><img src="https://github.com/KatsuteDev/Desktop-Flick/actions/workflows/npm_ci.yml/badge.svg" title="npm CI"></a>
    <a href="https://github.com/KatsuteDev/Desktop-Flick/actions/workflows/codeql.yml"><img src="https://github.com/KatsuteDev/Desktop-Flick/actions/workflows/codeql.yml/badge.svg" title="CodeQL"></a>
    <a href="https://github.com/KatsuteDev/Desktop-Flick/actions/workflows/deploy.yml"><img src="https://github.com/KatsuteDev/Desktop-Flick/actions/workflows/deploy.yml/badge.svg" title="Deploy"></a>
    <a href="https://github.com/KatsuteDev/Desktop-Flick/releases"><img title="version" src="https://img.shields.io/github/v/release/KatsuteDev/Desktop-Flick"></a>
    <a href="https://github.com/KatsuteDev/Desktop-Flick/blob/main/LICENSE"><img title="license" src="https://img.shields.io/github/license/KatsuteDev/Desktop-Flick"></a>
</div>

## Overview

Desktop Flick uses your mobile device's keyboard and mirrors the output onto the desktop.

<div align="center">
    <a href="https://github.com/KatsuteDev/Desktop-Flick">
        <img src="https://raw.githubusercontent.com/KatsuteDev/Desktop-Flick/main/sample.gif" alt="sample" width="750">
    </a>
</div>

## Setup

This application doesn't add a new keyboard, you need to add them to your mobile device first.
 - [Adding keyboard on iOS](https://support.apple.com/guide/iphone/add-or-change-keyboards-iph73b71eb/ios)
 - [Adding keyboard on Android](https://www.samsung.com/au/support/mobile-devices/customise-keyboard-layout/)

**Installation:**

 1. Download the latest release: [![version](https://img.shields.io/github/v/release/KatsuteDev/Desktop-Flick)](https://github.com/KatsuteDev/Desktop-Flick/releases)
 2. Either run the installer or extract the zip into the desired directory
     - Installer installs into `AppData/Local/Desktop-Flick`
 3. Run `Desktop-Flick.exe`
 4. Login with mobile device (you must be on the same internet network)
 5. Start typing

## Configuration

Default port is `7272`, this can be changed by going to the `config.json` and changing the `port` value. This config is generated on the first run.

```json
{
    "port": 7272
}
```

<hr>

### Contributing

- Build using `npm run build` or `npm run prepare`
- Test builds using `npm run start:dev`
- Package builds using `npm run make`
