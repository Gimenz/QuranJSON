# Quran JSON API | بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيم

Silakan menggunakannya semoga berkah.

### Folder structure for Qur'an JSON
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

### Menggunakan service QuranJSON API

> Rute API Surah banyak yang tidak tersedia dikarenakan terkena limit ukuran json, karena ini menggunakan service gratisan.

Dengan mengakses BASE_URL API : https://www.jsonstore.io/0cbbe501d81d44f64f10c9b10d51a7bd837827928b26f2055b7d274078c607f6/

#### Mengakses API Quran Sederhana

```
GET - BASE_URL/ 
```
#### Mengakses API Surah Al Fatihah Lengkap

```
GET - BASE_URL/surah/1 
```

### Menjalankan Service sendiri

```bash
npm install
npm start
```
