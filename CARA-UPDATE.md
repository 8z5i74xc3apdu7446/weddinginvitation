# 📝 Panduan Update File — Undangan Nana & Bowo

Panduan singkat cara mengganti foto, video, musik, dan data undangan.

---

## 🖼️ Ganti Foto Galeri (10 foto)

**Lokasi:** `assets/images/gallery/`

| File | Keterangan |
|------|-----------|
| `momen-01.jpg` | ⭐ Tampil di chat grup (preview 3 foto) |
| `momen-02.jpg` | ⭐ Tampil di chat grup (preview 3 foto) |
| `momen-03.jpg` | ⭐ Tampil di chat grup (preview 3 foto) |
| `momen-04.jpg` | Galeri saja |
| `momen-05.jpg` | Galeri saja |
| `momen-06.jpg` | Galeri saja |
| `momen-07.jpg` | Galeri saja |
| `momen-08.jpg` | Galeri saja |
| `momen-09.jpg` | Galeri saja |
| `momen-10.jpg` | Galeri saja |

**Cara ganti via GitHub Web:**
1. Buka folder `assets/images/gallery/`
2. Klik **Add file → Upload files**
3. Upload foto kamu, **WAJIB pakai nama yang sama** (`momen-01.jpg` dst)
4. Klik **Commit changes**

**Format foto:** JPG atau PNG, ukuran bebas, rekomendasi lebar min. 800px

---

## 👰🤵 Ganti Foto Profil Mempelai

**Lokasi:** `assets/images/profiles/`

| File | Keterangan |
|------|-----------|
| `nana.jpg` | Foto mempelai wanita |
| `bowo.jpg` | Foto mempelai pria |

**Format:** JPG/PNG, portrait (tinggi > lebar), rekomendasi 400×500px

---

## 👥 Ganti Foto Profil Grup

**Lokasi:** `assets/images/group/`

| File | Keterangan |
|------|-----------|
| `group-profile.jpg` | Foto yang muncul di header WhatsApp |

**Format:** JPG/PNG, kotak 1:1, rekomendasi 400×400px

> 💡 Bisa juga ganti langsung dari dalam app — klik foto grup di header

---

## 🎥 Ganti Video Prewedding

**Lokasi:** `assets/videos/`

| File | Keterangan |
|------|-----------|
| `prewedding.mp4` | Video yang diputar saat klik video call & galeri |

**Format:** MP4 H.264, rekomendasi 720p, ukuran max 50MB  
⚠️ File video besar tidak bisa upload via GitHub Web — gunakan Git CLI atau GitHub Desktop

---

## 🎵 Ganti Musik Background

**Lokasi:** `assets/` (root assets)

| File | Keterangan |
|------|-----------|
| `backsound.mp3` | Musik yang otomatis menyala saat undangan dibuka |

**Format:** MP3, rekomendasi 128kbps, ukuran max 5MB

---

## ✏️ Edit Data Teks (Nama, Tanggal, Lokasi, dll)

Buka file `index.html`, cari bagian:

```js
const CONFIG = {
  groupName:   "Warga Desa Penari",
  groupDesc:   "Pengumuman Resmi & Silaturahmi Warga",
  locationUrl: "https://maps.app.goo.gl/...",   // ← ganti link Maps
  couple: {
    brideName: "Nana",    // ← nama panggilan mempelai wanita
    groomName: "Bowo"     // ← nama panggilan mempelai pria
  },
  // foto galeri, video, stiker, anggota grup — semuanya di sini
}
```

Edit langsung via GitHub Web:
1. Klik file `index.html`
2. Klik ikon pensil ✏️ (Edit this file)
3. Cari `const CONFIG` dengan Ctrl+F
4. Edit nilainya
5. Klik **Commit changes**

---

## 🔗 Format Link per Tamu

```
https://8z5i74xc3apdu7446.github.io/desa-penari-undangan/?name=Nama+Tamu
```

Contoh:
```
?name=Budi+Santoso
?name=Keluarga+Bu+Dewi
?name=Mas+Arif+%26+Mbak+Rina
```

---

## ⚡ Cara Cepat Upload via GitHub Web

```
1. Buka github.com/8z5i74xc3apdu7446/desa-penari-undangan
2. Masuk ke folder yang dituju
3. Klik "Add file" → "Upload files"
4. Drag & drop file (nama HARUS sama dengan yang lama)
5. Klik "Commit changes"
6. Tunggu 1-2 menit → otomatis update di website
```