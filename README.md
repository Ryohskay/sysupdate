# pacup
***Simplify package updates***
- Forked by Ryohskay to test on other platforms.
- This project was originally built for a Japanese Linux Distro **open.Yellow.os**.
- My aim is to tune it for other operating systems I use.
- Please note that messages are modified from original Japanese to English.
  - This may produce some disparities between messages / descriptions, but the author is not liable for it. (See [LICENSE](LICENSE))

# TODO:
- Work with following package managers (and representative OSs I (might) refer to):
  - apt-rpm (PCLinuxOS) [^1]
  - fwupd (Ubuntu, Fedora)

- Less likely to use, but I'm interested in:
  - GNU guix (GNU guix system)
  - nixpkg (NixOS)

# package managers handled
- System package managers
  - apt
  - dnf
  - yum
  - pkg (FreeBSD, also `freebsd-update`)
  - pkg_* (OpenBSD, also `syspatch`)
  - pkgin (NetBSD)
  - slapt-get
- Userland package managers
  - flatpak
  - snap
  - homebrew (not verified)


[^1]: As of 25 Nov 2022, the upstream (apt-rpm.org) disappeared. It is probably due to the address no longer maintained.
It is totally up to each distribution what to do with this package manager... so I would not do any apt-rpm distro
other than PCLInuxOS.

## :fountain_pen: Upstream Contributors
**PenN**:
<a href="https://github.com/PengiNN"><img src="https://avatars.githubusercontent.com/u/103301288?v=4" alt="PenN Profile Image" title="PenN" width=150></a>
- Made a template for [**pacup**](https://github.com/PengiNN/pacup "PengiNN/pacup")

**桜咲ヒロ**:
<a href="https://github.com/Sakurasaki-Hiro"><img src="https://avatars.githubusercontent.com/u/114509862?v=4" alt="桜咲ヒロ Profile Image" title="桜咲ヒロ" width=150></a>
- [**Snap**](https://snapcraft.io/ "Snapcraft") and [**Flatpak**](https://flatpak.org/ "Flatpak") added to update platform

**Syuugo**:
<a href="https://github.com/s1204IT"><img src="https://avatars.githubusercontent.com/u/52069677?v=4" alt="Syuugo Profile Image" title="Syuugo" width=150></a>
- Mainly adding and modifying features
