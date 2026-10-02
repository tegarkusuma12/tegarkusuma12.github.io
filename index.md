# Tegar Maulana Bhakti Kusuma

**Data Scientist · Data Analyst · Data Engineer · AI Engineer**

📧 [kusumategar1255@gmail.com](mailto:kusumategar1255@gmail.com) · 📱 +62 851-7215-7204 · 📍 Surabaya  
[LinkedIn](https://linkedin.com/in/tegar-kusuma-connect) · [GitHub](https://github.com/tegarkusuma12)

---

## Tentang Saya

Mahasiswa **D4 Sains Data Terapan** di Politeknik Elektronika Negeri Surabaya (PENS) dengan fokus pada analitik data, data warehousing, dan artificial intelligence. Berpengalaman membangun sistem dari ETL pipeline, pemodelan prediktif, hingga deployment ke dashboard dan REST API.

---

## Keahlian

**Data Science**  
Machine Learning · NLP · Exploratory Data Analysis · Data Visualization · Sales Forecasting · Prescriptive Analytics

**Data Engineering**  
ETL Pipeline · PostgreSQL · Supabase · APScheduler · Airflow · Docker · SQLAlchemy

**LLM**  
LangChain · Groq API · Prompt Engineering · AI Agent (Tool-Calling)

**Backend**  
Python · FastAPI · Flask · REST API · Pandas · NumPy

**Tools**  
Git · DagsHub · Jupyter Notebook

---

## Proyek

---

### 🌍 Prediksi ISPU Jawa Timur

[GitHub](https://github.com/tegarkusuma12/Web-ISPU) · [Live Demo](https://web-prediksi-ispu.vercel.app/)

Belum ada sistem yang mampu memproyeksikan kualitas udara secara real-time untuk seluruh wilayah Jawa Timur. Proyek ini membangun sistem prediksi kualitas udara untuk 38 Kab/Kota di Jawa Timur yang menggabungkan data cuaca aktual, model prediksi XGBoost, dan dashboard peta interaktif.


- Merancang dan membangun **automated data pipeline** menggunakan APScheduler (cron per jam) untuk menarik data dari OpenWeather API dan menyimpannya ke Supabase PostgreSQL secara otomatis.
- Melakukan **feature engineering** berbasis deret waktu (lag features, rolling statistics) dan melatih model **XGBoost Multi-Output** untuk memproyeksikan 6 parameter polutan (PM2.5, PM10, SO2, CO, NO2, O3) hingga 24 jam ke depan.
- Mengimplementasikan kalkulator **ISPU standar Kemenlhk** (P.14/2020) untuk konversi konsentrasi polutan menjadi indeks kualitas udara.
- Membangun **REST API** menggunakan Flask dan merancang skema database dengan SQLAlchemy.
- Membuat **choropleth dashboard** menggunakan Leaflet.js dan Chart.js dengan fitur time-slider untuk melihat proyeksi +0 hingga +24 jam.

**Tech:** `Python` `XGBoost` `Flask` `Supabase` `APScheduler` `Leaflet.js` `Chart.js` `Docker`

---

### 🤖 SAKU — Smart POS & AI Assistant

[GitHub](https://github.com/tegarkusuma12/saku-smart-pos) · [Live Demo](https://saku-smart-pos-app.vercel.app/)

Pelaku UMKM seperti pemilik warung dan pedagang kecil sering kesulitan mencatat keuangan karena aplikasi kasir yang ada terlalu rumit. SAKU hadir sebagai platform Point of Sale dan business analytics yang dilengkapi AI chatbot berbahasa Indonesia — cukup ketik *"bayar listrik 150rb"* untuk mencatat transaksi, atau tanya *"besok butuh stok apa?"* untuk mendapat rekomendasi restock berbasis prediksi ML.


- Melakukan **EDA** (distribusi revenue, pola weekday vs weekend) dan melatih model **sales forecasting** menggunakan XGBoost dan Random Forest dengan evaluasi TimeSeriesSplit.
- Membangun modul **prescriptive analytics** yang mengubah output forecast menjadi rekomendasi restock (level urgensi: KRITIS / SEGERA / PERLU / AMAN).
- Mengembangkan **AI chatbot** menggunakan LangChain Agent dengan Groq LLM API dan 9 custom tools (catat pengeluaran, prediksi penjualan, cek hutang, rekomendasi restock, dll).
- Membangun backend **FastAPI** dan meng-containerize seluruh sistem menggunakan Docker.

**Tech:** `Python` `LangChain` `Groq LLM` `XGBoost` `FastAPI` `SQLAlchemy` `Docker`

---

### 🎴 REGOKEMON — Pokemon Card Value Analytic Tool

[GitHub](https://github.com/Bejochan/pokemon-card-value-analytic-tool)

Transaksi kartu Pokémon di marketplace rawan *mispricing* — sulit mengidentifikasi jenis kartu dari 20.000+ varian, menilai kondisi fisik secara objektif, dan mengetahui harga pasar wajar. REGOKEMON menyelesaikan ini dengan dual-model computer vision yang mengenali kartu secara instan, menilai kondisinya, lalu menghitung harga wajar dan memberikan sinyal transaksi.


- Merancang arsitektur sistem dan **pipeline identifikasi kartu** menggunakan OpenAI CLIP (ViT-B-32) + FAISS vector index untuk pencarian visual di antara 20.617 kartu referensi.
- Mengintegrasikan model **YOLOv8** untuk deteksi cacat fisik kartu (lecet, tertekuk, aus pinggir) sebagai condition grader.
- Membangun **analytics engine** dengan formula valuasi harga pasar wajar dan logika sinyal transaksi BUY/HOLD/SELL.
- Merancang **daily price tracker** menggunakan GitHub Actions cron job untuk sinkronisasi harga dari pokemontcg.io ke Supabase.

**Tech:** `PyTorch` `OpenAI CLIP` `YOLOv8` `FAISS` `FastAPI` `React` `Supabase` `GitHub Actions`

---

## Pendidikan

**D4 Sains Data Terapan** — Politeknik Elektronika Negeri Surabaya (PENS)  
Juli 2024 — Saat ini · IPK: **3.64**

**[Mastering AI Bootcamp](https://drive.google.com/file/d/142wzAxvX8PR5QeLlad8bZXdaPxklplww/view)** — Skill Academy by Ruangguru
