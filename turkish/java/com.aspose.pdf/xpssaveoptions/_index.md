---
title: "XpsSaveOptions"
linktitle: "XpsSaveOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Xps formatına dışa aktarma için kaydetme seçenekleri"
type: docs
weight: 5770
url: /tr/java/com.aspose.pdf/xpssaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.XpsSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class XpsSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

Xps formatına dışa aktarma için kaydetme seçenekleri

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XpsSaveOptions](#XpsSaveOptions--) | Yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar. |
| [getDefaultFont](#getDefaultFont--) | Varsayılan yazı tipi adını alır/ayarlar. Gömülü yazı tipi adı sistemde bulunamazsa kullanılır. |
| [getSaveTransparentTexts](#getSaveTransparentTexts--) | Şeffaf (OCR'lenmiş) metnin korunup korunmayacağını gösterir. |
| [getUseEmbeddedTrueTypeFonts](#getUseEmbeddedTrueTypeFonts--) | Gömülü TrueType yazı tiplerini kullanma bayrağını alır/ayarlar. Gömülü TrueType yazı tiplerinin kullanımından kaçınmak dönüşüm süresini azaltabilir. |
| [isUseNewImagingEngine](#isUseNewImagingEngine--) | UseNewImagingEngine seçeneğini alır veya ayarlar. |
| [setBatchSize](#setBatchSize-int-) | Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar. |
| [setDefaultFont](#setDefaultFont-java.lang.String-) | Varsayılan yazı tipi adını alır/ayarlar. Gömülü yazı tipi adı sistemde bulunamazsa kullanılır. |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Şeffaf (OCR'lenmiş) metnin korunup korunmayacağını gösterir. |
| [setUseEmbeddedTrueTypeFonts](#setUseEmbeddedTrueTypeFonts-boolean-) | Gömülü TrueType yazı tiplerini kullanma bayrağını alır/ayarlar. Gömülü TrueType yazı tiplerinin kullanımından kaçınmak dönüşüm süresini azaltabilir. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | UseNewImagingEngine seçeneğini alır veya ayarlar. |

### XpsSaveOptions {#XpsSaveOptions--}
```
public XpsSaveOptions()
```

Yapıcı

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar.

**Returns:**
int değer

### getDefaultFont {#getDefaultFont--}
```
public final String getDefaultFont()
```

Varsayılan yazı tipi adını alır/ayarlar. Gömülü yazı tipi adı sistemde bulunamazsa kullanılır.

**Returns:**
String değeri

### getSaveTransparentTexts {#getSaveTransparentTexts--}
```
public final boolean getSaveTransparentTexts()
```

Şeffaf (OCR'lenmiş) metnin korunup korunmayacağını gösterir.

**Returns:**
boolean değer

### getUseEmbeddedTrueTypeFonts {#getUseEmbeddedTrueTypeFonts--}
```
public final boolean getUseEmbeddedTrueTypeFonts()
```

Gömülü TrueType yazı tiplerini kullanma bayrağını alır/ayarlar. Gömülü TrueType yazı tiplerinin kullanımından kaçınmak dönüşüm süresini azaltabilir.

**Returns:**
boolean değer

### isUseNewImagingEngine {#isUseNewImagingEngine--}
```
@Deprecated public final boolean isUseNewImagingEngine()
```

UseNewImagingEngine seçeneğini alır veya ayarlar.

**Returns:**
boolean değer @deprecated UseNewImagingEngine artık kullanımdan kaldırılmıştır

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Kaynak ve hedef format çifti için toplu dönüşüm uygulanabilir ise toplu iş boyutunu tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setDefaultFont {#setDefaultFont-java.lang.String-}
Varsayılan yazı tipi adını alır/ayarlar. Gömülü yazı tipi adı sistemde bulunamazsa kullanılır.

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public final void setSaveTransparentTexts(boolean value)
```

Şeffaf (OCR'lenmiş) metnin korunup korunmayacağını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setUseEmbeddedTrueTypeFonts {#setUseEmbeddedTrueTypeFonts-boolean-}
```
public final void setUseEmbeddedTrueTypeFonts(boolean value)
```

Gömülü TrueType yazı tiplerini kullanma bayrağını alır/ayarlar. Gömülü TrueType yazı tiplerinin kullanımından kaçınmak dönüşüm süresini azaltabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public final void setUseNewImagingEngine(boolean value)
```

UseNewImagingEngine seçeneğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer @deprecated UseNewImagingEngine artık kullanımdan kaldırılmıştır |
