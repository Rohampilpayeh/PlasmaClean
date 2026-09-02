# PlasmaClean

<p align="center">
  <img src="assets/plasmaclean-icon.png" width="120" alt="PlasmaClean">
</p>

<h2 align="center">A lightweight system cleaner for Linux.</h2>

<p align="center">
  Clean unnecessary files, reclaim disk space, and keep your system tidy.
</p>

<p align="center">
  <img src="assets/plasmaclean-screenshot.png" width="420" alt="PlasmaClean">
</p>

---

## About

**PlasmaClean** is a lightweight Linux system cleaning utility designed with a clean, simple interface and support for multiple Linux distributions.

It automatically detects your package manager and provides a straightforward way to clean common system clutter without needing to manually search through directories or remember terminal commands.

Built with **Python and PySide6**, PlasmaClean is designed to stay fast, simple, and easy to use.

## Features

* **Application Cache** — Remove cached application data
* **Package Cache** — Clean downloaded package files
* **System Journal** — Remove older system logs
* **Thumbnail Cache** — Clear generated image and video thumbnails
* **Trash** — Empty the desktop trash
* **Unused Packages** — Find and remove orphaned packages
* **Automatic Detection** — Detects your Linux package manager automatically
* **Lightweight UI** — Simple interface designed for KDE Plasma
* **Compiled Releases** — Run PlasmaClean without installing Python or its dependencies

## Multi-Distribution Support

PlasmaClean is designed to work across multiple Linux distributions by detecting the package manager available on your system.

| Distribution / Family | Package Manager |
| --------------------- | --------------- |
| Arch Linux / Manjaro  | Pacman          |
| Debian / Ubuntu       | APT             |
| Fedora / RHEL         | DNF             |
| openSUSE              | Zypper          |
| Alpine Linux          | APK             |
| Gentoo                | Portage         |

More distributions and package managers may be supported in future releases.

## Why PlasmaClean?

Linux gives you powerful tools for managing your system, but keeping a machine clean can still involve checking several different locations and commands.

PlasmaClean puts common cleanup tasks into one simple interface.

**Scan. Select. Clean.**

## Download

Precompiled Linux releases are available through the **GitHub Releases** page.

Download the latest:

`PlasmaClean-Linux-x86_64.tar.gz`

Extract the archive and launch:

`app.bin`

The release is bundled with the required runtime components, so you don't need to install Python, PySide6, or the project's source code to run it.

## System Requirements

* Linux x86_64
* Qt6-compatible desktop environment
* KDE Plasma recommended
* Supported package manager for package-related cleanup features

## Technology

PlasmaClean is built using:

* Python
* PySide6 / Qt6
* Nuitka
* Native Linux package-management tools

## Project Status

PlasmaClean is an actively developed project.

The goal is to keep the application lightweight while gradually expanding distribution support, cleanup options, and system maintenance features.

## Security & Safety

PlasmaClean is designed to target known cache, log, thumbnail, trash, and package-manager locations rather than deleting arbitrary system files.

Some operations require administrator privileges and use the system's standard authentication mechanism.

Always review what you are cleaning before running system maintenance operations.

## Screenshots

<p align="center">
  <img src="assets/plasmaclean-screenshot.png" width="420" alt="PlasmaClean screenshot">
</p>

## Author

**Roham**

---

<p align="center">
  <b>PlasmaClean</b><br>
  Lightweight. Simple. Linux.
</p>

