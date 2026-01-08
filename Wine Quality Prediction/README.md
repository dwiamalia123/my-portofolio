# 🍷 Wine Quality Prediction
**Supervised Learning | Linear, Ridge & Lasso Regression**

## 📌 Project Summary
Project ini memprediksi **kualitas wine** berdasarkan fitur fisikokimia menggunakan **supervised learning**. Fokus analisis adalah memilih model regresi yang **paling stabil** untuk mendukung proses **quality control**.

## 🎯 Objectives
- Mengidentifikasi fitur yang berpengaruh terhadap kualitas wine  
- Menangani multikolinearitas antar fitur  
- Membangun dan membandingkan Linear, Ridge, dan Lasso Regression  
- Menentukan model terbaik berdasarkan evaluasi performa  

## 📂 Dataset
- **Sumber**: Wine Quality Dataset (UCI ML Repository)  
- **Jumlah data**: 1.599 observasi  
- **Target**: `quality`  
- **Fitur utama**: alcohol, volatile acidity, sulphates, acidity, dll  

## 🛠 Tools & Skills
- **Python** (Pandas, NumPy)  
- **Visualization** (Matplotlib, Seaborn)  
- **Machine Learning** (Scikit-learn)  
- Regression Models: **Linear, Ridge, Lasso**  
- **Standard Scaling**, **VIF/correlation-based feature selection**  

## 🔍 Key Analysis
- Tidak ada missing values  
- Menghapus **240 data duplikat** dan **354 outliers** (metode IQR)  
- Normalisasi menggunakan **Standard Scaler**  
- Seleksi fitur dengan **Heatmap & VIF** (menghapus `density` dan `pH` karena VIF ekstrem)  
- Menggunakan regularisasi untuk mengatasi multikolinearitas  

## 🤖 Modeling & Evaluation
Model yang dibandingkan:
- Linear Regression (baseline)  
- Ridge Regression (regularization)  
- Lasso Regression (feature shrinking)  

**Hasil utama:**
- **Ridge Regression** adalah model paling stabil dengan **RMSE terendah dan R² tertinggi**  
- Lebih robust terhadap multikolinearitas dibanding Linear dan Lasso  

## 💡 Insights & Business Value
- `alcohol` berpengaruh positif terhadap kualitas wine  
- `volatile acidity` berpengaruh negatif terhadap kualitas  
- Model Ridge dapat membantu **estimasi kualitas lebih awal** untuk mendukung kontrol kualitas dan keputusan produksi berbasis data  

## 🎤 Presentation
[[Wine Quality Presentation]](https://www.canva.com/design/DAG8GeCKUe4/DfMIG65guSe5yzd9piEYfg/edit?utm_content=DAG8GeCKUe4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)


## 📬 Contact
**Dwi Amalia**  
Email: dwiamalia228@gmail.com  
LinkedIn: https://www.linkedin.com/in/dwi-amalia-/  
GitHub: https://github.com/dwiamalia123  
