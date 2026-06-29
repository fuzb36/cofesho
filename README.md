# ☕ Kedai Kopi Digital

> Laman web bisnes pelajar — Kedai kopi digital yang moden dan responsif.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📋 Tentang Projek

**Kedai Kopi Digital** adalah laman web perniagaan pelajar yang direka khas untuk mempromosi dan mengambil pesanan kopi secara dalam talian. Laman web ini dibina menggunakan HTML5, CSS3 dan JavaScript dalam satu fail tunggal (`index.html`) — tanpa sebarang kebergantungan luaran (framework).

### ✨ Ciri-ciri Utama

| Ciri | Penerangan |
|------|------------|
| 🎨 **Hero Section** | Seksyen utama yang menarik dengan imej latar belakang dan animasi |
| 📋 **Menu Produk** | Paparan menu kopi dengan harga dan pilihan panas/sejuk |
| 📝 **Borang Pesanan** | Borang interaktif dengan pengesahan input dan ringkasan pesanan |
| 📱 **WhatsApp API** | Pesanan dihantar terus ke WhatsApp menggunakan `wa.me` API |
| 🗺️ **Google Maps** | Peta lokasi kedai yang boleh diklik |
| 📱 **Responsif** | Reka bentuk yang menyesuaikan saiz skrin (desktop, tablet, telefon) |
| 🌙 **Tema Gelap** | Skema warna profesional bertema gelap dengan aksen emas/kopi |

## 🍵 Menu & Harga

| Produk | Panas | Sejuk |
|--------|-------|-------|
| ☕ Kopi O | RM 2.00 | RM 2.50 |
| ☕ Kopi Latte | RM 2.50 | RM 3.00 |

## 🛠️ Teknologi

- **HTML5** — Struktur semantik laman web
- **CSS3** — Reka bentuk responsif, animasi, glassmorphism
- **JavaScript (Vanilla)** — Logik interaktif, pengesahan borang, WhatsApp API
- **Google Fonts** — Playfair Display & Inter

## 📂 Struktur Projek

```
cofesho/
├── index.html          # Fail utama (HTML + CSS + JS)
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
   git clone https://github.com/<username>/cofesho.git
   ```
2. **Buka fail:**
   ```bash
   cd cofesho
   ```
3. **Buka `index.html`** dalam pelayar web anda.

### Konfigurasi WhatsApp

Tukar nombor WhatsApp dalam fail `index.html` pada baris JavaScript:

```javascript
const WA_PHONE = '60123456789'; // Ganti dengan nombor anda
```

## 🌐 GitHub Pages

Laman web ini dihoskan di GitHub Pages:

🔗 **[Lawati Laman Web](https://<username>.github.io/cofesho/)**

### Cara Deploy ke GitHub Pages

1. Pergi ke **Settings** repositori di GitHub
2. Klik **Pages** di menu kiri
3. Di bawah **Source**, pilih **Deploy from a branch**
4. Pilih branch `main` dan folder `/ (root)`
5. Klik **Save**
6. Tunggu beberapa minit — laman web anda akan aktif!

## 📱 Ciri Borang Pesanan

Borang pesanan mengumpulkan maklumat berikut:

- **Nama Penuh** — Nama pelanggan
- **Nombor Telefon** — Untuk dihubungi
- **Alamat Penghantaran** — Untuk penghantaran
- **Pilihan Produk** — Pilihan kopi dengan varian (panas/sejuk) dan kuantiti

Selepas mengisi borang, pesanan akan dihantar secara automatik melalui **WhatsApp** menggunakan `wa.me` API.

## 📸 Tangkapan Skrin

Lihat laman web secara langsung untuk melihat reka bentuk penuh dengan:
- Animasi fade-in semasa skrol
- Kad menu dengan kesan hover
- Borang pesanan interaktif dengan ringkasan pesanan masa nyata
- Navigasi tetap dengan kesan blur

## 📜 Lesen

Projek ini dibina untuk tujuan pembelajaran dan perniagaan pelajar.

---

<p align="center">Dibina dengan ☕ dan ❤️ oleh pelajar kreatif</p>
