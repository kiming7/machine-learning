# 📊Analisis Perbandingan Random Forest Regression, Support Vector Regression, dan Decision Tree Regression untuk Prediksi Polusi Udara Berdasarkan Data Sensor Air Quality


## 📌 Deskripsi
Penelitian ini bertujuan untuk membangun model Machine Learning dalam memprediksi kadar gas CO (karbon monoksida) berdasarkan data kualitas udara. Model dikembangkan menggunakan beberapa algoritma regresi dan dievaluasi untuk mendapatkan performa terbaik.

---

## 🎯 Algoritma yang Digunakan
Beberapa algoritma yang digunakan dalam penelitian ini yaitu:
- Random Forest Regression
- Support Vector Regression (SVR)
- Decision Tree Regression

---

## ⚙️ Tahapan Machine Learning

### 1. Data Preprocessing
Tahap ini dilakukan untuk memastikan kualitas data sebelum digunakan dalam modeling, meliputi:
- Handling missing value
- Pembersihan data
- Penghapusan kolom yang tidak relevan
- Pengecekan missing value
- Pemilihan fitur (feature) dan target

---

### 2. Pembagian Data
Data dibagi menjadi data latih (training) dan data uji (testing) dengan beberapa skenario:
- 70:30
- 80:20
- 90:10

---

### 3. Modeling
Model dibangun menggunakan algoritma:
- Random Forest Regression
- Decision Tree Regression
- Support Vector Regression (SVR)

---

### 4. Hyperparameter Tuning
Dilakukan menggunakan **GridSearchCV** untuk mendapatkan kombinasi parameter terbaik dari masing-masing algoritma.

---

### 5. Evaluasi Model
Performa model dievaluasi menggunakan metrik:
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

## 📈 Hasil
Berdasarkan hasil pengujian, model terbaik diperoleh dari algoritma **Support Vector Regression (SVR)** dengan skenario pembagian data **90:10 (training:testing)**.

Model ini menghasilkan nilai:
- **R² Score: 0.984119**



