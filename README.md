# ZipTide ve Altın Fermuar — Çocuk Oyunu 🧬🎮

**GİKAL iGEM 2026 • ZipTide** projesinin "ZipTide ve Altın Fermuar — Küçük Bekçilerin Masalı"
hikayesinden uyarlanan, **5–6 yaş** için interaktif bir hikâye oyunu.

Oyun, hikâyenin 8 sahnesini takip eder ve her sahnede küçük çocukların kolayca
yapabileceği basit bir dokunma/sürükleme etkinliği sunar.

## Oynanış

| Sahne | Hikâye | Etkinlik |
|------|--------|----------|
| 1 | Huzurlu Dünya | Bekçilere dokun, seni selamlasınlar |
| 2 | Bekçilerin Görevi | Güzel şeyleri (su, kırıntı) içeri al; kara şeylere dokunma |
| 3 | Meraklı Zonulin | Zonulin bulutu fermuarı aralar |
| 4 | Karışan Düzen | Renkler solar; üzgün bekçileri sev ❤️ |
| 5 | Bir Kahraman Doğuyor | Parlayan parçalara dokun, ZipTide'ı tamamla ✨ |
| 6 | Yardım Yetişiyor | ZipTide gelir, merhaba de 👋 |
| 7 | Usul Usul Onarım | **Ana oyun:** altın çekmeyi tut, sağa sürükle, fermuarı kapat 🤏 |
| 8 | Yeniden Huzur | Kutlama! Küçük bir bekçi kahraman oldun 🎉 |

## Çocuk dostu tasarım

- **Sesli anlatım** — Her sahne Türkçe okunur (`🔊 Dinle`). Henüz okuma bilmeyen çocuklar için ideal.
- **Büyük dokunma alanları** — Küçük parmaklar için geniş, affedici hedefler.
- **Nazik ses efektleri** — Web Audio ile üretilen yumuşak melodiler; kazanınca ⭐ ve konfeti.
- **Ses aç/kapa** — Sol üstteki 🔊 düğmesiyle sesi ve anlatımı kapatabilirsiniz.
- **Tablet & telefon uyumlu** — Dokunmatik ekranlar ve yatay ekran için tasarlandı.
- **İnternet gerekmez** — Tek dosya + görseller; tamamen çevrimdışı çalışır.

## Eğitici mesaj

Hikâyedeki "küçük bekçiler" bağırsak duvarındaki **sıkı bağlantı (tight junction)**
hücrelerini, "altın fermuar" ise vücudu koruyan **bariyeri** temsil eder.
**Zonulin** bu bariyeri gevşeten gerçek bir proteindir; **ZipTide** ise ekibimizin
bilgisayarda tasarladığı, bariyeri onaran küçük bir peptittir.

## Çalıştırma

`index.html` dosyasını herhangi bir modern tarayıcıda açmanız yeterli.

```bash
# veya basit bir yerel sunucu ile:
python3 -m http.server 8000
# tarayıcıda: http://localhost:8000
```

## Dosyalar

- `index.html` — Oyunun tamamı (HTML + CSS + JS, tek dosya).
- `img/` — Hikâye kitabından uyarlanan sahne görselleri.
