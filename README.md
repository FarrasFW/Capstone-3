Travel Insurance prediction

Gambaran Proyek
Proyek ini bertujuan untuk memprediksi apakah seorang pemegang polis dari perusahaan asuransi perjalanan akan mengajukan klaim. Dengan memanfaatkan data historis dari pemegang polis, proyek ini membangun model prediktif untuk membantu perusahaan asuransi dalam mengelola risiko, mengoptimalkan strategi penetapan harga, dan meningkatkan alokasi sumber daya. Model ini membantu untuk mengantisipasi klaim, memberikan wawasan tentang pemegang polis yang lebih mungkin untuk mengajukan klaim asuransi.

Pernyataan Masalah
Perusahaan asuransi bertujuan untuk memaksimalkan profitabilitas dengan meminimalkan klaim yang tidak perlu sambil memastikan bahwa mereka dapat memprediksi dengan akurat pemegang polis mana yang lebih mungkin untuk mengajukan klaim. Tantangannya adalah memprediksi apakah seorang pemegang polis akan mengajukan klaim, dengan mempertimbangkan berbagai faktor seperti destinasi perjalanan, produk asuransi, dan riwayat pemegang polis.

Proyek ini berfokus pada pengembangan model machine learning yang memprediksi kemungkinan klaim yang akan diajukan oleh seorang pemegang polis, berdasarkan data historis. Perusahaan bertujuan untuk mengurangi false positives (salah memprediksi klaim akan diajukan) dan false negatives (gagal memprediksi klaim akan diajukan) karena kedua skenario ini membawa konsekuensi finansial yang signifikan.

Tujuan Proyek
Mengembangkan model machine learning untuk memprediksi apakah seorang pemegang polis akan mengajukan klaim asuransi.

Memastikan model meminimalkan false positives dan false negatives.

Membantu mengoptimalkan strategi penetapan harga dengan memberikan prediksi yang akurat.

Meningkatkan efisiensi pemrosesan klaim dan alokasi sumber daya.

Pemangku Kepentingan Utama
Tim Manajemen: Tertarik untuk meningkatkan profitabilitas perusahaan secara keseluruhan dan efisiensi operasional.

Departemen Manajemen Risiko: Bertujuan untuk menilai dan mengurangi risiko finansial terkait klaim.

Tim Underwriting: Menggunakan model untuk menilai tingkat risiko pemegang polis dan menetapkan premi dengan tepat.

Tim Klaim: Dapat menggunakan prediksi untuk memprioritaskan pemegang polis berisiko tinggi dan mencegah klaim palsu.

Pemegang Polis: Akan mendapatkan manfaat dari harga yang lebih optimal dan pemrosesan klaim yang lebih cepat.

Investor dan Pemegang Saham: Tertarik untuk meningkatkan stabilitas keuangan perusahaan dan mengurangi pengeluaran klaim yang tidak terduga.

Data
Proyek ini menggunakan data historis pemegang polis yang mencakup:

Destinasi: Destinasi perjalanan pemegang polis (dalam negeri atau internasional).

Produk Asuransi: Jenis asuransi perjalanan yang dibeli oleh pemegang polis.

Riwayat Klaim: Apakah pemegang polis mengajukan klaim atau tidak.

Variabel target untuk model ini adalah:

Klaim: Variabel biner dimana:

0 menandakan pemegang polis tidak mengajukan klaim.

1 menandakan pemegang polis mengajukan klaim.

Metodologi
Pra-pemrosesan Data
Menangani Data yang Hilang: Nilai yang hilang dalam dataset ditangani dengan imputasi atau penghapusan berdasarkan tingkat keparahan.

Rekayasa Fitur: Fitur relevan diekstraksi atau ditransformasi untuk meningkatkan kinerja model, seperti encoding variabel kategori atau penskalaan fitur numerik.

Pembagian Data: Dataset dibagi menjadi set pelatihan dan pengujian untuk mengevaluasi kinerja model.

Pengembangan Model
Model Machine Learning: Berbagai model (seperti Logistic Regression, Random Forest, XGBoost) dilatih dan diuji untuk akurasi prediksi.

Evaluasi Model: Model dievaluasi menggunakan F1-Score: Keseimbangan antara presisi dan recall.

Penyempurnaan Hyperparameter
Hyperparameter dioptimalkan menggunakan RandomizedSearchCV untuk menemukan konfigurasi terbaik yang memberikan kinerja terbaik pada model yang dipilih.

Pemrosesan Data: Menangani nilai yang hilang, encoding variabel kategori, dan membagi data menjadi set pelatihan dan pengujian.

Melatih Model: Memilih model (misalnya, RandomForestClassifier atau XGBoost) dan melatihnya dengan data pelatihan.

Evaluasi Model: Memeriksa kinerja model menggunakan metrik klasifikasi seperti akurasi, presisi, recall, dan F1-score.

Penerapan Model
Penerapan Model: Setelah model sepenuhnya dilatih dan disesuaikan, model dapat diterapkan di lingkungan produksi untuk memprediksi klaim secara real-time.

Ekspansi Fitur: Lebih banyak fitur, seperti informasi demografis pemegang polis, dapat ditambahkan untuk meningkatkan akurasi model.

Integrasi dengan Sistem Perusahaan: Model ini dapat diintegrasikan dengan sistem internal perusahaan asuransi untuk prediksi klaim otomatis.

Kesimpulan
Proyek ini menunjukkan kekuatan machine learning dalam memprediksi apakah seorang pemegang polis kemungkinan akan mengajukan klaim asuransi. Model prediktif ini dapat membantu perusahaan asuransi dalam mengelola risiko, mengoptimalkan harga, dan meningkatkan efisiensi proses klaim. Dengan peningkatan di masa depan, sistem ini dapat diintegrasikan ke dalam alur kerja perusahaan untuk memberikan prediksi secara real-time dan secara signifikan mengurangi biaya operasional.
