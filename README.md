# Analysis of F1 2026 Pre-Season Performance using K-Means Clustering

## 🏎️ Project Overview
This research aims to map the hierarchy of team strength and driver performance characteristics in the 2026 Formula 1 technical regulation era (50/50 Power Unit & Active Aerodynamics). Utilizing telemetry data from pre-season testing in Bahrain, this project implements **Unsupervised Learning** algorithms to penetrate the "sandbagging" phenomenon and uncover true performance patterns.

**Current Status:** 🏆 **Published** in Jurnal Terapan Teknologi Informasi (JUTEI) Vol. 10 No. 1, April 2026.

## 📊 Methodology
- **Clustering Algorithm:** K-Means Clustering.
- **Feature Selection:** Fastest Lap, Average Lap Time, Standard Deviation (Consistency), and Total Laps (Reliability).
- **Optimization:** Elbow Method (K=4) & Silhouette Coefficient.
- **Data Source:** [FastF1 API](https://github.com/theOehrly/Fast-F1) integration.

## 🛠️ Tech Stack
- **Language:** Python
- **Environment:** Google Colab
- **Libraries:** FastF1, Scikit-Learn, Pandas, Matplotlib, Seaborn.

## 📈 Key Findings (Summary)
Based on the clustering analysis, performance profiles are categorized into 4 strategic groups:
1. **Championship Leaders:** Possessing both peak pace and high reliability on the new power units.
2. **Midfield Competitors:** Showing speed potential but still in the optimization phase of hybrid energy mapping.
3. **Consistency Focused:** Teams prioritizing long-run mileage data over pure raw speed.
4. **Reliability Challengers:** Groups facing significant technical hurdles with the 2026 engine regulations.

## 📂 Repository Structure
- `notebooks/`: `.ipynb` files covering data cleaning, feature engineering, and the clustering process.
- `plots/`: Visualizations of the Elbow method, Silhouette Score, and Cluster Scatter Plots.
- `requirements.txt`: List of Python libraries required to run this project.

---
**Author:** Elsa Anggraini  
**Affiliation:** Universitas Bina Sarana Informatika (UBSI)  
**Topic:** Data Science, AI, & Machine Learning in Sports Telemetry.
