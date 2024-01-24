# Telco Churn Insight: Memprediksi Kehilangan Pelanggan dengan Algoritma Random Forest dan Decision Tree

## Deskripsi
Masalah utama dalam dunia bisnis adalah Customer Churn, atau kehilangan pelanggan, terutama dalam industri telekomunikasi yang mengalami persaingan yang sangat ketat. Berdasarkan penelitian, rata-rata tingkat churn bulanan di antara empat operator nirkabel teratas di AS adalah 1,9% hingga 2%. Tingkat churn pelanggan menjadi isu krusial bagi perusahaan telekomunikasi karena berdampak signifikan pada tingkat pertumbuhan perusahaan.

## Tujuan
Mengembangkan model klasifikasi menggunakan decision tree dan Random Forest untuk meramalkan kehilangan pelanggan dalam perusahaan telekomunikasi. Harapannya, model yang dihasilkan dapat membantu perusahaan memahami seberapa banyak pelanggan yang meninggalkan bisnis dan alasan di balik keputusan mereka untuk pergi.

## Data Collection
Dataset diperoleh langsung dari GitHub melalui sumber berikut: [Telco-Customer-Churn Dataset](https://github.com/arubhasy/dataset/blob/main/Telco-Customer-Churn.csv)

## Bahasa 
**Bahasa Pemrograman**: Python

**Library yang digunakan**: numpy, pandas, matplotlib, plotly express, seaborn, scikit-learn

## Analisis Data
### 1. Data Understanding
Pemahaman terkait data melibatkan analisis tipe data, volume tiap kategori, dan perbandingan antara customer churn dan no churn.

### 2. Data Preparation
- **Data Cleaning**: Menggunakan metode menghapus null value karena hanya sedikit data yang bernilai null.
- **Data Transformation**: Melakukan perubahan tipe data dan menghapus kolom yang tidak digunakan.

### 3. Splitting data
Pemisahan antara data test dan data train menggunakan rasio 80:20.

### 4. Modelling 
Penerapan metode klasifikasi menggunakan algoritma Decision Tree dan Random Forest.

### 5. Hasil Modelling dan Evaluasi Model
#### Decision Tree
Tingkat akurasi sebesar 72% dengan evaluasi positif yang lebih tinggi dibandingkan negatif. Evaluasi menunjukkan TN (True Negative) sebanyak 852 dan TP (True Positive) sebanyak 166.

#### Random Forest
Tingkat akurasi sebesar 81% dengan evaluasi positif yang lebih tinggi dibandingkan negatif. Evaluasi menunjukkan TN sebanyak 959 dan TP sebanyak 174.

Berdasarkan perbandingan, model menggunakan algoritma Random Forest lebih baik dengan hasil evaluasi sebagai berikut:
- **Accuracy**: 81%
- **Precision**: 85%
- **Recall**: 91%
- **F1-Score**: 88%

### 6. Penilaian Hasil Model 
Feature Importance menggunakan Random Forest menunjukkan bahwa variabel yang paling berpengaruh adalah Total Charges. Kesimpulan: pelanggan dengan Total Charges tinggi berpotensi melakukan churn lebih cepat.
