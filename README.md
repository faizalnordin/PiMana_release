# PiMana — Official Public Release Channel

This repository serves as the official public over-the-air (OTA) distribution and update channel for **PiMana** (Private Personal Automotive Navigation for Malaysians).

## Latest Release: v0.9.1 (Build 17)

- **Direct Download**: [pimana-v0.9.1.apk](pimana-v0.9.1.apk) (0.54 MB)
- **Mirror APK**: [pimana.apk](pimana.apk)
- **Release Date**: 2026-11-11
- **Package Name**: `com.pimana.app`
- **Min SDK**: Android 5.0 (API 21)
- **Target SDK**: Android 9.0 (API 28)

### What's New in v0.9.1:
- 🚀 FB-027: Kawalan Zum Peta Manual & Penunjuk %: Menambah butang terapung (+ / -) dan lencana peratusan (%) pada kokpit dengan zum lalai 110% (zoom 18.92).
- 🚀 FB-027: Zum Pintar Kedudukan Semasa: Menyusuri peta (swiping/browsing) dan menekan butang pusatkan semula (recenter) akan sentiasa kembali ke tahap zum kenderaan terkini (lalai 110%).
- 🚀 FB-027: Penapis Kestabilan Arah Kelajuan Rendah (Anti-Hop): Mengunci bearing kenderaan apabila kelajuan < 3.5 km/j bagi menghapuskan kursor melompat/berputar di lampu isyarat (mod roaming & navigating).
- 🚀 FB-028: Pelancaran Selamat Android Auto (KingInstaller): Melaksanakan launchMainActivity() dalam PiManaCarAppService.java dengan bendera selamat bagi menghapuskan NullPointerException pada unjuran skrin kenderaan.
- 🚀 FB-028: Format Masa ETA Padat: Menyokong paparan jam & minit 'Xhr Ymins' (contoh: '1hr 2mins', '4hrs 25mins', '1hr', '45 mins') dengan sebutan suara tepat.

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
   - Buka KingInstaller, pilih fail APK `pimana-v0.9.1.apk`, dan tekan **"Install as king"**.
   - Buka **Android Auto > Customize Launcher** di telefon anda. Ikon **PiMana** kini akan muncul dan boleh diaktifkan.

> [!NOTE]
> **Penting Mengenai Kemas Kini OTA & Android Auto**:
> - Bagi penggunaan biasa (telefon pintar / Android Head Unit berasingan): Kemas kini OTA dalam aplikasi berfungsi 100% secara langsung.
> - Bagi penggunaan melalui **Android Auto**: Apabila versi baharu dikeluarkan kelak, sila pasang kemas kini melalui KingInstaller ("Install as king") bagi mengekalkan cop pengesahan Google Play Store (`com.android.vending`) agar aplikasi kekal tersenarai di skrin Android Auto.

---

### Previous Releases / Versi Terdahulu (`old_version/`):
- [pimana-v0.9.0.apk](old_version/pimana-v0.9.0.apk) (0.51 MB)
- [pimana-v0.8.1.apk](old_version/pimana-v0.8.1.apk) (0.49 MB)
- [pimana-v0.8.0.apk](old_version/pimana-v0.8.0.apk) (0.49 MB)
- [pimana-v0.7.3.apk](old_version/pimana-v0.7.3.apk) (0.49 MB)
- [pimana-v0.7.2.apk](old_version/pimana-v0.7.2.apk) (0.49 MB)
- [pimana-v0.7.1.apk](old_version/pimana-v0.7.1.apk) (0.49 MB)
- [pimana-v0.7.0.apk](old_version/pimana-v0.7.0.apk) (0.49 MB)
- [pimana-v0.6.1.apk](old_version/pimana-v0.6.1.apk) (0.48 MB)
- [pimana-v0.6.0.apk](old_version/pimana-v0.6.0.apk) (0.48 MB)
- [pimana-v0.5.1.apk](old_version/pimana-v0.5.1.apk) (0.48 MB)
- [pimana-v0.4.0.apk](old_version/pimana-v0.4.0.apk) (0.46 MB)

---
*Official Telegram Channel*: https://t.me/pimana
