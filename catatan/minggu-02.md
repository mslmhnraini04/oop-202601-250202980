# Catatan Minggu 02: (Struktur OOP: Class, Object, Encapsulation)


## Yang saya kerjakan
Yang aku kerjakan di minggu ini yaitu melengkapi implementasi kelas "Aset Java" menggunakan field private (kode, nama, status, kondisi). Aku juga nambahin konstruktor, getter, dan setter yang udah ada validasinya (IllegalArgumentException) agar tidak bisa diisi null atau string kosong. Nilai awalnya otomatis di-set ke TERSEDIA buat status dan BAIK buat kondisi. 

## Keputusan desain
Pada keputusan desain aku pakai modifier final di field kode tanpa setter biar nilainya gak bisa diubah. Teks kode dan nama dinormalisasi pakai trim() dan toUpperCase() supaya formatnya konsisten. Terus untuk, logika validasi null dan spasi kosong digabung ke helper method validasiTeks() biar tidak berulang.

## Kendala
1. PowerShell Kena Block pas mau ngetes .\scripts\uji.ps1, sempat kena blokir Windows (PSSecurityException).
2. Sempat muncul garis merah yang menandakan error

## Penggunaan AI
- Alat yang dipakai: Claude dan Gemini
- Bagian yang dibantu AI: Membantu bkin struktur class Aset.java, membantu menyecek fungsi validasi IllegalArgumentException yang sempat error, sama benerin error pas pengujian di terminal.
- Prompt utama: Bntu perbaiki kode tersebut dan jelaskan tiap bagiannya
- Yang saya ubah atau tolak dari saran AI, dan alasannya: Tidak ada
- Satu hal yang saya pahami lebih baik sekarang: Aku jadi lebih paham fungsi private dan validasi if, biar data aset gak bisa diisi asal-asalan atau diubah sembarangan.