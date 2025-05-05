# Windows After Install

Things to do after installing Windows 11.

Microsoft Activation Scripts
<https://massgrave.dev>

## Soft

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
<https://qbittorrent.github.io/qBittorrent-website/download>

**Bitwarden** \
<https://bitwarden.com/download/>

**Adguard** \
<https://adguard.info>

**AdGuard VPN** - 3Gb free every month \
<https://adguardvpn-help.info/> \
<https://github.com/AdguardTeam/AdGuardVPNForWindows/releases>

**Stretchly** - The break time reminder app \
<https://hovancik.net/stretchly/>

## Windhawk

**The customization marketplace for Windows and programs.** \
Website: <https://windhawk.net/> \
<https://github.com/ramensoftware/windhawk>

- Taskbar height and icon size \
<https://windhawk.net/mods/taskbar-icon-size>

- Better file sizes in Explorer details \
<https://windhawk.net/mods/explorer-details-better-file-sizes>

- Slick Window Arrangement \
<https://windhawk.net/mods/slick-window-arrangement>

- Taskbar Clock Customization \
<https://windhawk.net/mods/taskbar-clock-customization> \
My example: `ddd',' d MMM • HH':'mm` = `Вс, 1 янв • 13:54`

---

## Scoop

**A command-line installer for Windows.** \
Website: <https://scoop.sh>

**Git** is required for scoop to add buckets:

```powershell
scoop install git

# then add most common buckets
scoop bucket add extras
scoop bucket add main
```

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

**64Gram** - unofficial Telegram Desktop \
<https://github.com/TDesktop-x64/tdesktop>

```powershell
scoop install 64gram
```

**Koodo Reader** - all-in-one ebook reader \
<https://www.koodoreader.com>

```powershell
scoop install extras/koodo-reader
```

**transmission** - A fast, easy, and free BitTorrent client. \
<https://transmissionbt.com>

```powershell
scoop install transmission
```

**powertoys** - A set of utilities for power users to tune and streamline their Windows experience for greater productivity.\
<https://github.com/microsoft/PowerToys>

```powershell
scoop install powertoys
```

### Tools for video editing

```powershell
scoop install handbrake
```

```powershell
scoop install ffmpeg
scoop install ffmpeg-batch
scoop install yt-dlp
```

### Fonts

**JetBrains Mono**: A free and open source typeface for developers

```powerschellll
scoop bucket add nerd-fonts
scoop install nerd-fonts JetBrainsMono-NF
```

**nexusfont** - Font manager \
<https://www.xiles.app/> \
`scoop install extras/nexusfont`
