# PiMana — Official Public Release Channel

This repository serves as the official public over-the-air (OTA) distribution and update channel for **PiMana** (Private Personal Automotive Navigation for Malaysians).

## Latest Release: v0.7.0 (Build 9)

- **Direct Download**: [pimana-v0.7.0.apk](pimana-v0.7.0.apk) (0.49 MB)
- **Mirror APK**: [pimana.apk](pimana.apk)
- **Release Date**: 2026-11-03
- **Package Name**: `com.pimana.app`
- **Min SDK**: Android 5.0 (API 21)
- **Target SDK**: Android 9.0 (API 28)

### What's New in v0.7.0:
- 🚀 Sokongan Navigasi Merentas Pulau (Penang Island): Pengesanan pintar dan penjanaan laluan merentasi selat ke Pulau Pinang dari tanah besar melalui dwi-jambatan; Jambatan Pertama (E36) atau Jambatan Kedua Sultan Abdul Halim Muadzam Shah (E28)
- 🚀 Penyesuaian Destinasi Pintar (Smart Destination Snapping): Pengecaman automatik bagi puncak atau kawasan larangan kenderaan seperti Bukit Bendera (Penang Hill), dialihkan terus ke Stesen Keretapi Bukit Bendera & Tempat Letak Kereta Bertingkat Air Itam dengan panduan visual
- 🚀 Kelajuan Inter-City & Koridor Lebuhraya Luar Talian: Pengoptimuman drastik carian jarak jauh (PLUS Utara E1, PLUS Selatan E2, LPT E8) mengurangkan kelewatan OSRM daripada 200s+ ke ~1.5s dengan fallback lebuhraya deterministik 0ms luar talian
- 🚀 Pembaikan Bounding Box & Mod Simulasi: Membaiki ralat inverted bounding box MapLibre GL bagi laluan barat laut (KLCC ke Ipoh/Kedah) serta penyegerakan input tersuai pada laci simulasi
- 🚀 Polisi Paparan Had Laju Tulen (Sifar-Andaian): Menghapuskan semua tekaan had laju. Lencana had laju kokpit hanya dipaparkan apabila menghampiri kamera AwAS/AES yang sahih (<=1,500m) atau amaran radar aktif; jika tiada kamera AwAS, lencana disembunyikan sepenuhnya

---

### 🚗 Panduan Penggunaan pada Android Auto (Skrin Kenderaan)

Sekiranya anda ingin memaparkan PiMana pada skrin Android Auto kereta anda:

1. **Aktifkan Developer Mode & Unknown Sources di Android Auto**:
   - Buka **Settings > Android Auto** di telefon anda.
   - Tatal ke bawah sehingga bahagian **Version**.
   - Ketuk pada perkataan **Version sebanyak 10 kali** sehingga mod pembangun aktif.
   - Tekan ikon 3-titik di bucu atas kanan ➔ pilih **Developer settings** ➔ tandakan **Unknown sources**.

2. **Pasang APK Menggunakan KingInstaller**:
   - Google secara lalai menyekat aplikasi luar (*sideload*) daripada dipaparkan di Android Auto melainkan ia dipasang dengan pengenalan Google Play Store.
   - Muat turun aplikasi percuma **[KingInstaller](https://github.com/fcaronte/KingInstaller/releases)** di telefon anda.
   - Buka KingInstaller, pilih fail APK `pimana-v0.7.0.apk`, dan tekan **"Install as king"**.
   - Buka **Android Auto > Customize Launcher** di telefon anda. Ikon **PiMana** kini akan muncul dan boleh diaktifkan.

> [!NOTE]
> **Penting Mengenai Kemas Kini OTA & Android Auto**:
> - Bagi penggunaan biasa (telefon pintar / Android Head Unit berasingan): Kemas kini OTA dalam aplikasi berfungsi 100% secara langsung.
> - Bagi penggunaan melalui **Android Auto**: Apabila versi baharu dikeluarkan kelak, sila pasang kemas kini melalui KingInstaller ("Install as king") bagi mengekalkan cop pengesahan Google Play Store (`com.android.vending`) agar aplikasi kekal tersenarai di skrin Android Auto.

---

### Previous Releases / Versi Terdahulu (`old_version/`):
- [pimana-v0.6.1.apk](old_version/pimana-v0.6.1.apk) (0.48 MB)
- [pimana-v0.6.0.apk](old_version/pimana-v0.6.0.apk) (0.48 MB)
- [pimana-v0.5.1.apk](old_version/pimana-v0.5.1.apk) (0.48 MB)
- [pimana-v0.4.0.apk](old_version/pimana-v0.4.0.apk) (0.46 MB)

---
*Official Telegram Channel*: https://t.me/pimana
