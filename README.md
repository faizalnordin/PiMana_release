# PiMana — Official Public Release Channel

This repository serves as the official public over-the-air (OTA) distribution and update channel for **PiMana** (Private Personal Automotive Navigation for Malaysians).

## Latest Release: v0.7.2 (Build 11)

- **Direct Download**: [pimana-v0.7.2.apk](pimana-v0.7.2.apk) (0.49 MB)
- **Mirror APK**: [pimana.apk](pimana.apk)
- **Release Date**: 2026-11-03
- **Package Name**: `com.pimana.app`
- **Min SDK**: Android 5.0 (API 21)
- **Target SDK**: Android 9.0 (API 28)

### What's New in v0.7.2:
- 🚀 Pembaikan Gesaan Kemas Kini Berulang (FB-014): Penyelarasan kod versi aplikasi dengan manifes pengeluaran serta integrasi pengesanan versi dinamik terus dari sistem operasi Android (PackageManager) bagi menghapuskan gesaan kemas kini palsu semasa aplikasi dilancarkan.
- 🚀 Penambahbaikan Format Maklum Balas: Pembersihan aksara backslash ('\') pada tanda noktah, sempang dan seru agar mesej maklum balas pemandu terpapar dengan kemas dan tepat di Telegram.
- 🚀 Penyelarasan UI/UX Modal & Pemasa Layar Peta: Butang tutup modal standard 36x36px bulat dengan kesan hover glow (FB-009) dan kiraan undur rehat peta 15-saat bermula pada akhir sentuhan (FB-010).

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
   - Buka KingInstaller, pilih fail APK `pimana-v0.7.2.apk`, dan tekan **"Install as king"**.
   - Buka **Android Auto > Customize Launcher** di telefon anda. Ikon **PiMana** kini akan muncul dan boleh diaktifkan.

> [!NOTE]
> **Penting Mengenai Kemas Kini OTA & Android Auto**:
> - Bagi penggunaan biasa (telefon pintar / Android Head Unit berasingan): Kemas kini OTA dalam aplikasi berfungsi 100% secara langsung.
> - Bagi penggunaan melalui **Android Auto**: Apabila versi baharu dikeluarkan kelak, sila pasang kemas kini melalui KingInstaller ("Install as king") bagi mengekalkan cop pengesahan Google Play Store (`com.android.vending`) agar aplikasi kekal tersenarai di skrin Android Auto.

---

### Previous Releases / Versi Terdahulu (`old_version/`):
- [pimana-v0.7.1.apk](old_version/pimana-v0.7.1.apk) (0.49 MB)
- [pimana-v0.7.0.apk](old_version/pimana-v0.7.0.apk) (0.49 MB)
- [pimana-v0.6.1.apk](old_version/pimana-v0.6.1.apk) (0.48 MB)
- [pimana-v0.6.0.apk](old_version/pimana-v0.6.0.apk) (0.48 MB)
- [pimana-v0.5.1.apk](old_version/pimana-v0.5.1.apk) (0.48 MB)
- [pimana-v0.4.0.apk](old_version/pimana-v0.4.0.apk) (0.46 MB)

---
*Official Telegram Channel*: https://t.me/pimana
