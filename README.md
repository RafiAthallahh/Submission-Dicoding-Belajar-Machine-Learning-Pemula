# Submission-Dicoding Belajar Machine Learning Pemula

Repositori ini merupakan tugas akhir dari course **Belajar Machine Learning untuk Pemula** yang diselenggarakan oleh **Dicoding**. Proyek ini bertujuan untuk membangun model klasifikasi gambar menggunakan dataset **Rock Paper Scissors**. Model ini akan mengklasifikasikan gambar ke dalam tiga kategori: batu, kertas, atau gunting.

## Deskripsi Proyek

Dalam proyek ini, saya telah mengimplementasikan jaringan saraf konvolusi (Convolutional Neural Network/CNN) untuk mengklasifikasikan gambar dari gerakan tangan yang mewakili batu, kertas, dan gunting. Dataset yang digunakan disediakan sebagai bagian dari course ini, dan berisi gambar yang sudah diberi label.

### Fitur Utama

- **Klasifikasi Gambar**: Model ini mampu mengklasifikasikan gambar menjadi tiga kelas: Batu, Kertas, dan Gunting.
- **Jaringan Saraf Konvolusi (CNN)**: Dibangun menggunakan TensorFlow dan Keras untuk mencapai akurasi yang baik.
- **Pelatihan dan Validasi**: Dataset dibagi menjadi set pelatihan dan validasi untuk mengevaluasi performa model.
- **Augmentasi Gambar**: Menggunakan **ImageDataGenerator** untuk melakukan augmentasi gambar agar meningkatkan generalisasi model.
- **Model Sequential**: Model dibangun menggunakan arsitektur Sequential.
- **Pelatihan Cepat**: Waktu pelatihan model dibatasi agar tidak lebih dari 30 menit.
- **Prediksi Gambar Unggahan**: Model mampu memprediksi gambar yang diunggah langsung ke Google Colaboratory.


## Dataset
Dataset yang digunakan merupakan kumpulan gambar dari gerakan tangan yang mewakili **batu**, **kertas**, dan **gunting** yang berasal dari https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip . Dataset ini dibagi menjadi set pelatihan dan pengujian untuk memvalidasi performa model.


- **Data Pelatihan**: Gambar-gambar yang digunakan untuk melatih model.
- **Data Validasi**: Digunakan untuk memvalidasi akurasi dan generalisasi model.

## Arsitektur Model
Model CNN ini terdiri dari beberapa lapisan, antara lain:
- Lapisan (Convolutional Layers)
- Lapisan MaxPooling
- Lapisan Fully Connected (Dense)
- Dropout untuk regularisasi

## Hasil
Model yang telah dilatih mencapai akurasi **90%** pada set validasi dan **89%** pada set validasi. Peningkatan di masa depan dapat mencakup fine-tuning model atau menambahkan lebih banyak data untuk generalisasi yang lebih baik.
