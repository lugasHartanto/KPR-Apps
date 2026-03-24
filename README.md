Aplikasi konsol berbasis Java untuk menghitung dan mensimulasikan cicilan Kredit Pemilikan Rumah (KPR) menggunakan metode anuitas. Dilengkapi dengan tabel amortisasi lengkap dan validasi input.


📋 Fitur

✅ Perhitungan cicilan KPR metode anuitas
✅ Tabel amortisasi lengkap per bulan
✅ Validasi input pengguna
✅ Format output dalam Rupiah (IDR)
✅ Ringkasan hasil: cicilan per bulan, total pembayaran, total bunga
🔄 Perhitungan bunga floating rate (coming soon)
🔄 Migrasi ke Spring Boot + Thymeleaf (coming soon)


Rumus Perhitungan Anuitas

M = P × [r(1+r)^n] / [(1+r)^n - 1]

Keterangan:
M = Cicilan per bulan
P = Pokok pinjaman (Harga Properti - Uang Muka)
r = Suku bunga per bulan (Bunga Tahunan ÷ 12 ÷ 100)
n = Jumlah bulan (Tenor Tahun × 12)
