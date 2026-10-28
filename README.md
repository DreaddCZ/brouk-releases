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

Brouk runs on macOS 15 or later.

- **Latest release:** [Releases](https://github.com/DreaddCZ/brouk-releases/releases)
  - Apple Silicon (M1 and later): `Brouk-<version>-arm64.dmg`
  - Intel: `Brouk-<version>-x86_64.dmg`
- Beta versions are marked as pre-releases.

Open the disk image and drag Brouk onto the Applications folder. Each release
lists the SHA-256 checksums of its images in `SHA256SUMS.txt`.

## Reporting a problem or an idea

[Open an issue](https://github.com/DreaddCZ/brouk/issues/new/choose) in the
source repository and pick **Bug report** or **Feature idea**. Issues are
public: don't include client names, internal addresses or screenshots of
client systems.

Security problems: report them privately, as described in
[SECURITY.md](https://github.com/DreaddCZ/brouk/blob/main/SECURITY.md).

## Update feeds

Installed copies of Brouk read these feeds (Sparkle):

- https://dreaddcz.github.io/brouk-releases/appcast-arm64.xml
- https://dreaddcz.github.io/brouk-releases/appcast-x86_64.xml
