# PlasmaClean

<p align="center">
  <img width="1024" height="1024" alt="plasmaclean" src="https://github.com/user-attachments/assets/36200561-4256-4540-9f8d-4ad436c49a99" />

</p>

<h1 align="center">PlasmaClean</h1>

<p align="center">
  Lightweight Linux system cleaner for KDE Plasma.
</p>

<p align="center">
  Clean system clutter, reclaim disk space, and keep your Linux desktop tidy.
</p>

<p align="center">

![Linux](https://img.shields.io/badge/Linux-Supported-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)
![KDE Plasma](https://img.shields.io/badge/KDE%20Plasma-Supported-1D99F3?style=for-the-badge\&logo=kde\&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![PySide6](https://img.shields.io/badge/PySide6-Qt6-41CD52?style=for-the-badge\&logo=qt\&logoColor=white)

</p>

---

## Preview


  <img width="383" height="589" alt="Screenshot_20260901_213341" src="https://github.com/user-attachments/assets/b36f6791-495d-4377-8d73-ea67830f7167" />


<p align="center">
  <img src="assets/PLACEME-SCREENSHOT.png" width="520" alt="Screenshot of the PlasmaClean application interface.">
</p>

---

## About

**PlasmaClean** is a lightweight Linux system cleaning utility designed for KDE Plasma.

It provides a simple graphical interface for finding and removing common system clutter without requiring users to manually search through directories or remember multiple terminal commands.

PlasmaClean automatically detects the package manager available on the system and uses the appropriate cleanup tools.

### What it can clean

* Application cache
* Package manager cache
* Old system journal logs
* Thumbnail cache
* Trash
* Unused/orphaned packages

---

## Supported Linux Distributions

PlasmaClean supports multiple Linux families through automatic package-manager detection.

| Linux family         | Package manager |
| -------------------- | --------------- |
| Arch Linux / Manjaro | Pacman          |
| Debian / Ubuntu      | APT             |
| Fedora / RHEL        | DNF             |
| openSUSE             | Zypper          |
| Alpine Linux         | APK             |
| Gentoo               | Portage         |

> Package-manager cleanup depends on the package manager available on the system.

---

## Installation

### Recommended: Install the compiled release

Download the latest **Linux x86_64** release from the GitHub Releases page.

The release is distributed as a standalone Linux application and does **not** require Python or PySide6 to be installed separately.

Extract the downloaded archive and run:

```bash
sudo ./install.sh
```

After installation, PlasmaClean will appear in your desktop's application menu.

You can launch it normally:

**Applications → PlasmaClean**

No terminal is required after installation.

---

## Why does installation require a password?

PlasmaClean is a **system utility**, so some of its operations need administrator privileges.

The installer uses `sudo` because it installs the application into system directories such as:

```text
/opt/PlasmaClean
/usr/share/applications
/usr/share/icons
```

These locations are protected by Linux and normally require administrator access.

PlasmaClean also uses the operating system's standard authentication mechanism when a cleanup operation requires elevated privileges.

Your password is **not used by PlasmaClean as an application password**. It is requested by Linux to authorize the privileged operation.

---

## How PlasmaClean Works

```text
Scan
  ↓
Select cleanup categories
  ↓
Review the amount of data
  ↓
Clean
```

PlasmaClean focuses on known cache, log, thumbnail, trash, and package-manager locations instead of randomly deleting files from the filesystem.

---

## Features

* Lightweight KDE Plasma interface
* Automatic package-manager detection
* Multiple Linux distribution families
* Application cache cleanup
* Package cache cleanup
* System journal cleanup
* Thumbnail cleanup
* Trash cleanup
* Orphan package cleanup
* Standalone compiled release
* No Python installation required for the compiled release

---

## Built With

![Python](https://img.shields.io/badge/Python-3.13-3776AB?style=flat-square\&logo=python\&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-6-41CD52?style=flat-square\&logo=qt\&logoColor=white)
![PySide6](https://img.shields.io/badge/PySide6-6.x-41CD52?style=flat-square\&logo=qt\&logoColor=white)
![Nuitka](https://img.shields.io/badge/Built%20with-Nuitka-4B8BBE?style=flat-square)

---

## Project Goals

PlasmaClean is designed to make common Linux maintenance tasks simple without turning system cleaning into a complicated process.

Planned improvements include:

* Additional package managers
* More cleanup categories
* Improved disk-space scanning
* More detailed cleanup information
* Additional desktop environment support
* Performance improvements

---

## Safety

PlasmaClean targets known cleanup locations and package-manager operations.

System-level operations may require administrator authorization.

Always review the selected cleanup categories before starting a cleanup.

---

## Status

![Status](https://img.shields.io/badge/Status-Active%20Development-3DAEE9?style=for-the-badge)

PlasmaClean is actively being developed.

---

## Author

**Roham**

---

<p align="center">
  <strong>PlasmaClean</strong><br>
  Lightweight. Simple. Linux.
</p>
