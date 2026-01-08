# 📱 Indian Kids Screen Time Analysis

## 📌 Project Overview
Project ini menganalisis **durasi dan pola penggunaan screen time pada anak-anak di India** untuk memahami kebiasaan digital mereka serta potensi dampaknya terhadap aktivitas harian.  
Analisis ini bertujuan memberikan insight berbasis data yang dapat membantu orang tua, pendidik, dan pemangku kebijakan dalam mengambil keputusan yang lebih baik terkait penggunaan perangkat digital pada anak.

---

## 🎯 Objectives
- Menganalisis rata-rata screen time anak-anak
- Mengidentifikasi aktivitas digital yang paling banyak menyita waktu
- Melihat perbedaan screen time berdasarkan usia dan jenis aktivitas
- Menyajikan insight dalam bentuk dashboard interaktif

---

## 📂 Dataset
- **Sumber**: Public Dataset (Kaggle)
- **Jumlah data**: ± beberapa ribu observasi
- **Populasi**: Anak-anak di India
- **Format data**: CSV

**Variabel utama:**
- `age`
- `gender`
- `daily_screen_time_hours`
- `activity_type`
- `device_type`

---

## 🛠 Tools & Technologies
- **Power BI** – Dashboard & visualisasi
- **Excel** – Data cleaning awal
- **SQL (opsional)** – Query eksplorasi data

---

## 🔍 Data Cleaning & Preparation
Tahapan yang dilakukan:
- Pengecekan missing values
- Standarisasi format data
- Pengelompokan kategori aktivitas
- Validasi nilai screen time

---

## 📈 Exploratory Data Analysis (EDA)
Insight utama dari analisis:
- Rata-rata screen time anak meningkat seiring bertambahnya usia
- Aktivitas hiburan (video & game) mendominasi screen time harian
- Perbedaan pola screen time berdasarkan jenis aktivitas

---

## 📊 Dashboard
Dashboard dibuat menggunakan **Power BI** dan menampilkan:
- Rata-rata screen time harian
- Distribusi screen time berdasarkan usia
- Perbandingan screen time per jenis aktivitas
- Visualisasi yang interaktif dan mudah dipahami

📎 **File Dashboard:**  
`Indian_Kids_Screen_Time.pbix`

---

## 💡 Insights & Recommendations
**Insights:**
- Anak usia tertentu memiliki screen time yang lebih tinggi dibandingkan kelompok lain
- Aktivitas non-edukatif memiliki proporsi terbesar dalam penggunaan layar

**Recommendations:**
- Orang tua disarankan untuk membatasi screen time pada aktivitas hiburan
- Mendorong penggunaan perangkat digital untuk aktivitas edukatif
- Monitoring screen time secara berkala

---

## 📁 Project Structure
```text
indian_kids_screen_time/
├── dataset/
│   └── indian_kids_screen_time.csv
├── dashboard/
│   └── Indian_Kids_Screen_Time.pbix
└── README.md
