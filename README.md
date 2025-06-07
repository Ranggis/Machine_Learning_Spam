# 📨 Detektor Pesan Spam dengan Streamlit

Aplikasi web interaktif untuk mendeteksi apakah sebuah pesan merupakan **spam** atau **bukan (ham)** menggunakan model machine learning yang sudah dilatih sebelumnya. Dibuat dengan 🔥 menggunakan **Streamlit**, **scikit-learn**, dan **pandas**.

---

## 🚀 Fitur Unggulan

* 🔍 **Deteksi Pesan Individu**

  * Ketik pesan langsung dan deteksi secara instan.
  * Tampilkan skor probabilitas untuk spam dan ham.
  * Riwayat deteksi otomatis tersimpan dan bisa diunduh.
  * Visualisasi hasil deteksi dalam bentuk grafik batang.

* 📂 **Deteksi Massal (CSV)**

  * Unggah file `.csv` berisi daftar pesan (header kolom: `pesan`).
  * Lakukan deteksi secara massal dan simpan hasilnya.

* ⚙️ **Pengaturan Lanjutan**

  * Atur ambang batas (threshold) klasifikasi spam sesuai kebutuhan.

---

## 🛠️ Instalasi

1. **Klon repositori ini**

```bash
git clone https://github.com/username-kamu/spam-detector-streamlit.git
cd spam-detector-streamlit
```

2. **Instal dependensi**

```bash
pip install -r requirements.txt
```

3. **Pastikan file model tersedia**

* Letakkan `model.pkl` dan `vectorizer.pkl` di direktori utama.

4. **Jalankan aplikasi**

```bash
streamlit run spam.py
```

---

## 📁 Struktur Folder

```
spam-detector-streamlit/
├── model.pkl
├── vectorizer.pkl
├── spam.py
├── requirements.txt
└── README.md
```

---

## 🤖 Informasi Model

* Model dikembangkan menggunakan algoritma dari `scikit-learn`.
* Cocok menggunakan Logistic Regression, Naive Bayes, atau Random Forest.
* Jangan lupa menyimpan `vectorizer` juga (contoh: TfidfVectorizer).

---

## 🌟 Fitur Mendatang

* Ekspor hasil ke PDF
* Notifikasi email otomatis
* Mode gelap (dark mode)
* Kemampuan retraining model secara langsung di aplikasi

---

## 🙌 Kredit

Dibuat oleh **Ranggis** ✨

> "Jangan biarkan pesan spam mengganggumu. Biarkan model yang menilai."

---

## 📄 Lisensi

Proyek ini menggunakan lisensi **MIT**. Silakan modifikasi dan bagikan sesuai kebutuhan!
