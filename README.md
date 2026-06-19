# Early Stage Diabetes Risk Prediction using Quadratic Discriminant Analysis (QDA)

Repositori ini berisi proyek Machine Learning untuk memprediksi risiko diabetes pada tahap awal berdasarkan tanda-tanda dan gejala klinis. Model utama yang digunakan dan dikembangkan dalam proyek ini adalah **Quadratic Discriminant Analysis (QDA)**.

## 📌 Tentang Proyek
Diabetes adalah salah satu penyakit kronis yang paling umum di dunia. Deteksi dini terhadap gejala awal sangat penting untuk mencegah komplikasi lebih lanjut. Proyek ini berfokus pada analisis data klinis pasien dan melatih model klasifikasi statistik (QDA) untuk menentukan apakah seorang pasien memiliki risiko tinggi terkena diabetes atau tidak.

## 📊 Dataset
Dataset yang digunakan dalam proyek ini diperoleh dari Kaggle:
🔗 [Early Stage Diabetes Risk Prediction Dataset](https://www.kaggle.com/datasets/ishandutta/early-stage-diabetes-risk-prediction-dataset)

Dataset ini berisi data tanda dan gejala dari pasien yang baru terdiagnosis diabetes atau menunjukkan kecenderungan diabetes.

### Fitur-Fitur Dataset:
* **Age:** Usia pasien (20-65 tahun).
* **Gender:** Jenis kelamin (Male / Female).
* **Polyuria:** Gejala sering buang air kecil (Yes / No).
* **Polydipsia:** Gejala rasa haus berlebihan (Yes / No).
* **Sudden Weight Loss:** Penurunan berat badan secara tiba-tiba (Yes / No).
* **Weakness:** Rasa lemah atau letih (Yes / No).
* **Polyphagia:** Nafsu makan berlebihan (Yes / No).
* **Genital Thrush:** Infeksi jamur pada area genital (Yes / No).
* **Visual Blurring:** Penglihatan kabur (Yes / No).
* **Itching:** Rasa gatal (Yes / No).
* **Irritability:** Mudah marah (Yes / No).
* **Delayed Healing:** Penyembuhan luka yang lambat (Yes / No).
* **Partial Paresis:** Kelumpuhan sebagian otot (Yes / No).
* **Muscle Stiffness:** Kaku otot (Yes / No).
* **Alopecia:** Kerontokan rambut / Kebotakan (Yes / No).
* **Obesity:** Obesitas (Yes / No).
* **Class:** Target klasifikasi (Positive / Negative).

## 🛠️ Alur Kerja Proyek (Workflow)
Di dalam file `ModelQDA.ipynb`, proses pengerjaan dibagi menjadi beberapa tahap berikut:
1. **Exploratory Data Analysis (EDA):** Memahami distribusi data, memeriksa *missing values*, serta visualisasi korelasi antar fitur.
2. **Data Preprocessing:** * Melakukan encoding pada fitur kategorikal (mengubah `Yes`/`No` dan `Male`/`Female` menjadi nilai numerik `1`/`0`).
   * Memisahkan fitur (*features*) dan target klasifikasi (*label*).
3. **Data Splitting:** Membagi dataset menjadi data latih (*training set*) dan data uji (*testing set*).
4. **Model Training:** Melatih model klasifikasi menggunakan algoritma **Quadratic Discriminant Analysis (QDA)** dari pustaka Scikit-Learn.
5. **Model Evaluation:** Mengevaluasi performa model menggunakan metrik akurasi, *Precision*, *Recall*, *F1-Score*, serta menampilkan *Confusion Matrix* untuk melihat performa prediksi riil vs prediksi model.

## 📁 Struktur Repositori
* `ModelQDA.ipynb` : Jupyter Notebook utama yang berisi kode implementasi dari awal hingga evaluasi model QDA.
* `README.md` : Dokumentasi lengkap mengenai proyek ini.

## 🚀 Cara Menjalankan Proyek Secara Lokal

1. **Clone Repositori Ini**
   ```bash
   git clone [https://github.com/zhabiansyah/Model-QDA.git](https://github.com/zhabiansyah/Model-QDA.git)
   cd Model-QDA
