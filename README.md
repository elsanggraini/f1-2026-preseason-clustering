# Analysis of F1 2026 Pre-Season Performance using K-Means Clustering

## 🏎️ Project Overview
Penelitian ini bertujuan untuk memetakan hirarki kekuatan tim dan karakteristik performa pembalap Formula 1 pada era regulasi teknis 2026 (Power Unit 50/50 & Active Aerodynamics). Menggunakan data telemetri dari pengujian pra-musim di Bahrain, project ini mengimplementasikan algoritma **Unsupervised Learning** untuk menembus fenomena *sandbagging*.

> **Current Status:** 📄 Under Review at *Jurnal Terapan Teknologi Informasi (JUTEI)*.  
> *Full manuscript will be uploaded following the official publication and acceptance.*

## 📊 Methodology
- **Clustering Algorithm:** K-Means Clustering
- **Feature Selection:** Fastest Lap, Average Lap Time, Standard Deviation (Consistency), and Total Laps (Reliability).
- **Optimization:** Elbow Method (K=4) & Silhouette Coefficient.
- **Data Source:** [FastF1 API](https://github.com/theOehrly/Fast-F1) integration.

## 🛠️ Tech Stack
- **Language:** Python
- **Environment:** Google Colab
- **Libraries:** FastF1, Scikit-Learn, Pandas, Matplotlib, Seaborn.

## 📈 Key Findings (Summary)
Berdasarkan hasil analisis clustering, profil performa dikelompokkan ke dalam 4 kategori strategis:
1. **Championship Leaders:** Memiliki kecepatan puncak (peak pace) sekaligus reliabilitas tinggi pada unit daya baru.
2. **Midfield Competitors:** Menunjukkan potensi kecepatan namun masih dalam tahap optimasi pemetaan energi hibrida.
3. **Consistency Focused:** Tim yang memprioritaskan data jarak tempuh (long-run) dibandingkan kecepatan murni.
4. **Reliability Challengers:** Kelompok yang menghadapi kendala teknis signifikan pada regulasi mesin 2026.

## 📂 Repository Structure
- `notebooks/`: File `.ipynb` berisi proses *data cleaning*, *feature engineering*, hingga *clustering*.
- `plots/`: Visualisasi grafik Elbow, Silhouette Score, dan Scatter Plot hasil pemetaan.
- `requirements.txt`: Daftar library Python yang diperlukan untuk menjalankan project ini.

---
**Author:** Elsa Anggraini  
**Affiliation:** Universitas Bina Sarana Informatika (UBSI)  
**Topic:** Data Science, AI, & Machine Learning in Sports Telemetry.
