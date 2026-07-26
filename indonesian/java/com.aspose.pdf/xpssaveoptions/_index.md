---
title: "XpsSaveOptions"
linktitle: "XpsSaveOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Opsi penyimpanan untuk ekspor ke format Xps"
type: docs
weight: 5770
url: /id/java/com.aspose.pdf/xpssaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.XpsSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class XpsSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Opsi penyimpanan untuk ekspor ke format Xps

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XpsSaveOptions](#XpsSaveOptions--) | Konstruktor |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan. |
| [getDefaultFont](#getDefaultFont--) | Mendapatkan/mengatur nama font default. Digunakan jika nama font yang disematkan tidak ditemukan di sistem. |
| [getSaveTransparentTexts](#getSaveTransparentTexts--) | Menunjukkan apakah harus mempertahankan teks transparan (OCR'ed). |
| [getUseEmbeddedTrueTypeFonts](#getUseEmbeddedTrueTypeFonts--) | Mendapatkan/mengatur flag untuk menggunakan font TrueType yang disematkan. Menghindari penggunaan font TrueType yang disematkan dapat mengurangi waktu konversi. |
| [isUseNewImagingEngine](#isUseNewImagingEngine--) | Mendapatkan atau mengatur opsi UseNewImagingEngine. |
| [setBatchSize](#setBatchSize-int-) | Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan. |
| [setDefaultFont](#setDefaultFont-java.lang.String-) | Mendapatkan/mengatur nama font default. Digunakan jika nama font yang disematkan tidak ditemukan di sistem. |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Menunjukkan apakah harus mempertahankan teks transparan (OCR'ed). |
| [setUseEmbeddedTrueTypeFonts](#setUseEmbeddedTrueTypeFonts-boolean-) | Mendapatkan/mengatur flag untuk menggunakan font TrueType yang disematkan. Menghindari penggunaan font TrueType yang disematkan dapat mengurangi waktu konversi. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Mendapatkan atau mengatur opsi UseNewImagingEngine. |

### XpsSaveOptions {#XpsSaveOptions--}
```
public XpsSaveOptions()
```

Konstruktor

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan.

**Returns:**
nilai int

### getDefaultFont {#getDefaultFont--}
```
public final String getDefaultFont()
```

Mendapatkan/mengatur nama font default. Digunakan jika nama font yang disematkan tidak ditemukan di sistem.

**Returns:**
nilai String

### getSaveTransparentTexts {#getSaveTransparentTexts--}
```
public final boolean getSaveTransparentTexts()
```

Menunjukkan apakah harus mempertahankan teks transparan (OCR'ed).

**Returns:**
nilai boolean

### getUseEmbeddedTrueTypeFonts {#getUseEmbeddedTrueTypeFonts--}
```
public final boolean getUseEmbeddedTrueTypeFonts()
```

Mendapatkan/mengatur flag untuk menggunakan font TrueType yang disematkan. Menghindari penggunaan font TrueType yang disematkan dapat mengurangi waktu konversi.

**Returns:**
nilai boolean

### isUseNewImagingEngine {#isUseNewImagingEngine--}
```
@Deprecated public final boolean isUseNewImagingEngine()
```

Mendapatkan atau mengatur opsi UseNewImagingEngine.

**Returns:**
nilai boolean @deprecated UseNewImagingEngine sudah tidak dipakai lagi

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Mendefinisikan ukuran batch jika konversi berkelompok berlaku untuk pasangan format sumber dan tujuan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setDefaultFont {#setDefaultFont-java.lang.String-}
Mendapatkan/mengatur nama font default. Digunakan jika nama font yang disematkan tidak ditemukan di sistem.

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public final void setSaveTransparentTexts(boolean value)
```

Menunjukkan apakah harus mempertahankan teks transparan (OCR'ed).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setUseEmbeddedTrueTypeFonts {#setUseEmbeddedTrueTypeFonts-boolean-}
```
public final void setUseEmbeddedTrueTypeFonts(boolean value)
```

Mendapatkan/mengatur flag untuk menggunakan font TrueType yang disematkan. Menghindari penggunaan font TrueType yang disematkan dapat mengurangi waktu konversi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public final void setUseNewImagingEngine(boolean value)
```

Mendapatkan atau mengatur opsi UseNewImagingEngine.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean @deprecated UseNewImagingEngine sudah tidak dipakai lagi |
