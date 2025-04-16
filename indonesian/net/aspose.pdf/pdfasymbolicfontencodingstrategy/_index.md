---
title: Class PdfASymbolicFontEncodingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.PdfASymbolicFontEncodingStrategy. Kelas ini menjelaskan aturan-aturan yang dapat digunakan untuk menyetel proses penyalinan data encoding untuk kasus ketika font simbolik TrueType memiliki lebih dari satu encoding.
type: docs
weight: 8330
url: /id/net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---
## Kelas PdfASymbolicFontEncodingStrategy

Kelas ini menjelaskan aturan-aturan yang dapat digunakan untuk menyetel proses penyalinan data encoding untuk kasus ketika font simbolik TrueType memiliki lebih dari satu encoding.

Beberapa dokumen PDF setelah konversi ke format PDF/A dapat menghasilkan error "More than one encoding in symbolic TrueType font's cmap". Apa penyebab error ini? Semua font simbolik TrueType memiliki tabel khusus "cmap" dalam data internalnya. Tabel ini memetakan kode karakter ke indeks glif. Dan tabel ini dapat berisi sub-tabel encoding yang berbeda yang menggambarkan encoding yang digunakan. Lihat informasi lanjutan tentang tabel cmap di https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Biasanya, tabel cmap berisi beberapa sub-tabel encoding, tetapi standar PDF/A mengharuskan bahwa hanya satu sub-tabel encoding yang tersisa untuk font ini dalam dokumen PDF/A atau harus ada sub-tabel encoding (3,0) di antara sub-tabel font ini. Dan pertanyaan kunci di sini - data apa yang harus diambil dari sub-tabel yang lain untuk disalin ke sub-tabel encoding tujuan (3,0)? Mayoritas font memiliki tabel cmap yang 'well-formed' di mana setiap sub-tabel encoding sepenuhnya konsisten dengan sub-tabel lainnya. Tetapi beberapa font memiliki tabel cmap dengan tabrakan - misalnya, satu sub-tabel memiliki indeks glif 100 untuk unicode 100, sementara sub-tabel lainnya memiliki indeks glif 200 untuk unicode 100 yang sama. Untuk menyelesaikan masalah ini, diperlukan strategi khusus. Secara default, strategi berikut digunakan: dicari sub-tabel mac (1,0). Jika tabel ini ditemukan, hanya data ini yang digunakan untuk mengisi sub-tabel tujuan (3,0). Jika sub-tabel mac tidak ditemukan, maka semua sub-tabel kecuali (3,0) akan diiterasi dan digunakan untuk menyalin data ke sub-tabel tujuan (3,0). Selain itu, pemetaan untuk setiap pasangan unicode (unicode, indeks glif) disalin ke tabel tujuan hanya jika tabel tujuan saat ini belum memiliki unicode tersebut. Jadi, contohnya, jika sub-tabel pertama memiliki indeks glif 100 untuk unicode 100, dan sub-tabel berikutnya memiliki indeks glif 200 untuk unicode 100 yang sama, maka hanya data dari sub-tabel pertama (unicode=100, indeks glif = 100) yang akan disalin. Jadi, setiap sub-tabel sebelumnya memiliki prioritas lebih tinggi daripada yang berikutnya. Properti dari kelas `PdfASymbolicFontEncodingStrategy` ini membantu menyetel perilaku default. Jika properti [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) dengan tipe [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) disetel, maka sub-tabel yang relevan akan digunakan dengan prioritas daripada sub-tabel mac (1,0). Nilai 'MacTable' dari enumerasi [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) tidak bermakna dalam kasus ini, karena menunjuk pada sub-tabel mac (1,0) yang akan digunakan secara default. Properti [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) mengabaikan semua prioritas untuk setiap sub-tabel. Jika properti ini disetel, maka hanya sub-tabel dari antrian yang dideklarasikan yang akan digunakan dalam urutan yang ditentukan. Jika sub-tabel yang ditentukan tidak ditemukan, maka iterasi default dari semua sub-tabel dan strategi penyalinan yang dijelaskan di atas akan digunakan. Objek [`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem/) menentukan sub-tabel encoding yang digunakan. Sub-tabel ini dapat disetel melalui kombinasi anggota (PlatformID, PlatformSpecificId) atau melalui enumerasi [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/). Dalam kasus ketika font tidak memiliki sub-tabel (3,0), sub-tabel lain akan digunakan untuk menjaga kompatibilitas PDF/A. Pemilihan sub-tabel yang akan digunakan dilakukan berdasarkan aturan yang sama seperti yang dijelaskan sebelumnya, sehingga properti [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) dan [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) digunakan untuk menentukan sub-tabel hasil, dan jika font tidak memiliki sub-tabel yang diminta, maka sub-tabel yang ada akan digunakan.

```csharp
public class PdfASymbolicFontEncodingStrategy
```

## Konstruktor

| Name | Description |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor)() | Konstruktor. Mengatur sub-tabel default (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_1)(CMapEncodingTableType) | Konstruktor |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_2)(Queue&lt;QueueItem&gt;) | Konstruktor |

## Properti

| Name | Description |
| --- | --- |
| [CmapEncodingTablesPriorityQueue](../../aspose.pdf/pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue/) { get; set; } | Menentukan antrian sub-tabel encoding yang akan diproses. |
| [PreferredCmapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy/preferredcmapencodingtable/) { get; set; } | Menentukan sub-tabel yang akan digunakan dengan prioritas daripada sub-tabel mac (1,0). Nilai 'MacTable' dari enumerasi [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) tidak bermakna dalam kasus ini. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)