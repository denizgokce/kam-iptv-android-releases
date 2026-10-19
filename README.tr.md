<p align="center">
  <img src="assets/icon.png" width="120" alt="KAM IPTV">
</p>

<h1 align="center">Android için KAM IPTV</h1>

<p align="center">
  Android telefon, tablet ve Android TV için IPTV oynatıcısı.<br>
  <b><a href="../../releases/latest">Son sürümü indir</a></b>
</p>

<p align="center">
  <a href="README.md">English</a> · Türkçe · <a href="README.de.md">Deutsch</a>
</p>

---

> **Listeni kendin getir.** KAM IPTV yalnızca bir oynatıcıdır. İçinde hiçbir
> kanal, film, dizi, liste ya da sağlayıcı yoktur — kendininkini eklersin.
> [Sorumluluk reddi](DISCLAIMER.tr.md)'ne bak.

Bu depoda **yalnızca kurulum dosyaları** var. Kaynak kodu açık değildir.
macOS ve Windows için [KAM IPTV Player](https://github.com/denizgokce/kam-iptv-player-releases)'a bak.

## İndirme

[Son sürümü](../../releases/latest) aç ve cihazına uyan dosyayı seç:

| Dosya | Kimin için |
|---|---|
| `kam-iptv-tv.apk` | Android TV ve TV kutuları (Mi Box, Google TV'li Chromecast, Fire TV) |
| `kam-iptv-tablet.apk` | Android tabletler |
| `kam-iptv-phone.apk` | Android telefonlar (64 bit) |

Android 7.0 ve sonrası. Her sürümde dosyaların SHA-256 özetleri `SHA256SUMS.txt` içinde.

En yeni TV derlemesinin adresi hep aynı — kumandayla yazmak için kısa:

```
https://github.com/denizgokce/kam-iptv-android-releases/releases/latest/download/kam-iptv-tv.apk
```

## Kurulum

Uygulama Google Play'de değil; Android bir kez kuruluma izin vermeni istiyor.

### Telefon ya da tablet

1. `.apk` dosyasını cihazda indir ve aç.
2. Sorulunca tarayıcına ya da dosya yöneticine **bilinmeyen uygulamaları yükleme** izni ver.
3. Play Protect bilinmeyen geliştirici uyarısı verirse **Yine de yükle**'yi seç.

### Android TV / TV kutusu

1. Play Store'dan ya da Amazon Appstore'dan **Downloader**'ı (AFTVnews) kur.
2. Downloader'da yukarıdaki TV adresini yaz ve kur.
3. Sorulunca Downloader'a bilinmeyen uygulamaları yükleme izni ver.

Ya da ADB olan bir bilgisayardan: `adb install -r kam-iptv-tv.apk`.

### Güncelleme

Yeni `.apk`'yi eskisinin üstüne kur. Listelerin, favorilerin ve geçmişin korunur.

## Neler yapıyor

**Kaynaklar**
- Sağlayıcının hesap bilgileriyle (sunucu, kullanıcı adı, parola) giriş yap ya
  da bir adresten, dosyadan veya yapıştırılan metinden M3U / M3U8 yükle.
- Birden çok liste; yenileme yalnız değişeni çeker.

**Gezinme**
- Ana Sayfa, Canlı, Diziler, Filmler, Arama, Son Eklenenler, Favoriler ve Son İzlenenler.
- Kumanda için yapılmış kendi Android TV arayüzü: yüzen menü, tam ekran
  tanıtım bandı ve ekran klavyesi. **Basit görünüm** — dört kutu, tek basışta
  oynatma — TV'de varsayılan.
- Tabletler dokunmaya uyarlanmış TV arayüzünü kullanır.
- Yıldızlı klasörler, kendi klasör grupların, kayıtlı süzgeç çipleri
  (*HD ama FHD değil*), ada, eklenme tarihine, puana ya da izlenme sayısına göre sıralama.

**Bilgiler**
- Ücretsiz Cinemeta servisinden afiş, konu, puan ve oyuncular, diller arası
  eşleşmeyle. Tek anahtarla kapanır; o zaman uygulamadan hiçbir şey çıkmaz.

**Oynatma**
- Canlı kanallar, filmler ve bölümler; ses ve altyazı seçimi.
- Apple TV'deki gibi, basılı tuttukça hızlanan kumandayla ileri-geri sarma.
- Bir şey ters gidince açık mesajlar: başlık açılamadı, sağlayıcı çalışmıyor,
  desteklenmeyen video.
- Filmler ve bölümler indirilip çevrimdışı izlenebilir.

## Gizlilik

- Hesap yok, telemetri yok, analitik yok.
- Listelerin, sağlayıcı bilgilerin, favorilerin ve geçmişin cihazında kalır.
- Kendiliğinden bağlanılan tek dış servis Cinemeta'dır, yalnız başlık adlarıyla,
  ve kapatılabilir.

## Sorun bildirme

Cihazını, Android sürümünü, uygulama sürümünü ve ne olduğunu yazarak bir
[issue](../../issues) aç. **Listeni, sağlayıcı adresini, kullanıcı adını ya da
parolanı asla paylaşma** — yayın adresleri bunları içerir.

---

Telif hakkı © 2026 KAM IPTV yazarları. Tüm hakları saklıdır. [LICENSE](LICENSE)
ve [sorumluluk reddi](DISCLAIMER.tr.md).
