---
title: "SvgLoadOptions"
linktitle: "SvgLoadOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili opsi untuk memuat/mengimpor file SVG ke dalam dokumen pdf."
type: docs
weight: 4700
url: /id/java/com.aspose.pdf/svgloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.SvgLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.SvgLoadOptions

```
public final class SvgLoadOptions extends LoadOptions
```

Mewakili opsi untuk memuat/mengimpor file SVG ke dalam dokumen pdf.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SvgLoadOptions](#SvgLoadOptions--) | Membuat objek {@code SvgLoadOptions}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getConversionEngine](#getConversionEngine--) | Mengizinkan pemilihan mesin konversi yang akan digunakan selama konversi. Saat ini mesin baru berada dalam tahap B-testing, sehingga nilai ini secara default diatur ke ConversionEngines.LegacyEngine |
| [getPageInfo](#getPageInfo--) | Mendapatkan info halaman yang harus diterapkan selama pemuatan dokumen. |
| [isAdjustPageSize](#isAdjustPageSize--) | Sesuaikan ukuran halaman PDF ke ukuran SVG |
| [setAdjustPageSize](#setAdjustPageSize-boolean-) | Sesuaikan ukuran halaman PDF ke ukuran SVG |
| [setConversionEngine](#setConversionEngine-int-) | Mengizinkan pemilihan mesin konversi yang akan digunakan selama konversi. Saat ini mesin baru berada dalam tahap B-testing, sehingga nilai ini secara default diatur ke ConversionEngines.LegacyEngine |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Mengatur info halaman yang harus diterapkan selama pemuatan dokumen. |

### SvgLoadOptions {#SvgLoadOptions--}
```
public SvgLoadOptions()
```

Membuat objek {@code SvgLoadOptions}.

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Mengizinkan pemilihan mesin konversi yang akan digunakan selama konversi. Saat ini mesin baru berada dalam tahap B-testing, sehingga nilai ini secara default diatur ke ConversionEngines.LegacyEngine

**Returns:**
Elemen ConversionEngines @see ConversionEngines

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Mendapatkan info halaman yang harus diterapkan selama pemuatan dokumen.

**Returns:**
objek PageInfo

### isAdjustPageSize {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```

Sesuaikan ukuran halaman PDF ke ukuran SVG

**Returns:**
nilai boolean

### setAdjustPageSize {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```

Sesuaikan ukuran halaman PDF ke ukuran SVG

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Mengizinkan pemilihan mesin konversi yang akan digunakan selama konversi. Saat ini mesin baru berada dalam tahap B-testing, sehingga nilai ini secara default diatur ke ConversionEngines.LegacyEngine

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| conversionEngine |  | Elemen ConversionEngines @see ConversionEngines |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Mengatur info halaman yang harus diterapkan selama pemuatan dokumen.
