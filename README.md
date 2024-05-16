# World Bank Project Costs

## About Project
Mini Project Data Engineer ini merupakan implementasi hasil pembelajaran dengan merancang aplikasi teknologi sesuai trend industri yang meliputi langkah-langkah ETL serta analisis, penyimpanan, dan visualisasi data. Tujuan utama dari proyek ini adalah untuk melakukan proses data cleaning dan menggabungkannya menjadi satu tabel untuk menjalankan model prediksi biaya total proyek Bank Dunia.

## Tech Stacks
daftar tools dan framework yang digunakan dalam bentuk list seperti ini:
- Data Ingestion (library Python: bs4, requests, sqlite3)
- Data Transformation (library Python: pandas, numpy, sklearn.preprocessing (MinMax Scaler))
- Storage (Local Database (MySQL) dan Cloud (Firebase), library Python: dotenv, pymysql, firebase_admin)
- Data Visualization (library Python: openai, matplotlib.pyplot, seaborn, plotly)
- Tools (Visual Studio Code, Jupyter Notebook, Github)

## ETL Architecture
![alt text](https://github.com/arumkinanthi/nimas-sekararum-kinanthi_mini-project_de/blob/main/etl-architecture.png)

## Setup 
1. install library yang digunakan, contoh:
   ```
   pip install pandas
   ```
2. setup tools-tools yang digunakan.
3. konfigurasi Firebase untuk load data ke cloud storage.
4. konfigurasi MySQL Workbench untuk load data ke local database.