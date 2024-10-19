# Submission-Dicoding Belajar Machine Learning Pemula

Repositori ini merupakan tugas akhir dari course **Belajar Machine Learning untuk Pemula** yang diselenggarakan oleh **Dicoding**. Proyek ini bertujuan untuk membangun model klasifikasi gambar menggunakan dataset **Rock Paper Scissors**. Model ini akan mengklasifikasikan gambar ke dalam tiga kategori: batu, kertas, atau gunting.

## Deskripsi Proyek

Dalam proyek ini, saya telah mengimplementasikan jaringan saraf konvolusi (Convolutional Neural Network/CNN) untuk mengklasifikasikan gambar dari gerakan tangan yang mewakili batu, kertas, dan gunting. Dataset yang digunakan disediakan sebagai bagian dari course ini, dan berisi gambar yang sudah diberi label.

### Fitur Utama
- **Klasifikasi Gambar**: Model ini mampu mengklasifikasikan gambar menjadi tiga kelas: Batu, Kertas, dan Gunting.
- **Jaringan Saraf Konvolusi (CNN)**: Dibangun menggunakan TensorFlow dan Keras untuk mencapai akurasi yang baik.
- **Pelatihan dan Validasi**: Dataset dibagi menjadi set pelatihan dan validasi untuk mengevaluasi performa model.

## Dataset
Dataset yang digunakan merupakan kumpulan gambar dari gerakan tangan yang mewakili **batu**, **kertas**, dan **gunting**. Dataset ini dibagi menjadi set pelatihan dan pengujian untuk memvalidasi performa model.

- **Data Pelatihan**: Gambar-gambar yang digunakan untuk melatih model.
- **Data Validasi**: Digunakan untuk memvalidasi akurasi dan generalisasi model.

## Arsitektur Model
Model CNN ini terdiri dari beberapa lapisan, antara lain:
- Lapisan Konvolusi (Convolutional Layers)
- Lapisan MaxPooling
- Lapisan Fully Connected (Dense)
- Dropout untuk regularisasi

## Hasil
Model yang telah dilatih mencapai akurasi sekitar **XX%** pada set validasi. Peningkatan di masa depan dapat mencakup fine-tuning model atau menambahkan lebih banyak data untuk generalisasi yang lebih baik.
