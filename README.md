# Upkeep for macOS

Upkeep helps keep your Mac's applications current with verified update sources,
clear installation status, and recovery safeguards.

## Downloads

[Download Upkeep for macOS](https://github.com/phalvorsen1/Upkeep-Releases/releases/latest/download/Upkeep-notarized.zip)

Upkeep 1.1.0 is a universal Apple Silicon + Intel build for macOS 14 or later.
It is Developer ID signed, notarized by Apple, and stapled. The released ZIP has
passed signature, checksum, stapled-ticket and Gatekeeper verification.

Versioned downloads appear on the [Releases page](https://github.com/phalvorsen1/Upkeep-Releases/releases).
Release assets will include the notarized application ZIP, release notes, and a
SHA-256 checksum file.

## Install

1. Download and unzip the release.
2. Move Upkeep.app to Applications, then open it.
3. Follow Upkeep's permission setup. Some updates still require administrator
   approval, vendor license review, or action in the Mac App Store.

Upkeep retains its legacy AppUpdater bundle identity to preserve existing
settings and update history. Do not delete your existing history to upgrade.

## About this repository

This public repository contains release information and downloadable builds only.
The application's source code is maintained in a separate private repository.
No source code, signing keys, notarization credentials, or personal diagnostic logs
are published here.

Use [Issues](https://github.com/phalvorsen1/Upkeep-Releases/issues) for support.
Please remove personal paths and other private information before posting logs.
