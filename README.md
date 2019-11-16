# Quran JSON API | بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيم

Silakan menggunakannya semoga berkah.

### Stuktur Direktori QuranJSON

```sh
.
├── LICENSE
├── quran-complete.json         // AL-Quran JSON Lengkap
├── quran.json                  // AL-Quran JSON
├── road_to_jannah.json         // API QuranJSON
└── surah                       // Direktori JSON Surah Lengkap
    └── <number_of:1-114>.json
```

## Penggunaan API / Service

### Menggunakan Service QuranJSON API

> Rute API Surah banyak yang tidak tersedia dikarenakan terkena limit ukuran json, karena ini menggunakan service gratisan.

Dengan mengakses BASE_URL API : https://www.jsonstore.io/0cbbe501d81d44f64f10c9b10d51a7bd837827928b26f2055b7d274078c607f6/

#### Mengakses API Quran Sederhana

```sh
GET - BASE_URL/ 
```
#### Mengakses API Surah Al Fatihah Lengkap

```sh
GET - BASE_URL/surah/1 
```

### Menjalankan Service sendiri

```sh
npm install
npm start
```
