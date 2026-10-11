# Stagelight

**Stagelight** is a free Windows app for showing worship songs, scripture, slides, images, videos and music on a projector, and you run it from your phone. The laptop stays connected to the projector; you control the service from a phone on the same Wi-Fi or the laptop's own hotspot. No app to install on the phone.

This repository only hosts the **installer and automatic updates**. The source code is kept in a separate, private repository.

## Features

- **Phone remote:** scan a QR code and run the whole service from your phone: next/previous, black screen, welcome screen, the service order and the full library.
- **Songs, scripture, custom slides and media** in one service list, with fade, slide-up, zoom or instant transitions.
- **Lyrics over video:** songs, scripture and slides can appear over a playing video or image.
- **Themes** with a drag-and-drop layout editor: no pixel values, text snaps to the centre and safe margins and shrinks to fit.
- **Bibles:** type a reference or pick book, chapter and verse; save passages for later and share them on WhatsApp.
- **Media:** images, videos, music and YouTube links, organised in folders.
- **Alerts** that scroll across the screen over everything, plus keyboard shortcuts (press **?** in the app).
- **Bring your library with you:** import songs (OpenLyrics), Bibles (OpenSong, Zefania, OSIS, USFX), themes and media exported from other programs.
- **Updates itself:** new versions download in the background and install when you restart.

## Install

1. Open the [latest release](https://github.com/Lord-Raven1/Stagelight-Release/releases/latest).
2. Download **`Stagelight-Setup-<version>.exe`** and run it. It installs for your Windows user only (no admin rights needed) and adds Start menu and desktop shortcuts.
3. Windows may show a blue **"Windows protected your PC"** (SmartScreen) message, because the app isn't code-signed. Click **More info → Run anyway**.

**Requirements:** Windows 10 or 11 (64-bit). Nothing else needs installing.

## First run

1. Plug in the projector. Stagelight puts its output on it full screen by itself (or choose the screen from **Projector** at the top).
2. Press **Import** and choose a folder of songs, Bibles, themes or media, for example everything you exported from your previous program.
3. Turn on Windows **Mobile hotspot**, connect your phone to it, press **Phone remote** and scan the code.
4. When Windows Firewall asks about Stagelight, click **Allow**, including on public networks, or your phone won't be able to connect.

## Updates

Stagelight checks this repository for a new version shortly after it starts and every few hours, downloads it in the background, and installs it when you choose **Restart and update** or the next time you close it, so it never updates in the middle of a service. Click the **Stagelight** name at the top left for **Check for updates** and the list of what's new.

## Your data

- Everything is stored **only on your PC**, in `%AppData%\Stagelight\`: songs, Bibles, themes, media, the service and settings. There's no account and nothing is uploaded.
- Your phone talks to the laptop directly over your Wi-Fi or hotspot, not over the internet.
- The only internet connections Stagelight makes are the update check to GitHub, and loading YouTube videos or web pages if you add them to a service.

## Uninstall

**Windows Settings → Apps → Installed apps → Stagelight → Uninstall.** Your data is left in `%AppData%\Stagelight\` in case you reinstall; delete that folder too if you want it gone.

## Feedback & bugs

[Open an issue](https://github.com/Lord-Raven1/Stagelight-Release/issues/new) here. You'll need a GitHub account, and issues are **public**, so please don't include anything private.

## Support

Stagelight is free. If it helps your church, you can leave a tip on **[Ko-fi](https://ko-fi.com/lordraven)** (card or PayPal), or use **♥ Support Stagelight** in the app's About window. Thank you!

## Downloads in each release

| File | What it is |
|---|---|
| `Stagelight-Setup-<version>.exe` | The installer: this is the one you want. |
| `latest.yml`, `*.blockmap` | Update files used by the app itself. |
| Source code (zip / tar.gz) | Added automatically by GitHub; contains only this README, not the app. |

---

Made by **Lord-Raven1**.
