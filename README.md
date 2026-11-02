# Brouk

Brouk is a lightweight web browser for work, built on Chromium (CEF). It keeps
several profiles side by side in one window, opens every link in the right
profile, and has its own password manager, history, bookmarks and ad blocking.

This repository holds only the published builds and the update feeds. Brouk
updates itself once installed.

**Source code:** [DreaddCZ/brouk](https://github.com/DreaddCZ/brouk), under the
Apache License 2.0. The "Source code" archives GitHub attaches to each release
below contain only this repository (the feeds), not Brouk's source; Brouk's
source for a release is its tag `v<version>` in
[DreaddCZ/brouk](https://github.com/DreaddCZ/brouk/tags).

## Download

Brouk runs on macOS 15 or later and on Windows 10 and 11 (x64).

- **Latest release:** [Releases](https://github.com/DreaddCZ/brouk-releases/releases)
  - Mac with Apple Silicon (M1 and later): `Brouk-<version>-arm64.dmg`
  - Mac with Intel: `Brouk-<version>-x86_64.dmg`
  - Windows: `Brouk-<version>-setup.exe`
- Beta versions are marked as pre-releases.

**macOS:** open the disk image and drag Brouk onto the Applications folder.
Each release lists the SHA-256 checksums of its images in `SHA256SUMS.txt`.

**Windows:** run the installer. It installs Brouk for you only, without
administrator rights. Its SHA-256 checksum is in
`Brouk-<version>-setup.exe.sha256`.

## Code signing

macOS releases are signed with the maintainer's Apple Developer ID and
notarized by Apple. The Windows installer is not code-signed, so Windows
SmartScreen warns about an unknown publisher: choose More info → Run anyway.
Updates on both systems are checked against Brouk's own signing key before
they are installed.

Privacy: see [Privacy](https://github.com/DreaddCZ/brouk#privacy) in the
source repository.

## Reporting a problem or an idea

[Open an issue](https://github.com/DreaddCZ/brouk/issues/new/choose) in the
source repository and pick **Bug report** or **Feature idea**. Issues are
public: don't include client names, internal addresses or screenshots of
client systems.

Security problems: report them privately, as described in
[SECURITY.md](https://github.com/DreaddCZ/brouk/blob/main/SECURITY.md).

## Update feeds

Installed copies of Brouk read these feeds:

- https://dreaddcz.github.io/brouk-releases/appcast-arm64.xml (macOS, Sparkle)
- https://dreaddcz.github.io/brouk-releases/appcast-x86_64.xml (macOS, Sparkle)
- https://dreaddcz.github.io/brouk-releases/windows-x64.json (Windows)
