# Gaya Arsitektur

## Pola yang Digunakan
Layered Architecture (Arsitektur Berlapis)

## Lapisan-lapisan
1. Presentation Layer — antarmuka pengguna (web/desktop) tempat anggota dan admin 
   berinteraksi dengan sistem.
2. Business Logic Layer — memproses aturan bisnis seperti validasi peminjaman, 
   perhitungan denda, dan pengecekan ketersediaan buku.
3. Data Access Layer — mengelola komunikasi antara aplikasi dan database.
4. Database Layer — penyimpanan data buku, anggota, dan transaksi peminjaman.

## Alasan Pemilihan
Layered architecture dipilih karena sistem perpustakaan memiliki alur kerja yang 
relatif standar (CRUD data buku, transaksi peminjaman), sehingga pemisahan tanggung 
jawab per lapisan memudahkan pengembangan, pengujian, dan pemeliharaan sistem tanpa 
memerlukan kompleksitas seperti microservices.