# Neon Studio — Audio Visualizer

> **Coba langsung:** [https://pedjoeangsolo.github.io/visualizer/](https://pedjoeangsolo.github.io/visualizer/)

Buka tautan di atas untuk mencoba Neon Studio langsung melalui browser—tidak perlu mengunduh atau memasang aplikasi.

Aplikasi audio visualizer berbasis browser untuk Android dan Windows 11.

## Fitur
- Pemutar audio lokal melalui browser.
- Visualizer Neon Fusion, Circular, Equalizer, dan Waveform.
- Pengaturan warna dan intensitas.
- Ekspor video MP4 jika codec H.264 tersedia, atau WebM sebagai alternatif.
- Pilihan 720p, 1080p, 1440p; 24, 30, 60, 90 FPS; bitrate 4–20 Mbps.
- Pemeriksaan dukungan codec browser dan peringatan performa.

## Menjalankan
1. Buka **[Neon Studio](https://pedjoeangsolo.github.io/visualizer/)**.
2. Pilih file audio dari perangkat.
3. Tekan Play.
4. Atur visual dan pengaturan ekspor.
5. Tekan **Mulai ekspor**, lalu **STOP & SIMPAN**.

## Preset YouTube
Default: 1920×1080 (16:9), 60 FPS, MP4, 8 Mbps. Browser yang tidak mendukung MP4 akan menampilkan peringatan; pilih WebM, jangan sekadar mengganti ekstensi file.

## Catatan kompatibilitas
- Format audio yang bisa diputar bergantung pada codec browser/perangkat. MP3/WAV umumnya paling kompatibel; FLAC/M4A/AAC bisa berbeda menurut browser.
- Dukungan MP4/MediaRecorder berbeda antar browser. Aplikasi mengecek MIME codec sebelum mengaktifkan ekspor.
- 1080p60 adalah target, bukan jaminan. Jika ekspor tersendat atau perangkat panas, turunkan ke 720p30.
- Untuk Windows 11 gunakan Chrome atau Edge terbaru. Di Android, tetap buka tab selama ekspor dan jangan kunci layar.

## GitHub Pages
Situs dipublikasikan melalui GitHub Pages dari branch `main` dan folder `/(root)`.

**Website:** https://pedjoeangsolo.github.io/visualizer/
**Repository:** https://github.com/PedjoeangSolo/visualizer
