# ☕ Kedai Kopi Digital

> Laman web bisnes pelajar — Kedai kopi digital yang moden, responsif, dan dilengkapi panel admin.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📋 Tentang Projek

**Kedai Kopi Digital** adalah laman web perniagaan pelajar yang direka khas untuk mempromosi dan mengambil pesanan kopi secara dalam talian. Dilengkapi dengan **panel admin** untuk mengurus menu, lokasi, dan tetapan kedai tanpa sentuh kod.

### ✨ Ciri-ciri Utama

| Ciri | Penerangan |
|------|------------|
| 🎨 **Hero Section** | Seksyen utama yang menarik dengan imej latar belakang dan animasi |
| 📋 **Menu Produk Dinamik** | Paparan menu yang boleh diurus melalui admin panel |
| 📝 **Borang Pesanan** | Borang interaktif dengan pengesahan input dan ringkasan pesanan |
| 📱 **WhatsApp API** | Pesanan dihantar terus ke WhatsApp menggunakan `wa.me` API |
| 🗺️ **Google Maps** | Peta lokasi yang boleh diubah melalui admin panel |
| 🔐 **Admin Panel** | Panel pengurusan penuh untuk mengurus semua aspek laman web |
| 🎨 **Tema Dinamik** | Pilihan tema gelap/cerah dengan warna custom |
| 👥 **Multi-Admin** | Sokongan berbilang akaun admin |
| 📱 **Responsif** | Reka bentuk yang menyesuaikan semua saiz skrin |

## 🍵 Menu Default & Harga

| Produk | Panas | Sejuk |
|--------|-------|-------|
| ☕ Kopi O | RM 2.00 | RM 2.50 |
| ☕ Kopi Latte | RM 2.50 | RM 3.00 |

> Menu boleh ditambah, diedit, dan dipadam melalui Admin Panel.

## 🔐 Admin Panel

### Akses Admin
- **URL**: `admin.html` (atau klik ikon ⚙️ di footer laman utama)
- **Default Login**: Username `admin` / Password `admin123`

### Ciri-ciri Admin Panel

| Bahagian | Fungsi |
|----------|--------|
| 📊 **Dashboard** | Ringkasan statistik menu dan kedai |
| ☕ **Pengurusan Menu** | Tambah / Edit / Padam item menu, varian, harga, gambar |
| 🏪 **Tetapan Kedai** | Nama kedai, tagline, nombor WhatsApp |
| 🗺️ **Tetapan Lokasi** | Google Maps embed URL dan pautan |
| 🎨 **Tema** | Mod gelap/cerah, 9 palet warna, atau warna custom |
| 👥 **Pengurusan Admin** | Tambah/buang akaun admin, tukar kata laluan |
| 💾 **Eksport/Import** | Backup dan pulihkan konfigurasi sebagai JSON |

### Nota Penting
- Data disimpan menggunakan **localStorage** (pada peranti yang sama sahaja)
- Guna fungsi **Eksport/Import** untuk pindah data ke peranti lain
- Password disimpan sebagai SHA-256 hash

## 🛠️ Teknologi

- **HTML5** — Struktur semantik laman web
- **CSS3** — Reka bentuk responsif, animasi, tema dinamik
- **JavaScript (Vanilla)** — Rendering dinamik, CRUD, pengesahan borang, WhatsApp API
- **Google Fonts** — Playfair Display & Inter
- **Web Crypto API** — Hash kata laluan SHA-256
- **localStorage** — Penyimpanan data konfigurasi

## 📂 Struktur Projek

```
cofesho/
├── index.html          # Laman utama (user/public view)
├── admin.html          # Panel admin (admin view)
├── images/
│   ├── hero-coffee.png # Imej hero section
│   ├── kopi-o.png      # Imej produk Kopi O
│   └── kopi-latte.png  # Imej produk Kopi Latte
└── README.md           # Dokumentasi projek
```

## 🚀 Cara Penggunaan

### Jalankan Secara Lokal

1. **Klon repositori:**
   ```bash
   git clone https://github.com/fuzb36/cofesho.git
   ```
2. **Buka fail:**
   ```bash
   cd cofesho
   ```
3. **Buka `index.html`** dalam pelayar web (laman awam)
4. **Buka `admin.html`** untuk akses panel admin

### Setup Admin

1. Buka `admin.html` → Log masuk dengan `admin` / `admin123`
2. Tukar kata laluan anda di bahagian **Pengurusan Admin**
3. Tambah item menu di bahagian **Menu**
4. Tetapkan nombor WhatsApp di bahagian **Tetapan Kedai**
5. Kemas kini lokasi di bahagian **Lokasi**

## 🌐 GitHub Pages

Laman web ini dihoskan di GitHub Pages:

🔗 **[Lawati Laman Web](https://fuzb36.github.io/cofesho/)**

### Cara Deploy ke GitHub Pages

1. Pergi ke **Settings** repositori di GitHub
2. Klik **Pages** di menu kiri
3. Di bawah **Source**, pilih **Deploy from a branch**
4. Pilih branch `main` dan folder `/ (root)`
5. Klik **Save**

## 🔄 Aliran Kerja

```
Admin Login → Admin Panel → Ubah Menu/Lokasi/Tetapan → Simpan
                                    ↓
                        index.html baca data → Pengguna lihat laman terkini
```

## 📜 Lesen

Projek ini dibina untuk tujuan pembelajaran dan perniagaan pelajar.

---

<p align="center">Dibina dengan ☕ dan ❤️ oleh pelajar kreatif</p>
