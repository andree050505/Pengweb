LAPORAN TUGAS 2 PEMROGRAMAN APLIKASI WEB
WEBSITE PROFIL DAN BERITA INSTITUT TEKNOLOGI SUMATERA

IDENTITAS MAHASISWA
Nama Lengkap : Andre Prasetya Daely
NIM          : 123140131
Program Studi: Teknik Informatika
Mata Kuliah  : Pengembangan Aplikasi Web (Kelas RB)
URL Website  : https://[username].github.io/pemweb/tugas2/
URL Repositori: https://github.com/[username]/pemweb

--------------------------------------------------------------------------------

1. DESKRIPSI TUGAS
Tugas ini bertujuan untuk membangun website berbasis HTML5 Semantik dengan mengangkat tema Institut Teknologi Sumatera (ITERA). Website ini terdiri dari dua halaman yang saling terhubung:
- Halaman Utama (index.html): Menyajikan profil kampus ITERA, visi dan misi, tabel daftar jurusan dan program studi unggulan, ringkasan berita, serta kontak kampus.
- Halaman Berita (berita.html): Menyajikan artikel lengkap mengenai pemanfaatan Pembangkit Listrik Tenaga Surya (PLTS) 1 MWp ITERA sebagai laboratorium riset energi terbarukan, dilengkapi dengan gambar ilustrasi, tanggal penerbitan, dan daftar berita terkait.

Sesuai arahan teknis, halaman web difokuskan pada ketepatan struktur semantik dokumen, keterhubungan link, validitas standar W3C, serta tata letak dokumen yang rapi dan terpusat.

--------------------------------------------------------------------------------

2. PENJELASAN ELEMEN STRUKTUR SEMANTIK
Berikut adalah penjelasan fungsi setiap tag semantik yang digunakan dalam proyek ini:

a. Tag header
Digunakan untuk memuat kepala halaman atau kepala artikel. Pada bagian atas situs, tag ini menampung logo resmi ITERA, nama institusi, dan slogan kampus. Tag ini juga digunakan di dalam elemen artikel untuk menampung judul berita, nama penulis, dan tanggal terbit.

b. Tag nav
Digunakan secara khusus untuk membungkus tautan navigasi utama situs, menghubungkan halaman beranda dengan halaman berita serta bagian-bagian informasi penting lainnya.

c. Tag main
Digunakan untuk menampung seluruh konten pokok yang bersifat unik pada setiap halaman, memisahkan isi utama dari navigasi dan footer.

d. Tag section
Digunakan untuk membagi isi halaman ke dalam kelompok topik yang jelas, seperti bagian profil, visi-misi, daftar jurusan, dan sorotan berita.

e. Tag article
Digunakan untuk membungkus konten mandiri seperti artikel berita. Seluruh teks berita beserta data publikasi dibungkus di dalam elemen ini.

f. Tag figure dan figcaption
Digunakan untuk menampilkan gambar dokumentasi kampus beserta takarir atau keterangan teks di bawah gambar.

g. Tag table, caption, thead, tbody, tr, th, dan td
Digunakan untuk menyajikan data jurusan dan program studi dalam bentuk tabel yang rapi. Elemen caption memberi judul tabel, thead memisahkan judul kolom, th memberi penanda sel judul, dan tbody memuat baris data.

h. Tag aside
Digunakan untuk menyajikan konten pelengkap, seperti informasi alamat kontak pada halaman utama dan daftar berita terkait pada halaman berita.

i. Tag footer
Digunakan pada bagian bawah halaman untuk menampilkan informasi hak cipta dan keterangan tugas.

j. Struktur Heading (h1, h2, h3)
Disusun secara berurutan tanpa melompat tingkat untuk menjaga hierarki informasi yang benar dan memudahkan pembacaan dokumen.

--------------------------------------------------------------------------------

3. TANTANGAN DAN SOLUSI
Dalam proses pengerjaan website ini, beberapa hal teknis yang dihadapi antara lain:

a. Validasi Standar Elemen Tabel
Kendala: Pada awalnya penggunaan atribut border pada tag table menyebabkan munculnya catatan peringatan pada validator resmi W3C karena dinilai tidak sesuai dengan standar HTML5 modern.
Solusi: Menghapus atribut border dari tag table dan menggunakan deklarasi style sederhana untuk garis pembatas tabel, sehingga dokumen lolos validasi W3C secara penuh.

b. Penataan Jalur Berkas dan Tautan untuk GitHub Pages
Kendala: Proyek akan dijalankan pada subdirektori GitHub Pages, sehingga penggunaan path absolut komputer lokal akan mengakibatkan tautan gambar dan antarhalaman tidak dapat dibuka di internet.
Solusi: Menggunakan path relatif yang konsisten untuk seluruh berkas gambar dan halaman HTML, sehingga website dapat diakses dengan baik di server GitHub Pages.

c. Kerapihan Posisi dan Tata Letak Dokumen
Kendala: Tanpa pengaturan posisi, tampilan default browser membuat seluruh elemen menumpuk di sisi kiri layar.
Solusi: Mengatur margin dan alignment dokumen agar berada di posisi rata tengah secara proporsional sehingga dokumen terlihat rapi dan nyaman dibaca.

--------------------------------------------------------------------------------

4. HASIL VALIDASI W3C
Pengujian validasi dilakukan melalui layanan resmi W3C Nu HTML Checker (https://validator.w3.org/).
Hasil pengujian menunjukkan kedua berkas berhasil lolos validasi penuh:
- Berkas index.html: Lolos tanpa error dan tanpa warning.
- Berkas berita.html: Lolos tanpa error dan tanpa warning.



--------------------------------------------------------------------------------

5. PANDUAN PUBLIKASI KE GITHUB PAGES
1. Buat repositori baru pada akun GitHub Anda dengan nama: pemweb
2. Unggah folder tugas2 yang berisi berkas index.html, berita.html, dan folder assets ke dalam repositori tersebut.
3. Masuk ke menu Settings pada repositori, pilih menu Pages.
4. Pada bagian Source, pilih branch main dan folder / (root), lalu simpan.
5. Website akan aktif dan dapat diakses melalui tautan:
   https://[username].github.io/pemweb/tugas2/
