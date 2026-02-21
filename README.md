# 💍 Undangan Digital Nana & Bowo
### WhatsApp Group Chat Style

> Undangan pernikahan interaktif berbasis web dengan tampilan mirip grup WhatsApp.

---

## 🌐 Demo

```
https://USERNAME.github.io/undangan-nana-bowo/?name=Nama+Tamu
```

---

## 📁 Struktur Folder

```
undangan-nana-bowo/
├── index.html                        ← File utama (semua kode ada di sini)
├── README.md
└── assets/
    ├── backsound.mp3                 ← 🎵 Ganti dengan musik background
    ├── videos/
    │   └── prewedding.mp4            ← 🎥 Ganti dengan video prewedding
    └── images/
        ├── group/
        │   └── group-profile.jpg     ← 👥 Foto profil grup WhatsApp
        ├── profiles/
        │   ├── nana.jpg              ← 👰 Foto mempelai wanita
        │   └── bowo.jpg              ← 🤵 Foto mempelai pria
        └── gallery/
            ├── momen-01.jpg          ← 📸 Foto galeri 1 (tampil di chat)
            ├─��� momen-02.jpg          ← 📸 Foto galeri 2 (tampil di chat)
            ├── momen-03.jpg          ← 📸 Foto galeri 3 (tampil di chat)
            ├── momen-04.jpg          ← 📸 Foto galeri 4
            ├── momen-05.jpg
            ├── momen-06.jpg
            ├── momen-07.jpg
            ├── momen-08.jpg
            ├── momen-09.jpg
            └── momen-10.jpg          ← 📸 Foto galeri 10
```

---

## ✏️ Cara Kustomisasi

### 1. Ganti Data di `index.html`

Cari bagian `const CONFIG = {` di dalam `index.html`, lalu edit:

```javascript
const CONFIG = {
  groupName: "Warga Desa Penari",          // ← Nama grup WhatsApp
  groupDesc: "Pengumuman Resmi & Silaturahmi Warga",
  locationUrl: "https://maps.app.goo.gl/...", // ← Link Google Maps lokasi acara
  couple: {
    brideName: "Nana",                      // ← Nama panggilan mempelai wanita
    groomName: "Bowo"                       // ← Nama panggilan mempelai pria
  },
  // ... dsb
}
```

### 2. Ganti File Media

| File | Keterangan |
|------|-----------|
| `assets/backsound.mp3` | Musik background — format MP3, maks 5MB |
| `assets/videos/prewedding.mp4` | Video prewedding — format MP4 H.264, 720p |
| `assets/images/group/group-profile.jpg` | Foto profil grup — 400×400px |
| `assets/images/profiles/nana.jpg` | Foto Nana — 600×800px portrait |
| `assets/images/profiles/bowo.jpg` | Foto Bowo — 600×800px portrait |
| `assets/images/gallery/momen-01.jpg` s/d `momen-10.jpg` | Foto galeri — bebas ukuran |

### 3. Link Undangan per Tamu

```
https://USERNAME.github.io/undangan-nana-bowo/?name=Budi+Santoso
```

Nama tamu akan muncul otomatis di splash screen.

---

## 🚀 Deploy ke GitHub Pages (Gratis)

1. Buka **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `(root)`
4. Klik **Save**
5. Tunggu 1–2 menit → link aktif

---

## 📋 Checklist Sebelum Share

- [ ] `assets/backsound.mp3` sudah diganti
- [ ] `assets/videos/prewedding.mp4` sudah diganti
- [ ] `assets/images/group/group-profile.jpg` sudah diganti
- [ ] `assets/images/profiles/nana.jpg` sudah diganti
- [ ] `assets/images/profiles/bowo.jpg` sudah diganti
- [ ] `assets/images/gallery/momen-01.jpg` s/d `momen-10.jpg` sudah diganti
- [ ] Data `CONFIG` di `index.html` sudah diupdate
- [ ] Link Google Maps sudah benar
- [ ] Test di HP (mobile-first)
- [ ] Test tombol musik bisa ON/OFF
- [ ] Test video call & voice call

---

## 🛠️ Teknologi

- Pure HTML + CSS + JavaScript (zero dependencies)
- Tidak butuh build step — langsung buka di browser
- Mobile-first, responsive

---

## 📄 License

MIT — bebas digunakan dan dimodifikasi.
