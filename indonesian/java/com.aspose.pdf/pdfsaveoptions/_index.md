---
title: "PdfSaveOptions"
linktitle: "PdfSaveOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Opsi penyimpanan untuk ekspor ke format Pdf"
type: docs
weight: 3790
url: /id/java/com.aspose.pdf/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.PdfSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.PdfSaveOptions

```
public class PdfSaveOptions extends SaveOptions
```

Opsi penyimpanan untuk ekspor ke format Pdf

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfSaveOptions](#PdfSaveOptions--) | Konstruktor |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDefaultFontName](#getDefaultFontName--) | Nama font yang digunakan secara default untuk font yang tidak ada di komputer. Ketika dokumen PDF yang disimpan ke PDF berisi font yang tidak tersedia di dokumen itu sendiri maupun di perangkat, API mengganti font tersebut dengan font default (jika font dengan {@code DefaultFontName} ditemukan di perangkat). |
| [getTempPath](#getTempPath--) | Jalur untuk file sementara. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Nama font yang digunakan secara default untuk font yang tidak ada di komputer. Ketika dokumen PDF yang disimpan ke PDF berisi font yang tidak tersedia di dokumen itu sendiri maupun di perangkat, API mengganti font tersebut dengan font default (jika font dengan {@code DefaultFontName} ditemukan di perangkat). |
| [setTempPath](#setTempPath-java.lang.String-) | Jalur untuk file sementara. |

### PdfSaveOptions {#PdfSaveOptions--}
```
public PdfSaveOptions()
```

Konstruktor

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Nama font yang digunakan secara default untuk font yang tidak ada di komputer. Ketika dokumen PDF yang disimpan ke PDF berisi font yang tidak tersedia di dokumen itu sendiri maupun di perangkat, API mengganti font tersebut dengan font default (jika font dengan {@code DefaultFontName} ditemukan di perangkat).

**Returns:**
nilai String

### getTempPath {#getTempPath--}
```
public final String getTempPath()
```

Jalur untuk file sementara.

**Returns:**
nilai String

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Nama font yang digunakan secara default untuk font yang tidak ada di komputer. Ketika dokumen PDF yang disimpan ke PDF berisi font yang tidak tersedia di dokumen itu sendiri maupun di perangkat, API mengganti font tersebut dengan font default (jika font dengan {@code DefaultFontName} ditemukan di perangkat).

### setTempPath {#setTempPath-java.lang.String-}
Jalur untuk file sementara.
