# Physical View

## Infrastruktur

1. Client — perangkat pengguna (komputer/laptop/smartphone) yang mengakses sistem 
   melalui browser.
2. Web Server — menjalankan aplikasi sistem perpustakaan (contoh: menggunakan Node.js 
   atau PHP).
3. Application Server — menjalankan logika bisnis (business logic layer).
4. Database Server — menyimpan seluruh data (buku, anggota, transaksi), menggunakan 
   MySQL/PostgreSQL.
5. Jaringan — client terhubung ke server melalui internet/jaringan kampus (LAN/WiFi), 
   menggunakan protokol HTTPS untuk keamanan data.

## Gambaran Koneksi

Client (Browser) --[HTTPS]--> Web Server --> Application Server --> Database Server

Seluruh komponen server dapat ditempatkan pada satu server fisik (untuk skala kecil) 
atau dipisah ke beberapa server berbeda (untuk skala lebih besar/production).