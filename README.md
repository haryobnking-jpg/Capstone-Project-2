# Capstone-Project-2
This repository used for capstone project 2 (Purwadhika)
Tujuannya adalah untuk **memprediksi harga mobil bekas di Arab Saudi** berdasarkan berbagai fitur seperti merk, tipe, tahun produksi, kapasitas mesin, jarak tempuh, dan lain-lain.  

Dengan model ini, diharapkan pembeli maupun penjual bisa memiliki estimasi harga yang lebih akurat untuk pengambilan keputusan.  

---

## Dataset  
Dataset yang digunakan berisi informasi mobil bekas dengan fitur sebagai berikut:  
- **Type** → tipe mobil (misalnya Corolla, Yukon, dsb)  
- **Make** → merek mobil (Toyota, GMC, Nissan, dll)  
- **Region** → lokasi penjualan  
- **Gear_Type** → transmisi (Manual/Automatic)  
- **Origin** → asal mobil (Saudi, Gulf Arabic, dll)  
- **Options** → paket/kelengkapan (Standard, Semi Full, Full)  
- **Year** → tahun produksi  
- **Engine_Size** → kapasitas mesin (liter)  
- **Mileage** → jarak tempuh (km)  
- **Negotiable** → apakah harga bisa dinego (1 = iya, 0 = tidak)  
- **Price** → harga mobil (target prediksi)  

---

## 🔧 Metodologi  
1. **Exploratory Data Analysis (EDA)** → melihat distribusi data, missing value, outlier  
2. **Preprocessing**  
   - Encoding data kategorikal (OneHotEncoder, BinaryEncoder)  
   - Train-Test Split  
3. **Benchmarking Model**  
   - Linear Regression  
   - KNN  
   - Decision Tree  
   - Random Forest  
   - XGBoost  
4. **Hyperparameter Tuning** → fokus pada XGBoost sebagai model terbaik  
5. **Model Evaluation**  
   - Metrik: RMSE, MAE, MAPE  
6. **Save & Load Model** → menggunakan Pickle  
