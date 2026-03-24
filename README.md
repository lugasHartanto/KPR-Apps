Aplikasi konsol berbasis Java untuk menghitung dan mensimulasikan cicilan Kredit Pemilikan Rumah (KPR) menggunakan metode anuitas. Dilengkapi dengan tabel amortisasi lengkap dan validasi input.


📋 Fitur

✅ Perhitungan cicilan KPR metode anuitas
✅ Tabel amortisasi lengkap per bulan
✅ Validasi input pengguna
✅ Format output dalam Rupiah (IDR)
✅ Ringkasan hasil: cicilan per bulan, total pembayaran, total bunga
🔄 Perhitungan bunga floating rate (coming soon)
🔄 Migrasi ke Spring Boot + Thymeleaf (coming soon)


KPR-Apps/
├── src/
│   └── main/
│       └── java/
│           └── org.kprcalc/
│               ├── Main.java                  # Entry point program
│               ├── model/
│               │   └── KprData.java           # Model data KPR
│               ├── service/
│               │   ├── KprService.java        # Abstract class service
│               │   ├── KprAnuitas.java        # Implementasi metode anuitas
│               │   └── KprFlat.java           # Implementasi metode flat
│               └── util/
│                   ├── Formatter.java         # Format angka ke Rupiah
│                   └── Validator.java         # Validasi input pengguna
├── pom.xml
└── README.md


Rumus Perhitungan Anuitas

M = P × [r(1+r)^n] / [(1+r)^n - 1]

Keterangan:
M = Cicilan per bulan
P = Pokok pinjaman (Harga Properti - Uang Muka)
r = Suku bunga per bulan (Bunga Tahunan ÷ 12 ÷ 100)
n = Jumlah bulan (Tenor Tahun × 12)
