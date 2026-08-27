---
title: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
linktitle: "PdfFormatConversionOptions.PdfANonSpecificationFlags"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas ini menyimpan flag untuk mengontrol konversi PDF/A pada kasus ketika dokumen PDF sumber tidak sesuai dengan spesifikasi PDF. Jika flag dari kelas ini digunakan, itu akan berkurang."
type: docs
weight: 3740
url: /id/java/com.aspose.pdf/pdfformatconversionoptions.pdfanonspecificationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions.PdfANonSpecificationFlags

```
public static class PdfFormatConversionOptions.PdfANonSpecificationFlags extends Object
```

Kelas ini menyimpan flag untuk mengendalikan konversi PDF/A pada kasus ketika dokumen PDF sumber tidak sesuai dengan spesifikasi PDF. Jika flag kelas ini digunakan, kinerjanya menurun tetapi diperlukan ketika dokumen PDF sumber tidak dapat dikonversi ke format PDF/A dengan cara biasa. Secara default semua flag diatur ke false.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfANonSpecificationFlags](#PdfANonSpecificationFlags--) | Konstruktor |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCheckDifferentNamesInFontDictionaries](#getCheckDifferentNamesInFontDictionaries--) | Beberapa dokumen PDF berisi font yang memiliki nama berbeda dalam data internal. Penggunaan flag ini memberlakukan logika pemrosesan khusus untuk kasus ketika bidang BaseFont dan FontDescriptor.FontName berbeda. |
| [setCheckDifferentNamesInFontDictionaries](#setCheckDifferentNamesInFontDictionaries-boolean-) | Beberapa dokumen PDF berisi font yang memiliki nama berbeda dalam data internal. Penggunaan flag ini memberlakukan logika pemrosesan khusus untuk kasus ketika bidang BaseFont dan FontDescriptor.FontName berbeda. |

### PdfANonSpecificationFlags {#PdfANonSpecificationFlags--}
```
public PdfANonSpecificationFlags()
```

Konstruktor

### getCheckDifferentNamesInFontDictionaries {#getCheckDifferentNamesInFontDictionaries--}
```
public boolean getCheckDifferentNamesInFontDictionaries()
```

Beberapa dokumen PDF berisi font yang memiliki nama berbeda dalam data internal. Penggunaan flag ini memberlakukan logika pemrosesan khusus untuk kasus ketika bidang BaseFont dan FontDescriptor.FontName berbeda.

**Returns:**
nilai boolean

### setCheckDifferentNamesInFontDictionaries {#setCheckDifferentNamesInFontDictionaries-boolean-}
```
public void setCheckDifferentNamesInFontDictionaries(boolean value)
```

Beberapa dokumen PDF berisi font yang memiliki nama berbeda dalam data internal. Penggunaan flag ini memberlakukan logika pemrosesan khusus untuk kasus ketika bidang BaseFont dan FontDescriptor.FontName berbeda.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
