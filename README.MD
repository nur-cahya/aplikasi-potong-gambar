# 
Aplikasi Potong Gambar adalah aplikasi web yang memungkinkan Anda mengunggah gambar, mempratinjaunya, memotongnya berdasarkan posisi dan ukuran, dan mengunduh gambar hasil pemotongan. Aplikasi web dibangun menggunakan Flask dan OpenCV.

## Fitur

- Pilih file gambar dari perangkat lokal Anda.
- Pratinjau gambar yang dipilih sebelum memotong.
- Pilih posisi potong dari opsi yang telah ditentukan.
- Tentukan ukuran tanaman sebagai nilai numerik.
- Pangkas gambar berdasarkan posisi dan ukuran yang dipilih.
- Lihat gambar yang dipotong yang dihasilkan.
- Unduh gambar yang dipotong.
- Unduh proses pemotongan sebagai file penurunan harga.

## Instalasi

1. Kloning repositori:
    git clone https://github.com/nur-cahya/aplikasi-potong-gambar.git

2. Ubah ke direktori proyek:
    cd py-img-cropper

3. Instal dependensi:
    pip instal -r requirements.txt

## Penggunaan

1. Mulai aplikasi web:
    aplikasi python.py

2. Buka browser web Anda dan buka `http://localhost:5000`.
3. Pilih file gambar dengan mengklik tombol "Pilih gambar".
4. Pratinjau gambar yang dipilih.
5. Pilih posisi pangkas dari daftar dropdown.
6. Tentukan ukuran pemotongan dalam piksel.
7. Klik tombol "Potong" untuk melakukan operasi pemotongan.
8. Lihat gambar hasil pemotongan.
9. Unduh gambar hasil pemotongan sebagai file markdown atau gambar.
