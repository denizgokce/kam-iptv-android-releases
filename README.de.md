<p align="center">
  <img src="assets/icon.png" width="120" alt="KAM IPTV">
</p>

<h1 align="center">KAM IPTV für Android</h1>

<p align="center">
  Ein IPTV-Player für Android-Smartphones, -Tablets und Android TV.<br>
  <b><a href="../../releases/latest">Neueste Version herunterladen</a></b>
</p>

<p align="center">
  <a href="README.md">English</a> · <a href="README.tr.md">Türkçe</a> · Deutsch
</p>

---

> **Bring deine eigene Playlist mit.** KAM IPTV ist nur ein Player. Er enthält
> keine Sender, Filme, Serien, Playlists oder Anbieter – du fügst deine eigenen
> hinzu. Siehe [Haftungsausschluss](DISCLAIMER.de.md).

Dieses Repository enthält **nur Installationsdateien**. Der Quellcode ist nicht öffentlich.
Für macOS und Windows siehe [KAM IPTV Player](https://github.com/denizgokce/kam-iptv-player-releases).

## Download

Öffne die [neueste Version](../../releases/latest) und wähle die Datei für dein Gerät:

| Datei | Für |
|---|---|
| `kam-iptv-tv.apk` | Android TV und TV-Boxen (Mi Box, Chromecast mit Google TV, Fire TV) |
| `kam-iptv-tablet.apk` | Android-Tablets |
| `kam-iptv-phone.apk` | Android-Smartphones (64 Bit) |

Android 7.0 oder neuer. Zu jeder Version stehen die SHA-256-Prüfsummen aller
Dateien in `SHA256SUMS.txt`.

Der neueste TV-Build hat immer dieselbe kurze Adresse – praktisch zum Eintippen
mit der Fernbedienung:

```
https://github.com/denizgokce/kam-iptv-android-releases/releases/latest/download/kam-iptv-tv.apk
```

## Installation

Die App ist nicht bei Google Play, daher fragt Android einmal nach der Erlaubnis.

### Smartphone oder Tablet

1. Lade die `.apk` auf dem Gerät herunter und öffne sie.
2. Erlaube deinem Browser bzw. Dateimanager auf Nachfrage, **unbekannte Apps zu installieren**.
3. Warnt Play Protect vor einem unbekannten Entwickler, wähle **Trotzdem installieren**.

### Android TV / TV-Box

1. Installiere **Downloader** (von AFTVnews) aus dem Play Store oder dem Amazon Appstore.
2. Gib in Downloader die TV-Adresse oben ein und installiere.
3. Erlaube Downloader auf Nachfrage, unbekannte Apps zu installieren.

Oder von einem Rechner mit ADB: `adb install -r kam-iptv-tv.apk`.

### Aktualisieren

Installiere die neue `.apk` über die alte. Playlists, Favoriten und Verlauf bleiben erhalten.

## Was er kann

**Quellen**
- Anmeldung mit den Zugangsdaten deines Anbieters (Server, Benutzername,
  Passwort) oder M3U / M3U8 von einer Adresse, aus einer Datei oder als eingefügter Text.
- Mehrere Playlists; beim Aktualisieren wird nur Geändertes geladen.

**Stöbern**
- Startseite, Live, Serien, Filme, Suche, Neu hinzugefügt, Favoriten und Zuletzt gesehen.
- Eine eigene Android-TV-Oberfläche für die Fernbedienung: schwebendes Menü,
  Vollbild-Banner und Bildschirmtastatur. Die **einfache Ansicht** – vier
  Kacheln, ein Druck zum Abspielen – ist auf dem TV Standard.
- Tablets nutzen die TV-Oberfläche, an Touch angepasst.
- Markierte Ordner, eigene Ordnergruppen, gespeicherte Filter-Chips
  (*HD, aber nicht FHD*), Sortierung nach Name, Hinzufügedatum, Bewertung oder Wiedergaben.

**Details**
- Poster, Handlung, Bewertungen und Besetzung vom kostenlosen Dienst Cinemeta,
  sprachübergreifend zugeordnet. Ein Schalter schaltet es ab; dann verlässt nichts die App.

**Wiedergabe**
- Live-Sender, Filme und Folgen, mit Audio- und Untertitelauswahl.
- Spulen mit der Fernbedienung, das schneller wird, je länger du hältst – wie auf Apple TV.
- Klare Meldungen bei Fehlern: Titel konnte nicht geöffnet werden, Anbieter
  nicht erreichbar, nicht unterstütztes Video.
- Filme und Folgen lassen sich herunterladen und offline ansehen.

## Datenschutz

- Kein Konto, keine Telemetrie, keine Analyse.
- Deine Playlists, Anbieterdaten, Favoriten und dein Verlauf bleiben auf deinem Gerät.
- Der einzige externe Dienst, der von selbst kontaktiert wird, ist Cinemeta –
  nur mit Titelnamen, und abschaltbar.

## Ein Problem melden

Eröffne ein [Issue](../../issues) mit Gerät, Android-Version, App-Version und
was passiert ist. **Poste niemals deine Playlist, Anbieteradresse, deinen
Benutzernamen oder dein Passwort** – Streamadressen enthalten sie.

---

Copyright © 2026 die KAM-IPTV-Autoren. Alle Rechte vorbehalten. Siehe
[LICENSE](LICENSE) und den [Haftungsausschluss](DISCLAIMER.de.md).
