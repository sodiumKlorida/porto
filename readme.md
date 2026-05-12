# Ezra Gilang Raharjo — Portfolio Website (vibe code)

> Personal portfolio website dengan dark mode untuk Ezra Gilang Raharjo, mahasiswa Rekayasa Perangkat Lunak Universitas Telkom Surabaya.

---

## 📋 Deskripsi

Website portfolio single-page berbasis HTML, CSS, dan JavaScript murni — tanpa framework eksternal. Menampilkan profil, keahlian, pengalaman akademik, dan informasi kontak secara visual dan interaktif.

---

## ✨ Fitur

- **Dark Mode** — desain penuh tema gelap dengan palet warna aksen ungu, merah, dan hijau mint
- **Custom Cursor** — cursor animasi dengan efek ring yang mengikuti mouse
- **Scroll Reveal** — elemen muncul secara animasi saat di-scroll
- **Marquee Banner** — scrolling otomatis daftar teknologi
- **Timeline Pengalaman** — tampilan kronologis pengalaman akademik
- **Responsive** — adaptif untuk tampilan desktop dan mobile
- **Zero Dependencies** — tidak membutuhkan library atau framework apapun

---

## 🗂️ Struktur Konten

| Section | Isi |
|---|---|
| Hero | Nama, tagline, CTA, statistik |
| About | Bio singkat, info kontak |
| Skills | Hard skills & soft skills |
| Experience | 7 pengalaman akademik (timeline) |
| Education | SMA & S1 |
| Contact | Email, telepon, GitHub |

---

## 🛠️ Teknologi

- **HTML5** — struktur semantik
- **CSS3** — variabel, grid, animasi, keyframes
- **JavaScript (Vanilla)** — Intersection Observer, cursor, scroll aktif
- **Google Fonts** — Syne + DM Mono

---

## 🚀 Cara Pakai

1. Download file `portfolio.html`
2. Buka langsung di browser (tidak perlu server)

```bash
# Atau jalankan dengan live server jika pakai VS Code
# Klik kanan portfolio.html → Open with Live Server
```

---

## 🎨 Kustomisasi

Semua warna diatur lewat CSS Variables di bagian `:root`:

```css
:root {
  --bg: #0a0a0f;          /* Background utama */
  --accent: #7c6dfa;      /* Aksen ungu */
  --accent2: #fa6d7c;     /* Aksen merah */
  --accent3: #6dfabc;     /* Aksen hijau mint */
  --text: #e8e8f0;        /* Teks utama */
  --muted: #6b6b80;       /* Teks sekunder */
}
```

### Menambahkan Foto

Cari elemen `.photo-placeholder` dan ganti dengan tag `<img>`:

```html
<div class="photo-frame">
  <img src="foto.jpg" alt="Ezra Gilang Raharjo" style="width:100%;display:block;">
</div>
```

---

## 👤 Profil

**Ezra Gilang Raharjo**  
📍 Sedati, Sidoarjo, Jawa Timur, 61253  
📧 ezra.gilang.e9@gmail.com  
📱 0895325812060  
🎓 Rekayasa Perangkat Lunak — Universitas Telkom Surabaya (2022–sekarang)

---

## 📄 Lisensi

Proyek ini dibuat untuk keperluan pribadi. Silakan dimodifikasi sesuai kebutuhan.
