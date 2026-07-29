---
title: "TiffSettings"
linktitle: "TiffSettings"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bu sınıf, pdf'yi Tiff'e aktarmak için ayarları temsil eder."
type: docs
weight: 220
url: /tr/java/com.aspose.pdf.devices/tiffsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.TiffSettings

```
public final class TiffSettings extends Object
```

Bu sınıf, pdf'yi Tiff'e aktarmak için ayarları temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffSettings](#TiffSettings--) |  {@code TiffSettings} sınıfının yeni bir örneğini başlatır. |
| [TiffSettings](#TiffSettings-boolean-) |  {@code TiffSettings} sınıfının yeni bir örneğini başlatır. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.ColorDepth-) |  {@code TiffSettings} sınıfının yeni bir örneğini başlatır. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-) |  {@code TiffSettings} sınıfının yeni bir örneğini başlatır. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-) |  {@code TiffSettings} sınıfının yeni bir örneğini başlatır. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-) |  {@code TiffSettings} sınıfının yeni bir örneğini başlatır. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-) |  {@code TiffSettings} sınıfının yeni bir örneğini başlatır. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.Margins-) |  {@code TiffSettings} sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBrightness](#getBrightness--) | Beyaz ve siyah renk dönüşümünün değer sınırını al. Bu parametre EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle veya ColorDepth.Format1bpp == 1 ile uygulanabilir. |
| [getCompression](#getCompression--) | <p> Sıkıştırmanın türünü alır. </p> Değer: Sıkıştırmanın türü. <hr> <p> Varsayılan değer CompressionType.LZW </p> |
| [getCoordinateType](#getCoordinateType--) | Sayfa koordinat tipini alır (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır. |
| [getDepth](#getDepth--) | <p> Renk derinliğini alır. </p> Değer: Renk derinliği. <hr> <p> Varsayılan değer ColorDepth.Default </p> |
| [getIndexedConversionType](#getIndexedConversionType--) | IndexedConversionType değerini alır. Varsayılan değer Simple. |
| [getMargins](#getMargins--) | Kenar boşluklarını alır. |
| [getShape](#getShape--) | <p> Şeklin türünü alır. </p> Değer: Şeklin türü. <hr> <p> Varsayılan değer ShapeType.None </p> |
| [getSkipBlankPages](#getSkipBlankPages--) | <p> Boş sayfaları atlayıp atlamayacağını belirten bir değeri alır. </p> Değer: Boş sayfaları atlamak gerekiyorsa {@code true}; aksi takdirde {@code false}. <hr> <p> Varsayılan değer false </p> |
| [isUseAlternativeImageEngine](#isUseAlternativeImageEngine--) | Alternatif görüntüleme motorunun kullanılıp kullanılmadığını belirleyen bir bayrağı alır. Linux OS için varsayılan olarak true değeri kullanılır. Windows OS için varsayılan değer false'tur. |
| [setBrightness](#setBrightness-float-) | Beyaz ve siyah renk dönüşümünün değer sınırını ayarlar. Bu parametre EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle veya ColorDepth.Format1bpp == 1 ile uygulanabilir. |
| [setCompression](#setCompression-com.aspose.pdf.devices.CompressionType-) | <p> Sıkıştırmanın türünü ayarlar. </p> Değer: Sıkıştırmanın türü. <hr> <p> Varsayılan değer CompressionType.LZW </p> |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Sayfa koordinat tipini ayarlar (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır. |
| [setDepth](#setDepth-com.aspose.pdf.devices.ColorDepth-) | <p> Renk derinliğini alır. </p> Değer: Renk derinliği. <hr> <p> Varsayılan değer ColorDepth.Default </p> |
| [setIndexedConversionType](#setIndexedConversionType-int-) | IndexedConversionType değerini ayarlar. |
| [setShape](#setShape-com.aspose.pdf.devices.ShapeType-) | <p> Şeklin tipini ayarlar. </p> Değer: Şeklin tipi. <hr> <p> Varsayılan değer ShapeType.None </p> |
| [setSkipBlankPages](#setSkipBlankPages-boolean-) | <p> Boş sayfaları atlayıp atlamayacağını gösteren bir değer ayarlar. </p> Değer: {@code true} boş sayfaları atlamak gerekiyorsa; aksi takdirde, {@code false}. <hr> <p> Varsayılan değer false </p> |
| [setUseAlternativeImageEngine](#setUseAlternativeImageEngine-boolean-) | Alternatif görüntüleme motorunun kullanılıp kullanılmayacağını belirleyen bir bayrak ayarlar. |

### TiffSettings {#TiffSettings--}
```
public TiffSettings()
```

 {@code TiffSettings} sınıfının yeni bir örneğini başlatır.

### TiffSettings {#TiffSettings-boolean-}
```
public TiffSettings(boolean skipBlankPages)
```

 {@code TiffSettings} sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| skipBlankPages |  | eğer {@code true} olarak ayarlanırsa [boş sayfaları atla]. |

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.ColorDepth-}
 {@code TiffSettings} sınıfının yeni bir örneğini başlatır.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-}
 {@code TiffSettings} sınıfının yeni bir örneğini başlatır.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-}
 {@code TiffSettings} sınıfının yeni bir örneğini başlatır.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-}
 {@code TiffSettings} sınıfının yeni bir örneğini başlatır.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-}
 {@code TiffSettings} sınıfının yeni bir örneğini başlatır.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.Margins-}
 {@code TiffSettings} sınıfının yeni bir örneğini başlatır.

### getBrightness {#getBrightness--}
```
public float getBrightness()
```

Beyaz ve siyah renk dönüşümünün değer sınırını al. Bu parametre EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle veya ColorDepth.Format1bpp == 1 ile uygulanabilir.

**Returns:**
parlaklık için kayan nokta değeri 0 ile 1 arasında olmalıdır. Varsayılan değer 0.33f'ye eşittir.

### getCompression {#getCompression--}
```
public CompressionType getCompression()
```

<p> Sıkıştırmanın türünü alır. </p> Değer: Sıkıştırmanın türü. <hr> <p> Varsayılan değer CompressionType.LZW </p>

**Returns:**
CompressionType öğesi @see CompressionType

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Sayfa koordinat tipini alır (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır.

**Returns:**
PageCoordinateType değeri @see PageCoordinateType

### getDepth {#getDepth--}
```
public ColorDepth getDepth()
```

<p> Renk derinliğini alır. </p> Değer: Renk derinliği. <hr> <p> Varsayılan değer ColorDepth.Default </p>

**Returns:**
ColorDepth öğesi @see ColorDepth

### getIndexedConversionType {#getIndexedConversionType--}
```
public int getIndexedConversionType()
```

IndexedConversionType değerini alır. Varsayılan değer Simple.

**Returns:**
IndexedConversionType öğesi @see IndexedConversionType

### getMargins {#getMargins--}
```
public Margins getMargins()
```

Kenar boşluklarını alır.

**Returns:**
Margins nesnesi

### getShape {#getShape--}
```
public ShapeType getShape()
```

<p> Şeklin türünü alır. </p> Değer: Şeklin türü. <hr> <p> Varsayılan değer ShapeType.None </p>

**Returns:**
ShapeType öğesi @see ShapeType

### getSkipBlankPages {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```

<p> Boş sayfaları atlayıp atlamayacağını belirten bir değeri alır. </p> Değer: Boş sayfaları atlamak gerekiyorsa {@code true}; aksi takdirde {@code false}. <hr> <p> Varsayılan değer false </p>

**Returns:**
boolean değer

### isUseAlternativeImageEngine {#isUseAlternativeImageEngine--}
```
public boolean isUseAlternativeImageEngine()
```

Alternatif görüntüleme motorunun kullanılıp kullanılmadığını belirleyen bir bayrağı alır. Linux OS için varsayılan olarak true değeri kullanılır. Windows OS için varsayılan değer false'tur.

**Returns:**
boolean değer

### setBrightness {#setBrightness-float-}
```
public void setBrightness(float value)
```

Beyaz ve siyah renk dönüşümünün değer sınırını ayarlar. Bu parametre EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle veya ColorDepth.Format1bpp == 1 ile uygulanabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | : Parlaklık değeri 0 ile 1 arasında olmalıdır. Varsayılan değer 0.33f'ye eşittir. |

### setCompression {#setCompression-com.aspose.pdf.devices.CompressionType-}
<p> Sıkıştırmanın türünü ayarlar. </p> Değer: Sıkıştırmanın türü. <hr> <p> Varsayılan değer CompressionType.LZW </p>

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Sayfa koordinat tipini ayarlar (Media/Crop kutuları). Varsayılan olarak CropBox değeri kullanılır.

### setDepth {#setDepth-com.aspose.pdf.devices.ColorDepth-}
<p> Renk derinliğini alır. </p> Değer: Renk derinliği. <hr> <p> Varsayılan değer ColorDepth.Default </p>

### setIndexedConversionType {#setIndexedConversionType-int-}
```
public void setIndexedConversionType(int value)
```

IndexedConversionType değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | IndexedConversionType öğesi @see IndexedConversionType |

### setShape {#setShape-com.aspose.pdf.devices.ShapeType-}
<p> Şeklin tipini ayarlar. </p> Değer: Şeklin tipi. <hr> <p> Varsayılan değer ShapeType.None </p>

### setSkipBlankPages {#setSkipBlankPages-boolean-}
```
public void setSkipBlankPages(boolean value)
```

<p> Boş sayfaları atlayıp atlamayacağını gösteren bir değer ayarlar. </p> Değer: {@code true} boş sayfaları atlamak gerekiyorsa; aksi takdirde, {@code false}. <hr> <p> Varsayılan değer false </p>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setUseAlternativeImageEngine {#setUseAlternativeImageEngine-boolean-}
```
public void setUseAlternativeImageEngine(boolean useAlternativeImageEngine)
```

Alternatif görüntüleme motorunun kullanılıp kullanılmayacağını belirleyen bir bayrak ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| useAlternativeImageEngine |  | boolean değer |
