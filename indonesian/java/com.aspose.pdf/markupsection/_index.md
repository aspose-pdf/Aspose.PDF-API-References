---
title: "MarkupSection"
linktitle: "MarkupSection"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili sebuah seksi markup - wilayah persegi panjang pada halaman yang berisi teks dan dapat dipisahkan secara visual dari blok teks lainnya."
type: docs
weight: 2890
url: /id/java/com.aspose.pdf/markupsection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupSection

```
public final class MarkupSection extends Object
```

Mewakili sebuah seksi markup - wilayah persegi panjang pada halaman yang berisi teks dan dapat dipisahkan secara visual dari blok teks lainnya.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFragments](#getFragments--) | <p> Koleksi objek {@code TextFragment} yang tidak kosong yang berada di dalam bagian. </p><hr> Objek {@code TextFragment} menyediakan akses ke teks hasil pencarian, properti teks, dan memungkinkan untuk mengedit teks serta mengubah keadaan teks (font, ukuran font, warna, dll). |
| [getParagraphs](#getParagraphs--) | Koleksi objek {@code MarkupParagraph} yang berada di dalam bagian. |
| [getRectangle](#getRectangle--) | Persegi panjang bagian |

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> Koleksi objek {@code TextFragment} yang tidak kosong yang berada di dalam bagian. </p><hr> Objek {@code TextFragment} menyediakan akses ke teks hasil pencarian, properti teks, dan memungkinkan untuk mengedit teks serta mengubah keadaan teks (font, ukuran font, warna, dll).

**Returns:**
daftar instance TextFragment

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

Koleksi objek {@code MarkupParagraph} yang berada di dalam bagian.

**Returns:**
daftar instance MarkupParagraph

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Persegi panjang bagian

**Returns:**
Instansi Rectangle
