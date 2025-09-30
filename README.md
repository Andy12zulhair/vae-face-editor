# vae-face-editor
An interactive face editor built with a Variational Autoencoder (VAE) in TensorFlow

# 🎨 VAE Creative Face Editor

Proyek ini adalah implementasi dari Variational Autoencoder (VAE) untuk memanipulasi atribut wajah secara interaktif. Model ini dilatih pada dataset CelebA dan dapat mengubah ekspresi senyum pada gambar wajah.


*(Tips: Unggah screenshot Anda ke repository, lalu salin link-nya ke sini)*

## ✨ Fitur
- **Manipulasi Senyum:** Mengubah ekspresi wajah dari cemberut menjadi tersenyum menggunakan slider.
- **Generasi Wajah:** Mampu menghasilkan wajah-wajah baru dari ruang laten.
- **Antarmuka Interaktif:** Dibangun dengan Gradio untuk kemudahan penggunaan.

## 🛠️ Teknologi yang Digunakan
- Python
- TensorFlow / Keras
- Gradio
- NumPy & Pandas
- Google Colab

## 🚀 Cara Menjalankan
1.  Clone repository ini.
2.  Buka file `VAE_Face_Editor.ipynb` di Google Colab.
3.  Pastikan Anda telah mengunggah bobot model (`encoder_weights.h5` dan `decoder_weights.h5`).
4.  Jalankan semua sel kode. Aplikasi Gradio akan muncul di bagian akhir.
