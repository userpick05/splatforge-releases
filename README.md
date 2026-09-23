# SplatForge Studio — Releases

Train, edit, and export **3D Gaussian Splats** on Windows, in one desktop app —
no terminal, no Python setup.

## Download

**Installers are no longer published in this repository.** They are now
distributed privately. If you use SplatForge and need an installer, ask the
author for access.

This repository remains the app's **version feed**. Each release here records a
version, its release notes, and a `SHA256SUMS` file listing the SHA-256 of that
version's installer files, so an installer you receive can be checked against it.

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

The app checks this page on launch and tells you when a newer version exists.
Its Download button opens the latest release here. To get the installer itself,
ask the author for access (see **Download** above).

## About

This repository holds **release metadata only**: version numbers, release notes
and installer checksums. The source code is maintained in a separate private
repository.

_SplatForge is an independent project. It contains no code from GPL-licensed
splat tools; its dependencies are permissively licensed (see the app's
THIRD_PARTY_NOTICES)._
