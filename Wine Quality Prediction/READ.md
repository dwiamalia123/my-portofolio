# 🍷 Wine Quality Prediction

## 📌 Project Overview
Project ini bertujuan untuk **memprediksi kualitas wine** berdasarkan karakteristik fisikokimia menggunakan pendekatan **machine learning**.  
Analisis ini membantu produsen wine memahami faktor-faktor utama yang memengaruhi kualitas produk sehingga dapat meningkatkan proses produksi dan kontrol kualitas.

---

## 🎯 Objectives
- Menganalisis hubungan antara variabel fisikokimia dan kualitas wine
- Melakukan exploratory data analysis (EDA)
- Membangun model prediksi kualitas wine
- Mengevaluasi performa model machine learning

---

## 📂 Dataset
- **Sumber**: UCI Machine Learning Repository
- **Jumlah data**: 1.599 data (Red Wine)
- **Target variable**: `quality`
- **Format data**: CSV

**Variabel utama:**
- `fixed acidity`
- `volatile acidity`
- `citric acid`
- `residual sugar`
- `alcohol`
- `pH`
- `sulphates`

---

## 🛠 Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Scikit-learn**
- **Jupyter Notebook**
- **GitHub**

---

## 🔍 Data Cleaning & Preparation
Langkah-langkah yang dilakukan:
- Pengecekan dan penanganan missing values
- Explorasi outliers
- Feature selection
- Data splitting (train-test split)
- Feature scaling

---

## 📈 Exploratory Data Analysis (EDA)
Temuan utama:
- Kadar alkohol memiliki korelasi positif terhadap kualitas wine
- Beberapa fitur seperti volatile acidity menunjukkan korelasi negatif
- Distribusi kualitas wine cenderung tidak seimbang

---

## 🤖 Modeling
Model yang digunakan:
- Linear Regression
- Random Forest Regressor *(atau classifier jika dikategorikan)*

**Evaluation metrics:**
- RMSE
- R² Score

Model terbaik menunjukkan performa yang stabil dalam memprediksi kualitas wine.

---

## 💡 Insights & Recommendations
**Insights:**
- Alcohol dan sulphates merupakan fitur paling berpengaruh
- Kualitas wine dapat diprediksi cukup baik menggunakan model ensemble

**Recommendations:**
- Fokus pada kontrol kadar alkohol dan sulphates
- Gunakan model prediksi sebagai alat bantu quality control

---

## 📁 Project Structure
```text
wine_quality_prediction/
├── dataset/
│   └── winequality-red.csv
├── notebook/
│   └── wine_quality_prediction.ipynb
└── README.md
