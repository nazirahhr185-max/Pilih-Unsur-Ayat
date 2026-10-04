# Ayat Tunggal: SIAPA, BUAT APA, APA

Permainan kuiz untuk murid mengenal pasti bahagian ayat tunggal.
Murid membaca ayat, kemudian memilih perkataan yang mewakili **SIAPA**, **BUAT APA** atau **APA**.
Selepas menjawab, ketiga-tiga bahagian ayat berwarna supaya murid nampak strukturnya.

Satu fail sahaja (`index.html`), tiada pemasangan diperlukan.

## Cara guna secara dalam talian (GitHub Pages)

1. Buat repositori baharu di GitHub, contohnya `ayat-tunggal`.
2. Muat naik `index.html` dan `README.md` (butang **Add file** → **Upload files**).
3. Buka **Settings** → **Pages**.
4. Di bawah **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, kemudian **Save**.
5. Tunggu 1 hingga 2 minit. Pautan permainan akan muncul di halaman yang sama, biasanya:
   `https://NAMA-ANDA.github.io/ayat-tunggal/`

Kongsi pautan itu dengan murid. Ia boleh dibuka di telefon, tablet atau komputer.

## Cara tukar soalan

Buka `index.html`, cari bahagian `SENTENCES` di dalam `<script>`, dan ubah senarai ayat:

```js
const SENTENCES = [
  ["Ali", "membaca", "buku"],      // [SIAPA, BUAT APA, APA]
  ["Siti", "menyiram", "bunga"],
];
```

Setiap ayat menjana 3 soalan secara automatik. Pilihan jawapan disusun rawak setiap kali main.
