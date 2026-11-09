# Catatan Minggu 03: Inheritance

## Yang saya kerjakan
Pada tugas minggu ke 3, saya melengkapi kode yang sudah disediakam pada subclass Ruang, Laptop, dan AlatLab yang mewarisi kelas induk Aset. Setiap subclass dilengkapi dengn atribut spesifik, konstruktor yang memanggil super(), validasi data sesuai aturan bisnis, serta override method getJenis().

## Keputusan desain
Saya memutuskan untuk menempatkan data yang sma (seperti kode dan nama aset) di kelaa induk Aset supaya tidak perlu menulis ulang kodenya. Sedangkam data yang berbeda-bed seperti kapasitas untuk ruangan, spesifikasi untuk laptop, dan tingkat risiko untuk alat lab saya taruh di masing-masing kelas.

## Kendala
Sempat mengalami kendala error karena ada salah tulis nama parameter saat memanggil method super().

## Penggunaan AI
- Alat yang dipakai: Gemini
- Bagian yang dibantu AI: Class Ruang.java, Laptop.java, dan AlatLab.java.
- Prompt utama: 
    1. Bantu periksa dibagian manakah erronya?
    2. Bagaimana penerapan inheritance yang benar pada model Ruang, Laptop, dan AlatLab, serta panduan validasi dan penentuan field nya?
- Yang saya ubah atau tolak dari saran AI, dan alasannya: Tidak ada
- Satu hal yang saya pahami lebih baik sekarang: Jadi lebih mengerti cara pakai super() untuk manggil konstruktor induk dan membuat validasi data di Java.