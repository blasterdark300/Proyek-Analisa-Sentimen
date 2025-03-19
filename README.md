# Proyek Analisis Sentimen

Proyek ini bertujuan untuk menganalisis sentimen dari data yang dikumpulkan melalui web scraping dari berbagai sumber seperti PlayStore, X (Twitter), Instagram, dan e-commerce.

## 🚀 Fitur Utama
- **Web Scraping**: Menggunakan Selenium dan BeautifulSoup untuk mengumpulkan data ulasan dan informasi terkait.
- **Ekstraksi Fitur & Pelabelan**: Menyaring data, melakukan preprocessing, dan memberi label sentimen.
- **Deep Learning**: Menerapkan model deep learning untuk klasifikasi sentimen.
- **Evaluasi Model**: Menganalisis akurasi model dengan target minimal **85%**.

## 📂 Struktur Direktori
```
Proyek-Analisa-Sentimen/
│-- data/                # Dataset hasil scraping
│-- models/              # Model deep learning yang telah dilatih
│-- notebooks/           # Jupyter Notebook untuk eksplorasi dan pelatihan model
│-- src/                 # Kode utama proyek
│   ├── scraping.py      # Script scraping data
│   ├── preprocessing.py # Data preprocessing
│   ├── train.py         # Pelatihan model
│   ├── evaluate.py      # Evaluasi model
│-- README.md            # Dokumentasi proyek
```

## ⚙️ Instalasi
Pastikan memiliki **Python 3.x** dan install dependensi dengan:
```bash
pip install -r requirements.txt
```

## 🔍 Cara Penggunaan
1. **Scrape Data**
   ```bash
   python src/scraping.py
   ```
2. **Preprocess Data**
   ```bash
   python src/preprocessing.py
   ```
3. **Latih Model**
   ```bash
   python src/train.py
   ```
4. **Evaluasi Model**
   ```bash
   python src/evaluate.py
   ```

## 🎯 Target Akhir
- Minimal **10.000 sampel data**
- Akurasi training set & testing set **≥92%**
- 3 skema pelatihan model untuk perbandingan performa

## 📜 Lisensi
Proyek ini dilisensikan di bawah MIT License.

---
Dibuat oleh **Krismono Sadi**
