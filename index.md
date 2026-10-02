# Tegar Maulana Bhakti Kusuma

**Data Scientist · Data Analyst · AI Engineer**

📧 kusumategar1255@gmail.com · 📱 +62 851-7215-7204 · 📍 Surabaya, Indonesia  
[LinkedIn](https://linkedin.com/in/tegar-kusuma-connect) · [GitHub](https://github.com/tegarkusuma12)

---

## Tentang Saya

Mahasiswa **D4 Sains Data Terapan** di Politeknik Elektronika Negeri Surabaya (PENS) dengan fokus pada *machine learning*, *computer vision*, dan *generative AI*. Berpengalaman membangun sistem data *end-to-end* — mulai dari ETL pipeline, pemodelan prediktif, hingga deployment dalam bentuk dashboard interaktif dan REST API.

---

## Keahlian Teknis

| Bidang | Teknologi |
|---|---|
| **Machine Learning** | XGBoost, Random Forest, Scikit-learn, Time Series Forecasting |
| **Computer Vision** | YOLOv8, OpenAI CLIP, OpenCV, PyTorch, FAISS |
| **Generative AI / NLP** | LangChain, Groq LLM API, Prompt Engineering, AI Agent |
| **Data Engineering** | Python, SQL, PostgreSQL, Supabase, ETL Pipeline, Pandas, NumPy |
| **Backend & Deployment** | FastAPI, Flask, Docker, REST API, SQLAlchemy |
| **Visualisasi** | Tableau, Chart.js, Leaflet.js, Matplotlib, Seaborn |

---

## Proyek Terpilih

### 1. REGOKEMON — Pokemon Card Value Analytic Tool 🎴

> Dual-Model Computer Vision & Estimasi Harga Pasar Wajar untuk Marketplace

🔗 [GitHub Repository](https://github.com/Bejochan/pokemon-card-value-analytic-tool)

Sistem analitika berbasis **Dual-Model Computer Vision** untuk membantu penjual & pembeli kartu Pokémon di marketplace.

- **Model 1 — Card Identifier:** OpenAI CLIP (ViT-B-32) + FAISS vector index untuk identifikasi instan (<10ms) di antara **20.617 jenis kartu**.
- **Model 2 — Condition Grader:** YOLOv8 untuk deteksi cacat fisik kartu (lecet, tertekuk, aus pinggir) secara otomatis dan objektif.
- **Analytics Engine:** Formula valuasi *Fair Market Price* yang menghitung deviasi harga marketplace dan menghasilkan sinyal transaksi **BUY / HOLD / SELL**.

**Tech:** `PyTorch` `OpenAI CLIP` `YOLOv8` `FAISS` `FastAPI` `React` `Supabase`

---

### 2. SAKU — Smart POS & AI Assistant 🤖

> Sistem Kasir & Akuntansi Cerdas Berbasis LLM Agent untuk UMKM

🔗 [GitHub Repository](https://github.com/tegarkusuma12/saku-smart-pos)

Platform POS dan business analytics dilengkapi **AI Chatbot berbahasa Indonesia** menggunakan LangChain Agent dengan 9 custom tools. Pelaku UMKM bisa mencatat keuangan menggunakan bahasa sehari-hari.

```
Kamu: bayar listrik 150rb
SAKU: ✅ Pengeluaran dicatat! 💸 Rp150.000 🏷️ listrik

Kamu: besok butuh stok apa?
SAKU: 📦 Rekomendasi Restock:
      🔴 Chitato — stok 5, restock 17 unit
```

- **End-to-End Data Pipeline:** Synthetic data generation (120 hari), ETL (SQLite → CSV), EDA, dan Sales Forecasting.
- **Prescriptive Analytics:** Rekomendasi restock otomatis berdasarkan forecast demand + current stock (urgency: KRITIS / SEGERA / PERLU / AMAN).
- **Sales Forecasting:** Model XGBoost / Random Forest dengan TimeSeriesSplit evaluation.

**Tech:** `LangChain` `Groq LLM` `XGBoost` `FastAPI` `SQLAlchemy` `Docker`

---

### 3. Prediksi ISPU Jawa Timur 🌍

> Dashboard Prediksi Kualitas Udara Real-time dengan ML Pipeline

🔗 [GitHub Repository](https://github.com/tegarkusuma12/Web-ISPU)

Sistem peringatan dini (*early warning system*) kualitas udara di **38 Kab/Kota Jawa Timur** yang memadukan data real-time, model prediksi ML, dan visualisasi choropleth map interaktif.

- **Automated Rolling Horizon Pipeline:** APScheduler (cron per jam) menarik data dari OpenWeather API → Supabase PostgreSQL → menjalankan inferensi ML otomatis.
- **XGBoost Multi-Output:** Memprediksi konsentrasi 6 polutan (PM2.5, PM10, SO2, CO, NO2, O3) hingga **24 jam ke depan**.
- **Kalkulator ISPU Kemenlhk:** Implementasi standar P.14/2020 dengan aturan minimal 18 jam data valid.
- **Interactive Dashboard:** Leaflet.js choropleth map + Chart.js + fitur Time-Slider untuk melihat proyeksi +0 hingga +24 jam.

**Tech:** `XGBoost` `Flask` `Supabase` `APScheduler` `Leaflet.js` `Chart.js`

---

## Pendidikan

### D4 Sains Data Terapan — PENS
**Politeknik Elektronika Negeri Surabaya** · Juli 2024 — Saat ini  
IPK: **3.64**

### Sertifikasi
**Mastering AI Bootcamp** — Skill Academy by Ruangguru

---

## Kontak

Tertarik untuk berkolaborasi atau menawarkan kesempatan? Hubungi saya!

- 📧 Email: [kusumategar1255@gmail.com](mailto:kusumategar1255@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/tegar-kusuma-connect](https://linkedin.com/in/tegar-kusuma-connect)
- 🐙 GitHub: [github.com/tegarkusuma12](https://github.com/tegarkusuma12)
- 📱 Telepon: +62 851-7215-7204
