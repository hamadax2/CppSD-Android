# C++ SD Android Downloads

Official public download page for **C++ SD**, an Android C/C++17 editor and compiler.

## Download

Download **C++ SD 1.4.5** from the [latest release](https://github.com/hamadax2/CppSD-Android/releases/tag/v1.4.5). This release is ARM64-only and lightweight:

- **arm64-v8a** — modern 64-bit ARM phones; smallest native ARM64 toolchain build
- Unity Ads: interstitial after every second run and rewarded ad after import or explicit save
- Test mode is disabled; live production ads are enabled for Game ID `800392954`
- The compiler archive is downloaded on demand instead of embedded in the APK
- Signed release builds
- SHA-256 checksums included in `SHA256SUMS.txt`
- Fixed light mode with a consistent editor and gutter surface
- Synchronized gutter scrolling without horizontal overlay translation
- Supports C/C++ editing, Find/Replace, Format Code, optional code folding (off by default), autocomplete fallback, interactive terminal shell, and Clang tools
- The old armeabi-v7a package is not included

## Screenshots

### C/C++ editor with code completion

The editor provides syntax highlighting, line numbers, code completion, and function signatures while writing C or C++ code.

![C++ SD editor with autocomplete](Screenshot_20261008_204213.jpg)

### Compiler diagnostics and project browser

Compiler and language-server diagnostics are displayed directly over the source code, while the project browser provides quick access to files and folders.

![C++ SD compiler diagnostics and project browser](Screenshot_20261008_204238.jpg)

### Editor and compiler settings

The Settings screen provides controls for dark mode, font size, word wrap, whitespace display, indentation, hidden files, and compiler options.

![C++ SD settings screen](Screenshot_20261008_204253.jpg)

## Verify the checksum

```sh
sha256sum -c SHA256SUMS.txt
```

This is a **download-only repository**. Application source code is not included. For support, open an issue in this repository.
