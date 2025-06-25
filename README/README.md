Sistem Case-Based Reasoning (CBR) untuk Analisis Putusan Pencurian di PN Surabaya

DESKRIPSI TUGAS
Project ini bertujuan membangun sistem Case-Based Reasoning (CBR) untuk mendukung analisis putusan pengadilan dengan mengambil kasus pidana khusus pencurian di Pengadilan Negeri Surabaya tahun 2024. Sistem dibangun menggunakan Python dan mengikuti 5 tahap utama dalam siklus CBR.

METODELOGI
Berikut adalah diagram siklus CBR yang digunakan:
1. Case Base: Unduh ≥30 putusan dari Direktori Mahkamah Agung dan ekstraksi metadata.
2. Case Representation: Ekstraksi pasal, pihak, amar putusan, dan ringkasan fakta.
3. Case Retrieval: Menggunakan TF-IDF dan Cosine Similarity untuk menemukan kasus termirip.
4. Solution Reuse: Mengambil amar putusan dari top-k kasus sebagai solusi prediksi.
5. Evaluation: Menghitung precision, recall, dan F1-score dari prediksi sistem.

INSTALASI
Jalankan perintah berikut untuk memasang semua dependensi:

BASH
pip install -r requirements.txt
