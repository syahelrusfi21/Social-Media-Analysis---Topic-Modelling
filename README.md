# Pilpres 2024 di Mata Netizen: Mengklasterisasi Reaksi Publik terhadap Kemenangan Paslon 02 dengan Pemodelan Topik berbasis LDA pada Platform Media Sosial Twitter

## Pendahuluan
Pemilihan Presiden (Pilpres) 2024 menandai kemenangan Prabowo Subianto dan Gibran Rakabuming Raka dengan 96.214.691 suara [1]. Di era digital, media sosial seperti Twitter menjadi platform utama bagi masyarakat untuk berbagi pendapat dan preferensi politik. Pilpres 2024 dianggap sebagai momen penting dalam politik Indonesia. Penelitian ini bertujuan menganalisis konten Twitter untuk melihat reaksi pengguna terhadap kemenangan pasangan calon nomor urut 02 pada Pilpres 2024 dengan menggunakan pemodelan topik. Algoritma pemodelan topik, yang merupakan unsupervised learning, menghasilkan koleksi frasa dan kata yang saling berhubungan, yang kemudian diklasifikasikan oleh peneliti [2]. Metode yang digunakan untuk pemodelan topik pada penelitian ini adalah Latent Dirichlet Allocation (LDA), yang unggul dalam mengklasterkan data berukuran besar serta dapat diterapkan untuk mengidentifikasi topik dalam jurnal ilmiah, klasifikasi, dan pengelompokan [3].

## Data
Dataset yang digunakan dalam penelitian ini berasal dari media sosial Twitter.
Data dikumpulkan menggunakan pustaka Tweet-Harvest, sebuah proyek yang dikembangkan oleh Helmi Satria [4].
Pengumpulan data dilakukan berdasarkan kata kunci yang ditentukan oleh peneliti. Kata kunci yang digunakan dalam penelitian ini adalah "kemenangan prabowo-gibran", dengan rentang waktu dari 20 Maret 2024 hingga 20 Mei 2024, serta hanya mengambil teks berbahasa Indonesia.
Terdapat 3253 data yang berhasil dikumpulkan, dan setelah dilakukan pra-pemrosesan, jumlah data menjadi 2632.
Data yang dianalisis hanya data yang berisi tweet saja.

## Metode
Metode pemodelan topik yang digunakan dalam penelitian ini adalah Latent Dirichlet Allocation (LDA) dengan nilai alpha = “auto”.
Metrik evaluasi yang digunakan adalah c_v coherence score.

## Referensi
[1] C. Indonesia, “Prabowo-Gibran Menang Pilpres 2024, Raih 96,2 Juta Suara,” CNN Indonesia. Accessed: Jun. 30, 2024. [Online]. Available: https://www.cnnindonesia.com/nasional/20240320184608-617-1076845/prabowo-gibran-menang-pilpres-2024-raih-962-juta-suara
[2] R. K. Gupta, R. Agarwalla, B. H. Naik, J. R. Evuri, A. Thapa, and T. D. Singh, “Prediction of Research Trends using LDA based Topic Modeling,” Glob. Transitions Proc., vol. 3, no. 1, pp. 298–304, 2022, doi: https://doi.org/10.1016/j.gltp.2022.03.015.
[3] S. A. Putri, P. D. Kusuma, and C. Setianingsih, “Clustering Topik pada Data Sentimen BPJS Kesehatan menggunakan Metode Latent Dirichlet Allocation,” e-Proceeding Eng., vol. 8, no. 5, pp. 6097–6105, 2021,
[4] H. Satria, “Cara Mendapatkan Data (Crawl) Twitter X - Maret 2024,” Helmi Satria Blog. Accessed: Jun. 20, 2024. [Online]. Available: https://helmisatria.com/blog/updated-crawl-data-twitter-x-maret-2024
