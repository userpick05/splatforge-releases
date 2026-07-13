# SplatForge Studio — Downloads

Train, edit, and export **3D Gaussian Splats** on Windows, in one desktop app —
no terminal, no Python setup.

## Download

**[⬇ Latest release](https://github.com/userpick05/splatforge-releases/releases/latest)**

Download **all** files for a release (the `.exe` and every `.bin` slice) into
the same folder, then run the `.exe`. The installer upgrades any previous
version in place.

## Requirements

- **Windows 10/11 (64-bit)**
- **NVIDIA RTX 50-series GPU** (the bundled GPU kernels are built for this
  generation; the app's built-in **System Check** tells you honestly if your
  machine isn't supported instead of failing cryptically)
- A current NVIDIA driver (the app checks and links the download if it's old)
- ~10 GB free disk space

The Visual C++ and WebView2 runtimes are bundled and installed automatically
when missing.

## Updates

The app checks this page on launch and offers to download a newer version when
one is published. You can also run `splatforge update-check` from a terminal.

## About

This repository hosts **published installer builds only**. The source code is
maintained in a separate private repository.

_SplatForge is an independent project. It contains no code from GPL-licensed
splat tools; its dependencies are permissively licensed (see the app's
THIRD_PARTY_NOTICES)._
