Kelompok mahasiswa presentasi hasil penerapan model CF dan CBF untuk sistem rekomendasi Pariwisata Toba.

Hasil Review dan Cek list untuk laporan akhir proyek:

Baseline (algoritma pembanding sudah di tune untuk menghasilkan performa yang paling optimal)
Untuk semua model: jelaskan parameter yang digunakan dan value dari setiap parameter. Misal: KNN, berapa K yang diujikan (3, 5, 9 etc), untuk model lain learning rate, iteration, berapa kali eksperimen dijalankan untuk mendapatkan performansi rata-rata.
Metrik evaluasi merepresentasikan performansi model untuk semua data yang ada di test-set (bukan 1 atau sebagian user saja).
Data telah dibagi sesuai petunjuk proyek train:validation:test 70%:15%:15%
Untuk content-based filtering, jelaskan pembentukan user profile dan item profile.
Untuk experimen: jelaskan desain evaluasi, apakah hold-out sampling saja (test, train, val) atau cross validation (k-fold cross validation).
Model yang diusulkan dipilih dengan justifikasi (kenapa, bagaimana) akan lebih baik dari model baseline. Jelaskan apa saja yang di tune, atau diubah dari model aslinya (data diperkaya, k-fold cross validation, penambahan bias dll).
Metrik evaluasi: RMSE, MAE, Precision, Recall, MAP.
Jumlah rekomendasi yang dikembalikan: 5, 10 (Top 5, Top 10).Berarti metrik menjadi Precision@10, Recall@10, MAP@10, Precision@5, Recall@5, MAP@5. Sementara RMSE, MAE tetap untuk semua.
Hasil:
Grafik untuk Rating metriks (RMSE, MAE) dibedakan grafiknya dengan Ranking Metriks (Precision, Recall, MAP). Tidak pada satu grafik/tidak pada satu tabel (jika menggunakan tabel).
Analisis:
Menampilkan top 5 tempat wisata yang dikembalikan baseline 1, baseline 2, dan proposed model untuk user target (ID dari user akan disampaikan kemudian).
Perbandingan rekomendasi tempat wisata yang dikembalikan oleh setiap model kepada user tertentu. Mengapa ketiga model memberikan hasil yang berbeda? Menurut Anda
Kesimpulan dan Saran
Laporan ditampilkan dalam bentuk slide presentasi.
Bonus:
Dapat membuktikan bahwa model tidak overfitting (tunjukkan grafik RMSE untuk validation dan training set).
Grafik untuk menampilkan hasil menggunakan pattern (tidak hanya warna) untuk memfasilitasi pembaca yang buta warna, pola akan lebih mudah dibandingkan.
