# 💼 Website Portofolio & Kontak - Fitrya Irfan

Proyek ini merupakan bagian dari tugas **Responsive Web Design (RWD)**.  
Website ini berisi dua halaman utama yang **saling terhubung melalui navigasi yang konsisten**, yaitu halaman **Portfolio** dan **Contact**.

---

## 🌐 Deskripsi Singkat

Website ini dirancang untuk menampilkan hasil karya dan memberikan sarana bagi pengunjung untuk **menghubungi atau mengajukan permintaan proyek** secara langsung.  
Seluruh halaman dibuat menggunakan **HTML5 dan CSS3**, serta telah menerapkan **konsep desain responsif (RWD)** agar tampilan tetap rapi di perangkat komputer maupun ponsel.

---

## 📄 Struktur Halaman

### 1️⃣ Halaman Portfolio (`portfolio.html`)

Halaman ini berfungsi untuk menampilkan daftar proyek yang telah atau sedang dikerjakan.  
Kontennya berupa **tabel data portofolio** yang terdiri atas beberapa kolom:

| Kolom | Deskripsi |
|-------|------------|
| **Nama Proyek** | Judul atau nama dari proyek yang dibuat |
| **Tahun** | Tahun pembuatan proyek |
| **Teknologi** | Teknologi atau bahasa pemrograman yang digunakan |
| **Status** | Menunjukkan apakah proyek sudah selesai atau belum |
| **Link Demo** | Tautan menuju hasil proyek (opsional) |

Contoh data proyek yang ditampilkan:
- Website Toko Online  
- Dashboard Admin  
- Landing Page Sekolah  
- Portfolio Pribadi  
- Blog Teknologi  

Selain itu, tabel ini bersifat **responsif**, artinya tetap bisa di-scroll dan dibaca dengan baik di layar kecil (mobile view).

🔗 **Navigasi yang tersedia:**
- [Home (index.html)](index.html)
- [Portfolio (portfolio.html)](portfolio.html)
- [Contact (contact.html)](contact.html)

---

### 2️⃣ Halaman Contact (`contact.html`)

Halaman ini berisi **form permintaan proyek** yang dapat digunakan pengunjung untuk mengirimkan pesan atau permintaan kerja sama.

#### Elemen form meliputi:
- **Nama Lengkap** → Input teks  
- **Email** → Input email  
- **Jenis Layanan** → Dropdown pilihan (Pembuatan Website, Konsultasi Teknologi, Review Portofolio)  
- **Deskripsi Proyek / Pesan** → Textarea untuk menulis detail proyek  
- **Checkbox** → Persetujuan ketentuan layanan  
- **Submit Button** → Untuk mengirim form  

Semua elemen form didesain **user-friendly** dan **responsif** untuk perangkat mobile.

🔗 **Navigasi yang tersedia:**
- [Home (index.html)](index.html)
- [Portfolio (portfolio.html)](portfolio.html)
- [Contact (contact.html)](contact.html)

---

## 🧭 Navigasi Antar Halaman

Kedua halaman ini terhubung melalui **navbar** yang sama di bagian atas:

```html
<nav class="navbar">
  <h1 class="logo">Fitrya Irfan</h1>
  <ul class="nav-links">
    <li><a href="index.html">Home</a></li>
    <li><a href="portfolio.html" class="active">Portfolio</a></li>
    <li><a href="contact.html">Contact</a></li>
  </ul>
</nav>
