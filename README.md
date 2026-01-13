# SVM-GWO-Breast-Cancer-Classification

# Breast Cancer Classification Using RBF-SVM Optimized by Grey Wolf Optimizer

## 📌 Deskripsi
Repository ini berisi implementasi klasifikasi kanker payudara menggunakan **Support Vector Machine (SVM)** dengan **kernel Radial Basis Function (RBF)** yang dioptimasi menggunakan **Grey Wolf Optimizer (GWO)**.  
Tujuan utama penelitian ini adalah meningkatkan performa klasifikasi dengan mengoptimalkan hyperparameter SVM, yaitu parameter **C** dan **γ (gamma)**.

Proyek ini dikembangkan sebagai bagian dari tugas mata kuliah dan ditujukan untuk eksperimen akademik.

---

## 📊 Dataset
Dataset yang digunakan merupakan dataset kanker payudara yang terdiri dari:
- **30 fitur numerik**
- **1 label kelas**:
  - `M` (Malignant)
  - `B` (Benign)

### Pembagian Data:
- **Train–Validation Set**
  - Dibagi kembali menjadi:
    - 80% data latih
    - 20% data validasi
- **Test Set**
  - Digunakan untuk evaluasi akhir model

---

## ⚙️ Metodologi
Tahapan penelitian meliputi:
1. **Prapemrosesan Data**
   - Konversi label ke numerik (M = 1, B = −1)
   - Normalisasi fitur menggunakan Min-Max Normalization [0,1]
2. **Baseline Model**
   - SVM dengan kernel RBF
   - Parameter awal: `C = 1.0`, `γ = 1.0`
3. **Optimasi Hyperparameter**
   - Menggunakan Grey Wolf Optimizer (GWO)
   - Parameter yang dioptimasi: `C` dan `γ`
4. **Pelatihan Model Akhir**
   - SVM dilatih ulang menggunakan parameter terbaik hasil GWO
5. **Evaluasi Model**
   - Menggunakan metrik akurasi pada data uji

---

## 🐺 Grey Wolf Optimizer (GWO)
Konfigurasi GWO yang digunakan:
- Jumlah serigala (wolves): **8**
- Jumlah iterasi maksimum: **50**
- Rentang parameter:
  - `C ∈ [0.1, 100]`
  - `γ ∈ [0.01, 10]`
- Fungsi fitness:
  - Akurasi validasi SVM
  - Ditambah penalti kecil untuk menghindari nilai parameter ekstrem

---

## 📈 Hasil Eksperimen
| Model | Akurasi |
|------|--------|
| SVM Baseline (RBF) | ±93% |
| SVM + GWO (Optimized) | **95.61%** |

Optimasi menggunakan GWO terbukti meningkatkan performa klasifikasi dibandingkan penggunaan parameter default.

---

## 📉 Visualisasi
- **Kurva konvergensi GWO**
- **Grafik akurasi selama iterasi**
- **Evaluasi akurasi pada data uji**

---

## 🧠 Teknologi yang Digunakan
- Python
- NumPy
- Pandas
- Matplotlib
- Google Colab / VS Code

# Breast Cancer Classification Using RBF-SVM Optimized by Grey Wolf Optimizer

## 📌 Deskripsi
Repository ini berisi implementasi klasifikasi kanker payudara menggunakan **Support Vector Machine (SVM)** dengan **kernel Radial Basis Function (RBF)** yang dioptimasi menggunakan **Grey Wolf Optimizer (GWO)**.  
Tujuan utama penelitian ini adalah meningkatkan performa klasifikasi dengan mengoptimalkan hyperparameter SVM, yaitu parameter **C** dan **γ (gamma)**.

Proyek ini dikembangkan sebagai bagian dari tugas mata kuliah dan ditujukan untuk eksperimen akademik.

---

## 📊 Dataset
Dataset yang digunakan merupakan dataset kanker payudara yang terdiri dari:
- **30 fitur numerik**
- **1 label kelas**:
  - `M` (Malignant)
  - `B` (Benign)

### Pembagian Data:
- **Train–Validation Set**
  - Dibagi kembali menjadi:
    - 80% data latih
    - 20% data validasi
- **Test Set**
  - Digunakan untuk evaluasi akhir model

---

## ⚙️ Metodologi
Tahapan penelitian meliputi:
1. **Prapemrosesan Data**
   - Konversi label ke numerik (M = 1, B = −1)
   - Normalisasi fitur menggunakan Min-Max Normalization [0,1]
2. **Baseline Model**
   - SVM dengan kernel RBF
   - Parameter awal: `C = 1.0`, `γ = 1.0`
3. **Optimasi Hyperparameter**
   - Menggunakan Grey Wolf Optimizer (GWO)
   - Parameter yang dioptimasi: `C` dan `γ`
4. **Pelatihan Model Akhir**
   - SVM dilatih ulang menggunakan parameter terbaik hasil GWO
5. **Evaluasi Model**
   - Menggunakan metrik akurasi pada data uji

---

## 🐺 Grey Wolf Optimizer (GWO)
Konfigurasi GWO yang digunakan:
- Jumlah serigala (wolves): **8**
- Jumlah iterasi maksimum: **50**
- Rentang parameter:
  - `C ∈ [0.1, 100]`
  - `γ ∈ [0.01, 10]`
- Fungsi fitness:
  - Akurasi validasi SVM
  - Ditambah penalti kecil untuk menghindari nilai parameter ekstrem

---

## 📈 Hasil Eksperimen
| Model | Akurasi |
|------|--------|
| SVM Baseline (RBF) | ±93% |
| SVM + GWO (Optimized) | **95.61%** |

Optimasi menggunakan GWO terbukti meningkatkan performa klasifikasi dibandingkan penggunaan parameter default.

---

## 📉 Visualisasi
- **Kurva konvergensi GWO**
- **Grafik akurasi selama iterasi**
- **Evaluasi akurasi pada data uji**

---

## 🧠 Teknologi yang Digunakan
- Python
- NumPy
- Pandas
- Matplotlib
- Google Colab / VS Code

# Breast Cancer Classification Using RBF-SVM Optimized by Grey Wolf Optimizer

## 📌 Deskripsi
Repository ini berisi implementasi klasifikasi kanker payudara menggunakan **Support Vector Machine (SVM)** dengan **kernel Radial Basis Function (RBF)** yang dioptimasi menggunakan **Grey Wolf Optimizer (GWO)**.  
Tujuan utama penelitian ini adalah meningkatkan performa klasifikasi dengan mengoptimalkan hyperparameter SVM, yaitu parameter **C** dan **γ (gamma)**.

Proyek ini dikembangkan sebagai bagian dari tugas mata kuliah dan ditujukan untuk eksperimen akademik.

---

## 📊 Dataset
Dataset yang digunakan merupakan dataset kanker payudara yang terdiri dari:
- **30 fitur numerik**
- **1 label kelas**:
  - `M` (Malignant)
  - `B` (Benign)

### Pembagian Data:
- **Train–Validation Set**
  - Dibagi kembali menjadi:
    - 80% data latih
    - 20% data validasi
- **Test Set**
  - Digunakan untuk evaluasi akhir model

---

## ⚙️ Metodologi
Tahapan penelitian meliputi:
1. **Prapemrosesan Data**
   - Konversi label ke numerik (M = 1, B = −1)
   - Normalisasi fitur menggunakan Min-Max Normalization [0,1]
2. **Baseline Model**
   - SVM dengan kernel RBF
   - Parameter awal: `C = 1.0`, `γ = 1.0`
3. **Optimasi Hyperparameter**
   - Menggunakan Grey Wolf Optimizer (GWO)
   - Parameter yang dioptimasi: `C` dan `γ`
4. **Pelatihan Model Akhir**
   - SVM dilatih ulang menggunakan parameter terbaik hasil GWO
5. **Evaluasi Model**
   - Menggunakan metrik akurasi pada data uji

---

## 🐺 Grey Wolf Optimizer (GWO)
Konfigurasi GWO yang digunakan:
- Jumlah serigala (wolves): **8**
- Jumlah iterasi maksimum: **50**
- Rentang parameter:
  - `C ∈ [0.1, 100]`
  - `γ ∈ [0.01, 10]`
- Fungsi fitness:
  - Akurasi validasi SVM
  - Ditambah penalti kecil untuk menghindari nilai parameter ekstrem

---

## 📈 Hasil Eksperimen
| Model | Akurasi |
|------|--------|
| SVM Baseline (RBF) | ±93% |
| SVM + GWO (Optimized) | **95.61%** |

Optimasi menggunakan GWO terbukti meningkatkan performa klasifikasi dibandingkan penggunaan parameter default.

---

## 📉 Visualisasi
- **Kurva konvergensi GWO**
- **Grafik akurasi selama iterasi**
- **Evaluasi akurasi pada data uji**

---

## 🧠 Teknologi yang Digunakan
- Python
- NumPy
- Pandas
- Matplotlib
- Google Colab / VS Code

---

## 📝 Catatan
- Implementasi SVM dilakukan **from scratch** tanpa library SVM bawaan.
- Proses optimasi dilakukan satu kali run sesuai kebutuhan presentasi.
- Kode difokuskan pada kejelasan algoritma dan analisis akademik.

---

## 👩‍💻 Author
Proyek ini disusun untuk keperluan akademik dan pembelajaran algoritma optimasi serta machine learning.
