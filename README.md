# Klasifikasi SMS dengan Menggunakan Algoritma Support Vector Machine (SVM)
## Deskripsi Project
Proyek ini bertujuan untuk membangun model klasifikasi SMS menggunakan algoritma Support Vector Machine (SVM).
Selain itu, proyek ini mengevaluasi kinerja SVM dalam menangani data teks (SMS), mencakup proses cleaning, preprocessing dan modelling.

## Dataset 
Dataset
Nama Dataset: SMS Spam (Rahmi F. & Wibisono Y., 2016)
1142 Data, dan 2 Kolom (Teks dan Label) Setelah cleaning.
Deskripsi Label:
0: Normal SMS
1: Penipuan
2: Promosi


![image](https://github.com/user-attachments/assets/0ca7f5fb-0d7c-4462-9abe-603796d73fe4)

## Tahapan Project
1. Text Cleaning
   * Cek Missing Value
   * Cek Duplikat dan hapus data duplikat
   * Membersihkan karakter, tanda baca, emoticon  yang tidak bermakna.
2. Text Preprocessing
   * Tokenizing : Berfungsi untuk memecah teks menjadi unit-unit kecil seperti kata (word tokenization) atau kalimat (sentence tokenization).
   * Normalisasi :  Bertujuan untuk mengubah kata tidak baku, singkatan (seperti dpt menjadi dapat) ke bentuk standar.
   * Stopwords :  Berfungsi menghapus kata-kata umum yang tidak signifikan (tidak penting)
   * Stemming : Mengembalikan kata ke bentuk dasar untuk menyamakan kata dengan makna serupa.
3. Modelling
   Menggunakan Support Vector Machine (SVM) sebagai algoritma utama.
## Hasil
1. Model SVM dengan kernel linear berhasil mencapai akurasi sebesar 90%
2. Kinerja Klasifikasi Berdasarkan Kelas:
   * Kelas 0 (SMS Normal) : Presisi 91%, recall 92%, dan F1-score 91%
   * Kelas 1 (SMS Fraud): Presisi sebesar 93% dan recall 87% dan  F1-score 90%.
   *  Kelas 2 (SMS Promo): Presisi 81%, recall 90%, dan F1-score 85%,
3. Confusion Matrix:
   Sebagian besar data diklasifikasikan dengan benar, tetapi terdapat beberapa kesalahan klasifikasi.
4. Nilai AUC sebesar 97% menunjukkan bahwa model memiliki kemampuan yang sangat baik untuk membedakan antara kelas-kelas yang ada dalam data
   
## Pengembangan Selanjutnya
1. Menerapkan teknik penyeimbangan data (seperti SMOTE) untuk mengatasi ketidakseimbangan dataset.
2. Menggunakan algoritma lain seperti Random Forest atau XGBoost.

# Kontribusi
Meliana Endang Nyimas Lisna
