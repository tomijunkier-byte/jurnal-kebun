# 📱 Panduan Install Jurnal Kebun ke HP Android

## File yang perlu diupload ke GitHub:
```
kebun-pwa/
├── index.html        ← aplikasi utama
├── manifest.json     ← konfigurasi PWA
├── sw.js             ← service worker (offline)
└── icons/
    ├── icon-192.png  ← ikon app kecil
    └── icon-512.png  ← ikon app besar
```

---

## LANGKAH 1 — Buat akun GitHub
1. Buka https://github.com di HP atau PC
2. Klik **Sign up** → isi email, password, username
3. Verifikasi email

---

## LANGKAH 2 — Buat Repository baru
1. Login ke GitHub, klik tombol **+** (pojok kanan atas) → **New repository**
2. Isi:
   - **Repository name**: `jurnal-kebun`
   - Pilih **Public**
   - Centang **Add a README file**
3. Klik **Create repository**

---

## LANGKAH 3 — Upload semua file
Di halaman repository yang baru dibuat:

1. Klik **Add file** → **Upload files**
2. Upload file-file ini satu per satu atau drag & drop:
   - `index.html`
   - `manifest.json`
   - `sw.js`
3. Klik **Commit changes**

Lalu upload folder icons:
1. Klik **Add file** → **Upload files**
2. Buat path `icons/` dengan cara ketik `icons/` di kolom nama file
3. Upload `icon-192.png` dan `icon-512.png`
4. Klik **Commit changes**

---

## LANGKAH 4 — Aktifkan GitHub Pages
1. Di halaman repository, klik tab **Settings**
2. Di menu kiri, klik **Pages**
3. Di bagian **Source**, pilih:
   - Branch: **main**
   - Folder: **/ (root)**
4. Klik **Save**
5. Tunggu 1–2 menit, akan muncul link seperti:
   👉 `https://usernamekamu.github.io/jurnal-kebun`

---

## LANGKAH 5 — Install ke HP Android
1. Buka Chrome di HP Android
2. Ketik link GitHub Pages kamu di address bar
3. Tunggu halaman terbuka
4. Tap menu Chrome (titik tiga **⋮** di pojok kanan atas)
5. Tap **"Add to Home Screen"** atau **"Install App"**
6. Tap **Install** / **Add**

✅ Aplikasi akan muncul di layar utama HP seperti app biasa!

---

## Catatan Penting
- **Data tersimpan di HP** — tidak perlu internet setelah install (offline ready)
- **Gratis sepenuhnya** — GitHub Pages gratis untuk project publik
- **Update app**: kalau ada perubahan, cukup replace file di GitHub, app otomatis update saat ada koneksi

---

## Struktur URL setelah deploy:
`https://[username].github.io/jurnal-kebun/`
