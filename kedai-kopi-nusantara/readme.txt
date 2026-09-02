================================================================================
TUGAS PRAKTIKUM BASIC WEB PROGRAMMING
PROYEK WEBSITE PROFIL PERUSAHAAN: KEDAI KOPI NUSANTARA
================================================================================

A. IDENTITAS MAHASISWA
--------------------------------------------------------------------------------
Nama Lengkap   : [Nama Mahasiswa]
NIM            : [Nomor Induk Mahasiswa]
Kelas / Sesi   : [Kelas Praktikum / Sesi Lab]
Mata Kuliah    : Basic Web Programming (Semester 3)
Tahun Akademik : 2026/2027

B. DESKRIPSI SINGKAT PROYEK
--------------------------------------------------------------------------------
"Kedai Kopi Nusantara" adalah website profil perusahaan statis multi-halaman
yang dirancang untuk memperkenalkan kedai kopi spesialisasi biji kopi lokal asli
Indonesia (Aceh Gayo, Toraja Kalosi, Bali Kintamani, dan Flores Bajawa).

Website ini dibangun menggunakan:
- Semantic HTML5 murni (<header>, <nav>, <main>, <section>, <article>, <figure>,
  <figcaption>, <footer>) yang terstruktur dan bebas div-soup.
- CSS kustom murni (css/style.css) dengan pemanfaatan CSS Variables, palet warna
  kopi nusantara (Espresso, Latte, Warm Caramel, Cream), dan tipografi Google Fonts
  ('Playfair Display' untuk heading dan 'Poppins' untuk body text).
- Framework Bootstrap 5.3 (CDN) untuk sistem grid responsif (mobile-first) dan
  komponen interaktif navbar toggle tanpa custom JavaScript tambahan.
- Kepatuhan standar W3C: DOCTYPE valid, meta viewport & charset, atribut alt pada
  seluruh gambar Unsplash beresolusi tinggi, label form terhubung dengan ID input,
  serta bebas dari inline styling (no inline CSS).

C. STRUKTUR & DAFTAR 5 HALAMAN WEB
--------------------------------------------------------------------------------
1. index.html (Beranda)
   - Hero Section dengan tagline kuat, deskripsi, dan tombol CTA.
   - Ringkasan Kedai yang memperkenalkan 4 varietas biji kopi nusantara.
   - 4 Card Keunggulan (Biji Kopi Asli, Suasana Nyaman, WiFi Cepat, Harga Bersahabat)
     dengan tata letak 1 kolom di mobile (col-12) dan 4 kolom sejajar di desktop (col-lg-3).
   - Footer lengkap dengan jam operasional, alamat, dan tautan sosial media.

2. about.html (Tentang Kami)
   - Cerita & Sejarah: 1 kolom di mobile (col-12), 2 kolom sejajar di desktop (col-lg-6).
   - Visi & Misi: 1 kolom di mobile (col-12), 2 kolom berdampingan di desktop (col-lg-6).
   - Tim Kami: 3 profil barista & pengrajin kopi (1 kolom mobile col-12, 3 kolom desktop col-lg-4).

3. menu.html (Menu)
   - Judul section "Menu Kami".
   - 6 sajian kopi & kudapan nusantara lengkap dengan foto produk Unsplash,
     deskripsi singkat, dan badge harga (Rp) yang rapi tanpa filter JavaScript.
   - Tata letak responsif: 1 kolom di mobile (col-12), 3 kolom di desktop (col-lg-4).

4. gallery.html (Galeri)
   - Koleksi 8 foto tematik suasana kedai, pemanggangan biji, seduh manual, dan produk.
   - Tata letak responsif: Wajib 2 kolom di layar mobile <=576px (col-6) dan 4 kolom di
     layar desktop >=1200px (col-lg-3).
   - Menggunakan tag semantik <figure> dan <figcaption> dengan efek hover zoom halus.

5. contact.html (Kontak)
   - Tata letak responsif: Mobile <=576px 1 kolom bertumpuk (info & peta di atas, form di bawah);
     Desktop >=1200px 2 kolom sejajar (kiri info kontak & Google Maps embed, kanan form).
   - Formulir kirim pesan statis dengan label terhubung atribut id input dan tombol submit.

D. STRUKTUR DIREKTORI PROYEK
--------------------------------------------------------------------------------
kedai-kopi-nusantara/
├── index.html
├── about.html
├── menu.html
├── gallery.html
├── contact.html
├── css/
│   └── style.css
└── readme.txt

E. PETUNJUK MENJALANKAN PROYEK
--------------------------------------------------------------------------------
1. Buka folder "kedai-kopi-nusantara" di web browser pilihan Anda (Google Chrome,
   Mozilla Firefox, Microsoft Edge).
2. Klik ganda pada berkas "index.html" untuk membuka halaman Beranda.
3. Seluruh navigasi antar-halaman dapat diuji secara langsung melalui menu navbar.
4. Uji responsivitas dengan mengubah ukuran jendela browser atau menggunakan fitur
   Inspect Element Device Toolbar (Toggle Device Emulation) pada mobile (<576px)
   maupun desktop (>1200px).
================================================================================

