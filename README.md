![LOGO](https://ew.com/thmb/SpqVHh6pwaeIEqFO9hmVtMCiS4M=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/Spotify-089b80c169d44fcfa110aebc6801289f.jpg)

### Sumber Data
Dataset berasal dari proyek [TidyTuesday](https://github.com/rfordatascience/tidytuesday) dan dikumpulkan menggunakan paket [`spotifyr`](https://github.com/charlie86/spotifyr). Data dirilis pada **21 Januari 2020** dan dapat diakses melalui tautan berikut:  
[spotify_songs.csv](https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2020/2020-01-21/spotify_songs.csv).

Paket `spotifyr` digunakan untuk mendapatkan metadata lagu dari API Spotify, mencakup informasi seperti popularitas lagu, nama artis, album, genre, serta atribut audio (danceability, energy, valence, dll.).

### Variabel dalam Dataset:
Dataset ini terdiri dari 19 variabel, termasuk:
- `track_id`, `track_name`, `track_artist`: Identifikasi dan informasi dasar mengenai lagu.
- `track_popularity`: Popularitas lagu berdasarkan nilai antara 0-100.
- `playlist_name`, `playlist_genre`: Nama playlist dan genre playlist terkait.
- `danceability`, `energy`, `acousticness`, dan lainnya: Atribut audio yang menggambarkan karakteristik musik lagu seperti keterpaduan untuk berdansa, energi, keaslian suara, dan lainnya.

### Kekhasan Data:
- **Nilai Hilang**: Data ini memiliki beberapa nilai yang hilang pada atribut tertentu, seperti `key` atau `mode`. Nilai hilang ini biasanya dicatat dengan angka -1 atau dengan tidak adanya data (NA).
- **Imputasi**: Tidak ada informasi eksplisit tentang imputasi data dalam dokumentasi yang tersedia. Namun, untuk analisis lebih lanjut, nilai hilang dapat diproses dengan teknik imputasi atau penghapusan berdasarkan tujuan analisis.

Secara keseluruhan, dataset ini menawarkan gambaran menyeluruh tentang lagu-lagu populer di Spotify dengan variabel yang menggambarkan aspek teknis dan emosional dari musik tersebut.
