# 🚀 Linilogic.my.id — Deployment Guide

## 📁 Struktur Project

```
D:\linilogic\
├── index.html              # Landing page utama
├── css/
│   └── style.css           # Styling dark theme
├── reviews/
│   ├── index.html          # Halaman daftar semua review
│   └── earphone-tws-terbaik-2026.html   # Artikel review contoh
└── README.md               # Panduan ini
```

## ⚡ Cara Deploy (Pilih Salah Satu)

### Opsi 1: Cloudflare Pages (GRATIS & RECOMMENDED)

1. **Buat akun Cloudflare** → https://dash.cloudflare.com/sign-up (gratis)
2. **Tambahkan domain linilogic.my.id** ke Cloudflare
   - Masuk ke Cloudflare → `Add a Site` → ketik `linilogic.my.id`
   - Cloudflare akan scan DNS record
   - Ganti nameserver domain di **www.rumahweb.com** (registrar) ke nameserver Cloudflare
   - Nameserver Cloudflare akan muncul setelah setup
3. **Deploy via Cloudflare Pages**
   - Klik `Workers & Pages` → `Pages` → `Upload Assets`
   - Upload folder `D:\linilogic\` (semua file)
   - Set domain custom → pilih `linilogic.my.id`
   - Cloudflare Pages gratis, unlimited bandwidth untuk site statis!

### Opsi 2: GitHub Pages

1. Buat repository GitHub: `linilogic.my.id`
2. Push semua file ke branch `main`
3. Setting → Pages → pilih branch `main`, folder `/ (root)`
4. Set custom domain ke `linilogic.my.id`
5. Arahkan DNS ke GitHub Pages IP

### Opsi 3: Netlify (GRATIS)

1. Buka netlify.com, login via GitHub/GitLab
2. Drag & drop folder `D:\linilogic\` ke Netlify
3. Set custom domain → `linilogic.my.id`
4. Arahkan DNS

## 🔗 Setup Link Afiliasi

Setelah site live, ganti link `#` di artikel dengan link afiliasi:

1. **Shopee Afiliasi** → daftar di https://affiliate.shopee.co.id
2. **Tokopedia Afiliasi** → daftar di https://publisher.tokopedia.com
3. **TikTok Shop** → daftar https://affiliate.tiktok.com

Format link yang perlu diganti:
```
🔗 Cek Harga di Shopee →    # arahkan ke link afiliasi Shopee
🔗 Cek di Tokopedia →       # arahkan ke link afiliasi Tokopedia
```

## 📝 Cara Nambah Artikel Baru

1. Copy file template: `reviews/earphone-tws-terbaik-2026.html`
2. Rename sesuai produk (misal: `smartwatch-xiaomi-2026.html`)
3. Update konten:
   - Ubah `<title>` dan meta description
   - Ganti judul, gambar, spesifikasi
   - Update link afiliasi
4. Tambah link card artikel baru di `reviews/index.html` dan `index.html`
5. Upload ulang ke Cloudflare Pages / GitHub / Netlify

## ✅ Checklist Harian

- [ ] Update link afiliasi kalau expired
- [ ] Tambah 1 review baru per minggu (target)
- [ ] Share artikel ke grup FB/WA/Telegram
- [ ] Pantau traffic via Cloudflare Analytics (gratis)

---

**Selamat cuan! 🚀💰**
