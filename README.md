Dataset dapat diunduh di Google Drive:
https://drive.google.com/drive/folders/1d6uwnOSpVl2K2Q-csjQ6MBFf7HgKBjK9?usp=sharing

# Segmentasi Pelanggan dengan Analisis RFM dan K-Means Clustering
Proyek ini menerapkan analisis RFM (Recency, Frequency, Monetary) dan algoritma K-Means Clustering untuk segmentasi pelanggan berdasarkan perilaku belanja. Hasil analisis membantu mengidentifikasi kelompok pelanggan seperti loyal, potensial, dan berisiko, sehingga strategi pemasaran dapat lebih tepat sasaran.

1. Tujuan
Penelitian ini bertujuan untuk melakukan segmentasi pelanggan berdasarkan perilaku belanja dengan pendekatan RFM (Recency, Frequency, Monetary).
Tujuan spesifiknya adalah:
- Mengelompokkan pelanggan menjadi beberapa segmen berdasarkan kedekatan   transaksi terakhir (recency), frekuensi pembelian (frequency), dan total nilai transaksi (monetary).
- Menyediakan dasar pengambilan keputusan bagi perusahaan untuk strategi pemasaran yang tepat sasaran.
- Meningkatkan retensi pelanggan, loyalitas, dan nilai penjualan.

2. Algoritma yang Digunakan
Algoritma yang digunakan adalah K-Means Clustering, salah satu metode unsupervised learning untuk mengelompokkan data berdasarkan kemiripan karakteristik.

3. Alasan Pemilihan Algoritma
a). Sesuai untuk Data Tanpa Label
Dataset pelanggan tidak memiliki kategori/kelas yang jelas. K-Means dapat menemukan pola dan membentuk kelompok secara otomatis tanpa memerlukan label sebelumnya.
b). Efisien dan Cepat
Cocok untuk dataset besar seperti Online Retail II, karena memiliki kompleksitas komputasi yang relatif rendah.
c). Hasil Mudah Diinterpretasi
Output K-Means berupa centroid (titik pusat cluster) yang mudah dipahami dan divisualisasikan.
d). Sangat Cocok untuk Data RFM
Data RFM setelah dinormalisasi berbentuk numerik dan berbasis jarak, sehingga algoritma K-Means yang menggunakan perhitungan Euclidean Distance dapat bekerja optimal.

4. Penjelasan RFM
Recency (R): Jarak waktu sejak pembelian terakhir pelanggan. Semakin kecil nilainya, semakin baru interaksi pelanggan.
Frequency (F): Jumlah pembelian yang dilakukan pelanggan. Semakin tinggi nilainya, semakin sering pelanggan bertransaksi.
Monetary (M): Total uang yang dibelanjakan pelanggan. Semakin besar nilainya, semakin bernilai pelanggan bagi perusahaan.

5. Interpretasi Hasil
Contoh hasil segmentasi dengan 4 cluster:
- Cluster 0: Pelanggan baru dengan frekuensi pembelian rendah dan nilai transaksi kecil.
- Cluster 1: Pelanggan lama yang jarang bertransaksi namun pernah berbelanja dengan nilai besar.
- Cluster 2: Pelanggan aktif dan loyal dengan frekuensi pembelian tinggi dan nilai transaksi besar.
- Cluster 3: Pelanggan menengah dengan frekuensi dan nilai pembelian moderat.

Hasil ini dapat digunakan untuk:
- Memberikan promo khusus kepada pelanggan loyal (Cluster 2).
- Mengaktifkan kembali pelanggan lama (Cluster 1).
- Mendorong pembelian pelanggan baru (Cluster 0).
