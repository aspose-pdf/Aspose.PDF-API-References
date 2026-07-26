---
title: "PdfASymbolicFontEncodingStrategy"
linktitle: "PdfASymbolicFontEncodingStrategy"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas ini menjelaskan aturan yang dapat digunakan untuk menyesuaikan proses penyalinan data enkoding untuk kasus ketika font simbolik TrueType memiliki lebih dari satu enkoding. Beberapa dokumen PDF setelah."
type: docs
weight: 3690
url: /id/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy

```
public class PdfASymbolicFontEncodingStrategy extends Object
```

Kelas ini menjelaskan aturan yang dapat digunakan untuk menyesuaikan proses penyalinan data enkoding untuk kasus ketika font simbolik TrueType memiliki lebih dari satu enkoding. Beberapa dokumen PDF setelah dikonversi ke format PDF/A dapat menghasilkan error "More than one encoding in symbolic TrueType font's cmap". Apa penyebab error ini? Semua font simbolik TrueType memiliki tabel khusus "cmap" dalam data internalnya. Tabel ini memetakan kode karakter ke indeks glif. Dan tabel ini dapat berisi sub‑tabel enkoding yang berbeda yang menjelaskan enkoding yang digunakan. Lihat informasi lanjutan tentang tabel cmap di https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Biasanya tabel cmap berisi beberapa sub‑tabel enkoding, tetapi standar PDF/A mengharuskan bahwa hanya satu sub‑tabel enkoding yang boleh tersisa untuk font ini dalam dokumen PDF/A atau harus ada sub‑tabel enkoding (3,0) di antara sub‑tabel font ini. Dan pertanyaan kunci di sini - data apa yang harus diambil dari sub‑tabel lain untuk disalin ke tabel enkoding tujuan (3,0)? Sebagian besar font memiliki tabel cmap yang 'well‑formed' di mana setiap sub‑tabel enkoding sepenuhnya konsisten dengan sub‑tabel lain. Namun beberapa font memiliki tabel cmap dengan tabrakan - misalnya satu sub‑tabel memiliki indeks glif 100 untuk unicode 100, tetapi sub‑tabel lain memiliki indeks glif 200 untuk unicode 100 yang sama. Untuk menyelesaikan masalah ini diperlukan strategi khusus. Secara default strategi berikut digunakan: sub‑tabel mac(1,0) dicari. Jika tabel ini ditemukan, hanya data ini yang digunakan untuk mengisi tabel tujuan (3,0). Jika sub‑tabel mac tidak ditemukan, maka semua sub‑tabel kecuali (3,0) diiterasi dan digunakan untuk menyalin data ke sub‑tabel tujuan (3,0). Juga pemetaan untuk setiap unicode (unicode, indeks glif) disalin ke tabel tujuan hanya jika tabel tujuan belum memiliki unicode tersebut pada saat ini. Jadi, misalnya jika sub‑tabel pertama memiliki indeks glif 100 untuk unicode 100, dan sub‑tabel berikutnya memiliki indeks glif 200 untuk unicode 100 yang sama, hanya data dari sub‑tabel pertama (unicode=100, indeks glif = 100) yang akan disalin. Sehingga setiap sub‑tabel sebelumnya memiliki prioritas lebih tinggi daripada yang berikutnya. Properti dari kelas ini { PdfASymbolicFontEncodingStrategy} membantu menyesuaikan perilaku default. Jika properti {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) bertipe { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} diatur, maka sub‑tabel yang relevan akan digunakan dengan prioritas di atas sub‑tabel mac(1,0). Nilai 'MacTable' dari enumerasi {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} tidak masuk akal dalam kasus ini, karena menunjuk ke sub‑tabel mac (1,0) yang sama yang akan digunakan secara default. Properti {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) mengabaikan semua prioritas untuk setiap sub‑tabel. Jika properti ini diatur, maka hanya sub‑tabel dari antrian yang dideklarasikan yang akan digunakan dalam urutan yang ditentukan. Jika sub‑tabel yang ditentukan tidak ditemukan, maka iterasi default semua sub‑tabel dan strategi penyalinan yang dijelaskan di atas akan digunakan. Objek { PdfASymbolicFontEncodingStrategy.QueueItem} menentukan sub‑tabel enkoding yang digunakan. Sub‑tabel ini dapat diatur melalui kombinasi anggota (PlatformID, PlatformSpecificId) atau melalui enumerasi { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}. Jika font tidak memiliki sub‑tabel (3,0), sub‑tabel lain akan digunakan untuk menjaga kompatibilitas PDF/A. Pemilihan sub‑tabel yang akan digunakan dibuat berdasarkan aturan yang sama seperti yang dijelaskan sebelumnya, sehingga properti {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) dan {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) digunakan untuk menentukan sub‑tabel hasil, dan jika font tidak memiliki sub‑tabel yang diminta, maka sub‑tabel yang ada akan digunakan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy--) | Konstruktor. Mengatur subtable default (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-) | Konstruktor. Mengatur subtable default (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-short-) | Konstruktor |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCmapEncodingTablesPriorityQueue](#getCmapEncodingTablesPriorityQueue--) | Menentukan antrian subtable enkoding yang akan diproses. |
| [getPreferredCmapEncodingTable](#getPreferredCmapEncodingTable--) | Menentukan subtable yang akan digunakan dengan prioritas lebih tinggi daripada subtable mac (1,0). Nilai 'MacTable' dari enumerasi {@code QueueItem.CMapEncodingTableType} tidak masuk akal dalam kasus ini. |
| [setCmapEncodingTablesPriorityQueue](#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-) | Menentukan antrian subtable enkoding yang akan diproses. |
| [setPreferredCmapEncodingTable](#setPreferredCmapEncodingTable-short-) | Menentukan subtable yang akan digunakan dengan prioritas lebih tinggi daripada subtable mac (1,0). Nilai 'MacTable' dari enumerasi {@code QueueItem.CMapEncodingTableType} tidak masuk akal dalam kasus ini. |

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy()
```

Konstruktor. Mengatur subtable default (mac 1,0)

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-}
Konstruktor. Mengatur subtable default (mac 1,0)

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-short-}
```
public PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)
```

Konstruktor

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| preferredEncodingTable |  | subtable enkoding yang akan digunakan dengan prioritas lebih tinggi daripada subtable mac (1,0) @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |

### getCmapEncodingTablesPriorityQueue {#getCmapEncodingTablesPriorityQueue--}
```
public com.aspose.ms.System.Collections.Generic.Queue< PdfASymbolicFontEncodingStrategy.QueueItem > getCmapEncodingTablesPriorityQueue()
```

Menentukan antrian subtable enkoding yang akan diproses.

**Returns:**
Antrian dari QueueItem

### getPreferredCmapEncodingTable {#getPreferredCmapEncodingTable--}
```
public short getPreferredCmapEncodingTable()
```

Menentukan subtable yang akan digunakan dengan prioritas lebih tinggi daripada subtable mac (1,0). Nilai 'MacTable' dari enumerasi {@code QueueItem.CMapEncodingTableType} tidak masuk akal dalam kasus ini.

**Returns:**
CMapEncodingTableType elemen @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType

### setCmapEncodingTablesPriorityQueue {#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-}
Menentukan antrian subtable enkoding yang akan diproses.

### setPreferredCmapEncodingTable {#setPreferredCmapEncodingTable-short-}
```
public void setPreferredCmapEncodingTable(short value)
```

Menentukan subtable yang akan digunakan dengan prioritas lebih tinggi daripada subtable mac (1,0). Nilai 'MacTable' dari enumerasi {@code QueueItem.CMapEncodingTableType} tidak masuk akal dalam kasus ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | preferredEncodingTable encoding subtable yang akan digunakan dengan prioritas terhadap mac subtable(1,0) @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |
