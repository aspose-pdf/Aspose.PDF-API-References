---
title: "PdfASymbolicFontEncodingStrategy"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Class ini menjelaskan aturan yang dapat digunakan untuk menyesuaikan proses penyalinan data enkoding untuk kasus ketika font simbolik TrueType memiliki lebih dari satu enkoding. Beberapa dokumen PDF setelah konversi ke format PDF/A dapat mengalami kesalahan More than one encoding in symbolic TrueType fonts cmap. Apa penyebab kesalahan ini? Semua font simbolik TrueType memiliki tabel khusus cmap di dalam data internalnya. Tabel ini memetakan kode karakter ke indeks glif. Dan tabel ini dapat berisi sub‑tabel enkoding yang berbeda yang menjelaskan enkoding yang digunakan. Lihat informasi lanjutan tentang tabel cmap di https//developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Biasanya tabel cmap berisi beberapa sub‑tabel enkoding tetapi standar PDF/A mengharuskan hanya satu sub‑tabel enkoding 30 yang boleh disisakan untuk font ini dalam dokumen PDF/A. Dan pertanyaan kunci di sini – data apa yang harus diambil dari sub‑tabel lain untuk disalin ke tabel enkoding tujuan 30. Mayoritas font memiliki tabel cmap yang terbentuk dengan baik dimana setiap sub‑tabel enkoding sepenuhnya konsisten dengan sub‑tabel lain. Namun beberapa font memiliki tabel cmap dengan tabrakan – misalnya satu sub‑tabel memiliki indeks glif 100 untuk unicode 100 tetapi sub‑tabel lain memiliki indeks glif 200 untuk unicode 100 yang sama. Untuk menyelesaikan masalah ini diperlukan strategi khusus. Secara default strategi berikut digunakan: sub‑tabel mac10 dicari. Jika tabel ini ditemukan, hanya data tersebut yang digunakan untuk mengisi tabel tujuan 30. Jika sub‑tabel mac tidak ditemukan, maka semua sub‑tabel kecuali 30 diiterasi dan digunakan untuk menyalin data ke sub‑tabel tujuan 30. Juga pemetaan untuk setiap indeks glif unicode disalin ke tabel tujuan hanya jika tabel tujuan belum memiliki unicode tersebut pada saat ini. Jadi misalnya jika sub‑tabel pertama memiliki indeks glif 100 untuk unicode 100 dan sub‑tabel berikutnya memiliki indeks glif 200 untuk unicode 100 yang sama, hanya data dari sub‑tabel pertama (unicode100 indeks glif 100) yang akan disalin. Jadi setiap sub‑tabel sebelumnya memiliki prioritas lebih tinggi dibandingkan yang berikutnya. Properti dari kelas PdfASymbolicFontEncodingStrategy./pdfasymbolicfontencodingstrategy membantu menyesuaikan perilaku default. Jika properti PreferredCmapEncodingTable./pdfasymbolicfontencodingstrategy/preferredcmapencodingtable bertipe CMapEncodingTableType./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype disetel, maka sub‑tabel yang relevan akan digunakan dengan prioritas di atas sub‑tabel mac10. Nilai MacTable dari enumerasi CMapEncodingTableType./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype tidak memiliki arti dalam kasus ini karena menunjuk ke sub‑tabel mac10 yang sama yang akan digunakan secara default. Properti CmapEncodingTablesPriorityQueue./pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue membuang semua prioritas untuk setiap sub‑tabel. Jika properti ini disetel, maka hanya sub‑tabel dari antrian yang dideklarasikan yang akan digunakan dalam urutan yang ditentukan. Jika sub‑tabel yang disebutkan tidak ditemukan, maka iterasi default semua sub‑tabel dan strategi penyalinan yang dijelaskan di atas akan digunakan. Objek QueueItem./pdfasymbolicfontencodingstrategy.queueitem menentukan sub‑tabel enkoding yang digunakan. Sub‑tabel ini dapat disetel melalui kombinasi anggota PlatformID PlatformSpecificId atau melalui enumerasi CMapEncodingTableType./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype."
type: docs
weight: 1190
url: /id/python-net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---

## PdfASymbolicFontEncodingStrategy class

Kelas ini menjelaskan aturan yang dapat digunakan untuk menyesuaikan proses penyalinan data enkoding untuk kasus<br/>            ketika font simbolik TrueType memiliki lebih dari satu enkoding.
            Beberapa dokumen PDF setelah konversi ke format PDF/A dapat mengalami kesalahan <br/>            "More than one encoding in symbolic TrueType font's cmap". 
            Apa penyebab kesalahan ini? Semua font simbolik TrueType memiliki tabel khusus "cmap"<br/>            dalam data internalnya. Tabel ini memetakan kode karakter ke indeks glif. 
            Dan tabel ini dapat berisi sub‑tabel enkoding yang berbeda yang<br/>            menjelaskan enkoding yang digunakan. Lihat informasi lanjutan tentang tabel cmap di<br/>            https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html.
            Biasanya tabel cmap berisi beberapa sub‑tabel enkoding, tetapi standar PDF/A mengharuskan<br/>            hanya satu sub‑tabel enkoding (3,0) yang harus dipertahankan untuk font ini dalam dokumen PDF/A. 
            Dan pertanyaan kunci di sini - data apa yang harus diambil dari sub‑tabel lain untuk disalin ke
            tabel enkoding tujuan (3,0)? Sebagian besar font memiliki tabel cmap yang 'well-formed' dimana
            setiap sub‑tabel enkoding sepenuhnya konsisten dengan sub‑tabel lain. Tetapi beberapa font
            memiliki tabel cmap dengan tabrakan - misalnya satu sub‑tabel memiliki indeks glif 
            100 untuk unicode 100, tetapi sub‑tabel lain memiliki indeks glif 200 untuk unicode 100 yang sama.
            Untuk menyelesaikan masalah ini diperlukan strategi khusus. 
            Secara default strategi berikut digunakan: 
            sub‑tabel mac(1,0) dicari. Jika tabel ini ditemukan, hanya data ini yang digunakan untuk mengisi tabel tujuan
            (3,0). Jika sub‑tabel mac tidak ditemukan maka semua sub‑tabel kecuali (3,0) diiterasi 
            dan digunakan untuk menyalin data ke sub‑tabel tujuan (3,0). Juga pemetaan untuk setiap unicode (unicode, indeks glif)
            disalin ke tabel tujuan hanya jika tabel tujuan belum memiliki unicode tersebut pada saat ini. 
            Jadi, misalnya jika sub‑tabel pertama memiliki indeks glif 100 untuk unicode 100, dan sub‑tabel berikutnya memiliki
            indeks glif 200 untuk unicode 100 yang sama, hanya data dari sub‑tabel pertama (unicode=100, indeks glif = 100) yang akan disalin. 
            Sehingga setiap sub‑tabel sebelumnya memiliki prioritas lebih tinggi daripada yang berikutnya. 
            Properti dari kelas ini [PdfASymbolicFontEncodingStrategy](/pdf/python-net/aspose.pdf/pdfasymbolicfontencodingstrategy/) membantu menyesuaikan perilaku default. 
            Jika properti [preferred_cmap_encoding_table](/pdf/python-net/aspose.pdf/pdfasymbolicfontencodingstrategy/) bertipe [CMapEncodingTableType](/pdf/python-net/aspose.pdf.pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtabletype/)
            diatur, maka sub‑tabel yang relevan akan digunakan dengan prioritas di atas sub‑tabel mac(1,0). Nilai 'MacTable' dari
            enumerasi [CMapEncodingTableType](/pdf/python-net/aspose.pdf.pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtabletype/) tidak memiliki arti dalam kasus ini, karena ia 
            menunjuk ke sub‑tabel mac yang sama (1,0) yang akan digunakan secara default. 
            Properti [None](/pdf/python-net/aspose.pdf/pdfasymbolicfontencodingstrategy/) mengabaikan semua prioritas untuk setiap sub‑tabel.
            Jika properti ini diatur, maka hanya sub‑tabel dari antrian yang dideklarasikan yang akan digunakan dalam urutan yang ditentukan.
            Jika sub‑tabel yang ditentukan tidak ditemukan maka iterasi default semua sub‑tabel dan strategi penyalinan yang dijelaskan di atas
            akan digunakan.
            Objek [QueueItem](/pdf/python-net/aspose.pdf.pdfasymbolicfontencodingstrategy/queueitem/) menentukan sub‑tabel enkoding yang digunakan. Sub‑tabel ini dapat diatur
            melalui kombinasi anggota (PlatformID, PlatformSpecificId) atau melalui enumerasi [CMapEncodingTableType](/pdf/python-net/aspose.pdf.pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtabletype/).

Tipe PdfASymbolicFontEncodingStrategy menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| PdfASymbolicFontEncodingStrategy() | Konstruktor. Menetapkan sub‑tabel default (mac 1,0) |
| PdfASymbolicFontEncodingStrategy(preferred_encoding_table) | Menginisialisasi instance baru dari kelas PdfASymbolicFontEncodingStrategy |
## Properti
| Nama | Deskripsi |
| :- | :- |
| preferred_cmap_encoding_table | Menentukan subtabel yang akan digunakan dengan prioritas terhadap subtabel mac(1,0). Nilai 'MacTable' dari<br/>            enumerasi [CMapEncodingTableType](/pdf/python-net/aspose.pdf.pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtabletype/) tidak masuk akal dalam kasus ini. |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

