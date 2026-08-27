---
title: "MarkupParagraph"
linktitle: "MarkupParagraph"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili sebuah paragraf."
type: docs
weight: 2880
url: /id/java/com.aspose.pdf/markupparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupParagraph

```
public final class MarkupParagraph extends Object
```

Mewakili sebuah paragraf.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getContinuationPageNumbers](#getContinuationPageNumbers--) | Daftar nomor halaman di mana paragraf dilanjutkan. Akan cocok dengan halaman tempat paragraf dimulai jika dilanjutkan di kolom berikutnya pada halaman yang sama. |
| [getFragments](#getFragments--) | <p> Kumpulan objek {@code TextFragment} yang tidak kosong dari paragraf. </p><hr> Objek {@code TextFragment} menyediakan akses ke teks hasil pencarian, properti teks, dan memungkinkan untuk mengedit teks serta mengubah keadaan teks (font, ukuran font, warna, dll). |
| [getFragmentsInternal](#getFragmentsInternal--) |  |
| [getLines](#getLines--) | <p> Baris-baris paragraf. Setiap baris direpresentasikan oleh daftar fragmen teks. </p><hr> Objek {@code TextFragment} menyediakan akses ke teks hasil pencarian, properti teks, dan memungkinkan untuk mengedit teks serta mengubah keadaan teks (font, ukuran font, warna, dll). |
| [getLinesInternal](#getLinesInternal--) |  |
| [getPoints](#getPoints--) | Titik-titik poligon yang menggambarkan paragraf. Titik awal adalah sudut kiri bawah paragraf. Dan titik-titik berikutnya berada dalam urutan berlawanan arah jarum jam. |
| [getSecondaryPoints](#getSecondaryPoints--) | Titik-titik poligon sekunder yang menggambarkan kelanjutan paragraf. Tidak akan null jika paragraf dilanjutkan di kolom atau halaman berikutnya. Titik awal adalah sudut kiri bawah paragraf. Dan titik-titik berikutnya berada dalam urutan berlawanan arah jarum jam. |
| [getText](#getText--) | Mendapatkan objek teks {@code string} yang direpresentasikan oleh objek {@code MarkupParagraph}. |
| [setText](#setText-java.lang.String-) | Mendapatkan atau mengatur teks paragraf. |

### getContinuationPageNumbers {#getContinuationPageNumbers--}
```
public final List < Integer > getContinuationPageNumbers()
```

Daftar nomor halaman di mana paragraf dilanjutkan. Akan cocok dengan halaman tempat paragraf dimulai jika dilanjutkan di kolom berikutnya pada halaman yang sama.

**Returns:**
daftar Integer

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Kumpulan objek {@code TextFragment} yang tidak kosong dari paragraf. </p><hr> Objek {@code TextFragment} menyediakan akses ke teks hasil pencarian, properti teks, dan memungkinkan untuk mengedit teks serta mengubah keadaan teks (font, ukuran font, warna, dll).

**Returns:**
daftar instance TextFragment

### getFragmentsInternal {#getFragmentsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< TextFragment > getFragmentsInternal()
```



### getLines {#getLines--}
```
public List <com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLines()
```

<p> Baris-baris paragraf. Setiap baris direpresentasikan oleh daftar fragmen teks. </p><hr> Objek {@code TextFragment} menyediakan akses ke teks hasil pencarian, properti teks, dan memungkinkan untuk mengedit teks serta mengubah keadaan teks (font, ukuran font, warna, dll).

**Returns:**
daftar instance TextFragment

### getLinesInternal {#getLinesInternal--}
```
public com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Collections.Generic.List< TextFragment >> getLinesInternal()
```



### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Titik-titik poligon yang menggambarkan paragraf. Titik awal adalah sudut kiri bawah paragraf. Dan titik-titik berikutnya berada dalam urutan berlawanan arah jarum jam.

**Returns:**
array instance Point

### getSecondaryPoints {#getSecondaryPoints--}
```
public final List < Point []> getSecondaryPoints()
```

Titik-titik poligon sekunder yang menggambarkan kelanjutan paragraf. Tidak akan null jika paragraf dilanjutkan di kolom atau halaman berikutnya. Titik awal adalah sudut kiri bawah paragraf. Dan titik-titik berikutnya berada dalam urutan berlawanan arah jarum jam.

**Returns:**
daftar Point[]

### getText {#getText--}
```
public String getText()
```

Mendapatkan objek teks {@code string} yang direpresentasikan oleh objek {@code MarkupParagraph}.

**Returns:**
nilai String

### setText {#setText-java.lang.String-}
Mendapatkan atau mengatur teks paragraf.
