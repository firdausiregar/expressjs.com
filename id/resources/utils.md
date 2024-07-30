---
layout: page
title: Express utilitas
menu: resources
lang: id
---
## Fungsi utilitas Express

Organisasi GitHub [pillarjs](https://github.com/pillarjs) berisi sejumlah modul
untuk fungsi utilitas yang mungkin berguna secara umum.

| Modul utilitas | Deskripsi|
|-----------------|------------|
| [cookie](https://www.npmjs.com/package/cookies) | Dapatkan dan atur cookie HTTP(S) yang dapat ditandatangani untuk mencegah gangguan, menggunakan Keygrip. Dapat digunakan dengan pustaka HTTP Node.js atau sebagai middleware Express.|
| [csrf](https://www.npmjs.com/package/csrf) | Berisi logika di balik pembuatan dan verifikasi token CSRF.  Gunakan modul ini untuk membuat middleware CSRF khusus.|
| [finalhandler](https://www.npmjs.com/package/finalhandler) | Berfungsi untuk dipanggil sebagai langkah terakhir untuk merespons permintaan HTTP.|
| [parseurl](https://www.npmjs.com/package/parseurl) | Parsing URL dengan caching. |
| [pencocokan jalur](https://www.npmjs.com/package/path-match) | Pembungkus tipis di sekitar [path-to-regexp](https://github.com/component/path-to-regexp) untuk mempermudah ekstraksi nama parameter.|
| [jalur-ke-regexp](https://www.npmjs.com/package/path-to-regexp) | Ubah string jalur gaya Ekspres seperti ``/pengguna/:nama` menjadi ekspresi reguler.|
| [jalur penyelesaian](https://www.npmjs.com/package/resolve-path) | Menyelesaikan jalur relatif terhadap jalur root dengan validasi. |
| [router](https://www.npmjs.com/package/router) | Router bergaya middleware sederhana. |
| [routington](https://www.npmjs.com/package/routington) |  Router URL berbasis Trie untuk menentukan dan mencocokkan URL. |
| [kirim](https://www.npmjs.com/package/send) | Pustaka untuk streaming file sebagai respons HTTP, dengan dukungan untuk respons parsial (rentang), negosiasi GET bersyarat, dan peristiwa granular.|
| [templasi](https://www.npmjs.com/package/templation) | Lihat sistem yang mirip dengan `res.render()` yang terinspirasi oleh [co-views](https://github.com/visionmedia/co-views) dan [consolidate.js](https://github.com/visionmedia/ konsolidasi.js/). |

Untuk modul tambahan terkait HTTP tingkat rendah, lihat [jshttp](http://jshttp.github.io/).
