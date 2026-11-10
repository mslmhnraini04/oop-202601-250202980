# Catatan Minggu 04: Polymorphism

## Yang saya kerjakan
Saya melengkapi kode untuk menghitung denda keterlambatan di kelas induk `Aset` dan tiga kelas turunannys. Selain itu, saya juga membuat fungsi pencarian di `KatalogAset` yang bisa dipkai dua cara yaitu berdasarkam nama saja, atau berdasarkan nama sekaligus jenis asetnya.

## Keputusan desain
Pengecekan jumlah hari saya taruh di kelas induk `Aset` biar kodenya rapi dan tidak perlu ditulis berulang di kelas anak. Untuk pencarian, teksnya disamakan jadi huruf kecil semua duly biar hasilnya tetap ketemu walaupun penulisan huruf kapitalnya beda.

## Kendala
Sempat kena error pas ngetes pakai `.\scripts\uji`.ps1 karena diblokir kebijakan PowerShell. Masalah ini selesai setelah nambahin perintah `-ExecutionPolicy Bypass` pas menjalankan skripnya.

## Penggunaan AI
- Alat yang dipakai: Gemini
- Bagian yang dibantu AI: Logika perhitungam denda di `Aset` dan pembuatan fungsi overloading cari di `KatalogAset`.
- Prompt utama: Bantu benarkan kode yang error
- Yang saya ubah atau tolak dari saran AI, dan alasannya: Tidak ada
- Satu hal yang saya pahami lebih baik sekarang: Perbedaan dari overriding (menimpa fungsi dari kelas induk) dan overloading (pakai nama fungsi yang sama tapi beda isian parameternya).