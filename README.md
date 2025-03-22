# Image Classification dengan CNN & MobileNetV2

## Deskripsi
Proyek ini bertujuan untuk melakukan klasifikasi gambar menggunakan model Convolutional Neural Network (CNN) dan MobileNetV2.
Model dibuat, dilatih, dan dievaluasi menggunakan TensorFlow dan Keras.

## Dataset
Dataset yang digunakan adalah Intel Image Classification dari **https://www.kaggle.com/datasets/puneet6060/intel-image-classification**, yang terdiri dari gambar pemandangan dalam berbagai kategori:
- Bangunan
- Hutan
- Gunung
- Laut
- Jalan
- Gletser

## Arsitektur Model
Terdapat dua model yang digunakan:
1. **CNN Kustom**: Model CNN yang dibuat sendiri dengan beberapa lapisan convolutional dan pooling.
2. **MobileNetV2**: Model MobileNetV2 yang telah di-pretrained pada ImageNet dan ditambahkan lapisan kustom untuk klasifikasi dataset ini.

## Instalasi
Untuk menjalankan proyek ini, pastikan Anda telah menginstal semua dependensi dengan perintah berikut:

```bash
pip install -r requirements.txt
```

## Konversi Model
Model yang telah dilatih dapat dikonversi ke format lain:
- **SavedModel (TensorFlow format)**
- **HDF5 (.h5 format)**
- **TFLite (TensorFlow Lite)**
- **TFJS (TensorFlow.js)**

---
Semoga bermanfaat! 🚀

