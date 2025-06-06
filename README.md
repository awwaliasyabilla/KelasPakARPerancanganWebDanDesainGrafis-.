# Presentasi Proyek: Platform Les Privat Online

## 1. Latar Belakang & Masalah

* Banyak siswa kesulitan menemukan tutor privat berkualitas.
* Belajar offline terbatas oleh lokasi dan waktu.
* Proses pemesanan les masih manual dan tidak efisien.

## 2. Solusi: Platform Les Privat Online

* Website/aplikasi untuk mempertemukan siswa dan tutor secara online.
* Fitur booking jadwal fleksibel.
* Integrasi video call (Zoom/Jitsi) dan chat realtime (Firebase).
* Dashboard terpisah untuk siswa dan tutor.
* Sistem rating & review tutor.
* Admin panel untuk kontrol penuh.

## 3. Demo Singkat

* Homepage → Cari tutor
* Registrasi & Login (Siswa & Tutor)
* Dashboard Siswa → Booking Les
* Dashboard Tutor → Terima/Menolak Jadwal
* Video Conference + Chat Realtime
* Admin Panel

## 4. Proses Pengembangan

### UI/UX

* Tools: Figma, Adobe XD
* Riset → Wireframe → Mockup → Implementasi HTML/CSS
* Fokus: Responsive, CTA jelas, ramah pengguna

### Coding

* Frontend: HTML, CSS (Tailwind), JS
* Backend: Node.js/Express / PHP Laravel
* Auth: Login/Register dengan bcrypt (hash password)
* API: REST (jadwal, booking, user)
* Database: Firebase / MySQL
* Keamanan: Validasi, session, sanitasi input

### Hosting

* Frontend: Netlify / Vercel
* Backend: Railway / Render
* Database: Firebase / PlanetScale
* Domain (opsional): Freenom/Namecheap

## 5. Tantangan & Solusi

| Tantangan            | Solusi                        |
| -------------------- | ----------------------------- |
| Integrasi Zoom/Jitsi | Jitsi iframe API / Zoom SDK   |
| Chat Realtime        | Firebase RTDB                 |
| Booking fleksibel    | Kalender + form ketersediaan  |
| Role-based access    | Session/token + redirect role |
| Responsive           | Tailwind + testing mobile     |
| Hosting backend      | Railway + Netlify atau Vercel |

## 6. Dokumentasi GitHub

### Repo: `Kelas-PakAR-PerancanganWebDanDesainGrafis`

**README.md:**

* Deskripsi proyek
* Fitur utama
* Link demo
* Struktur folder
* Panduan install

**docs/**

* User Manual: Cara daftar, booking, chat
* Panduan login, dashboard, jadwal

**technical/**

* Struktur frontend/backend
* API endpoint (POST /register, GET /jadwal)
* Langkah deploy ke Netlify + Railway

---

Jika kamu butuh file presentasi (.pptx) atau README yang bisa langsung diupload ke GitHub, tinggal minta saja!

iya saya butuh
