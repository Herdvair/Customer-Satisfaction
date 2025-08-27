# Overview : Tiket Review System

link ppt : [Laporan Lengkap Ticket Review System](https://docs.google.com/presentation/d/1ACNR_HD7tJjat5QGnfBWlEjOCMU_lmnaeOh5F38sN3o/edit?usp=sharing)

# Latar Belakang
Proyek ini bertujuan untuk menganalisis kepuasan pelanggan dan sentimen pengguna terhadap layanan ticketing system. Analisis ini dilakukan dengan menggunakan data survei yang berisi rating, skor, serta ulasan teks dari pengguna. Sebagai seorang data analyst di perusahaan konsultan, peran utama adalah menyatukan laporan terkait Customer Satisfaction dan Sentiment Analysis ke dalam sebuah dashboard, sekaligus menyajikan insight yang relevan untuk pengambilan keputusan.

# Analisis Objektif
Pada proyek ini akan dilakukan analisis untuk mengukur seberapa besar partisipasi responden dalam survei untuk melihat rata-rata tingkat kepuasan pelanggan terhadap layanan, tingkat kemudahan penggunaan sistem, tingkat kesediaan pengguna untuk merekomendasikan sistem ke orang lain hingga melakukan analisis sentimen berdasarkan ulasan teks pengguna.

# Konten
Dilakukan beberapa tahap untuk menganalisis kasus ini :

1. Data Cleaning
    - Pembersihan data survei untuk memastikan hanya entri valid yang digunakan.
    - Penanganan nilai kosong pada skor maupun teks ulasan.

2. Penghitungan Skor Kepuasan
    - Menghitung CSAT, CES, dan NPS berdasarkan skor survei.
    - Mengelompokkan responden ke dalam kategori Promoter, Passive, dan Detractor.

3. Sentiment Analysis
    - Membersihkan teks ulasan (whitespace, URL, username).
    - Mengklasifikasikan ulasan ke dalam kategori sentimen (positif, netral, negatif).

4. Finalization for Dashboard
    - Menyimpan dataset akhir yang sudah mencakup kategori NPS dan sentimen untuk digunakan dalam visualisasi dan pelaporan.

# Temuan Penting

1. CSAT dan CES mengukur kepuasan dan kemudahan penggunaan sistem.
2. NPS menunjukkan distribusi pelanggan ke dalam Promoter, Passive, dan Detractor, sehingga dapat mengukur loyalitas pengguna.
3. Sentiment Analysis dari ulasan teks menambah konteks kualitatif, memperlihatkan aspek mana yang sering dipuji maupun dikeluhkan.
4. Data yang sudah digabungkan (skor + sentimen) siap divisualisasikan dalam dashboard untuk monitoring performa sistem tiket.

# Rekomendasi yang dapat ditindaklanjuti
1. Pada aspek customer satisfaction score, tingkatkan layanan pelanggan melalui pelatihan staf dan perbaikan sistem respons, pertahankan kualitas features dan value for money, sekaligus jadikan sebagai keunggulan dalam strategi pemasaran.
2. Pada aspek customer effort score, pertahankan kemudahan penggunaan dengan terus menyederhanakan alur dan antarmuka pengguna serta jadikan kemudahan ini dalam promosi, karena menjadi nilai jual yang kuat dibanding kompetitor.
3. Pada aspek net promotor score, identifikasi dan perbaiki penyebab ketidakpuasan, terutama dari feedback pelanggan yang memberi skor rendah, serta membangun  loyalitas pelanggan melalui peningkatan layanan atau program referral.
4. Pada aspek sentimen analisis, pertahankan kualitas layanan dan produk yang mendorong sentimen positif dan meninjau dan tangani ulasan negatif dan meningkatkan persepsi publik.



