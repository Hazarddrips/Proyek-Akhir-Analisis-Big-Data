# **<center>Final Project Analisis Big Data</center>**


![LOGO](https://ew.com/thmb/SpqVHh6pwaeIEqFO9hmVtMCiS4M=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/Spotify-089b80c169d44fcfa110aebc6801289f.jpg)

# <center>Eksplorasi Analisis Musik Spotify: Wawasan Mendalam tentang Genre, Fitur, dan Tren</center>

## **Table of Contents**
1. [**Overview**](#Overview)
2. [**Objective**](#Objective)
3. [**Dataset**](#Dataset)
4. [**Methodology**](#Methodology)
5. [**Insights**](#Insights)
6. [**Dependencies**](#Dependencies)
7. [**Usage**](#Usage)
8. [**Team Members**](#Team-Members)
9. [**Repository Structure**](#Repository-Structure)
10. [**References**](#References)


## **Overview**
Proyek ini bertujuan untuk mengeksplorasi dan menganalisis data lagu-lagu Spotify dengan fokus pada genre, fitur audio, dan tren yang muncul. Melalui eksplorasi data (EDA), analisis ini bertujuan untuk mengidentifikasi pola-pola musik yang relevan dan memberikan wawasan tentang hubungan antar genre dan fitur yang mempengaruhi popularitas lagu. Sebagai tambahan, K-Nearest Neighbors (KNN) digunakan untuk memberikan rekomendasi berdasarkan pola-pola musik yang terdeteksi, meskipun fokus utama dari proyek ini adalah analisis eksplorasi data dan pemahaman karakteristik musik seperti danceability, energy, dan acousticness.

---

## **Objective**

Tujuan dari proyek ini adalah untuk menggali pola-pola dan tren yang ada dalam dataset lagu Spotify. Khususnya, proyek ini bertujuan untuk:
Menganalisis hubungan antara fitur-fitur audio (seperti danceability, energy, acousticness) dengan genre musik.
Membangun sistem rekomendasi menggunakan KNN untuk merekomendasikan lagu-lagu berdasarkan kesamaan fitur musik.
Mengidentifikasi genre dan fitur yang mendominasi playlist tertentu dan memahami faktor-faktor yang mempengaruhi popularitas lagu di platform Spotify.

---

## **Dataset**

Dataset berasal dari proyek [TidyTuesday](https://github.com/rfordatascience/tidytuesday) dan dikumpulkan menggunakan paket [`spotifyr`](https://github.com/charlie86/spotifyr). Data dirilis pada **21 Januari 2020** dan dapat diakses melalui tautan berikut:  
[spotify_songs.csv](https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2020/2020-01-21/spotify_songs.csv).

Paket `spotifyr` digunakan untuk mendapatkan metadata lagu dari API Spotify, mencakup informasi seperti popularitas lagu, nama artis, album, genre, serta atribut audio (danceability, energy, valence, dll.).

### Variabel dalam Dataset:
Dataset ini terdiri dari 19 variabel, termasuk:
- `track_id`, `track_name`, `track_artist`: Identifikasi dan informasi dasar mengenai lagu.
- `track_popularity`: Popularitas lagu berdasarkan nilai antara 0-100.
- `playlist_name`, `playlist_genre`: Nama playlist dan genre playlist terkait.
- `danceability`, `energy`, `acousticness`, dan lainnya: Atribut audio yang menggambarkan karakteristik musik lagu seperti keterpaduan untuk berdansa, energi, keaslian suara, dan lainnya.

---

## **Methodology**

1. Data import and cleaning.
2. Exploratory Data Analysis (EDA).
3. Optional: Advanced analysis KNN untuk song recommendation system

---

## **Insights**
[Summarize the key findings from your analysis, highlighting important patterns or trends.]

---

### **Dependencies**
Proyek ini menggunakan beberapa dependensi untuk menjalankan analisis. Berikut adalah daftar dependensi yang diperlukan:

pandas, versi 1.4.3
openpyxl, versi 3.0.10
numpy, versi 1.23.0
numpy-stl, versi 2.17.1
matplotlib, versi 3.5.2
ipympl, versi 0.9.1
jupyterlab, versi 3.4.4
ipywidgets, versi 7.7.1
tqdm, versi 4.64.0
Catatan: Belum diuji sepenuhnya, namun bisa digunakan di lingkungan Python.

---

## **Usage**
[Write this section yourself.]
1. Clone Repository
Clone repository ini :
    
    ```
    git clone https://github.com/Hazarddrips/Proyek_Akhir_Analisis_Big_Data.git
    ```
    ```
    cd Proyek_Akhir_Analisis_Big_Data
    ```
2. Install Dependencies
Install paket yang dibutuhkan:
    ```
    pip install -r requirements.txt
    ```
3. Jalankan Jupyter Notebook
Buka file analisisbigdata.ipynb dengan Jupyter:
    ```
    jupyter notebook analisisbigdata.ipynb
    ```
4. Dataset
Pastikan file `spotify_songs.csv` ada di direktori yang sama dengan notebook.

5. Jelajahi Analisis
Ikuti langkah-langkah di notebook untuk pembersihan dan analisis data.

---

## **Team Members**

   * [Taufik Suryo Abintoro](https://github.com/) 
   * [Febriansyah Ilham Nur Wakit](https://github.com/) 
   * [Haidar Zakki Jumali](https://github.com/) 

---

## **Repository Structure**
- `spotify_songs.csv`: Dataset berisi data lagu-lagu Spotify, termasuk informasi seperti nama lagu, artis, genre, durasi, dan metrik lainnya yang digunakan untuk analisis.
- `.ipynb`: Jupyter Notebook yang berisi langkah-langkah analisis data, mulai dari pembersihan data hingga eksplorasi dan visualisasi untuk menemukan wawasan yang relevan dari dataset.
- `README.md`: Pengantar dan gambaran umum proyek, termasuk instruksi penggunaan, tujuan analisis, serta bagaimana cara menjalankan dan mereplikasi analisis ini.
---

## **References**
- Dataset: [TidyTuesday](https://github.com/rfordatascience/tidytuesday)
- Additional Resources: 
    * https://github.com/SPARC-FAIR-Codeathon/QuiltedTutorials
    * https://github.com/SPARC-FAIR-Codeathon/KnowMore


---