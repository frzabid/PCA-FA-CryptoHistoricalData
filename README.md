# PCA-FA-CryptoHistoricalData  

## Deskripsi  
Repositori ini berisi skrip R untuk melakukan analisis *Principal Component Analysis* (PCA) dan *Factor Analysis* (FA) pada dataset historis. Metode ini digunakan untuk mereduksi dimensi data dan menemukan pola atau faktor tersembunyi yang dapat membantu memahami struktur variabel yang kompleks.  

## Fitur Utama  
- Pre-processing data dan pengecekan missing values  
- Uji KMO dan Bartlett Test untuk kelayakan analisis  
- Perhitungan PCA secara manual dan menggunakan fungsi `prcomp` serta `FactoMineR`  
- Visualisasi Scree Plot, Biplot, dan Correlation Circle  
- Kontribusi variabel pada komponen utama  
- Analisis FA dengan metode Bartlett scores  
- Visualisasi diagram faktor  

## Struktur File  
- `PCA & FA.R` — Skrip utama analisis PCA dan FA menggunakan R  
- Dataset: Pastikan data tersedia dengan format CSV (disesuaikan pada script bagian `read.csv()`)  

## Cara Penggunaan  
1. Download dataset dalam format CSV (`Crypto_Historical_Data.csv`)  
2. Sesuaikan path file pada baris:  
```r
data <- read.csv("D:/Anmul/Data PCA and PA/Crypto_Historical_Data.csv")
```  
3. Jalankan skrip `PCA & FA.R` menggunakan RStudio atau environment R lainnya.  
4. Lihat hasil analisis, visualisasi, dan interpretasi komponen dan faktor.  

## Library yang Digunakan  
- `readxl`  
- `psych`  
- `corrplot`  
- `dplyr`  
- `FactoMineR`  
- `factoextra`  
- `gridExtra`  

## Visualisasi Output  
- Scree Plot  
- Biplot PCA  
- Correlation Circle  
- Faktor loading diagram  

## Catatan  
- Pastikan semua library telah terinstal sebelum menjalankan skrip.  
- PCA dan FA dapat digunakan tidak hanya untuk data kripto, tetapi juga untuk analisis data multivariat lainnya.  

