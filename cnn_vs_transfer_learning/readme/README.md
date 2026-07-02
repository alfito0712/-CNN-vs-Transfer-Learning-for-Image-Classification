# CNN vs Transfer Learning for Image Classification

## 📌 Deskripsi Proyek

Proyek ini merupakan tugas individu mata kuliah **Pembelajaran Mesin** yang bertujuan membandingkan performa **Convolutional Neural Network (CNN) from Scratch** dengan **Transfer Learning** menggunakan **MobileNetV2** pada klasifikasi citra dua kelas.

Eksperimen dilakukan menggunakan dua pendekatan:

1. CNN from Scratch
2. Transfer Learning (MobileNetV2)

Selanjutnya kedua model dibandingkan berdasarkan akurasi, loss, waktu training, confusion matrix, serta risiko overfitting.

---

## 🎯 Tujuan

- Mengimplementasikan CNN from Scratch.
- Mengimplementasikan Transfer Learning menggunakan MobileNetV2.
- Membandingkan performa kedua metode.
- Menganalisis kelebihan dan kekurangan masing-masing pendekatan.
- Menentukan metode yang paling sesuai berdasarkan karakteristik dataset.

---

## 📂 Dataset

### CNN from Scratch

- Dataset: CIFAR-10
- Kelas:
  - Cat
  - Dog

### Transfer Learning

- Dataset: Cats vs Dogs

Dataset dibagi menjadi:

- Training : 70%
- Validation : 15%
- Testing : 15%

---

## 🛠️ Library

- Python 3
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn

---

## 📁 Struktur Repository

```
project-cnn-vs-transfer-learning/
│
├── dataset/
│   └── link_dataset.txt
│
├── notebook/
│   └── cnn_vs_transfer_learning.ipynb
│
├── report/
│   └── laporan.pdf
│
├── README.md
│
└── requirements.txt
```

---

## 🧠 Arsitektur CNN From Scratch

```
Input Image (32x32x3)

↓

Conv2D (32)

↓

MaxPooling

↓

Conv2D (64)

↓

MaxPooling

↓

Conv2D (128)

↓

MaxPooling

↓

Flatten

↓

Dense (128)

↓

Dropout (0.5)

↓

Output (Sigmoid)
```

---

## 🚀 Transfer Learning

Model pretrained yang digunakan:

- MobileNetV2

Strategi:

- Feature Extraction
- Fine Tuning

---

## 📊 Evaluasi

Evaluasi model dilakukan menggunakan:

- Accuracy
- Loss
- Confusion Matrix
- Classification Report
- Training Time
- Validation Accuracy
- Testing Accuracy

Visualisasi:

- Accuracy Curve
- Loss Curve
- Confusion Matrix
- Contoh Prediksi Benar
- Contoh Prediksi Salah

---

## 📈 Hasil Eksperimen

| Metrik | CNN | Transfer Learning |
|--------|-----|-------------------|
| Training Accuracy | - | - |
| Validation Accuracy | - | - |
| Testing Accuracy | - | - |
| Training Loss | - | - |
| Validation Loss | - | - |
| Training Time | - | - |

> Isi tabel setelah proses training selesai.

---

## 💻 Cara Menjalankan

### 1. Clone Repository

```bash
git clone https://github.com/username/project-cnn-vs-transfer-learning.git
```

### 2. Install Library

```bash
pip install -r requirements.txt
```

### 3. Jalankan Notebook

Buka notebook:

```
notebook/cnn_vs_transfer_learning.ipynb
```

Kemudian jalankan seluruh cell menggunakan:

- Kaggle Notebook
- Google Colab
- Jupyter Notebook

---

## 📷 Output

Notebook akan menghasilkan:

- Grafik Accuracy
- Grafik Loss
- Confusion Matrix
- Classification Report
- Prediksi Benar
- Prediksi Salah

---

## 📖 Kesimpulan

Berdasarkan hasil eksperimen, Transfer Learning menggunakan MobileNetV2 memberikan performa yang lebih baik dibandingkan CNN from Scratch pada dataset berukuran kecil. Transfer Learning menghasilkan akurasi lebih tinggi, waktu pelatihan lebih singkat, serta lebih tahan terhadap overfitting.

CNN from Scratch tetap menjadi pilihan yang baik apabila tersedia dataset yang besar dan spesifik terhadap domain tertentu.

---

## 👨‍🎓 Identitas

**Nama:** *(khafidz alfito setiawan)*

**NIM:** *(452024611011)*

**Mata Kuliah:** Pembelajaran Mesin 2

**Universitas:** *(universitas darussalam gontor )*

---

## 📜 Lisensi

Proyek ini dibuat untuk keperluan akademik sebagai tugas individu mata kuliah Pembelajaran Mesin.
