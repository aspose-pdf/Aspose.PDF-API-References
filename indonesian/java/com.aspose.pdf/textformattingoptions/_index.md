---
title: "TextFormattingOptions"
linktitle: "TextFormattingOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili opsi pemformatan teks"
type: docs
weight: 5080
url: /id/java/com.aspose.pdf/textformattingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextFormattingOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextFormattingOptions

```
public final class TextFormattingOptions extends TextOptions
```

Mewakili opsi pemformatan teks

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextFormattingOptions](#TextFormattingOptions--) | Menginisialisasi instance baru dari objek {@code TextFormattingOptions} dengan mode pembungkus kata yang tidak terdefinisi. |
| [TextFormattingOptions](#TextFormattingOptions-int-) | Menginisialisasi instance baru dari objek {@code TextFormattingOptions} untuk mode pembungkus kata yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFirstLineIndent](#getFirstLineIndent--) | Mendapatkan atau mengatur nilai indentasi baris pertama. |
| [getHyphenSymbol](#getHyphenSymbol--) | <p> Mendapatkan atau mengatur simbol hyphen yang digunakan dalam proses hyphenation. </p><hr> Untuk menghilangkan gambar hyphen (dengan prosedur pembungkus tetap aktif) silakan set string kosong string.Empty untuk HyphenSymbol. |
| [getLineSpacing](#getLineSpacing--) | Mendapatkan mode spasi baris. Nilai default adalah LineSpacingMode.FontSize |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Mendapatkan atau mengatur nilai indentasi baris berikutnya. |
| [getWrapMode](#getWrapMode--) | Mendapatkan mode pembungkus kata. Nilai default adalah WordWrapMode.NoWrap |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Mendapatkan atau mengatur nilai indentasi baris pertama. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | <p> Mendapatkan atau mengatur simbol hyphen yang digunakan dalam proses hyphenation. </p><hr> Untuk menghilangkan gambar hyphen (dengan prosedur pembungkus tetap aktif) silakan set string kosong string.Empty untuk HyphenSymbol. |
| [setLineSpacing](#setLineSpacing-int-) | Mengatur mode spasi baris. Nilai default adalah LineSpacingMode.FontSize |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Mendapatkan atau mengatur nilai indentasi baris berikutnya. |
| [setWrapMode](#setWrapMode-int-) | Mengatur mode pembungkus kata. Nilai default adalah WordWrapMode.NoWrap |

### TextFormattingOptions {#TextFormattingOptions--}
```
public TextFormattingOptions()
```

Menginisialisasi instance baru dari objek {@code TextFormattingOptions} dengan mode pembungkus kata yang tidak terdefinisi.

### TextFormattingOptions {#TextFormattingOptions-int-}
```
public TextFormattingOptions(int wrapMode)
```

Menginisialisasi instance baru dari objek {@code TextFormattingOptions} untuk mode pembungkus kata yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| wrapMode |  | Mode pembungkus kata. @see WordWrapMode |

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Mendapatkan atau mengatur nilai indentasi baris pertama.

**Returns:**
nilai float

### getHyphenSymbol {#getHyphenSymbol--}
```
public final String getHyphenSymbol()
```

<p> Mendapatkan atau mengatur simbol hyphen yang digunakan dalam proses hyphenation. </p><hr> Untuk menghilangkan gambar hyphen (dengan prosedur pembungkus tetap aktif) silakan set string kosong string.Empty untuk HyphenSymbol.

**Returns:**
nilai String

### getLineSpacing {#getLineSpacing--}
```
public int getLineSpacing()
```

Mendapatkan mode spasi baris. Nilai default adalah LineSpacingMode.FontSize

**Returns:**
nilai int @see LineSpacingMode

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Mendapatkan atau mengatur nilai indentasi baris berikutnya.

**Returns:**
nilai float

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Mendapatkan mode pembungkus kata. Nilai default adalah WordWrapMode.NoWrap

**Returns:**
nilai WordWrapMode @see WordWrapMode

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Mendapatkan atau mengatur nilai indentasi baris pertama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
<p> Mendapatkan atau mengatur simbol hyphen yang digunakan dalam proses hyphenation. </p><hr> Untuk menghilangkan gambar hyphen (dengan prosedur pembungkus tetap aktif) silakan set string kosong string.Empty untuk HyphenSymbol.

### setLineSpacing {#setLineSpacing-int-}
```
public void setLineSpacing(int value)
```

Mengatur mode spasi baris. Nilai default adalah LineSpacingMode.FontSize

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int @see LineSpacingMode |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Mendapatkan atau mengatur nilai indentasi baris berikutnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Mengatur mode pembungkus kata. Nilai default adalah WordWrapMode.NoWrap

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai WordWrapMode @see WordWrapMode |
