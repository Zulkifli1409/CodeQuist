# 🧠 CodeQuiz - Uji Wawasan Teknologi

**CodeQuiz** adalah aplikasi kuis berbasis web interaktif yang menguji pengetahuan teknologi pengguna. Cocok untuk pelajar, mahasiswa, dan profesional IT. Proyek ini berjalan sepenuhnya di sisi klien (frontend-only) tanpa memerlukan backend atau database.

---

## 🚀 Fitur Utama

- ✅ **Gameplay Jelas**: Jawab pertanyaan pilihan ganda dengan sistem skor dan akurasi.
- ✅ **Interaksi Langsung**: Klik jawaban, gunakan power-up, ubah mode dan tingkat kesulitan.
- ✅ **Hasil & Statistik**: Tampilkan skor akhir, akurasi, dan prestasi pengguna.
- ✅ **Tanpa Backend**: Semua berjalan di frontend menggunakan HTML, CSS, dan JavaScript.
- 📖 **Mode Cerita**: Ikuti kuis melalui bab-bab cerita interaktif.
- ⚡ **Power-Ups**: Gunakan fitur bantuan seperti 50:50, tambah waktu, dan lewati soal.

---

## 🛠️ Teknologi yang Digunakan

- HTML5
- CSS3 (dengan efek animasi dan transisi)
- JavaScript (Vanilla)
- Web Audio API untuk efek suara
- JSON eksternal (`questions.json`, `stories.json`) untuk konten soal dan cerita

---

## 📦 Struktur Proyek

```

/
├── index.html           # File utama frontend (single-page application)
├── questions.json       # (Opsional) Daftar soal kuis (format JSON)
└── stories.json         # (Opsional) Daftar cerita & bab dalam mode cerita

```

> Jika `questions.json` atau `stories.json` tidak tersedia, aplikasi menggunakan fallback data secara otomatis.

---

## ▶️ Cara Menjalankan

1. **Unduh atau kloning repositori ini** ke komputer lokal.
2. **Buka file `index.html`** di browser (cukup klik dua kali).
3. Mulai bermain dan uji wawasanmu!

> Tidak perlu instalasi atau konfigurasi tambahan. Aplikasi bisa berjalan secara offline setelah dibuka.

---

## 📸 Cuplikan

![CodeQuiz Preview](https://i.postimg.cc/0NLTRHbZ/Screenshot-2025-05-29-214247.png)

---

## ✨ Prestasi dalam Game

- 🏆 Perfect Score – Jawaban benar semua
- ⚡ Speed Demon – Jawaban cepat minimal 3 soal
- 🔥 Streak Master – Jawaban benar berturut-turut minimal 3
- 💪 Pure Skill – Skor tinggi tanpa power-up

---

## 📄 Lisensi

Proyek ini bersifat open-source dan bebas digunakan untuk keperluan pendidikan dan pribadi.

---

## 👥 Tim Pengembang

- **Desain & Logika Game**: Zulkifli
- **Frontend**: HTML, CSS, JS murni (tanpa framework)
- **Suara & Animasi**: Web Audio API + CSS Animation

---

## 💡 Catatan

- Untuk menambah soal, edit file `questions.json` sesuai format.
- Untuk menambah cerita, modifikasi file `stories.json`.
- Power-up dan statistik tersimpan hanya selama sesi berjalan.

---

Selamat bermain dan semoga wawasan teknologimu semakin tajam! 🎉
