# Pengantar Web mining 

## Topik web mining terdiri dari 

A. Pengantar web mining

Web Mining adalah proses mengektraksi informasi dari web menggunakan teknik data mining. Proses web mining mencakup tiga tahap Utama yaitu : pengumpulan data (crawling, API, eksplorasi), pra-pemrosesan (transformasi, seleksi fitur, dan pembuatan embedding), dan data mining (pembangunan model, evaluasi, iterasi).   

B. Web Crawling 

Web crawling adalah proses otomatis data dari halaman-halaman web. Program untuk melakukan crawling disebut crawler. Program ini mengikuti tautan antar halaman web untuk menemukan dan mengunduh konten, lalu menyimpan dalam sebuah database yang kemudian digunakan oleh mesin pencari untuk membuat indeks dan memberkan hasil pencarian yang relevan kepada pengguna. 

Tujuan Web Crawling adalah 

1. Membuat indeks mesin pencari 

2. Pengumpulan data 

3. Pemantauan prubahan 

C. Web Data Prepocessing 

Web data processing adalah tahap persiapan data sebelum dilakukan analisis. Data dari web biasanya tidak terstruktur, mengandung noise, dan berukuran besar sehingga memerluka pembersihan. Proses preprocessing meliputi penghapusan tag HTML, normalisasi teks, penghapusan stop word, stemming, dan konversi ke format yang sesuai. Tahap ini sangat penting agar model analisis dapat bekerja secara optimal.

D. Pembelajaran Terawasi (Supervised Learning)

Pembelajaran terawasi adalah salah satu pendekatan utama dalam pembelajaran mesin yang menggunakan data berlabel untuk melatih model. Metode ini digunakan untuk membangun model prediktif yang dilatih menggunakan data berlabe, yang berarti setiap contoh data dilengkapi dengan label atau hasil yang diinginkan. Dalam web mining, pembelajaran terawasi sering digunakan untuk klasifikasi dokumen, analisis sentimen, dan deteksi spam. Algoritma umum yang digunakan adalah decision tree, naive bayes, san support vector machine.

E. Pembelajaran Tak Terawasi (Unsupervised Learning)

Pembelajaran tak terawasi adalah metode pembelajaran mesin yang tidak memerlukan data label. Dalam web mining, metode ini sering digunakan untuk clustering dokumen, segmentasi pengguna, dan analisis topik. Algoritma yang umum digunakan adalah k-means, hierarchical clustering, dan metode berbasis asosisai. 

F. Web Content Mining (Text Mining) Web Content Mining (Text Mining) berfokus pada konten halaman seperti teks, gambar, video, audio, data terstruktur. 

Aplikasi yang digunakan adalah : 
 
- Ekstraksi informasi adalah proses otomatis untuk mengambil data terstruktur dari konten web yang tidak terstruktur atau semi-struktur. Contohnya adalah mengekstraks nama orang, lokasi, atau tanggal.
 
- Topic modelling adalah metode untuk menemukan topik tersembunyi dalam kumpulan dokumen secara otomatis. 

- Klasifikasi dokumen adalah pengelompokan dokumen ke dalam kategori yang sudah ditentukan. 

- Peringkasan dokumen bertujuan untuk menghasilkan ringkasan teks yang singkat tetapi tetap mempertahankan informasi penting dari dokumen asli. 

- Pengelompokan dokumen adalah pengelompokan dokumen berdasarkan kesamaan antar dokumen. Teknik yang digunakan adalah Algritma K-Means, Pengelompokan Hierarkis, S-BERT. 

- Ektraksi kata kunci bertujuan untuk menentukan kata atau prasa penting dalam teks yang ada dalam dokumen. 

G. Web Usage Mining 
Web Usage Mining adalah mengekstrak informasi dari data interaksi pengguna, melalui kunjungan halaman web dan transaksi. Analisis ini digunakan untuk karakteristik pengguna dan profil penggunaan, data clickstream (catatan untuk klik pengguna saat menjelajahi situs web), analisis clickstream (proses menganalisis pola perilaku pengguna). 

Aplikasi yang digunakan adalah : 

- Product recommendation yaitu semua fitur yang memprediksi dan menyarankan produk yang paling mungkin diminati oleh seorang pengguna. 

- Prsonalized search (pencarian yang dipersonalisasi) yaitu pendekatan dalam pencarian informasi di mana hasil pencarian disesuaikan dengan perilaku, dan konteks pengguna individu. 

H. Web Structure Mining (Graph Mining) 
Web Structure Mining (Graph Mining) berfokus pada pola hyperlink dan hubungan antar halaman atau actor di web, termasuk jaringan sosial. 

Aplikasi yang digunakan dalam Grafik web adalah representasi visual dari halaman web sebagai simpul (node) dan hyperlink sebagai sisi (edge). 

Metode yang umum digunakan adalah centrality dan K-Cores untuk menentukan simpul penting dan komunitas dalam jaringan.

I. Deployment Sistem 

Deployment system adalah proses pemindahan system atau aplikasi dari lingkungan pengembangan ke lingkungan produksi yang sebenarnya agar dapat digunakan oleh pengguna akhir. Tahap ini terjadi setelah pengembangan dan pengujian selesai, bertujuan agar system berjalan secara stabil, aman, dan sesuai dengan kebutuhan. 

Tujuan utama deploy sistem adalah : 
1. Membuat sistem tersedia 

2.  Memberikan solusi 

3. Memastikan ketersediaan
