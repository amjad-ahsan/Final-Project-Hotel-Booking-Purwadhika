Prediksi Pembatalan Pemesanan Hotel & Dasbor Analitik

Proyek ini berisi analisis data pemesanan hotel dari dua jenis hotel (Resort dan City Hotel). Tujuan utamanya adalah membangun model machine learning yang dapat memprediksi kemungkinan seorang tamu akan membatalkan pemesanannya. Selain model prediktif, proyek ini juga dilengkapi dengan dasbor interaktif di Tableau untuk eksplorasi dan visualisasi data.

Latar Belakang Masalah

Industri perhotelan sering menghadapi tantangan akibat tingginya tingkat pembatalan pemesanan. Pembatalan yang tidak terduga menyebabkan kerugian pendapatan karena kamar yang seharusnya terisi menjadi kosong dan sulit untuk dijual kembali dalam waktu singkat. Proyek ini bertujuan untuk mengatasi masalah tersebut dengan menyediakan alat bantu berbasis data untuk pengambilan keputusan yang lebih baik.

Dasbor Visualisasi Data

Sebuah dasbor interaktif telah dibuat menggunakan Tableau untuk memberikan wawasan mendalam dari data secara visual. Dasbor ini mencakup analisis tren pemesanan, profil tamu, perbandingan kinerja antara hotel kota dan resort, serta faktor-faktor yang berkorelasi dengan pembatalan.

Lihat Dasbor Langsung di Tableau Public

https://public.tableau.com/app/profile/eldi.andreanov/viz/Finalprojectvisualisazion/DashboardHome?publish=yes

 Model Prediksi Machine Learning

    - Model machine learning dibangun untuk mengklasifikasikan apakah sebuah pemesanan akan dibatalkan (is_canceled = 1) atau tidak (is_canceled = 0).

    - Tujuan: Mengidentifikasi pemesanan berisiko tinggi sebelum tanggal kedatangan.

    - Model yang Digunakan: Model klasifikasi seperti Random Forest atau Gradient Boosting digunakan karena kemampuannya menangani hubungan non-linear dalam data.

    - Fitur Utama yang Digunakan:

Model ini dilatih menggunakan berbagai fitur, termasuk:
  
    lead_time: Jarak hari antara pemesanan dan kedatangan.
    
    deposit_type: Jenis pembayaran deposit.
    
    market_segment: Segmen pasar pemesan.
    
    customer_type: Tipe pelanggan.
    
    previous_cancellations: Riwayat pembatalan sebelumnya.
    
    country: Negara asal tamu.
    
    Evaluasi: Kinerja model dievaluasi menggunakan metrik seperti Accuracy, Precision, Recall, dan F1-Score.

Teknologi yang Digunakan

  - Analisis & Pemodelan: Python
    
  - Library Python: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

  - Lingkungan Kerja: Jupyter Notebook

  - Visualisasi & Dasbor: Tableau Public

  - Struktur Repository

    ├── data/

    │    └── hotel_bookings.csv

    ├── notebooks/

    │    └── Analisis & Pemodelan Hotel.ipynb

    ├── model/

    │    └── hotel_cancellation_model.pkl

    └── README.md

jupyter lab
  
Buka file .ipynb di dalam folder notebooks/ untuk melihat proses analisis dan pelatihan model.


Kontributor
  
Eldi Andreanov & Amjad Muhammad Ahsan Ayub La Tanrang
