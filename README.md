# Görev Takip Uygulaması

Günlük görevlerinizi yönetmek ve takip etmek için geliştirilmiş Flutter uygulaması.

## Özellikler

✨ **Görev Yönetimi**
- Yeni görev ekleme
- Görevleri tamamlama/silme
- Görevlerinizi listede görüntüleme

🎨 **Tasarım**
- Modern ve kullanıcı dostu arayüz
- Özel tema desteği
- Google Fonts entegrasyonu

💾 **Veri Saklama**
- Görevler cihazda saklanır
- Uygulama kapatılsa da veriler kaybolmaz

## Teknolojiler

- **Flutter** - UI Framework
- **Dart** - Programlama Dili
- **Provider** - State Management
- **Shared Preferences** - Local Storage
- **Google Fonts** - Typography
- **Flutter Speed Dial** - FAB Widget

## Kurulum

### Gereksinimler
- Flutter SDK (3.7.2+)
- Dart SDK
- Android Studio / Xcode (emülatör için)

### Adımlar

1. **Repository'yi klonla**
```bash
git clone https://github.com/kullanıcıadı/gorev-takip-uygulamasi.git
cd gorev-takip-uygulamasi
```

2. **Paketleri yükle**
```bash
flutter pub get
```

3. **Uygulamayı çalıştır**
```bash
flutter run
```

## Proje Yapısı

```
lib/
├── main.dart              # Ana giriş noktası
├── tema.dart              # Tema ayarları
├── ekranlar/              # Arayüz ekranları
│   ├── ana_ekran.dart     # Ana sayfa
│   └── giris_ekran.dart   # Giriş sayfası
└── model/                 # Veri modelleri
    └── gorev.dart         # Görev modeli
```

## Kullanım

1. **Görev Ekle:** Sağ alttaki "+" butonuna tıkla
2. **Görev Tamamla:** Görev üzerine tıkla
3. **Görev Sil:** Görevde kaydır veya sil butonuna tıkla

