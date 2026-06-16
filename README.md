# Perbandingan Performa Arsitektur CNN Klasik (CIFAR-10) vs Transfer Learning MobileNetV2 (Cats vs Dogs)
Proyek ini dibuat untuk memenuhi Tugas Individu Pembelajaran Mesin 2 mengenai klasifikasi citra menggunakan dua pendekatan Deep Learning yang berbeda.

Nama: Aliya Rathina Muhammad

NIM: 452024618074

Mata Kuliah: Pembelajaran Mesin 2

# Deskripsi Tugas
Membandingkan dua pendekatan utama dalam klasifikasi citra:
1. **CNN from Scratch**: Melatih arsitektur Convolutional Neural Network dari nol menggunakan dataset **CIFAR-10**.
2. **Transfer Learning**: Memanfaatkan arsitektur pretrained **MobileNetV2** (Feature Extraction dengan bobot ImageNet) menggunakan dataset **Cats vs Dogs**.

Kedua model dilatih dengan pembagian dataset standar yaitu **70% Training, 15% Validation, dan 15% Testing**.

# Struktur Repository
Ketentuan struktur tugas:

```text
project-cnn-vs-transfer-learning/
│
├── dataset/
│   ├── train/         
│   └── test/         
│
├── notebook/
│   └── cnn_vs_transfer_learning.ipynb 
│
├── report/
│   └── laporan.pdf    
│
├── README.md          
└── requirements.txt    
```
