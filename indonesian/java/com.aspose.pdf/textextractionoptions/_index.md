---
title: "TextExtractionOptions"
linktitle: "TextExtractionOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili opsi ekstraksi teks"
type: docs
weight: 5060
url: /id/java/com.aspose.pdf/textextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextExtractionOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextExtractionOptions

```
public final class TextExtractionOptions extends TextOptions
```

Mewakili opsi ekstraksi teks

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextExtractionOptions](#TextExtractionOptions-int-) | Menginisialisasi instansi baru dari objek {@code TextExtractionOptions} untuk mode pemformatan teks yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFormattingMode](#getFormattingMode--) | Mendapatkan mode pemformatan. |
| [getScaleFactor](#getScaleFactor--) | Mendapatkan faktor yang akan diterapkan untuk mengubah ukuran font selama ekstraksi dalam mode murni. Menetapkan nilai yang lebih kecil menghasilkan lebih banyak spasi dalam teks yang diekstrak. Nilai default adalah 1 - tidak ada skala; Menetapkan nilai ke nol memungkinkan algoritma memilih skala secara otomatis. |
| [setFormattingMode](#setFormattingMode-int-) | Mengatur mode pemformatan. |
| [setScaleFactor](#setScaleFactor-double-) | Mengatur faktor yang akan diterapkan untuk mengubah ukuran font selama ekstraksi dalam mode murni. Menetapkan nilai yang lebih kecil menghasilkan lebih banyak spasi dalam teks yang diekstrak (dari 1 hingga 10). Nilai default adalah 1 - tidak ada skala; Menetapkan nilai ke nol memungkinkan algoritma memilih skala secara otomatis. |

### TextExtractionOptions {#TextExtractionOptions-int-}
```
public TextExtractionOptions(int formattingMode)
```

Menginisialisasi instansi baru dari objek {@code TextExtractionOptions} untuk mode pemformatan teks yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formattingMode |  | Nilai mode pemformatan teks. @see TextFormattingMode |

### getFormattingMode {#getFormattingMode--}
```
public int getFormattingMode()
```

Mendapatkan mode pemformatan.

**Returns:**
Nilai TextFormattingMode @see TextFormattingMode

### getScaleFactor {#getScaleFactor--}
```
public double getScaleFactor()
```

Mendapatkan faktor yang akan diterapkan untuk mengubah ukuran font selama ekstraksi dalam mode murni. Menetapkan nilai yang lebih kecil menghasilkan lebih banyak spasi dalam teks yang diekstrak. Nilai default adalah 1 - tidak ada skala; Menetapkan nilai ke nol memungkinkan algoritma memilih skala secara otomatis.

**Returns:**
nilai double

### setFormattingMode {#setFormattingMode-int-}
```
public void setFormattingMode(int value)
```

Mengatur mode pemformatan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Nilai TextFormattingMode @see TextFormattingMode |

### setScaleFactor {#setScaleFactor-double-}
```
public void setScaleFactor(double value)
```

Mengatur faktor yang akan diterapkan untuk mengubah ukuran font selama ekstraksi dalam mode murni. Menetapkan nilai yang lebih kecil menghasilkan lebih banyak spasi dalam teks yang diekstrak (dari 1 hingga 10). Nilai default adalah 1 - tidak ada skala; Menetapkan nilai ke nol memungkinkan algoritma memilih skala secara otomatis.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |
