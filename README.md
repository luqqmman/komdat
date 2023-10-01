# Kavita

![](https://github.com/luqqmman/komdat/blob/main/dokumentasi/homepage.png)

## Sekilas tentang Kavita
Ringan dan cepat dengan desain yang apik, Kavita adalah perpustakaan digital yang dihosting sendiri dan mendukung beragam format file. Instal untuk mulai membaca dan berbagi server Anda dengan teman-teman Anda.


## instalasi

### Kebutuhan sistem:
- docker
- docker-compose
- root access

### Proses Instalasi
1. Siapkan VPS dengan akses root
![](https://github.com/luqqmman/komdat/blob/main/dokumentasi/root.png)
2. Pastikan docker dan docker-compose terinstal
![](https://github.com/luqqmman/komdat/blob/main/dokumentasi/docker.png)
3. Membuat folder baru bernama kavita (opsional)
4. Membuat file compose.yaml dengan isi sebagai berikut
![](https://github.com/luqqmman/komdat/blob/main/dokumentasi/yaemel.png)
5. Jalankan perintah docker-compose up -d (di folder compose.yaml tersimpan)
6. Cek instalasi dengan membuka port 5000 di vps melalui browser
7. Buat akun admin


## Cara Pemakaian
1. Untuk menambah buku/manga, masuk sebagai admin
2. Klik ikon gear di pojok kanan atas
3. Klik Libraries Tab
4. Kemudian pilih tambah library 
5. Berikan nama dan tipe library, klik next
6. Pilih folder berisi file yang ingin anda upload
7. Klik share, next, dan save


## Fitur

### Dukungan File yang luas
- Manga/Komik: ZIP, RAR, RAR5, CBR, CBZ, CB7, CBT, TAR.GZ, 7ZIP/7Z
- Buku: EPUB2, EPUB3, PDF
- Gambar Mentah: JPG/JPEG, PNG, WebP, GIF, AVIF

### Pembaca Manga/Komik
- Penskalaan Gambar agar sesuai dengan layar perangkat Anda atau ganti sesuai keinginan Anda
- Pemisahan Gambar untuk penyebaran halaman yang digabungkan, jangan gulir di tablet Anda, cukup pisahkan
- Mode layar penuh
- Mode pembaca halaman ganda dengan bayangan opsional untuk meniru membaca buku
- Arah Membaca: Kiri/Kanan, Atas/Bawah
- Pembaca webtoon (bergulir) bawaan
- Membaca seluruh arsip tanpa menutup pembaca

### Pembaca buku
- Pembaca interaktif - dapat berinteraksi dengan teks, menjalankan javascript, dan mengalirkan halaman ke UI
- Mode gelap tetap ada di antara pemuatan halaman
- Mode imersif, hanya Anda dan kata-kata
- Mode layar penuh
- Tidak ada mode gulir dengan halaman virtual
- Tema Gelap, Hitam, atau Putih untuk dinikmati di perangkat OLED dan e-Ink
- Sesuaikan pengalaman membaca Anda dengan Font khusus, Ukuran Font, Margin, Arah Membaca, Tema, dll
- Daftar Isi hanya dengan sekali klik
- Ingat posisi garis dan lanjutkan dari bagian terakhir yang Anda tinggalkan, apa pun perangkatnya

### Pembaca PDF
- Pembaca PDF khusus untuk memberi Anda pengalaman terbaik untuk PDF Anda
- Menawarkan mode terang/gelap dan banyak opsi penyesuaian
- Manajemen Pengguna dan Berbagi

### Buat pengguna dan bagikan perpustakaan Anda dengan mereka
- Berikan izin kepada pengguna untuk melihat perpustakaan atau melihat koleksi media campuran yang berbeda
- Peringkat dan ulasan bawaan untuk setiap pengguna Anda
- Batasan usia untuk akun pengguna

## Demo
username: komdat
password: superkomdat
https://ipb.link/komdat-kavita-p3


## referensi
- https://wiki.kavitareader.com/en
