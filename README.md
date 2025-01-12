## Customer

- [Nightly Builds](https://github.com/xfinity-remote/support-customer/releases/tag/nightly)
- [Nightly Pipelines](https://github.com/xfinity-remote/support-customer/actions/workflows/flutter-nightly.yml)

## Provider

- [Nightly Builds](https://github.com/xfinity-remote/support-provider/releases/tag/nightly)
- [Nightly Pipelines](https://github.com/xfinity-remote/support-provider/actions/workflows/flutter-nightly.yml)

## Xfinity Provider Build Files

The following table provides detailed information about each build file, its target platform, supported architecture, and a brief description.

| **Build Name**                                  | **Platform**     | **Architecture** | **Description**                                                                |
| ----------------------------------------------- | ---------------- | ---------------- | ------------------------------------------------------------------------------ |
| `XfinityProvider-{version}-x86_64.pkg.tar.zst`  | Linux (Arch)     | x86_64           | For Arch Linux-based systems, distributed as a package file.                   |
| `XfinityProvider-{version}.x86_64-suse.rpm`     | Linux (openSUSE) | x86_64           | For openSUSE systems, distributed in RPM format.                               |
| `XfinityProvider-{version}.x86_64.rpm`          | Linux (RHEL)     | x86_64           | For Red Hat-based systems (e.g., Fedora, CentOS), distributed in RPM format.   |
| `XfinityProvider-{version}-aarch64-aarch64.dmg` | macOS            | ARM64            | For macOS running on Apple Silicon (M1, M2).                                   |
| `XfinityProvider-{version}-aarch64.apk`         | Android          | ARM64            | For Android devices with ARM64 architecture.                                   |
| `XfinityProvider-{version}-armv7.apk`           | Android          | ARMv7            | For older Android devices with ARMv7 architecture.                             |
| `XfinityProvider-{version}-universal.apk`       | Android          | Universal        | A universal APK that works on most Android architectures.                      |
| `XfinityProvider-{version}-unsigned.tar.gz`     | Linux            | Source           | Source code for building the application manually on Linux systems.            |
| `XfinityProvider-{version}-x86-sciter.exe`      | Windows          | x86              | A lightweight version for x86 Windows systems using Sciter UI.                 |
| `XfinityProvider-{version}-x86_64-x86_64.dmg`   | macOS            | x86_64           | For macOS running on Intel processors.                                         |
| `XfinityProvider-{version}-x86_64.apk`          | Android          | x86_64           | For Android devices with x86_64 architecture.                                  |
| `XfinityProvider-{version}-x86_64.deb`          | Linux (Debian)   | x86_64           | For Debian-based Linux systems (e.g., Ubuntu), distributed in DEB format.      |
| `XfinityProvider-{version}-x86_64.exe`          | Windows          | x86_64           | Standard installer for 64-bit Windows systems.                                 |
| `XfinityProvider-{version}-x86_64.msi`          | Windows          | x86_64           | MSI installer for 64-bit Windows systems, suitable for enterprise deployments. |
| **Source Code**                                 | Cross-platform   | Source           | Provided in `.zip` and `.tar.gz` formats for manual builds.                    |
