# 🚢 OmniShip Logistics: Control Tower Dashboard

> ⚠️ **Disclaimer:** Proyek ini adalah portofolio pribadi yang dibuat untuk tujuan demonstrasi kemampuan *Data Analytics*. **OmniShip** adalah entitas bisnis fiktif. Seluruh data yang digunakan dalam analisis ini bersumber dari dataset publik di **Kaggle** (*E-Commerce Shipping Data*).

![Dashboard Preview](dashboard/OmniShip%20Dashboard.jpg)

## 📌 Deskripsi Proyek
Proyek ini merupakan simulasi *end-to-end Data Analytics* yang merancang sebuah "Control Tower" (Pusat Kendali) berbasis data untuk perusahaan e-commerce logistik. Tujuan utama proyek ini adalah melacak performa pengiriman, menganalisis faktor penyebab keterlambatan (*late delivery*), dan mengukur dampaknya terhadap kepuasan pelanggan (*customer satisfaction*).

🔗 **[Klik di sini untuk melihat Dashboard Interaktif](https://app.powerbi.com/view?r=eyJrIjoiNWQ5MDQ0MmUtYmM4Yy00MWJjLTg0NWItMzVkZDgwM2VjNDcyIiwidCI6IjkwYWZmZTBmLWMyYTMtNDEwOC1iYjk4LTZjZWI0ZTk0ZWYxNSIsImMiOjEwfQ%3D%3D)**

## 🛠️ Tech Stack & Tools
* **Python (Jupyter Notebook):** Exploratory Data Analysis (EDA) & Data Cleaning (Pandas, Matplotlib)
* **Power BI:** Data Modeling, DAX (Data Analysis Expressions), & Visualisasi Interaktif
* **Power Query:** Transformasi Data & Lokalisasi Bahasa

## 📊 Business Insights Utama
Berdasarkan analisis yang dilakukan pada *dashboard*, ditemukan beberapa *insight* operasional:
1. **Bottleneck Area:** Blok Gudang F merupakan titik krisis dengan volume keterlambatan tertinggi mencapai 2,2 Ribu pesanan, mengindikasikan perlunya audit kapasitas di area tersebut.
2. **Anomali Promo Diskon:** Terdapat korelasi negatif yang mengejutkan, di mana pesanan dengan nominal diskon rendah (<$10) justru mengalami lonjakan rasio keterlambatan terbesar dibandingkan kategori diskon lainnya.
3. **Dampak pada Pelanggan:** Keterlambatan pengiriman terbukti merusak kepercayaan pelanggan secara signifikan. Sekitar 60% pelanggan yang memberikan rating bintang 1 adalah mereka yang paketnya mengalami keterlambatan.

## 📂 Struktur Repositori
* `data/`: Berisi dataset mentah dan dataset yang sudah dibersihkan.
* `notebook/`: Berisi *script* Python untuk proses *cleaning* dan EDA.
* `dashboard/`: Berisi dokumentasi visual *dashboard* final.

***
