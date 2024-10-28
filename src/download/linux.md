---
title: Download Prism Launcher for Linux
permalink: /download/
eleventyNavigation:
  key: <i class="fa fa-linux" aria-hidden="true"></i>Linux
  order: 1
---

<div class="download-content">
  <div class="row">
    <div class="column">
      <div>
        <h1>Linux Download</h1>
        <p>Coming Soon</p>
     </div>
    </div>
    <div class="column">
      {% image "Modpack Installer", "./src/img/screenshots/LauncherLight.png", "./src/img/screenshots/LauncherDark.png" %}
    </div>
  </div>
</div>

<div class="infobox top">

# <img src="https://www.vectorlogo.zone/logos/alpinelinux/alpinelinux-icon.svg" height="20"> Alpine Linux

[APK Packages](https://pkgs.alpinelinux.org/packages?name=prismlauncher) are available on Alpine Linux Edge for multiple architectures

```bash
apk add prismlauncher
```

</div>

<div class="infobox top">

# <img src="https://www.vectorlogo.zone/logos/archlinux/archlinux-icon.svg" height="20"/> Arch Linux / <img src="https://upload.wikimedia.org/wikipedia/commons/3/3e/Manjaro-logo.svg" height="20"/> Manjaro

An official package is available in the Arch Linux repositories:
[![prismlauncher](https://img.shields.io/badge/archlinux-prismlauncher-blue?logo=archlinux&logoColor=white)](https://archlinux.org/packages/extra/x86_64/prismlauncher/)

There are several AUR packages available:  
[![prismlauncher-qt5](https://img.shields.io/badge/aur-prismlauncher--qt5-blue)](https://aur.archlinux.org/packages/prismlauncher-qt5/)  
[![prismlauncher-git](https://img.shields.io/badge/aur-prismlauncher--git-blue)](https://aur.archlinux.org/packages/prismlauncher-git/)
[![prismlauncher-qt5-git](https://img.shields.io/badge/aur-prismlauncher--qt5--git-blue)](https://aur.archlinux.org/packages/prismlauncher-qt5-git/)

## Installing

```bash
# stable source package:
pacman -S prismlauncher
# latest git package:
yay -S prismlauncher-git
```

If you want to use Qt 5 to build the packages instead:

```bash
# stable Qt 5 source package:
yay -S prismlauncher-qt5
# stable Qt 5 binary package:
yay -S prismlauncher-qt5-bin
# latest Qt 5 git package:
yay -S prismlauncher-qt5-git
```

You can replace yay -S with your preferred [AUR helper's](https://wiki.archlinux.org/title/AUR_helpers) install command.

## Installation using Chaotic-AUR

If you have not already enabled the Chaotic-AUR follow their instructions on <https://aur.chaotic.cx/> to enable it.

```bash
# stable package:
sudo pacman -S prismlauncher
# latest git package:
sudo pacman -S prismlauncher-git
```

If you want to use Qt 5 to build the packages instead:

```bash
# stable Qt 5 package:
sudo pacman -S prismlauncher-qt5
# latest Qt 5 git package:
sudo pacman -S prismlauncher-qt5-git
```

</div>

<div class="infobox top">

# <img src="https://www.vectorlogo.zone/logos/centos/centos-icon.svg" height="20"> CentOS Stream / <img src="https://www.vectorlogo.zone/logos/getfedora/getfedora-icon.svg" height="20"> Fedora / <img src="https://www.vectorlogo.zone/logos/redhat/redhat-icon.svg" height="20"> Red Hat Enterprise Linux

RPM packages are available on [Copr](https://copr.fedorainfracloud.org/coprs/g3tchoo/prismlauncher/) for x86_64 and aarch64.
If you are on an Enterprise Linux distribution (RHEL, CentOS, Rocky, etc.) and do not have the EPEL repositories enabled, please enable them [here](https://docs.fedoraproject.org/en-US/epel/#_el9).

Nightly builds are updated automatically in the [Terra repository](https://terra.fyralabs.com/) and built on Copr every 24 hours.

```bash
# enables the copr repo
sudo dnf copr enable g3tchoo/prismlauncher
# stable releases
sudo dnf install prismlauncher
# nightly builds
sudo dnf install prismlauncher-nightly
```

</div>

<div class="infobox top">

# <img src="https://www.vectorlogo.zone/logos/debian/debian-icon.svg" height="20" /> Debian / <img src="https://www.vectorlogo.zone/logos/ubuntu/ubuntu-icon.svg" height="20" /> Ubuntu (x86_64, ARM64)

We use [makedeb](https://docs.makedeb.org/) for our Debian packages.  
Several MPR packages are available:

[![prismlauncher](https://img.shields.io/badge/mpr-prismlauncher-orange)](https://mpr.makedeb.org/packages/prismlauncher)  
[![prismlauncher-bin](https://img.shields.io/badge/mpr-prismlauncher--bin-orange)](https://mpr.makedeb.org/packages/prismlauncher-bin)  
[![prismlauncher-git](https://img.shields.io/badge/mpr-prismlauncher--git-orange)](https://mpr.makedeb.org/packages/prismlauncher-git)

## Installation using Prebuilt MPR (recommended)

```bash
sudo apt install lsb-release # install if not installed
curl -q 'https://proget.makedeb.org/debian-feeds/prebuilt-mpr.pub' | gpg --dearmor | sudo tee /usr/share/keyrings/prebuilt-mpr-archive-keyring.gpg 1> /dev/null
echo "deb [signed-by=/usr/share/keyrings/prebuilt-mpr-archive-keyring.gpg] https://proget.makedeb.org prebuilt-mpr $(lsb_release -cs)" | sudo tee /etc/apt/sources.list.d/prebuilt-mpr.list
sudo apt update
sudo apt install prismlauncher
```

Prebuilt MPR supports Debian 11, 12, and Ubuntu 20.04, 22.04, 22.10, and 23.04.

## Installing with mist, the MPR CLI

First, install [makedeb](https://www.makedeb.org/) and [mist](https://docs.makedeb.org/using-the-mpr/mist-the-mpr-cli/#installing-mist) using the instructions on their websites.

You can then use it to easily install Prism Launcher:

```bash
# stable source package:
mist install prismlauncher
# stable binary package:
mist install prismlauncher-bin
# latest git package:
mist install prismlauncher-git
```

## Installing with Pacstall

Installing [Pacstall](https://pacstall.dev/)

```bash
sudo bash -c "$(curl -fsSL https://git.io/JsADh || wget -q https://git.io/JsADh -O -)"
```

Installing Prism Launcher

```bash
# latest git package:
pacstall -I prismlauncher-git
```

</div>
  
<div class="infobox top">

# <img src="https://www.vectorlogo.zone/logos/debian/debian-icon.svg" height="20" /> Debian / <img src="https://www.vectorlogo.zone/logos/raspberrypi/raspberrypi-icon.svg" height="20" /> Pi OS / <img src="https://www.vectorlogo.zone/logos/ubuntu/ubuntu-icon.svg" height="20" /> Ubuntu (ARM32/64)

Prism Launcher is available in the [pi-apps](https://github.com/Botspot/pi-apps) store as a deb install:

[![pi-apps-badge](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2FBotspot%2Fpi-apps-analytics%2Fmain%2Fpackage_data_v2.json&query=%24.Minecraft%20Java%20Prism%20Launcher.Version&label=Pi-Apps&color=c51a4a)](https://github.com/Botspot/pi-apps)

NOTE: Only supports Debian/Raspbian/Pi OS Buster and newer and Ubuntu 18.04 and newer.
_Debian-based ARM packages are community-maintained, Prism Launcher is not responsible for outdated versions._

</div>

<div class="infobox top">

# <img src="https://www.gentoo.org/assets/img/logo/gentoo-signet.svg" height="20" /> Gentoo

Ebuilds are available in the official Gentoo repository, under [`games-action/prismlauncher`](https://packages.gentoo.org/packages/games-action/prismlauncher).
Note that, for the time being, it is not stabilized, so it's masked for `~amd64` and `~arm64` only.

```bash
sudo emaint sync -a

# If you need to unmask the package, and considering `package.accept_keywords` to be a folder.
echo ">=games-action/prismlauncher-5.0" | sudo tee -a /etc/portage/package.accept_keywords/prismlauncher
# Or do this if you want to build from the latest commit instead of a release
echo "=games-action/prismlauncher-9999 **" | sudo tee -a /etc/portage/package.accept_keywords/prismlauncher

emerge games-action/prismlauncher
```

Have fun! :)

</div>
  
<div class="infobox top">

# <img src="https://www.vectorlogo.zone/logos/nixos/nixos-icon.svg" height="20" /> Nix

A [Nix derivation](https://github.com/PrismLauncher/PrismLauncher/blob/develop/nix/README.md) is available.

Packages are available for all current Nix distributions.

</div>
  
<div class="infobox top">

# <img src="https://upload.wikimedia.org/wikipedia/commons/d/d0/OpenSUSE_Logo.svg" height="20"> openSUSE

RPM packages are available on the [Open Build Service](https://download.opensuse.org/repositories/home:/getchoo/).

```bash
# add repository (if on leap, replace 'openSUSE_Tumbleweed' with '15.4')
zypper addrepo https://download.opensuse.org/repositories/home:getchoo/openSUSE_Tumbleweed/home:getchoo.repo
# refresh repository cache
zypper refresh
# stable releases (Qt6 version, only for Tumbleweed)
zypper install prismlauncher
# latest builds (Qt6 version, only for Tumbleweed)
zypper install prismlauncher-nightly
# stable releases (Qt5 version, available for Leap and Tumbleweed)
zypper install prismlauncher-qt5
# latest builds (available for Leap and Tumbleweed)
zypper install prismlauncher-qt5-nightly
```

</div>

<div class="infobox top">

# <img src="https://upload.wikimedia.org/wikipedia/commons/3/34/Slackware_logo.svg" height="20"> Slackware

Prism Launcher is available on [SlackBuilds](https://slackbuilds.org/repository/15.0/games/PrismLauncher/) maintained by Samuel Young. The package is only available for Slackware version 15.0 (currently)!

_Note: You may need to edit the `PrismLauncher.SlackBuild` file and change the VERSION variable to reflect that of the source code, although it is better if you wait for the maintainer to update the SlackBuild file._

```bash
# download launcher slackbuild archive
wget https://slackbuilds.org/slackbuilds/15.0/games/PrismLauncher.tar.gz
# extract archive
tar -xpvf PrismLauncher.tar.gz; cd PrismLauncher-*
# download source specified in PrismLauncher.info, for example for version 7.1:
wget https://github.com/PrismLauncher/PrismLauncher/releases/download/7.1/PrismLauncher-7.1.tar.gz
# verify integrity
md5sum PrismLauncher-*.tar.gz # compare the result with the md5 in PrismLauncher.info
# enter root environment and grant permissions
su -l; chmod +x PrismLauncher.SlackBuild
# build package
./PrismLauncher.SlackBuild
# install package (name dependent on version, cpu arch)
cd /tmp; installpkg PrismLauncher-*.tgz
```

</div>

<div class="infobox top">

# <img src="https://bitcu.co/en/wp-content/uploads/2020/07/Void_Linux_logo.svg_.png" height="20"> Void Linux

Prism Launcher is available on the official Void repository.

```bash
sudo xbps-install PrismLauncher
```

</div>
