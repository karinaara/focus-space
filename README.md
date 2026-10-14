# 🍅 FocusSpace — Pomodoro & Ambient Sounds

**FocusSpace** adalah aplikasi produktivitas berbasis web yang menggabungkan *timer* Pomodoro, suara latar ambient (*synthesized live* menggunakan Web Audio API), pemutar musik YouTube, dan manajemen tugas (*to-do list*). Dilengkapi dengan mode fokus (Zen mode) dan pelacak *streak* harian.

---

### 🌟 Fitur Utama

* **🎯 Customizable Pomodoro Timer:** Mode Focus, Short Break, dan Long Break yang dapat disesuaikan durasinya beserta siklus otomatis.
* **🌧️ Live Synthesized Ambient Sounds:** Suara ambient (Rain, Ocean Waves, Cafe, Deep Brown Noise) dibuat secara langsung menggunakan Web Audio API tanpa perlu mengunduh file audio eksternal.
* **🎵 YouTube Music Player Integration:** Putar musik atau *preset* playlist (Lofi Radio, Chillhop, Chill Jazz) langsung di dalam aplikasi.
* **📝 Task & Active Task Tracker:** Tambahkan tugas, atur estimasi Pomodoro, dan hubungkan tugas aktif ke *timer*.
* **🔥 Daily Stats & Streak Counter:** Pelacak jumlah Pomodoro harian dan *streak* hari berturut-turut.
* **🧘 Zen / Focus Mode:** Sembunyikan semua elemen antarmuka yang mengganggu fokus hanya dengan satu tombol (atau tekan tombol `F`).
* **🔒 Privacy-First:** Semua data tugas, pengaturan, dan riwayat tersimpan 100% di peramban lokal (`localStorage`).

---

### ⌨️ Shortcut Keyboard

* `Space` : Mulai / Jeda timer
* `F` : Masuk / Keluar dari Zen Focus Mode
* `Esc` : Keluar dari Zen Focus Mode / Menutup dialog

---

### 🛠️ Teknologi yang Digunakan

* HTML5 & Tailwind CSS
* Vanilla JavaScript (ES6+)
* Web Audio API (untuk efek suara ambient sintetis & chime)
* Lucide Icons
* YouTube Iframe API
* LocalStorage API

---

### 🚀 Cara Menjalankan Secara Lokal

1. *Clone* repositori ini:
   ```bash
   git clone [https://github.com/USERNAME/focus-space.git](https://github.com/USERNAME/focus-space.git)
