---
title: "HtmlDiffOutputGenerator"
linktitle: "HtmlDiffOutputGenerator"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk menghasilkan representasi html dari perbedaan teks. Pemutusan baris yang dihapus ditandai dengan - tanda paragraf."
type: docs
weight: 10
url: /id/java/com.aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.HtmlDiffOutputGenerator

**All Implemented Interfaces:**
IFileOutputGenerator, IStringOutputGenerator

```
public class HtmlDiffOutputGenerator extends Object implements IStringOutputGenerator , IFileOutputGenerator
```

Mewakili kelas untuk menghasilkan representasi html dari perbedaan teks. Pemutusan baris yang dihapus ditandai dengan - tanda paragraf.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator--) | Membuat sebuah instance dari kelas {@link HtmlDiffOutputGenerator}. |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-) | Membuat sebuah instance dari kelas {@link HtmlDiffOutputGenerator}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [generateOutput](#generateOutput-java.util.List-) | Menghasilkan output berdasarkan perbedaan antar teks dan menyimpannya ke sebuah file. |
| [generateOutput](#generateOutput-java.util.List-java.lang.String-) | Menghasilkan output berdasarkan perbedaan antar teks dan menyimpannya ke sebuah file. |
| [generateOutput1](#generateOutput1-java.util.List-) | Menghasilkan output berdasarkan perbedaan antar teks dan menyimpannya ke sebuah file. |
| [generateOutput1](#generateOutput1-java.util.List-java.lang.String-) | Menghasilkan output berdasarkan perbedaan antar teks dan menyimpannya ke sebuah file. |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-) |  |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-) | Metode internal |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [getDeleteStyle](#getDeleteStyle--) | Mendapatkan dan mengatur string bergaya CSS untuk operasi Delete. Contoh: color: #003300; background-color: #ccff66; |
| [getEqualStyle](#getEqualStyle--) | Mendapatkan dan mengatur string bergaya CSS untuk operasi Equal. Contoh: color: #003300; background-color: #ccff66; |
| [getInsertStyle](#getInsertStyle--) | Mendapatkan dan mengatur string bergaya CSS untuk operasi Insert. Contoh: color: #003300; background-color: #ccff66; |
| [getStrikethroughDeleted](#getStrikethroughDeleted--) | Dapatkan atau atur gaya text-decoration: line-through untuk operasi delete. Nilai default adalah {@code False}. |
| [setDeleteStyle](#setDeleteStyle-java.lang.String-) | Mendapatkan dan mengatur string bergaya CSS untuk operasi Delete. Contoh: color: #003300; background-color: #ccff66; |
| [setEqualStyle](#setEqualStyle-java.lang.String-) | Mendapatkan dan mengatur string bergaya CSS untuk operasi Equal. Contoh: color: #003300; background-color: #ccff66; |
| [setInsertStyle](#setInsertStyle-java.lang.String-) | Mendapatkan dan mengatur string bergaya CSS untuk operasi Insert. Contoh: color: #003300; background-color: #ccff66; |
| [setStrikethroughDeleted](#setStrikethroughDeleted-boolean-) | Dapatkan atau atur gaya text-decoration: line-through untuk operasi delete. Nilai default adalah {@code False}. |

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator--}
```
public HtmlDiffOutputGenerator()
```

Membuat sebuah instance dari kelas {@link HtmlDiffOutputGenerator}.

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-}
Membuat sebuah instance dari kelas {@link HtmlDiffOutputGenerator}.

### generateOutput {#generateOutput-java.util.List-}
Menghasilkan output berdasarkan perbedaan antar teks dan menyimpannya ke sebuah file.

### generateOutput {#generateOutput-java.util.List-java.lang.String-}
Menghasilkan output berdasarkan perbedaan antar teks dan menyimpannya ke sebuah file.

### generateOutput1 {#generateOutput1-java.util.List-}
Menghasilkan output berdasarkan perbedaan antar teks dan menyimpannya ke sebuah file.

### generateOutput1 {#generateOutput1-java.util.List-java.lang.String-}
Menghasilkan output berdasarkan perbedaan antar teks dan menyimpannya ke sebuah file.

### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-}


### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-}
Metode internal

### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### getDeleteStyle {#getDeleteStyle--}
```
public final String getDeleteStyle()
```

Mendapatkan dan mengatur string bergaya CSS untuk operasi Delete. Contoh: color: #003300; background-color: #ccff66;

**Returns:**
nilai String

### getEqualStyle {#getEqualStyle--}
```
public final String getEqualStyle()
```

Mendapatkan dan mengatur string bergaya CSS untuk operasi Equal. Contoh: color: #003300; background-color: #ccff66;

**Returns:**
nilai String

### getInsertStyle {#getInsertStyle--}
```
public final String getInsertStyle()
```

Mendapatkan dan mengatur string bergaya CSS untuk operasi Insert. Contoh: color: #003300; background-color: #ccff66;

**Returns:**
nilai String

### getStrikethroughDeleted {#getStrikethroughDeleted--}
```
public final boolean getStrikethroughDeleted()
```

Dapatkan atau atur gaya text-decoration: line-through untuk operasi delete. Nilai default adalah {@code False}.

**Returns:**
nilai boolean

### setDeleteStyle {#setDeleteStyle-java.lang.String-}
Mendapatkan dan mengatur string bergaya CSS untuk operasi Delete. Contoh: color: #003300; background-color: #ccff66;

### setEqualStyle {#setEqualStyle-java.lang.String-}
Mendapatkan dan mengatur string bergaya CSS untuk operasi Equal. Contoh: color: #003300; background-color: #ccff66;

### setInsertStyle {#setInsertStyle-java.lang.String-}
Mendapatkan dan mengatur string bergaya CSS untuk operasi Insert. Contoh: color: #003300; background-color: #ccff66;

### setStrikethroughDeleted {#setStrikethroughDeleted-boolean-}
```
public final void setStrikethroughDeleted(boolean value)
```

Dapatkan atau atur gaya text-decoration: line-through untuk operasi delete. Nilai default adalah {@code False}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
