<p align="center">
  <img src="assets/icon.png" width="120" alt="KAM IPTV">
</p>

<h1 align="center">KAM IPTV for Android</h1>

<p align="center">
  An IPTV player for Android phones, tablets and Android TV.<br>
  <b><a href="../../releases/latest">Download the latest release</a></b>
</p>

<p align="center">
  English · <a href="README.tr.md">Türkçe</a> · <a href="README.de.md">Deutsch</a>
</p>

---

> **Bring your own playlist.** KAM IPTV is only a player. It ships with no
> channels, films, series, playlists or provider of any kind — you add your
> own. See the [disclaimer](DISCLAIMER.md).

This repository holds **installers only**. The source code is not public.
For macOS and Windows, see [KAM IPTV Player](https://github.com/denizgokce/kam-iptv-player-releases).

## Download

Open the [latest release](../../releases/latest) and pick the file for your device:

| File | For |
|---|---|
| `kam-iptv-tv.apk` | Android TV and TV boxes (Mi Box, Chromecast with Google TV, Fire TV) |
| `kam-iptv-tablet.apk` | Android tablets |
| `kam-iptv-phone.apk` | Android phones (64-bit) |

Android 7.0 or later. Each release lists the SHA-256 checksum of every file in
`SHA256SUMS.txt`.

The newest TV build always has the same short address — handy for typing on a
remote:

```
https://github.com/denizgokce/kam-iptv-android-releases/releases/latest/download/kam-iptv-tv.apk
```

## Installing

The app is not on Google Play, so Android asks you to allow the install once.

### Phone or tablet

1. Download the `.apk` on the device and open it.
2. When asked, allow your browser or file manager to **install unknown apps**.
3. If Play Protect warns about an unknown developer, choose **Install anyway**.

### Android TV / TV box

1. Install **Downloader** (by AFTVnews) from the Play Store or Amazon Appstore.
2. In Downloader, enter the TV address above and install.
3. Allow Downloader to install unknown apps when asked.

Or, from a computer with ADB: `adb install -r kam-iptv-tv.apk`.

### Updating

Install the new `.apk` over the old one. Your playlists, favourites and
history are kept.

## What it does

**Sources**
- Sign in with your provider's account details (server, username, password),
  or load an M3U / M3U8 from an address, a file or pasted text.
- More than one playlist; refresh only fetches what changed.

**Browsing**
- Home, Live, Series, Movies, Search, Recently Added, Favourites and Recents.
- An Android TV interface of its own, made for the remote: a floating menu,
  a full-screen hero and an on-screen keyboard. **Simple view** — four tiles
  and one press to play — is the default on TV.
- Tablets run the TV interface adapted for touch.
- Starred folders, your own folder groups, saved filter chips (*HD but not FHD*),
  and sorting by name, date added, rating or play count.

**Details**
- Posters, plots, ratings and cast from the free Cinemeta service, matched
  across languages. One switch turns it off; then nothing leaves the app.

**Playback**
- Live channels, films and episodes, with audio and subtitle selection.
- Remote scrubbing that speeds up the longer you hold, as on Apple TV.
- Clear messages when something fails: the title could not be opened, the
  provider is down, unsupported video.
- Films and episodes can be downloaded and watched offline.

## Privacy

- No account, no telemetry, no analytics.
- Your playlists, provider details, favourites and history stay on your device.
- The only outside service contacted on its own is Cinemeta, with title names
  only, and it can be switched off.

## Reporting a problem

Open an [issue](../../issues) with your device, Android version, the app
version and what happened. **Never post your playlist, provider address,
username or password** — stream addresses contain them.

---

Copyright © 2026 the KAM IPTV authors. All rights reserved. See [LICENSE](LICENSE)
and the [disclaimer](DISCLAIMER.md).
