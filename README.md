# 💍 Undangan Digital Nana & Bowo
### WhatsApp Group Chat Style

> Undangan pernikahan interaktif berbasis web dengan tampilan mirip grup WhatsApp.
> Pure HTML + CSS + JS — tanpa framework, tanpa build step.

---

## 🌐 Live Demo

```
https://8z5i74xc3apdu7446.github.io/desa-penari-undangan/
https://8z5i74xc3apdu7446.github.io/desa-penari-undangan/?name=Nama+Tamu
```

---

## 📁 Struktur Folder

```
desa-penari-undangan/
├── index.html                        ← File utama (semua kode ada di sini)
├── package.json
├── .gitignore
├── README.md
├── CARA-UPDATE.md                    ← Panduan ganti foto/video/musik
└── assets/
    ├── backsound.mp3                 ← 🎵 Musik background (ganti dengan file asli)
    ├── videos/
    │   └── prewedding.mp4            ← 🎥 Video prewedding (ganti dengan file asli)
    └── images/
        ├── group/
        │   └── group-profile.jpg     ← 👥 Foto profil grup WhatsApp
        ├── profiles/
        │   ├── nana.jpg              ← 👰 Foto mempelai wanita
        │   └── bowo.jpg              ← 🤵 Foto mempelai pria
        └── gallery/
            ├── momen-01.jpg          ← 📸 Tampil di chat (preview)
            ├── momen-02.jpg          ← 📸 Tampil di chat (preview)
            ├── momen-03.jpg          ← 📸 Tampil di chat (preview)
            ├── momen-04.jpg
            ├── momen-05.jpg
            ├── momen-06.jpg
            ├── momen-07.jpg
            ├── momen-08.jpg
            ├── momen-09.jpg
            └── momen-10.jpg
```

---

## ✏️ Cara Kustomisasi

### 1. Edit data di `index.html`
Cari bagian `const CONFIG = {` lalu ubah:
```js
groupName:   "Warga Desa Penari",
locationUrl: "https://maps.app.goo.gl/…",
couple: { brideName: "Nana", groomName: "Bowo" },
```

### 2. Ganti file media
Upload ke folder yang sesuai dengan **nama file yang sama persis**.
Lihat panduan lengkap di **[CARA-UPDATE.md](./CARA-UPDATE.md)**

---

## 🚀 Deploy ke GitHub Pages (Gratis)

```
Settings → Pages → Branch: main → / (root) → Save
```
Tunggu 1–2 menit, link langsung aktif.

---

## 🔗 Format Link per Tamu

```
https://8z5i74xc3apdu7446.github.io/desa-penari-undangan/?name=Budi+Santoso
https://8z5i74xc3apdu7446.github.io/desa-penari-undangan/?name=Keluarga+Bu+Dewi
```

---

## 📄 License
MIT — bebas digunakan dan dimodifikasi.