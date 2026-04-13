# 🔍 Lensa Bahasa

> **Deteksi Bias dan Framing Berita Secara Cerdas** — Powered by Anthropic Claude AI

Website literasi media berbasis AI untuk mendeteksi bias bahasa, framing, dan kualitas jurnalistik sebuah berita.

---

## ✨ Fitur Utama

- 📰 **Topik Berita** — Ringkasan otomatis tentang apa yang dibahas berita
- 📊 **Skor Netralitas** — Penilaian 0–100 seberapa netral sebuah berita
- 🤖 **Deteksi Konten AI** — Identifikasi apakah berita ditulis manusia atau AI
- 🔦 **Sorotan Bias Visual** — Kata bias disorot merah (tinggi) & kuning (sedang)
- ⚠️ **Daftar Kata Bias** — Penjelasan detail tiap kata/frasa berindikasi bias
- 🔎 **Temuan** — Penilaian apakah inti berita akurat, perlu diverifikasi, atau menyesatkan
- 📘 **Edukasi** — Materi lengkap tentang bias, framing, dan netralitas
- 📖 **Tutorial** — Panduan penggunaan langkah demi langkah

---

## 🚀 Cara Deploy ke GitHub Pages

### Langkah 1 — Siapkan Repository

```bash
# Buat repository baru di GitHub (nama bebas, misal: lensa-bahasa)
# Lalu clone ke komputer kamu:
git clone https://github.com/USERNAME/lensa-bahasa.git
cd lensa-bahasa
```

### Langkah 2 — Copy File

Copy file `index.html` (dan `README.md` ini) ke dalam folder repository kamu.

```
lensa-bahasa/
├── index.html   ← file utama website
└── README.md
```

### Langkah 3 — Push ke GitHub

```bash
git add .
git commit -m "Initial commit: Lensa Bahasa website"
git push origin main
```

### Langkah 4 — Aktifkan GitHub Pages

1. Buka repository di GitHub
2. Klik **Settings** → **Pages**
3. Di bagian **Source**, pilih: **Deploy from a branch**
4. Pilih branch: **main**, folder: **/ (root)**
5. Klik **Save**
6. Tunggu 1–3 menit, lalu akses: `https://USERNAME.github.io/lensa-bahasa`

---

## 🔑 Cara Mendapatkan API Key

Website ini memerlukan **Anthropic API Key** untuk mengaktifkan fitur analisis AI:

1. Buka [console.anthropic.com](https://console.anthropic.com)
2. Daftar atau login
3. Klik menu **API Keys** → **Create Key**
4. Salin key yang muncul (`sk-ant-api03-...`)
5. Di website Lensa Bahasa, klik **"Atur API Key"** di navbar
6. Tempel key → Simpan

> 🔒 API Key **hanya tersimpan di browser** (sessionStorage) dan tidak dikirim ke server manapun. Key akan terhapus otomatis saat tab ditutup.

---

## 🛠️ Teknologi

| Teknologi | Penggunaan |
|-----------|-----------|
| HTML5 | Struktur halaman |
| CSS3 | Styling & animasi |
| JavaScript (Vanilla) | Logika aplikasi & API call |
| Anthropic Claude API | Analisis AI |
| GitHub Pages | Hosting statis gratis |

> ℹ️ **Catatan tentang PHP**: GitHub Pages hanya mendukung file statis (HTML/CSS/JS). PHP tidak bisa berjalan di GitHub Pages. Website ini sengaja dibangun 100% dengan JavaScript agar kompatibel dengan GitHub Pages.

---

## 📁 Struktur Halaman

```
🏠 Home        — Landing page dengan CTA
🔍 Analisis    — Input teks + hasil analisis AI
📘 Edukasi     — Materi bias, framing, netralitas
📖 Tutorial    — Panduan penggunaan 7 langkah
ℹ️ Tentang    — Info tim & proyek
```

---

## ✏️ Kustomisasi

Di file `index.html`, cari bagian berikut dan ganti sesuai info kelompokmu:

```html
<!-- Baris sekitar bagian "Tentang Kami" -->
<div class="abt-chip">🎓 [Nama Kelompok Kamu]</div>

<li>[Nama Anggota 1] — Project Lead & Frontend</li>
<li>[Nama Anggota 2] — AI Integration & Logic</li>
<li>[Nama Anggota 3] — Content & Research</li>
<li>[Nama Anggota 4] — UI/UX Design</li>
<li>[Nama Anggota 5] — Dokumentasi & Testing</li>
```

---

## 📄 Lisensi

Dibuat untuk keperluan tugas/proyek. Bebas dimodifikasi sesuai kebutuhan.

---

*© 2026 Lensa Bahasa — Untuk literasi media Indonesia yang lebih baik* 🇮🇩
