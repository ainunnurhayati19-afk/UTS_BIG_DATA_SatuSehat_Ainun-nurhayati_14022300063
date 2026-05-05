# UTS_BIG_DATA_SatuSehat_Ainun-nurhayati_14022300063
# Analisis Ulasan Aplikasi Pemerintah di Google Play Store Menggunakan AI IndoBERT/IndoRoBERTa

## Deskripsi Proyek
Proyek ini dibuat untuk mengambil data ulasan aplikasi pemerintah Indonesia dari Google Play Store menggunakan library `google-play-scraper`, kemudian melakukan analisis sentimen menggunakan model AI Bahasa Indonesia yaitu **IndoRoBERTa** dari HuggingFace Transformers.

Analisis ini bertujuan untuk mengetahui sentimen pengguna terhadap aplikasi pemerintah berdasarkan ulasan yang diberikan di Google Play Store.

---

## Tools dan Library
- Python
- Google Colab
- google-play-scraper
- pandas
- transformers
- torch

---

## Langkah Pengerjaan

### 1. Membuka Google Colab
Buka:
https://colab.research.google.com/

---

### 2. Install Library
Jalankan perintah berikut di Google Colab:

```python
pip install google-play-scraper transformers torch pandas
