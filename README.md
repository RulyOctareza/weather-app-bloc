<p align="center">
  <img src="docs/preview/hero.svg" alt="Weather App BLoC — ilustrasi aplikasi cuaca" width="100%">
</p>

<h1 align="center">Weather App — BLoC</h1>

<p align="center">
  <b>Cuaca real-time berdasarkan lokasimu.</b><br>
  Flutter · BLoC · OpenWeather
</p>

<p align="center">
  <a href="https://flutter.dev"><img alt="Flutter" src="https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter&logoColor=white"></a>
  <a href="https://bloclibrary.dev"><img alt="BLoC" src="https://img.shields.io/badge/State-BLoC-2496ED"></a>
  <img alt="OpenWeather" src="https://img.shields.io/badge/API-OpenWeather-FFB300">
</p>

---

## ✨ Preview

<p align="center">
  <img src="docs/preview/hero.png" alt="Mockup gelap Weather App" width="90%">
</p>

<p align="center">
  <img src="Screenshot_1742693075.png" alt="Screenshot Weather App" width="260">
</p>

---

## 📖 Tentang

Aplikasi cuaca minimalis: lokasi pengguna dideteksi otomatis, lalu data cuaca real-time
diambil dari OpenWeather API. Dibuat sebagai latihan menerapkan **BLoC** untuk state
management yang scalable dan mudah dirawat.

---

## 🌟 Fitur

- 📍 **Deteksi lokasi otomatis** dengan `geolocator`
- 🌦️ **Cuaca real-time** dari OpenWeather API
- 🔄 **State management BLoC** yang reaktif
- 🔑 **API key aman** lewat `flutter_dotenv`
- 🎨 UI minimalis dan mudah dibaca

---

## 🛠️ Tech Stack

| Area | Pilihan |
|---|---|
| Framework | Flutter |
| State management | `flutter_bloc` 9, `bloc` 9 |
| Lokasi | `geolocator` |
| Cuaca | `weather` 3 |
| Konfigurasi | `flutter_dotenv` |
| Utilitas | `intl`, `equatable` |

---

## 🧱 Struktur

```text
lib/
├── bloc/           # Event, state, dan bloc cuaca
├── data/           # Model & repository cuaca
├── screens/        # Halaman utama
└── main.dart
```

---

## 🚀 Menjalankan

1. Buat file `.env` di root:
   ```env
   OPENWEATHER_API_KEY=your_key_here
   ```
2. Daftarkan `.env` di `pubspec.yaml` pada bagian `assets`.
3. Jalankan:
   ```bash
   flutter pub get
   flutter run
   ```

---

## 🔭 Rencana

- Rekomendasi pakaian berdasarkan cuaca
- Animasi cuaca
- Multi-bahasa

---

## 🧪 Testing

```bash
flutter analyze
flutter test
```
