# Köprü

Telefon ↔ bilgisayar arası dosya, metin ve not aktarımı. Tek dosya: `index.html`.

## GitHub Pages'te yayınlama
1. github.com'da **New repository** → ad: `kopru`, **Public** → Create.
2. **uploading an existing file** bağlantısına tıkla, `index.html` ve `README.md` dosyalarını sürükle → **Commit changes**.
3. **Settings → Pages** → Source: **Deploy from a branch**, Branch: **main** / **(root)** → Save.
4. 1-2 dakika sonra site: `https://KULLANICI-ADIN.github.io/kopru/`

## Kullanım
1. Bilgisayarda siteyi aç.
2. Telefonun kamerasıyla QR kodu okut.
3. "Bağlandı ✓" yazınca dosya seç veya metin gönder.

İki cihazda da sayfa açık olmalı.

## Bilmen gerekenler
- Dosyalar WebRTC ile cihazdan cihaza gider; eşleşme için PeerJS'in ücretsiz sunucusu kullanılır.
- Hız ağına bağlıdır; aynı Wi-Fi'da en hızlıdır. Bazı mobil veri, okul ve iş ağlarında bağlantı kurulamayabilir.
- Eşleşme kodunu/QR'ı kimseyle paylaşma: kodu bilen bağlanabilir ve notlarını alır.
- Gelen dosya bellekte tutulur; çok büyük dosyalarda (yüzlerce MB üstü) telefon zorlanabilir.
- Notlar tarayıcıda saklanır, ara sıra **Yedek al**.
