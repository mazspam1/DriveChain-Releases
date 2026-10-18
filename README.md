# DriveChain releases

This repository only holds the Windows installers for DriveChain and the feed the app checks for updates. The source code lives somewhere else.

## Install

1. Open [the latest release](https://github.com/mazspam1/DriveChain-Releases/releases/latest) and download `DriveChain_<version>_x64-setup.exe`.
2. Run the installer. It is not Authenticode-signed, so Windows SmartScreen may warn about it. Click **More info**, then **Run anyway**.
3. Keep the PC online the first time DriveChain starts. It downloads several GB of runtime libraries and NFL data.

Requirements:
- Windows 10 or 11, x64.
- An NVIDIA GPU with driver 580 or newer (CUDA 13).
- 40 GB of free disk space.

## Updates

Once DriveChain is installed it checks this repository for new versions and shows a notice in the app when one is available. Every update is signed, and the app checks the signature before installing anything.

Releases tagged `free-channel` hold the update feed (`latest-free.json`). Do not delete them.

DriveChain is a research model, not betting advice.
