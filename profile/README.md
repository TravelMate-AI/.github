# TravelMate.AI - DBS Coding Camp 2025 Capstone Project 🤖

<div align="center">
    <img src="https://i.postimg.cc/kGz7SVnL/Screenshot-2025-05-20-222015.png" alt="TravelMate.AI" width="20%" />
</div>

 
This project is the development of an AI Travel Advisor website, featuring a chatbot capable of providing travel tips, planning assistance, and more. Additionally, it offers a destination recommendation system tailored to the user's preferences. The system leverages an intent classification-based machine learning model, seamlessly integrated into a user-friendly website interface.

**Theme:** Social, Culture, Tourism

## About the Project 🚀
The project consists of two main recommendation systems:

1. Tourism Recommender: Provides tourism recommendations based on user prompt and location.
2. Hotel Recommender: Provides hotel recommendations based on user prompt and location.

this model ????

## Fitur
- Rekomendasi perjalanan berdasarkan deskripsi dan lokasi pengguna (ex: wisata alam yang asri di kota Malang, dll.).
- Rekomendasi Hotel: Berdasarkan deskripsi yang diberikan oleh pengguna, sistem memberikan rekomendasi hotel yang relevan dengan lokasi yang ditentukan.
- Model Klasifikasi Hotel: Memprediksi kategori hotel berdasarkan deskripsi menggunakan model pembelajaran mendalam (Deep Learning) dengan bantuan Keras dan Keras Tuner untuk penyesuaian hyperparameter.
- Hyperparameter Tuning: Penggunaan Keras Tuner untuk mencari hyperparameter terbaik untuk model pembelajaran mendalam yang digunakan.
- Pengolahan Embedding Teks: Menggunakan IndoBERT untuk menghasilkan embedding dari deskripsi hotel, yang kemudian digunakan untuk proses pelatihan dan rekomendasi.

## Teknologi yang Digunakan
- **Python**: Bahasa pemrograman utama.
- **TensorFlow**: Framework utama untuk membangun dan melatih model deep learning.
- **Keras**: Digunakan untuk membangun model neural network dan hyperparameter tuning.
- **IndoBERT**: Model bahasa pre-trained untuk Bahasa Indonesia, digunakan untuk menghasilkan embedding teks.
- **Keras Tuner**: Digunakan untuk mengoptimalkan hyperparameter model neural network.
- **Scikit-learn**: Digunakan untuk pemisahan data latih dan validasi serta pemrosesan data seperti label encoding.
- **Pandas**: Digunakan untuk manipulasi dan analisis data dalam bentuk DataFrame.
- **Cosine Similarity**: Digunakan untuk menghitung kesamaan antara embedding deskripsi hotel dengan input pengguna.

## Instalasi
Proyek ini memerlukan beberapa paket Python untuk dijalankan. Berikut adalah daftar paket yang diperlukan:

- TensorFlow: pip install tensorflow
- Keras Tuner: pip install keras-tuner
- Scikit-learn: pip install scikit-learn
- Transformers: pip install transformers
- Pandas: pip install pandas
- NumPy: pip install numpy

### Persyaratan
1. Python 3.7 atau lebih baru.
2. Paket-paket Python berikut:
    - TensorFlow
    - Scikit-learn
    - Pandas
    - Numpy
    - Transformers
    - keras Tuner
   
### Langkah-langkah Instalasi ( belum fix)

1. **Clone repository ini ke komputer Anda**:
    ```bash
    git clone https://github.com/username/nama-repository.git
    cd nama-repository
    ```

2. **Install dependencies**:
    Jika Anda menggunakan `pip`, buat virtual environment dan install dependencies:
    ```bash
    python -m venv venv
    source venv/bin/activate  # Untuk Linux/MacOS
    venv\Scripts\activate  # Untuk Windows
    pip install -r requirements.txt
    ```

    File `requirements.txt` yang berisi dependensi dapat dibuat dengan perintah:
    ```bash
    pip freeze > requirements.txt
    ```

3. **Download dataset**:
    - Pastikan Anda sudah memiliki dataset yang diperlukan. Dataset yang digunakan adalah `cleaned_dataset_wisata.csv` dan `cleaned_dataset_hotel.csv`. Anda dapat mengunduhnya dan menaruhnya di folder yang sesuai.

## Penggunaan ( bingung )

Untuk menjalankan chatbot rekomendasi wisata:
1. Jalankan script Python:
    ```bash
    python chatbot.py
    ```

2. Chatbot akan meminta input pengguna. Anda dapat mengetikkan pertanyaan seperti:
    - "Rekomendasikan wisata alam di Jember"
    - "Rekomendasikan hotel harga terjangkau di kota Malang"
    - "Rekomendasikan wisata murah di Surabaya"
    - "Rekomendasikan hotel yang ada kolam renang di Batu"

    Ketik "keluar" untuk menghentikan chatbot. ??????

## Menyimpan dan Memuat Model

- **Menyimpan model**: Setelah melatih model, model akan disimpan menggunakan Keras `model.save()` ke dalam file `.h5`:
    ```python
    self.model.save_model('tourism_recommender.h5') ( Ganti ama save model nanti )
    ```

- **Memuat model**: Anda bisa memuat model yang telah disimpan menggunakan:
    ```python
    self.model.load_model('tourism_recommender.h5')  ( Ganti ama save model nanti )
    ```

## Struktur Direktori
```bash
    /TravelMate.AI
    │
    ├── Data/
    │   ├── cleaned_dataset_wisata.csv
    │   └── cleaned_dataset_hotel.csv
    ├── Model Chatbot.ipynb 
    └── README.md
```

## Our Team 👥

### Machine Learning Engineer

1. Danish Gyan Pramana
  - Institusi: Universitas Brawijaya
  - Email: danishgyanpramana2018@gmail.com
  - LinkedIn: [Danish Gyan Pramana](www.linkedin.com/in/danishgyanpramana)
  - GitHub: [](https://github.com/vynnzz) 

2. Nikola Izzan Ar Rasheed
  - Institusi: Universitas Brawijaya
  - Email:
  - LinkedIn: [Nikola Izzan Ar Rasheed](www.linkedin.com/in/nikolaizzan/)
  - GitHub: [nikolaizz](github.com/nikolaizz)

3. Taufik Neldi
  - Institusi: Universitas Brawijaya
  - Email: taufikneldi02@gmail.com
  - LinkedIn: [Taufik Neldi](www.linkedin.com/in/taufik-neldi-90aa50279/)
  - GitHub: [Neldi30](github.com/Neldi30)

### Frontend/Backend Developer

1. Muhammad Rasyad Putra Ekardi
  - Institusi: Universitas Brawijaya
  - Email:
  - LinkedIn: www.linkedin.com/in/ 
  - GitHub: [rasyadpe](https://github.com/rasyadpe) 

2. Leonardez Flobert Gunawan
  - Institusi: Universitas Tarumanagara
  - Email: 
  - LinkedIn: www.linkedin.com/in/ 
  - GitHub: [LazerHart](https://github.com/LazerHart) 

3. Zahruldin
  - Institusi: Universitas Nurdin Hamzah
  - Email: 
  - LinkedIn: www.linkedin.com/in/ 
  - GitHub: [](https://github.com/) 


© 2025 TravelMate.AI - DBS Coding Camp 2025 Capstone Project
