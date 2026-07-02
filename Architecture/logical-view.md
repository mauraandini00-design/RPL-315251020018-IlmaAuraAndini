# Logical View

## Komponen/Modul Utama
1. Modul Autentikasi — menangani login anggota dan admin.
2. Modul Katalog Buku — menampilkan dan mencari data buku.
3. Modul Peminjaman — memproses transaksi peminjaman dan pengembalian.
4. Modul Denda — menghitung dan mencatat denda keterlambatan.
5. Modul Anggota — mengelola data profil dan riwayat anggota.
6. Modul Laporan — menghasilkan laporan statistik untuk admin.

## Hubungan Antarmodul (Diagram Teks)

Anggota -> Modul Autentikasi -> Modul Katalog Buku -> Modul Peminjaman
Modul Peminjaman -> Modul Denda (saat pengembalian terlambat)
Modul Peminjaman -> Modul Anggota (update riwayat)
Admin -> Modul Autentikasi -> Modul Laporan
Semua Modul -> Database (melalui Data Access Layer)

Catatan: Diagram ini juga bisa digambar visual menggunakan draw.io, lalu screenshot 
dan disimpan di folder architecture/images/, kemudian disisipkan di sini.