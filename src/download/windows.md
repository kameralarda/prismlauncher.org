---
title: Download Prism Launcher for Windows
eleventyNavigation:
  key: <i class="fa fa-windows" aria-hidden="true"></i> Windows
  order: 4
---

<div class="download-content">
  <div class="row">
    <div class="column">
      <div>
        <h1>Windows Download</h1>
        <p>Windows 10/11 64bit</p>
        <a class="button size-large" href="https://github.com/kameralarda/PrismLauncherCracked/releases/download/{{version.current}}/prismlauncher.exe">Installer (.exe)</a>
        <a class="button size-large" href="https://github.com/kameralarda/PrismLauncherCracked/releases/download/{{version.current}}/portable.7z">Portable (.7z)</a>
      </div>
    </div>
    <div class="column">
      {% image "Modpack Installer", "./src/img/screenshots/windows/LauncherLight.png", "./src/img/screenshots/windows/LauncherDark.png" %}
    </div>
  </div>
</div>

<div class="infobox top">

### Advanced Windows install options

#### MinGW-w64

These builds are built with MinGW and do not require the Visual C++ Redistributable to be installed on your system. They require Windows 10/11 64bit.

Note: These builds are less tested than the MSVC builds.

- [Installer (64bit) (.exe)](https://github.com/PrismLauncher/PrismLauncher/releases/download/{{version.current}}/PrismLauncher-Windows-MinGW-w64-Setup-{{version.current}}.exe)

### CLI (community-maintained)

#### Winget Package

```powershell
winget install -e PrismLauncher.PrismLauncher
```

#### Stable Scoop Package

```powershell
scoop bucket add games
scoop install prismlauncher 
```

#### Unstable Scoop Package

Same as above, but it's an unstable git [development build](/wiki/development/development-builds) rather than a stable build.

```powershell
scoop bucket add versions
scoop install prismlauncher-git
```

#### Chocolatey Package

```powershell
choco install prismlauncher
```

*Chocolatey and Scoop packages are community-maintained, Prism Launcher is not responsible for outdated versions.*

#### [PortableApps.com](https://portableapps.com) Installer

A community maintained portable installer for Prism Launcher can be found [here](https://RuiNtD.github.io/PrismLauncherPortable/).

</div>
