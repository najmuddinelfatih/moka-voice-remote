Moka GitHub Pages V3A-3
========================

Isi folder ini:
- index.html : Moka Voice Remote untuk GitHub Pages

Cara deploy singkat:
1. Buat repository GitHub baru, misalnya moka-voice-remote.
2. Upload file index.html ke root repository.
3. Buka Settings -> Pages.
4. Source: Deploy from a branch.
5. Branch: main, folder: /root.
6. Save.
7. Tunggu GitHub Pages memberi URL, misalnya https://username.github.io/moka-voice-remote/

Target ESP32 default:
- Static IP: 192.168.18.22
- mDNS: moka.local

Catatan:
- Perangkat yang membuka web app harus satu WiFi dengan Moka.
- Kalau perintah dari GitHub Pages tidak sampai ke ESP32, coba target Static IP dulu.
- Kalau voice gagal, cek izin microphone browser.
