# Klasifikasi_Dengue

Judul Riset: OPTIMASI BAYESIAN PADA CATBOOST BERBASIS EXPLAINABLE ARTIFICIAL INTELLIGENCE UNTUK KLASIFIKASI PENYAKIT DENGUE
Nama: Natasya Meryl Damayanti
Program Studi: Informatika, UPN "Veteran" Jawa Timur

1. Formulasi Masalah
Diagnosis awal penyakit dengue sulit dibedakan dari infeksi akut lain karena kemiripan gejala (demam, nyeri kepala, mual), sehingga penilaian kategori diagnosis dengue, demam dengue (DF) vs demam berdarah dengue (DHF) umumnya masih bergantung pada pemeriksaan klinis dan laboratorium manual oleh tenaga medis. Pada rumah sakit rujukan dengan volume pasien tinggi seperti RS Surabaya, dibutuhkan metode komputasi yang mampu membantu klasifikasi secara cepat, konsisten, dan dapat dipertanggungjawabkan secara klinis.
Rumusan masalah:
Bagaimana penerapan algoritma CatBoost yang dioptimasi menggunakan Bayesian Optimization untuk melakukan klasifikasi penyakit dengue berdasarkan data klinis pasien?
Bagaimana performa model CatBoost sebelum dan sesudah dilakukan optimasi hyperparameter menggunakan Bayesian Optimization dalam klasifikasi penyakit dengue?
Bagaimana implementasi model CatBoost hasil optimasi Bayesian Optimization dan interpretasi SHAP ke dalam aplikasi berbasis web?

3. Research Gap dari Penelitian Terdahulu
Kesimpulan gap: belum ada penelitian yang menggabungkan CatBoost + perbandingan strategi Bayesian Optimization (Default/TPE/GP) + SHAP, pada data rekam medis rumah sakit rujukan Indonesia dengan penanganan missing value dan ketidakseimbangan kelas yang sesuai karakteristik data nyata (bukan data publik yang sudah bersih).

4. Peluang Pengembangan
Perbandingan strategi tuning (Default vs TPE vs GP) pada data klinis dengan fitur kategorikal campuran belum banyak dikaji spesifik untuk CatBoost pada domain dengue.
Penanganan native CatBoost untuk missing value dan nilai ekstrem klinis, sebagai alternatif dari oversampling sintetis (SMOTE) yang berisiko menghasilkan kombinasi nilai lab tidak realistis pada dataset kecil.
Interpretasi berbasis SHAP untuk menjembatani model black box dengan kebutuhan tenaga medis akan transparansi keputusan klinis.
Pengembangan lanjutan: dashboard interaktif (Streamlit) untuk tenaga medis, dan ekstraksi label keparahan granular (DHF I-IV/DSS) dari catatan klinis bebas teks sebagai riset multi-kelas lanjutan.

5. Rencana Topik yang Dipilih
OPTIMASI BAYESIAN PADA CATBOOST BERBASIS EXPLAINABLE ARTIFICIAL INTELLIGENCE UNTUK KLASIFIKASI PENYAKIT DENGUE, studi kasus data rekam medis pasien di Rumah Sakit Surabaya
