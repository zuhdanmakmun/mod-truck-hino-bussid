# Mod Truck Hino 500 700 BUSSID — Content Repository

Repository ini adalah **sumber data konten** untuk aplikasi Android **"Mod Truck Hino 500 700 BUSSID"** (ZM Studio Labs), sebuah katalog mod truk Hino untuk game Bus Simulator Indonesia (BUSSID).

Aplikasi ini bersifat **online** — seluruh data mod (nama, deskripsi, gambar, link unduhan) diambil langsung dari `mods.json` di repo ini secara real-time, sehingga konten bisa diperbarui kapan saja tanpa perlu update aplikasi di Play Store.

---

## 📁 Struktur Repository

```
mod-truck-hino-bussid/
├── mods.json           # Katalog utama — daftar seluruh mod (fetch oleh app)
├── config.json          # Konfigurasi app (status maintenance, dll)
├── thumbnails/           # Gambar thumbnail tiap mod (.webp)
└── README.md             # File ini
```

## 🗂️ Kategori Mod

| Kategori | Deskripsi |
|---|---|
| 🌴 Muatan Sawit | Truk dengan muatan kelapa sawit |
| 🔊 Sound System | Truk pengangkut sound system / DJ |
| 🚛 Hino 500 700 | Berbagai varian muatan Hino 500 & 700 |
| 🛣️ Truck Sumatra | Truk bergaya khas Sumatra |
| ⛰️ Truck Kalimantan | Truk bergaya khas Kalimantan |

## 📦 File Mod

Setiap mod tersedia dalam format `.bussidmod` atau `.bussidvehicle`, di-host di [GitHub Releases](../../releases) repo ini agar mendukung file berukuran besar tanpa batasan repo Git biasa.

| Format | Lokasi instalasi di BUSSID |
|---|---|
| `.bussidmod` | `Internal Storage/BUSSID/Mods` |
| `.bussidvehicle` | `Internal Storage/BUSSID/Vehicles` |

## 🔗 Endpoint yang Digunakan Aplikasi

```
Base URL:
https://raw.githubusercontent.com/zuhdanmakmun/mod-truck-hino-bussid/main/

Katalog mod:
https://raw.githubusercontent.com/zuhdanmakmun/mod-truck-hino-bussid/main/mods.json

Thumbnail:
https://raw.githubusercontent.com/zuhdanmakmun/mod-truck-hino-bussid/main/thumbnails/{nama_file}.webp

File mod:
https://github.com/zuhdanmakmun/mod-truck-hino-bussid/releases/download/v1.0/{nama_file}.bussidmod
```

## ⚠️ Disclaimer

Aplikasi "Mod Truck Hino 500 700 BUSSID" adalah **companion app tidak resmi** dan **tidak berafiliasi** dengan Maleo selaku developer resmi Bus Simulator Indonesia. Seluruh konten mod dalam repo ini merupakan hasil karya komunitas BUSSID yang dibagikan secara gratis untuk keperluan non-komersial.

Jika Anda adalah pembuat asli salah satu mod dan ingin konten Anda dihapus dari katalog ini, silakan hubungi kami.

---

**Developer:** ZM Studio Labs
**Platform:** Android · Google Play Store
**Privacy Policy:** [zmstudiolabs.blogspot.com/p/privacy-policy.html](https://zmstudiolabs.blogspot.com/p/privacy-policy.html)
