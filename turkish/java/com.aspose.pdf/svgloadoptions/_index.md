---
title: "SvgLoadOptions"
linktitle: "SvgLoadOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "SVG dosyasını PDF belgesine yükleme/ithal etme seçeneklerini temsil eder."
type: docs
weight: 4700
url: /tr/java/com.aspose.pdf/svgloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.SvgLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.SvgLoadOptions

```
public final class SvgLoadOptions extends LoadOptions
```

SVG dosyasını PDF belgesine yükleme/ithal etme seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SvgLoadOptions](#SvgLoadOptions--) | Oluşturur {@code SvgLoadOptions} nesnesi. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getConversionEngine](#getConversionEngine--) | Dönüşüm sırasında kullanılacak dönüşüm motorunun seçilmesine izin verir. Şu anda yeni motor B-test aşamasındadır, bu nedenle bu değer varsayılan olarak ConversionEngines.LegacyEngine olarak ayarlanır. |
| [getPageInfo](#getPageInfo--) | Belge yüklenirken uygulanması gereken sayfa bilgilerini alır. |
| [isAdjustPageSize](#isAdjustPageSize--) | PDF sayfa boyutunu SVG boyutuna ayarlar. |
| [setAdjustPageSize](#setAdjustPageSize-boolean-) | PDF sayfa boyutunu SVG boyutuna ayarlar. |
| [setConversionEngine](#setConversionEngine-int-) | Dönüşüm sırasında kullanılacak dönüşüm motorunun seçilmesine izin verir. Şu anda yeni motor B-test aşamasındadır, bu nedenle bu değer varsayılan olarak ConversionEngines.LegacyEngine olarak ayarlanır. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Belge yüklenirken uygulanması gereken sayfa bilgilerini ayarlar. |

### SvgLoadOptions {#SvgLoadOptions--}
```
public SvgLoadOptions()
```

Oluşturur {@code SvgLoadOptions} nesnesi.

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Dönüşüm sırasında kullanılacak dönüşüm motorunun seçilmesine izin verir. Şu anda yeni motor B-test aşamasındadır, bu nedenle bu değer varsayılan olarak ConversionEngines.LegacyEngine olarak ayarlanır.

**Returns:**
ConversionEngines öğesi @see ConversionEngines

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Belge yüklenirken uygulanması gereken sayfa bilgilerini alır.

**Returns:**
PageInfo nesnesi

### isAdjustPageSize {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```

PDF sayfa boyutunu SVG boyutuna ayarlar.

**Returns:**
boolean değer

### setAdjustPageSize {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```

PDF sayfa boyutunu SVG boyutuna ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Dönüşüm sırasında kullanılacak dönüşüm motorunun seçilmesine izin verir. Şu anda yeni motor B-test aşamasındadır, bu nedenle bu değer varsayılan olarak ConversionEngines.LegacyEngine olarak ayarlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| conversionEngine |  | ConversionEngines öğesi @see ConversionEngines |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Belge yüklenirken uygulanması gereken sayfa bilgilerini ayarlar.
