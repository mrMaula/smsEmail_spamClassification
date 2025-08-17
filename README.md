# SMS/Email Spam Classification Project

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://python.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.2.2-orange)](https://scikit-learn.org)

Proyek machine learning untuk klasifikasi pesan SMS/email menjadi spam atau ham (bukan spam).

## 📌 Gambaran Umum
Proyek ini mengembangkan model machine learning yang dapat mengidentifikasi pesan spam dengan akurasi tinggi. Sistem ini dapat digunakan untuk aplikasi penyaringan pesan otomatis.

## 📂 Struktur Proyek
smsEmail_spamClassification/
├── data/ # Folder dataset
│ └── dataset.csv # Dataset utama
├── images/ # Screenshot dan gambar hasil
│ └── wordcloud.png # Visualisasi kata-kata spam
├── spam_classification.ipynb # Notebook utama
├── requirements.txt # Dependensi proyek
└── README.md # Dokumentasi ini


## ⚙️ Teknologi yang Digunakan
- **Python 3.9**
- **Scikit-learn** (Untuk model machine learning)
- **Pandas** (Pengolahan data)
- **NLTK** (Natural Language Processing)
- **Matplotlib/Seaborn** (Visualisasi data)

## 📊 Dataset
Dataset berasal dari [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) di Kaggle:
- 5,572 pesan SMS
- 2 kategori: spam/ham
- Fitur utama: teks pesan dan label

## 🚀 Cara Menjalankan Proyek
1. Clone repositori:
```bash
git clone https://github.com/username/sms-email-spam-classification.git
2. Install dependensi:
```bash
pip install -r requirements.txt
3. Jalankan Jupyter Notebook:
```bash
jupyter notebook spam_classification.ipynb
4. Eksekusi Notebook sel demi sel


## 📈 Hasil Utama
Model terbaik yang dihasilkan:
- Model: SVM + TF-IDF
- Akurasi: 97%
- Precision (spam): 89%
- Recall (spam): 92%

## 🤝 Kontribusi
1. Fork proyek ini
2. Buat branch baru (git checkout -b fitur-baru)
3. Commit perubahan (git commit -m 'Tambahkan fitur')
4. Push ke branch (git push origin fitur-baru)
5. Buat Pull Request


© 2025 [M.Ridho Maula] | Portofolio Data Science

