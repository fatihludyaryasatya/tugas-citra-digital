# Tugas Citra Digital

Pembuktian bahwa citra digital adalah susunan angka, menggunakan Python di Google Colab.

## Isi
- Shape, dtype, dan nilai piksel (array NumPy)
- Pembesaran 8x8 piksel beserta nilainya
- Pemisahan kanal R, G, B
- Konversi grayscale dan histogram
- Modifikasi angka piksel dan rekonstruksi gambar
- Analisis metadata (format, ukuran, EXIF)

## Struktur File
- `tugas_citra_digital.ipynb` : notebook Google Colab (kode dan penjelasan)
- `hasil_rekonstruksi.png` : gambar hasil rekonstruksi dari array angka
- `gray_8x8.csv` : nilai grayscale potongan 8x8 piksel
- `piksel_5x5.npy` : nilai RGB potongan 5x5 piksel (format NumPy)

## Cara Menjalankan
1. Buka `tugas_citra_digital.ipynb` di Google Colab.
2. Simpan foto (format HEIC) di Google Drive, lalu sesuaikan `drive_path` pada sel pertama dengan lokasi foto tersebut.
3. Klik **Runtime → Run all** dan izinkan akses Google Drive saat diminta.

Foto asli tidak disertakan di repository karena mengandung metadata pribadi (termasuk lokasi GPS). Hasil pengolahan sudah tersimpan pada output notebook dan file hasil di atas.

## Penulis
Fatih Ludy Aryasatya, NIM 24260047
Teknik Informatika, Universitas Nahdlatul Ulama Indonesia
