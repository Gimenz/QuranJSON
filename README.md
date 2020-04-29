# Quran JSON API | بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيم

JSON Alquran Lengkap Sempurna Sederhana (Terjemahan Indonesia, Tafsir, dan Audio) Beserta dengan REST API. Silakan menggunakannya sebaik mungkin dan semoga berkah.

## Stuktur Direktori QuranJSON

```sh
.
├── README.md
├── quran-complete.json         // AL-Quran JSON Lengkap
├── quran.json                  // AL-Quran JSON
├── road_to_jannah.json         // API QuranJSON
└── surah                       // Direktori JSON Surah Lengkap
    └── <number_of:1-114>.json
```

## Real app that uses QuranJSON

- [Quran Daily: Unlock Your Heart (iOS)](https://apps.apple.com/us/app/quran-daily-unlock-your-heart/id1494995253)

Add your application to this list with a pull request

## Penggunaan API / Service

### Menjalankan Service sendiri

```sh
npm install
npm start
```

#### Mengakses API Quran Sederhana

```sh
GET - BASE_URL/
```

#### Mengakses API Surah Al Fatihah Lengkap

```sh
GET - BASE_URL/surah/1
```

### Menggunakan Service QuranJSON Github JSON

Dapat langsung diakses melalui direktori.

Quran:

```sh
https://raw.githubusercontent.com/penggguna/QuranJSON/master/quran.json
```

Surah:

```sh
https://raw.githubusercontent.com/penggguna/QuranJSON/master/surah/1.json
```
