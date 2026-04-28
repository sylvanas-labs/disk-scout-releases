# Disk Scout - Releases

This repository hosts public release artifacts for **Disk Scout**, a Windows disk analysis and cleanup tool.

> Source code: [sylvanas-labs/disk-scout](https://github.com/sylvanas-labs/disk-scout)

## Downloads

Go to the [Releases](../../releases) tab to download the latest version.

| Platform | File | Notes |
|----------|------|-------|
| Windows | `DiskScout-*-Setup.exe` | User-level Windows installer |
| Windows | `DiskScout-*-win-x64.zip` | Portable runtime archive |

## Release Tracks

| Track | Tag format | Description |
|-------|------------|-------------|
| Stable | `v1.2.3` | Built from `main`. |
| Beta | `v1.2.3-beta.N` | Built from `develop`. |

## Installing on Windows

Run the setup executable and follow the installer prompts. Disk Scout installs to your user profile and does not require administrator privileges.

## Channel Manifests

The CI workflow updates `channels/beta.json` and `channels/stable.json` when releases are published.

