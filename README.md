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

## Interpretasi dan Kesimpulan
Dari hasil percobaan yang dilakukan dalam penelitian ini, kami menentukan delapan topik dalam pemodelan topik berbasis LDA. Terlihat bahwa reaksi masyarakat di media sosial Twitter terhadap kemenangan Prabowo-Gibran pada pilpres 2024 cukup menarik. Dari pemodelan topik menggunakan data Twitter ini, kita dapat mengungkap hal-hal yang mungkin saja belum disebarluaskan oleh media televisi.

Dari sini, kita dapat interpretasikan bahwa topik pertama mencakup kata-kata seperti "harapan", "cerah", "bersorak", "adil", "maju", "disambut", "sukses", "impian", dan "tekad". Ini mengindikasikan sebuah topik yang berfokus pada aspirasi positif, harapan, dan optimisme terhadap kemajuan di masa depan, serta semangat untuk mencapai tujuan yang dianggap berarti dan adil.

Topik kedua memuat kata-kata seperti "selamat", "anies", "berhasil", "nasdem", "paloh", "menginspirasi", "surya", "dukungan", dan "tasyakuran". Ini mengindikasikan topik tentang inspirasi dan dukungan yang berkaitan dengan Partai Nasdem, Anies Baswedan, dan Surya Paloh.

Topik ketiga memuat kata-kata seperti "maju", "semangat", "keyakinan", "jokowi", "diharapkan", "mengubah", "optimisme", "dedikasi", dan "sambut". Hal ini mengindikasikan topik yang berfokus pada semangat untuk maju, keyakinan dalam perubahan positif, serta Jokowi yang diharapkan mampu membawa perubahan yang lebih baik.

Topik keempat memuat kata-kata seperti "kepercayaan", "perjuangan", "syukuran", "membanggakan", "inklusif", "berkelanjutan", "keunggulan", "kasih", dan "menggembirakan". Ini mengindikasikan topik yang membahas nilai-nilai kepercayaan, perjuangan untuk mencapai tujuan, serta penghargaan terhadap pencapaian yang membanggakan dan berkelanjutan.

Topik kelima memuat kata-kata seperti "positif", "gemilang", "dukungan", "semangat", "tonggak", "kegembiraan", "kalah", "ekonomi", dan "tantangan". Ini mengindikasikan topik yang berhubungan dengan evaluasi positif terhadap dukungan dan prestasi, serta tantangan-tantangan yang dihadapi dalam konteks tertentu.

Topik keenam memuat kata-kata seperti "kemajuan", "kecurangan", "ganjar", "amanah", "menyambut", "mendukung", "antusiasme", "kebahagiaan", dan "legowo". Ini mengindikasikan topik yang berfokus pada kelegowoan Ganjar Pranowo terhadap hasil keputusan pilpres 2024 walaupun terdapat indikasi kecurangan, serta dukungan dan antusiasme terhadap hasil keputusan yang ada.

Topik ketujuh memuat kata-kata seperti "semangat", "03", "unggul", "01", "gugatan", "menggugah", "terima", "sengketa", "kalah", dan "ganjarmahfud". Ini mengindikasikan topik yang berkaitan dengan sengketa dan semangat untuk menggugat hasil keputusan Pilpres 2024.

Terakhir, topik kedelapan memuat kata-kata seperti "curang", "segar", "maju", "bangga", "berkembang", "keadilan", "senang", "mempercayai", "jokowi", dan "mandat". Ini mengindikasikan topik yang berhubungan dengan evaluasi terhadap keadilan, kebanggaan terhadap kemajuan atau prestasi, serta keyakinan terhadap pemimpin atau keputusan yang diberikan. Walaupun tidak dapat dipungkiri masih terdapat kecurangan.

Berdasarkan analisis dan pemodelan topik berbasis Latent Dirichlet Allocation (LDA) yang dilakukan, didapatkan 8 topik optimal dengan nilai koherensi sebesar 0.6480404285755261. Dari 8 topik tersebut, dapat disimpulkan bahwa reaksi masyarakat Indonesia yang tertuang di media sosial Twitter terhadap kemenangan Prabowo-Gibran pada Pilpres 2024, mayoritas memberikan reaksi positif, dukungan, dan harapan untuk kemajuan Indonesia di masa mendatang. Meskipun demikian, tidak dapat dipungkiri masih terdapat beberapa indikasi kecurangan yang memicu sengketa dan gugatan dari lawan politik pasangan calon tersebut.

## Referensi
[1] C. Indonesia, “Prabowo-Gibran Menang Pilpres 2024, Raih 96,2 Juta Suara,” CNN Indonesia. Accessed: Jun. 30, 2024. [Online]. Available: https://www.cnnindonesia.com/nasional/20240320184608-617-1076845/prabowo-gibran-menang-pilpres-2024-raih-962-juta-suara

[2] R. K. Gupta, R. Agarwalla, B. H. Naik, J. R. Evuri, A. Thapa, and T. D. Singh, “Prediction of Research Trends using LDA based Topic Modeling,” Glob. Transitions Proc., vol. 3, no. 1, pp. 298–304, 2022, doi: https://doi.org/10.1016/j.gltp.2022.03.015.

[3] S. A. Putri, P. D. Kusuma, and C. Setianingsih, “Clustering Topik pada Data Sentimen BPJS Kesehatan menggunakan Metode Latent Dirichlet Allocation,” e-Proceeding Eng., vol. 8, no. 5, pp. 6097–6105, 2021,

[4] H. Satria, “Cara Mendapatkan Data (Crawl) Twitter X - Maret 2024,” Helmi Satria Blog. Accessed: Jun. 20, 2024. [Online]. Available: https://helmisatria.com/blog/updated-crawl-data-twitter-x-maret-2024.
