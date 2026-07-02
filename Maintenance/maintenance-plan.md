# Maintenance Plan
## Sistem: Aplikasi Manajemen Perpustakaan

## Corrective
1. Memperbaiki bug pada fitur peminjaman buku yang tidak mengurangi stok setelah transaksi berhasil.
2. Memperbaiki kesalahan perhitungan denda keterlambatan pengembalian buku.
3. Memperbaiki error saat anggota mencari buku dengan judul yang mengandung karakter khusus.

## Adaptive
4. Menyesuaikan sistem dengan kebijakan baru batas maksimal peminjaman buku per anggota.
5. Menyesuaikan integrasi dengan sistem akademik kampus karena perubahan format data mahasiswa (NIM/NIS).
6. Memperbarui library barcode scanner agar kompatibel dengan perangkat scanner model terbaru.

## Perfective
7. Menambahkan fitur reservasi/booking buku yang sedang dipinjam anggota lain.
8. Menambahkan fitur notifikasi email/SMS pengingat sebelum jatuh tempo pengembalian buku.
9. Mempercepat proses pencarian katalog buku dengan optimasi indexing database.

## Preventive
10. Melakukan refactoring pada modul manajemen data anggota agar kode lebih mudah dipelihara.
11. Melakukan backup database peminjaman secara berkala untuk mencegah kehilangan data.
12. Memperbarui dokumentasi teknis sistem setiap ada perubahan fitur.