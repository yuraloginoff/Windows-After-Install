# Windows After Install

Things to do after installing Windows 11.

## OS Activation

**Microsoft Activation Scripts (MAS)** - Open-source Windows and Office activator featuring HWID, Ohook, TSforge, KMS38, and Online KMS activation methods, along with advanced troubleshooting. \
Website: [massgrave.dev](https://massgrave.dev)

## System tweaks

**ExplorerPatcher** - This project aims to enhance the working environment on Windows. \
[GitHub](https://github.com/valinet/ExplorerPatcher)

**ExplorerTabUtility** - Force new File Explorer window to open as tab, not as window. \
[GitHub](https://github.com/w4po/ExplorerTabUtility)

**Windhawk** - The customization marketplace for Windows and programs. \
[Website](https://windhawk.net), [GitHub](https://github.com/ramensoftware/windhawk)

## Soft

**Scoop** - A command-line installer for Windows. \
Website: [scoop.sh](https://scoop.sh)

Installation:

```shell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression

# Git is required for scoop to add buckets
scoop install git

# then add most common buckets
scoop bucket add extras
scoop bucket add main
```

### Browsers

**Brave** - Secure, Fast & Private Web Browser with Adblocker. \
Website: [brave.com](https://brave.com/) \
`scoop install brave`

**Telegram** \
<https://desktop.telegram.org/>

**Яндекс Диск** \
<https://360.yandex.ru/disk/download/>

**Revo Uninstaller Free**\
<https://www.revouninstaller.com/products/revo-uninstaller-free/>

**ImageGlass** - A lightweight, versatile image viewer \
<https://imageglass.org/>

**mpc-hc** - An extremely light-weight, open source media player. \
<https://github.com/clsid2/mpc-hc/releases>

**Mailspring** \
<https://www.getmailspring.com/>

**VSCode** - Lightweight but powerful source code editor \
<https://code.visualstudio.com>

**qBittorrent** \
<https://www.qbittorrent.org/> \
<https://qbittorrent.github.io/qBittorrent-website/download> \
`scoop install extras/qbittorrent` \
`scoop install extras/qbittorrent-enhanced`

**Bitwarden** \
<https://bitwarden.com/download/>

**Adguard** \
<https://adguard.info>

**AdGuard VPN** - 3Gb free every month \
<https://adguardvpn-help.info/> \
<https://github.com/AdguardTeam/AdGuardVPNForWindows/releases>

**Stretchly** - The break time reminder app \
<https://hovancik.net/stretchly/>

---

**everything** - Locate files and folders by name instantly.\
<https://www.voidtools.com/>

```powershell
scoop install everything
```

**QuickLook** - Bring macOS “Quick Look” feature to Windows.\
<https://github.com/QL-Win/QuickLook>

```powershell
scoop install extras/quicklook
```

**ditto** - An enhanced clipboard manager
<https://ditto-cp.sourceforge.io>

```powershell
scoop install ditto
```

**Koodo Reader** - all-in-one ebook reader \
<https://www.koodoreader.com>

```powershell
scoop install extras/koodo-reader
```

**powertoys** - A set of utilities for power users to tune and streamline their Windows experience for greater productivity.\
<https://github.com/microsoft/PowerToys>

```powershell
scoop install powertoys
```

### Fonts

**nexusfont** - Font manager \
<https://www.xiles.app/> \
`scoop install extras/nexusfont`

**JetBrains Mono**: A free and open source typeface for developers

```powerschellll
scoop bucket add nerd-fonts
scoop install nerd-fonts JetBrainsMono-NF
```

### Audio, video

```powershell
scoop install handbrake
```

```powershell
scoop install ffmpeg
scoop install ffmpeg-batch
```

**mp3tag** - <https://www.mp3tag.de/en> \
Powerful and easy-to-use tool to edit metadata of audio files.

```powershell
scoop install extras/mp3tag
```

**mkvtoolnix** - <https://mkvtoolnix.download/> \
A set of tools to create, alter and inspect Matroska files.

```powershell
scoop install extras/mkvtoolnix
```

### Downloading

**yt-dlp** - <https://github.com/yt-dlp/yt-dlp> \
A youtube-dl fork with additional features and fixes.

```powershell
scoop install yt-dlp
```

**transmission** - <https://transmissionbt.com> \
A fast, easy, and free BitTorrent client.

```powershell
scoop install transmission
```
