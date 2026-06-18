# NoirSonance Toolkit for Cardputer Zero

Compact studio field toolkit for Cardputer Zero.

This repository is the public app-store distribution package for **NoirSonance Toolkit**.
It intentionally contains the installable Cardputer Zero app artifact, metadata,
and icon only. The private development source is not published here.

## Install

Download the Debian package from `dist/` and install it on a Cardputer Zero:

```sh
sudo dpkg -i dist/noirsonance-toolkit_0.1.0-noirsonance2_arm64.deb
sudo systemctl restart APPLaunch.service
```

Or run:

```sh
./install.sh
```

## Package

- Package: `noirsonance-toolkit`
- Version: `0.1.0-noirsonance2`
- Architecture: `arm64`
- Target: M5Stack Cardputer Zero / APPLaunch

## Privacy

NoirSonance Toolkit runs locally on the device. No private VaultPi, Gitea, Wi-Fi, password,
token, or personal server endpoint is bundled in this public package.
