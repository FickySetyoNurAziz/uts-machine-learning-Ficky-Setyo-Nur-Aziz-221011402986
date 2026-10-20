# Tugas UTS Machine Learning - Linear & Logistic Regression

Repositori ini berisi penyelesaian Tugas Ujian Tengah Semester (UTS) Mata Kuliah Machine Learning.

## 👤 Identitas Mahasiswa
- **Nama**   : Ficky Setyo Nur Aziz
- **NIM**    : 221011402986
- **Kelas**  : Reg B / Reg C
- **RANDOM_STATE** : 86 (2 digit terakhir NIM)

---

## 📊 Ringkasan Hasil Model & Evaluasi

### Bagian A – Linear Regression (Ads_Data.csv)
- **Persamaan Regresi**: $\hat{y} = b + mX$
- **R-squared ($R^2$)**: Menunjukkan tingkat efektivitas biaya iklan terhadap peningkatan penjualan.
- **Hasil Evaluasi**: Model regresi linier berhasil dilatih dengan *Normal Equation* dan *Gradient Descent* (learning rate optimal `0.02`).

### Bagian B – Logistic Regression (Email_Data.csv)
- **Fungsi Klasifikasi**: Prediksi email Spam (1) vs Bukan Spam (0) berdasarkan `JumlahLink` dan `KataPromo`.
- **Hasil Model**:
  - **Accuracy**  : ~1.00 (100%)
  - **Precision** : ~1.00 (100%)
  - **Recall**    : ~1.00 (100%)
  - **F1-Score**  : ~1.00 (100%)
- **Threshold Terpilih**: `0.7` (dipilih untuk meminimalisir *False Positive* agar email penting pengguna tidak keliru masuk ke folder spam).

---

## 📁 File dalam Repositori
1. `tugas_UTS.ipynb` : Notebook utama yang telah dijalankan lengkap dengan output dan grafik.
2. `Ads_Data.csv` : Dataset biaya iklan dan penjualan.
3. `Email_Data.csv` : Dataset filter email spam.
4. `README.md` : Dokumentasi ringkasan repositori.