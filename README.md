[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Kubuntu (KDE Plasma) & Bigscreen post-installation script

Basic Kubuntu post-installation shell script to setup a TV box. Feel free to fork and tailor it according to your own needs. I put an emphasis on **(re-)usability** and **simplicity**: No fancy libraries, unnecessary loops or colorful prompts... just plain linux commands that are easy to understand and to modify.

## Features

- 📂 Folder structure creation
- 📦 Supports flatpak, snap, .deb and apt package installation
- 🗑️ Cleaning of unnecessary packages and files
- 🔧 Custom actions

## Running the script

The first thing I do on a clean Pop!_OS installation...

```sh
wget https://raw.githubusercontent.com/margrevm/kubuntu-post-install/main/plasma-postinstall.sh
chmod +x pop-postinstall.sh 
./pop-postinstall.sh 
```

## Supported versions

- Kubuntu 22.04 (LTS) - **Current version**

## Credits

By Mike Margreve (mike.margreve@outlook.com) and licensed under MIT. The original source can be found here: https://github.com/margrevm/kubuntu-post-install
