# Player Clustering & Similarity Finder

> Mencari pemain sepak bola dengan playstyle mirip pemain bintang, tapi market value jauh lebih murah.

## 🔗 Tautan Demo


## 📋 Daftar Isi
- [Pemahaman Bisnis](#-pemahaman-bisnis)
- [Pemahaman Data](#-pemahaman-data)
- [Pendekatan](#-pendekatan)
- [Hasil & Visualisasi](#-hasil--visualisasi)
- [Teknologi](#-teknologi)
- [Pengaturan](#-pengaturan)
- [Status](#-status)
- [Kredit](#-kredit)

---

## 💼 Pemahaman Bisnis
**Latar belakang:**
Klub-klub Eropa modern (Brentford, Brighton, dll.) dikenal menggunakan pendekatan data-driven untuk menemukan pemain bertalenta dengan harga di bawah pasar — pendekatan yang populer disebut *"Moneyball" ala sepak bola*.

**Pertanyaan penelitian:**
> "Pemain mana yang profil statistik playstyle-nya paling mirip dengan pemain bintang tertentu, tetapi memiliki market value jauh lebih rendah?"

**Manfaat:**
Klub dengan anggaran transfer terbatas (atau analis/scout individu) bisa mendapat rekomendasi pemain berbasis data, bukan sekadar reputasi atau eksposur media. Menemukan pemain dengan gaya main mirip bintang tapi harga jauh lebih murah membuka peluang efisiensi biaya transfer.

**Jenis analisis:**
Predictive analysis (unsupervised learning/clustering), dikombinasikan dengan descriptive analysis untuk ranking kemiripan & perbandingan harga.

**Hipotesis awal:**
Ada pemain-pemain di liga non-top-5 Eropa yang secara statistik punya kontribusi progresif (progressive carries/passes, SCA, xA) setara pemain bintang, tapi belum ter-highlight karena bermain di liga dengan eksposur media lebih kecil.

---

## 📊 Pemahaman Data
**Sumber data:**
| Sumber | Data yang diambil | Link |
|---|---|---|
| [Nama sumber] | [Data apa] | [URL] |

**Elemen data yang digunakan:**
- [Elemen data 1]
- [Elemen data 2]

**Catatan kualitas data:**
[Missing values, inkonsistensi antar sumber, ukuran sampel, batasan lain yang ditemukan saat investigasi]

---

## 🧭 Pendekatan
1. **Persiapan data:** [Cleaning, filtering, normalisasi/scaling, feature engineering yang dilakukan]
2. **Metode analisis:** [Teknik yang dipakai — misal clustering, regresi, correlational — dan alasan memilihnya]
3. **Validasi:** [Bagaimana hasil dicek/divalidasi, kalau ada]

---

## 🖼️ Hasil & Visualisasi
[Screenshot chart/dashboard, atau ringkasan temuan utama dalam 2-3 poin]

- **Temuan utama:** [...]
- **Insight:** [...]

---

## 🛠️ Teknologi
- Bahasa: Python
- Library: pandas, scikit-learn
- Tools: Jupyter

## ⚙️ Pengaturan
```bash
git clone [url-repo]
pip install -r requirements.txt
python player_clustering.py
```

## 📌 Status
- [x] Ide & pertanyaan ditentukan
- [ ] Data terkumpul
- [ ] Data dibersihkan
- [ ] Analisis selesai
- [ ] Hasil dipresentasikan

**Progress Log:**
- `[2026-09-07]` — Menentukan pertanyaan penelitian & jenis analisis (predictive/clustering). Menyusun starter script (`player_clustering.py`) untuk feature scaling, K-Means, dan cosine similarity.
