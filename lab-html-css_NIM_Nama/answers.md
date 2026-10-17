
# Jawaban Praktikum: Muhammad Faiz Abdullah mukhtar (10224054)

## Bagian 1: Pemanasan


## Bagian 1: Pemanasan

1. Selector: `nav a.active:hover`.
   Deklarasi: `color: red;`.
   Property: `color`.
   Value: `red`.
   Pseudo-class: `:hover`.

2. Block: `p`, `li`, dan `h2`.
   Inline: `span`, `a`, dan `strong`.
   Catatan: `li` secara default menggunakan display: list-item.

3. Paragraf yang menjadi hijau adalah A dan B,
   karena keduanya merupakan elemen p di dalam
   elemen dengan class `box`.

4. Warnanya merah, karena selector `#title`
   memiliki specificity lebih tinggi daripada
   `.heading` dan `h1`.

5. Tag HTML tidak tersusun dengan benar.
   Tag `<strong>` dibuka di dalam `<p>`, tetapi
   penutup `</strong>` berada setelah `</p>`.
   Seharusnya: `<p>Hello <strong>world</strong></p>`.


## Bagian 3: Prediksi Selector Golf


## Bagian 3: Prediksi Selector Golf

P1.
(a) Weekly hack nights: biru.
(b) Bring your own laptop: oranye.
(c) © 2026 Student Affairs: biru.

P2.
Urutan specificity tertinggi ke terendah:
1. #tech p
2. .club p
3. main section p
4. p

Setelah diuji (hasil sebenarnya):
(a) Biru, (b) oranye, (c) biru.

## Bagian 4: Box model

Q1 (content-box):

Q2 (border-box):

Pengecekan DevTools:

## Bagian 5: Tabel debug


## Bagian 5: Tabel debug

| # | Baris | Bug | Perbaikan | Cara menemukannya |
|---|---|---|---|---|
| 1 | CSS body | `colour` bukan property CSS yang valid | Ganti menjadi `color` | DevTools |
| 2 | CSS header | Kurang titik koma setelah `background` | Tambahkan `;` | Membaca kode |
| 3 | CSS selector | `.Card` tidak cocok dengan class `card` | Ganti menjadi `.card` | Membaca kode |
| 4 | CSS news list | `18 px` memiliki spasi yang salah | Ganti menjadi `18px` | DevTools |
| 5 | CSS footer | `centre` bukan nilai `text-align` yang valid | Ganti menjadi `center` | DevTools |
| 6 | Heading | Tag `<h1>` ditutup dengan `</h2>` | Ganti menjadi `</h1>` | W3C Validator |
| 7 | Link About | Tanda kutip atribut `href` tidak lengkap | Ganti menjadi `href="about.html"` | W3C Validator |
| 8 | Daftar berita | ID `newsList` tidak cocok dengan `#news-list` | Samakan nama ID dan selector CSS | Membaca kode |
| 9 | Gambar | Elemen `img` tidak memiliki atribut `alt` | Tambahkan `alt` yang deskriptif | W3C Validator |

## Bagian 6: Tabel Code Review

| # | Baris | Masalah | Mengapa penting | Perbaikan saya |
|---|-------|---------|-----------------|----------------|

### Refleksi

1.
2.
3.

## Bagian 7: Exit ticket

1.
2.
3.
