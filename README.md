# 💝 Arkadaşlık Kutusu - Web Versiyonu

Sevgili arkadaşlarınızdan gelen sesli mesajları dinleyebileceğiniz özel bir web uygulaması.

## 📱 iOS'ta Nasıl Kullanılır

### Yöntem 1: Tarayıcıdan Açma (En Kolay)
1. `index.html` dosyasını bir web sunucusuna yükleyin (GitHub Pages, Netlify, Vercel vb.)
2. iPhone'unuzda Safari ile siteyi açın
3. Kartlara tıklayarak sesli mesajları dinleyin

### Yöntem 2: Ana Ekrana Ekleme (Uygulama Gibi)
1. Safari'de siteyi açın
2. Aşağıdaki paylaş butonuna ⬆️ basın
3. "Ana Ekrana Ekle" seçeneğini seçin
4. "Ekle" butonuna basın
5. Artık ana ekranınızdan uygulama gibi açabilirsiniz!

### Yöntem 3: Lokal Test (Geliştirici)
Bilgisayarınızda:
```bash
cd arkadaslik-kutusu
python3 -m http.server 8000
```
Sonra iPhone'unuzda aynı WiFi ağındaysanız:
- `http://[BILGISAYAR-IP-ADRESI]:8000` adresini Safari'de açın

## 📂 Dosya Yapısı
```
arkadaslik-kutusu/
├── index.html              # Ana sayfa
├── manifest.json           # PWA yapılandırması
├── README.md              # Bu dosya
└── resources/
    ├── audio/             # Sesli mesajlar
    │   ├── ceren.mp3
    │   ├── didem.mp3
    │   ├── esma.mp3
    │   ├── merve.mp3
    │   ├── nisa.mp3
    │   └── sena.mp3
    └── images/            # Fotoğraflar
        ├── ceren.jpeg
        ├── didem.jpeg
        ├── emoji.png
        ├── esma.jpeg
        ├── merve.jpeg
        ├── nisa.jpeg
        └── sena.jpeg
```

## ✨ Özellikler
- 📱 iOS Safari'de mükemmel çalışır
- 🎵 Sesli mesaj oynatma/duraklatma
- 📊 İlerleme çubuğu ve süre gösterimi
- 💅 Modern ve şık tasarım
- 🌙 Karanlık mod desteği
- 📲 Ana ekrana eklenebilir (PWA)
- ⚡ Hızlı ve responsive

## 🚀 Yayınlama Önerileri

### GitHub Pages (Ücretsiz)
1. GitHub'da yeni bir repository oluşturun
2. Tüm dosyaları yükleyin
3. Settings > Pages > "main" branch'i seçin
4. Siteniz `https://[kullaniciadi].github.io/[repo-adi]` adresinde olacak

### Netlify (Ücretsiz)
1. [netlify.com](https://netlify.com)'a kaydolun
2. Klasörü sürükle-bırak ile yükleyin
3. Anında canlıya alınır!

### Vercel (Ücretsiz)
1. [vercel.com](https://vercel.com)'a kaydolun
2. Projeyi import edin
3. Otomatik deploy olur

## 💡 İpuçları
- **Ses çalmazsa**: İlk önce ekrana bir kez dokunun (iOS güvenlik özelliği)
- **Yavaş yükleniyorsa**: Ses dosyaları büyük, WiFi kullanın
- **Offline kullanım**: Ana ekrana ekledikten sonra WiFi olmadan da açılır
- **Tam ekran**: Ana ekrana eklerseniz tam ekran olarak açılır

## 🎨 Özelleştirme
`index.html` dosyasındaki stil kodlarını değiştirerek renkleri ve tasarımı özelleştirebilirsiniz.

---

💌 Sevgiyle hazırlandı
