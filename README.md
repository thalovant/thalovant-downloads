# Thalovant Downloads

This is where the desktop builds of Thalovant Voice are published. The
repository holds no code; every build lives on the
[Releases page](https://github.com/thalovant/thalovant-downloads/releases), and
the [latest release](https://github.com/thalovant/thalovant-downloads/releases/latest)
is the one to install.

Each release carries the same set of files for one version:

| Platform | File |
| --- | --- |
| Windows (x64 or ARM64) | `Thalovant-Voice-<version>-windows-<arch>-setup.exe`, or the `.msi` |
| macOS (Apple silicon or Intel) | `Thalovant-Voice-<version>-macos-<arch>.dmg` |
| Linux (x64 or ARM64) | `Thalovant-Voice-<version>-linux-<arch>.AppImage` |

Every file has a `.sha256` beside it, and `SHA256SUMS` lists them all. To check
a download on Linux or macOS:

```bash
sha256sum -c Thalovant-Voice-<version>-linux-x64.AppImage.sha256
```

You don't usually need to come here. The setup page in the Thalovant console
links the right file for the computer you're on, and pairing happens through
the setup link rather than the installer. [Install Voice](https://docs.thalovant.com/manage/install-thalovant-voice/)
walks through the whole thing, including headless Linux.

Found a security problem in a build? Please don't open an issue; follow the
[security policy](https://github.com/thalovant/.github/blob/main/SECURITY.md).
