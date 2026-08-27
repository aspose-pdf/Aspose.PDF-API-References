---
title: "PageMarkup"
linktitle: "PageMarkup"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Markup halaman yang direpresentasikan oleh koleksi {@code MarkupSection} dan {@code MarkupParagraph}."
type: docs
weight: 3420
url: /id/java/com.aspose.pdf/pagemarkup/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageMarkup

```
public final class PageMarkup extends Object
```

Markup halaman yang direpresentasikan oleh koleksi {@code MarkupSection} dan {@code MarkupParagraph}.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getNumber](#getNumber--) | Mendapatkan nomor halaman yang diproses. |
| [getParagraphs](#getParagraphs--) | Mendapatkan koleksi {@code MarkupParagraph} yang ditemukan pada halaman. |
| [getRectangle](#getRectangle--) | Mendapatkan persegi panjang halaman yang diproses. |
| [getSections](#getSections--) | Mendapatkan koleksi {@code MarkupSection} yang ditemukan pada halaman. |
| [getTextFragments](#getTextFragments--) | <p> Mendapatkan koleksi {@code TextFragment} yang ditemukan pada halaman. </p><hr> Objek {@code TextFragment} menyediakan akses ke teks hasil pencarian, properti teks, dan memungkinkan untuk mengedit teks serta mengubah keadaan teks (font, ukuran font, warna, dll). |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah baris teks awal dari bagian berikutnya dapat diperlakukan sebagai kelanjutan dari paragraf terakhir pada bagian sebelumnya. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah baris teks awal dari bagian berikutnya dapat diperlakukan sebagai kelanjutan dari paragraf terakhir pada bagian sebelumnya. |

### getNumber {#getNumber--}
```
public int getNumber()
```

Mendapatkan nomor halaman yang diproses.

**Returns:**
nilai int

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Mendapatkan koleksi {@code MarkupParagraph} yang ditemukan pada halaman.

**Returns:**
Daftar instance MarkupParagraph

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Mendapatkan persegi panjang halaman yang diproses.

**Returns:**
objek Rectangle

### getSections {#getSections--}
```
public List < MarkupSection > getSections()
```

Mendapatkan koleksi {@code MarkupSection} yang ditemukan pada halaman.

**Returns:**
Daftar instance MarkupSection

### getTextFragments {#getTextFragments--}
```
public List < TextFragment > getTextFragments()
```

<p> Mendapatkan koleksi {@code TextFragment} yang ditemukan pada halaman. </p><hr> Objek {@code TextFragment} menyediakan akses ke teks hasil pencarian, properti teks, dan memungkinkan untuk mengedit teks serta mengubah keadaan teks (font, ukuran font, warna, dll).

**Returns:**
Daftar instance TextFragment

### isMulticolumnParagraphsAllowed {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah baris teks awal dari bagian berikutnya dapat diperlakukan sebagai kelanjutan dari paragraf terakhir pada bagian sebelumnya.

**Returns:**
nilai boolean

### setMulticolumnParagraphsAllowed {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah baris teks awal dari bagian berikutnya dapat diperlakukan sebagai kelanjutan dari paragraf terakhir pada bagian sebelumnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
