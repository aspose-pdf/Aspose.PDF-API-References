---
title: "XslFoLoadOptions"
linktitle: "XslFoLoadOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili opsi untuk memuat/mengimpor file XSL-FO ke dalam dokumen pdf."
type: docs
weight: 5780
url: /id/java/com.aspose.pdf/xslfoloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.XmlLoadOptions, com.aspose.pdf.XslFoLoadOptions

```
public final class XslFoLoadOptions extends XmlLoadOptions
```

Mewakili opsi untuk memuat/mengimpor file XSL-FO ke dalam dokumen pdf.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XslFoLoadOptions](#XslFoLoadOptions--) | Membuat objek {@code XslFoLoadOptions} tanpa data xsl. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.io.InputStream-) | Membuat objek {@code XslFoLoadOptions} tanpa data xsl. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.lang.String-) | Membuat objek {@code XslFoLoadOptions} tanpa data xsl. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBasePath](#getBasePath--) | Jalur dasar/url dari mana jalur relatif ke sumber eksternal (jika ada) yang direferensikan dalam file SVG yang dimuat dicari. |
| [getParsingErrorsHandlingType](#getParsingErrorsHandlingType--) | Dokumen XSLFO sumber dapat berisi kesalahan pemformatan. Enum ini menguraikan strategi yang mungkin untuk menangani kesalahan tersebut. |
| [setBasePath](#setBasePath-java.lang.String-) |  |
| [setParsingErrorsHandlingType](#setParsingErrorsHandlingType-int-) | Dokumen XSLFO sumber dapat berisi kesalahan pemformatan. Enum ini menguraikan strategi yang mungkin untuk menangani kesalahan tersebut. |

### XslFoLoadOptions {#XslFoLoadOptions--}
```
public XslFoLoadOptions()
```

Membuat objek {@code XslFoLoadOptions} tanpa data xsl.

### XslFoLoadOptions {#XslFoLoadOptions-java.io.InputStream-}
Membuat objek {@code XslFoLoadOptions} tanpa data xsl.

### XslFoLoadOptions {#XslFoLoadOptions-java.lang.String-}
Membuat objek {@code XslFoLoadOptions} tanpa data xsl.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

Jalur dasar/url dari mana jalur relatif ke sumber eksternal (jika ada) yang direferensikan dalam file SVG yang dimuat dicari.

**Returns:**
String

### getParsingErrorsHandlingType {#getParsingErrorsHandlingType--}
```
public int getParsingErrorsHandlingType()
```

Dokumen XSLFO sumber dapat berisi kesalahan pemformatan. Enum ini menguraikan strategi yang mungkin untuk menangani kesalahan tersebut.

**Returns:**
Elemen ParsingErrorsHandlingTypes @see ParsingErrorsHandlingTypes

### setBasePath {#setBasePath-java.lang.String-}


### setParsingErrorsHandlingType {#setParsingErrorsHandlingType-int-}
```
public void setParsingErrorsHandlingType(int parsingErrorsHandlingType)
```

Dokumen XSLFO sumber dapat berisi kesalahan pemformatan. Enum ini menguraikan strategi yang mungkin untuk menangani kesalahan tersebut.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parsingErrorsHandlingType |  | Elemen ParsingErrorsHandlingTypes @see ParsingErrorsHandlingTypes |
