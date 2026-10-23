# Pertemuan 09 List dan Pengolahan Data Numerik
Nama: Ahadin Ilman
NIM: 2225250220
Kelas: 3A

## Tujuan
Mengolah kumpulan data numerik dengan list Python secara terstruktur.

## Struktur Program
* `latihan/01_buat_list.py`: Pembuatan dan pembacaan list.
* `latihan/02_indeks_slicing.py`: Akses elemen via indeks dan slicing.
* `latihan/03_manipulasi_list.py`: Modifikasi, append, insert, dan remove.
* `latihan/04_agregasi_nilai.py`: Perhitungan statistik dasar.
* `latihan/05_filter_kelulusan.py`: Penyaringan data berdasarkan syarat.
* `latihan/06_fungsi_statistik.py`: Penerapan fungsi pada list.
* `praktik/analisis_nilai_mahasiswa.py`: Program utama analisis nilai.

## Cara Menjalankan
python3 praktik/analisis_nilai_mahasiswa.py

## Test Case
* Data `[60, 70, 80]` -> Rata-rata: `70.00` (Status: Berhasil)
* Data `[60, 70, 80]` -> Min/Max: `60 / 80` (Status: Berhasil)
* Data `[60, 70, 80]` -> Jumlah lulus: `3` (Status: Berhasil)
* Data `[59, 60, 61]` -> Batas kelulusan (>=60): `2 lulus` (Status: Berhasil)
* List kosong -> Penanganan fungsi aman tanpa error `ZeroDivisionError` (Status: Berhasil)

## Refleksi
Memahami bahwa indeks list dimulai dari angka 0 sangat penting untuk menghindari kesalahan `IndexError`, serta penggunaan fungsi `len()` membuat perhitungan rata-rata menjadi dinamis.