---
title: "RenderingOptions"
linktitle: "RenderingOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Renderleme seçeneklerini temsil eder."
type: docs
weight: 4150
url: /tr/java/com.aspose.pdf/renderingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.RenderingOptions

```
public final class RenderingOptions extends Object
```

Renderleme seçeneklerini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RenderingOptions](#RenderingOptions--) | Yeni bir {@code RenderingOptions} nesnesinin örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAnalyzeFonts](#getAnalyzeFonts--) | Metindeki tüm karakterlerin görüntülenebilmesini sağlamak için gerektiğinde yazı tiplerini değiştirir. Yazı tipi ikame algoritması şu adımları izler: 1. Kullanıcı DefaultFontName özelliğini açıkça ayarlamışsa, belirtilen yazı tipinin istenen karakterleri görüntüleyip görüntüleyemediğini kontrol eder. 2. Kullanıcı tanımlı bir yazı tipi ayarlanmamışsa, {@code FontRepository.Sources} aracılığıyla eklenen yazı tipleri içinde arama yapar. 3. Metni analiz ederek alfabesini veya betiğini belirler ve buna göre yazı tipi adları önerir. Bu yazı tiplerini sistemde bulup kullanmayı dener. 4. Bir geri dönüş olarak, sistemde gerekli karakterleri görüntüleyebilen herhangi bir yazı tipini arar. |
| [getBarcodeOptimization](#getBarcodeOptimization--) | Barkod optimizasyon modunu alır. |
| [getConvertFontsToUnicodeTTF](#getConvertFontsToUnicodeTTF--) | Tüm yazı tiplerinin TTF unicode sürümlerine dönüştürüleceğini gösterir. Bu, uyumluluk nedenleriyle ve yazı tipi kullanımını optimize etmek için faydalıdır, çünkü her yeni TTF yazı tipi kaynak yazı tipindeki tüm sembolleri içermez, yalnızca metinde kullanılan sembolleri içerir. |
| [getDefaultFontName](#getDefaultFontName--) | Eksik yazı tiplerinin yerine kullanılan varsayılan yazı tipi adını alır/ayarlar. |
| [getHeightExtraUnits](#getHeightExtraUnits--) | AppendRectangle operatörü için dikdörtgenin genişliğini artırmak veya azaltmak amacıyla kullanılan bir değeri alır veya ayarlar. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Yazı tipi eksikliğiyle ilgili hataların göz ardı edilip edilmeyeceğini belirten değeri alır veya ayarlar. true - yazı tipi eksikliği hatalarının göz ardı edileceği anlamına gelir. Yanlış kaynaklara referans veren metin bölümleri işleme sırasında atlanır. varsayılan olarak false. |
| [getInterpolationHighQuality](#getInterpolationHighQuality--) | Ara değerleme için yüksek kalite modunu alır veya ayarlar. |
| [getMaxFontsCacheSize](#getMaxFontsCacheSize--) | Yazı tipleri önbelleğindeki maksimum yazı tipi sayısı. Varsayılan değer 10'dur. |
| [getMaxSymbolsCacheSize](#getMaxSymbolsCacheSize--) | Sembol önbelleğindeki maksimum sembol sayısı. Varsayılan değer 100'dür. |
| [getOptimizeDimensions](#getOptimizeDimensions--) | Boyutları optimize etme modunu alır veya ayarlar. |
| [getScaleImagesToFitPageWidth](#getScaleImagesToFitPageWidth--) | Sayfadaki tüm görüntüleri sayfanın genişliğine sığdırmak için ölçeklendiren bir değeri alır veya ayarlar. |
| [getSystemFontsNativeRendering](#getSystemFontsNativeRendering--) | Sistem yazı tiplerinin yerel olarak işlendiği bir modu alır. |
| [getUseFontHinting](#getUseFontHinting--) | Bu bayrağın kullanımı font ipucu (font hinting) mekanizmasını etkinleştirir. Font ipucu, bir kontur yazı tipinin görüntüsünü ayarlamak için matematiksel talimatların kullanılmasını ifade eder. Bazı durumlarda bu bayrağın açılması metin okunabilirliği sorunlarını çözebilir. Şu anda bu bayrağın kullanımı yalnızca kaynak belgede TTF yazı tipleri kullanılıyorsa etkili olabilir. |
| [getUseNewImagingEngine](#getUseNewImagingEngine--) | Yeni görüntü işleme motorunun kullanılıp kullanılmadığını belirleyen bir bayrağı alır. |
| [getWidthExtraUnits](#getWidthExtraUnits--) | AppendRectangle operatörü için dikdörtgenin genişliğini artırmak veya azaltmak amacıyla kullanılan bir değeri alır veya ayarlar. |
| [isTryToSkipDocumentErrors](#isTryToSkipDocumentErrors--) | PDF dosyası işlenirken hataları atlamak için kullanılan bir değeri alır. |
| [setAnalyzeFonts](#setAnalyzeFonts-boolean-) | Metindeki tüm karakterlerin görüntülenebilmesini sağlamak için gerektiğinde yazı tiplerini değiştirir. Yazı tipi ikame algoritması şu adımları izler: 1. Kullanıcı DefaultFontName özelliğini açıkça ayarlamışsa, belirtilen yazı tipinin istenen karakterleri görüntüleyip görüntüleyemediğini kontrol eder. 2. Kullanıcı tanımlı bir yazı tipi ayarlanmamışsa, {@code FontRepository.Sources} aracılığıyla eklenen yazı tipleri içinde arama yapar. 3. Metni analiz ederek alfabesini veya betiğini belirler ve buna göre yazı tipi adları önerir. Bu yazı tiplerini sistemde bulup kullanmayı dener. 4. Bir geri dönüş olarak, sistemde gerekli karakterleri görüntüleyebilen herhangi bir yazı tipini arar. |
| [setBarcodeOptimization](#setBarcodeOptimization-boolean-) | Barkod optimizasyon modunu ayarlar. |
| [setConvertFontsToUnicodeTTF](#setConvertFontsToUnicodeTTF-boolean-) | Tüm yazı tiplerinin TTF unicode sürümlerine dönüştürüleceğini gösterir. Bu, uyumluluk nedenleriyle ve yazı tipi kullanımını optimize etmek için faydalıdır, çünkü her yeni TTF yazı tipi kaynak yazı tipindeki tüm sembolleri içermez, yalnızca metinde kullanılan sembolleri içerir. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Eksik yazı tiplerinin yerine kullanılan varsayılan yazı tipi adını alır/ayarlar. |
| [setHeightExtraUnits](#setHeightExtraUnits-float-) | AppendRectangle operatörü için dikdörtgenin genişliğini artırmak veya azaltmak amacıyla kullanılan bir değeri alır veya ayarlar. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Yazı tipi eksikliğiyle ilgili hataların göz ardı edilip edilmeyeceğini belirten değeri alır veya ayarlar. true - yazı tipi eksikliği hatalarının göz ardı edileceği anlamına gelir. Yanlış kaynaklara referans veren metin bölümleri işleme sırasında atlanır. varsayılan olarak false. |
| [setInterpolationHighQuality](#setInterpolationHighQuality-boolean-) | Ara değerleme için yüksek kalite modunu alır veya ayarlar. |
| [setMaxFontsCacheSize](#setMaxFontsCacheSize-int-) | Yazı tipleri önbelleğindeki maksimum yazı tipi sayısı. Varsayılan değer 10'dur. |
| [setMaxSymbolsCacheSize](#setMaxSymbolsCacheSize-int-) | Sembol önbelleğindeki maksimum sembol sayısı. Varsayılan değer 100'dür. |
| [setOptimizeDimensions](#setOptimizeDimensions-boolean-) | Boyutları optimize etme modunu alır veya ayarlar. |
| [setScaleImagesToFitPageWidth](#setScaleImagesToFitPageWidth-boolean-) | Sayfadaki tüm görüntüleri sayfanın genişliğine sığdırmak için ölçeklendiren bir değeri alır veya ayarlar. |
| [setSystemFontsNativeRendering](#setSystemFontsNativeRendering-boolean-) | Sistem yazı tiplerinin yerel olarak işlendiği bir modu ayarlar. |
| [setTryToSkipDocumentErrors](#setTryToSkipDocumentErrors-boolean-) | PDF dosyası işlenirken hataları atlamak için kullanılan bir değeri ayarlar. |
| [setUseFontHinting](#setUseFontHinting-boolean-) | Bu bayrağın kullanımı font ipucu (font hinting) mekanizmasını etkinleştirir. Font ipucu, bir kontur yazı tipinin görüntüsünü ayarlamak için matematiksel talimatların kullanılmasını ifade eder. Bazı durumlarda bu bayrağın açılması metin okunabilirliği sorunlarını çözebilir. Şu anda bu bayrağın kullanımı yalnızca kaynak belgede TTF yazı tipleri kullanılıyorsa etkili olabilir. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | Yeni görüntü işleme motorunun kullanılıp kullanılmadığını belirleyen bir bayrağı ayarlar. |
| [setWidthExtraUnits](#setWidthExtraUnits-float-) | AppendRectangle operatörü için dikdörtgenin genişliğini artırmak veya azaltmak amacıyla kullanılan bir değeri alır veya ayarlar. |

### RenderingOptions {#RenderingOptions--}
```
public RenderingOptions()
```

Yeni bir {@code RenderingOptions} nesnesinin örneğini başlatır.

### getAnalyzeFonts {#getAnalyzeFonts--}
```
public final boolean getAnalyzeFonts()
```

Metindeki tüm karakterlerin görüntülenebilmesini sağlamak için gerektiğinde yazı tiplerini değiştirir. Yazı tipi ikame algoritması şu adımları izler: 1. Kullanıcı DefaultFontName özelliğini açıkça ayarlamışsa, belirtilen yazı tipinin istenen karakterleri görüntüleyip görüntüleyemediğini kontrol eder. 2. Kullanıcı tanımlı bir yazı tipi ayarlanmamışsa, {@code FontRepository.Sources} aracılığıyla eklenen yazı tipleri içinde arama yapar. 3. Metni analiz ederek alfabesini veya betiğini belirler ve buna göre yazı tipi adları önerir. Bu yazı tiplerini sistemde bulup kullanmayı dener. 4. Bir geri dönüş olarak, sistemde gerekli karakterleri görüntüleyebilen herhangi bir yazı tipini arar.

**Returns:**
boolean değer

### getBarcodeOptimization {#getBarcodeOptimization--}
```
public boolean getBarcodeOptimization()
```

Barkod optimizasyon modunu alır.

**Returns:**
boolean değer

### getConvertFontsToUnicodeTTF {#getConvertFontsToUnicodeTTF--}
```
public boolean getConvertFontsToUnicodeTTF()
```

Tüm yazı tiplerinin TTF unicode sürümlerine dönüştürüleceğini gösterir. Bu, uyumluluk nedenleriyle ve yazı tipi kullanımını optimize etmek için faydalıdır, çünkü her yeni TTF yazı tipi kaynak yazı tipindeki tüm sembolleri içermez, yalnızca metinde kullanılan sembolleri içerir.

**Returns:**
boolean değer

### getDefaultFontName {#getDefaultFontName--}
```
public final String getDefaultFontName()
```

Eksik yazı tiplerinin yerine kullanılan varsayılan yazı tipi adını alır/ayarlar.

**Returns:**
String değeri

### getHeightExtraUnits {#getHeightExtraUnits--}
```
public final float getHeightExtraUnits()
```

AppendRectangle operatörü için dikdörtgenin genişliğini artırmak veya azaltmak amacıyla kullanılan bir değeri alır veya ayarlar.

**Returns:**
float değer

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Yazı tipi eksikliğiyle ilgili hataların göz ardı edilip edilmeyeceğini belirten değeri alır veya ayarlar. true - yazı tipi eksikliği hatalarının göz ardı edileceği anlamına gelir. Yanlış kaynaklara referans veren metin bölümleri işleme sırasında atlanır. varsayılan olarak false.

**Returns:**
boolean değer

### getInterpolationHighQuality {#getInterpolationHighQuality--}
```
public boolean getInterpolationHighQuality()
```

Ara değerleme için yüksek kalite modunu alır veya ayarlar.

**Returns:**
boolean değer

### getMaxFontsCacheSize {#getMaxFontsCacheSize--}
```
public int getMaxFontsCacheSize()
```

Yazı tipleri önbelleğindeki maksimum yazı tipi sayısı. Varsayılan değer 10'dur.

**Returns:**
int değer

### getMaxSymbolsCacheSize {#getMaxSymbolsCacheSize--}
```
public int getMaxSymbolsCacheSize()
```

Sembol önbelleğindeki maksimum sembol sayısı. Varsayılan değer 100'dür.

**Returns:**
int değer

### getOptimizeDimensions {#getOptimizeDimensions--}
```
public final boolean getOptimizeDimensions()
```

Boyutları optimize etme modunu alır veya ayarlar.

**Returns:**
boolean değer

### getScaleImagesToFitPageWidth {#getScaleImagesToFitPageWidth--}
```
@Deprecated public final boolean getScaleImagesToFitPageWidth()
```

Sayfadaki tüm görüntüleri sayfanın genişliğine sığdırmak için ölçeklendiren bir değeri alır veya ayarlar.

**Returns:**
boolean değer @deprecated ScaleImagesToFitPageWidth artık kullanımdan kaldırılmıştır.

### getSystemFontsNativeRendering {#getSystemFontsNativeRendering--}
```
public boolean getSystemFontsNativeRendering()
```

Sistem yazı tiplerinin yerel olarak işlendiği bir modu alır.

**Returns:**
boolean değer

### getUseFontHinting {#getUseFontHinting--}
```
public boolean getUseFontHinting()
```

Bu bayrağın kullanımı font ipucu (font hinting) mekanizmasını etkinleştirir. Font ipucu, bir kontur yazı tipinin görüntüsünü ayarlamak için matematiksel talimatların kullanılmasını ifade eder. Bazı durumlarda bu bayrağın açılması metin okunabilirliği sorunlarını çözebilir. Şu anda bu bayrağın kullanımı yalnızca kaynak belgede TTF yazı tipleri kullanılıyorsa etkili olabilir.

**Returns:**
boolean değer

### getUseNewImagingEngine {#getUseNewImagingEngine--}
```
@Deprecated public boolean getUseNewImagingEngine()
```

Yeni görüntü işleme motorunun kullanılıp kullanılmadığını belirleyen bir bayrağı alır.

**Returns:**
boolean değer @deprecated UseNewImagingEngine artık kullanımdan kaldırılmıştır

### getWidthExtraUnits {#getWidthExtraUnits--}
```
public float getWidthExtraUnits()
```

AppendRectangle operatörü için dikdörtgenin genişliğini artırmak veya azaltmak amacıyla kullanılan bir değeri alır veya ayarlar.

**Returns:**
float değer

### isTryToSkipDocumentErrors {#isTryToSkipDocumentErrors--}
```
public boolean isTryToSkipDocumentErrors()
```

PDF dosyası işlenirken hataları atlamak için kullanılan bir değeri alır.

**Returns:**
boolean değer

### setAnalyzeFonts {#setAnalyzeFonts-boolean-}
```
public final void setAnalyzeFonts(boolean value)
```

Metindeki tüm karakterlerin görüntülenebilmesini sağlamak için gerektiğinde yazı tiplerini değiştirir. Yazı tipi ikame algoritması şu adımları izler: 1. Kullanıcı DefaultFontName özelliğini açıkça ayarlamışsa, belirtilen yazı tipinin istenen karakterleri görüntüleyip görüntüleyemediğini kontrol eder. 2. Kullanıcı tanımlı bir yazı tipi ayarlanmamışsa, {@code FontRepository.Sources} aracılığıyla eklenen yazı tipleri içinde arama yapar. 3. Metni analiz ederek alfabesini veya betiğini belirler ve buna göre yazı tipi adları önerir. Bu yazı tiplerini sistemde bulup kullanmayı dener. 4. Bir geri dönüş olarak, sistemde gerekli karakterleri görüntüleyebilen herhangi bir yazı tipini arar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setBarcodeOptimization {#setBarcodeOptimization-boolean-}
```
public void setBarcodeOptimization(boolean value)
```

Barkod optimizasyon modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setConvertFontsToUnicodeTTF {#setConvertFontsToUnicodeTTF-boolean-}
```
public void setConvertFontsToUnicodeTTF(boolean value)
```

Tüm yazı tiplerinin TTF unicode sürümlerine dönüştürüleceğini gösterir. Bu, uyumluluk nedenleriyle ve yazı tipi kullanımını optimize etmek için faydalıdır, çünkü her yeni TTF yazı tipi kaynak yazı tipindeki tüm sembolleri içermez, yalnızca metinde kullanılan sembolleri içerir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Eksik yazı tiplerinin yerine kullanılan varsayılan yazı tipi adını alır/ayarlar.

### setHeightExtraUnits {#setHeightExtraUnits-float-}
```
public final void setHeightExtraUnits(float value)
```

AppendRectangle operatörü için dikdörtgenin genişliğini artırmak veya azaltmak amacıyla kullanılan bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Yazı tipi eksikliğiyle ilgili hataların göz ardı edilip edilmeyeceğini belirten değeri alır veya ayarlar. true - yazı tipi eksikliği hatalarının göz ardı edileceği anlamına gelir. Yanlış kaynaklara referans veren metin bölümleri işleme sırasında atlanır. varsayılan olarak false.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setInterpolationHighQuality {#setInterpolationHighQuality-boolean-}
```
public void setInterpolationHighQuality(boolean value)
```

Ara değerleme için yüksek kalite modunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setMaxFontsCacheSize {#setMaxFontsCacheSize-int-}
```
public void setMaxFontsCacheSize(int value)
```

Yazı tipleri önbelleğindeki maksimum yazı tipi sayısı. Varsayılan değer 10'dur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setMaxSymbolsCacheSize {#setMaxSymbolsCacheSize-int-}
```
public void setMaxSymbolsCacheSize(int value)
```

Sembol önbelleğindeki maksimum sembol sayısı. Varsayılan değer 100'dür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setOptimizeDimensions {#setOptimizeDimensions-boolean-}
```
public final void setOptimizeDimensions(boolean value)
```

Boyutları optimize etme modunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setScaleImagesToFitPageWidth {#setScaleImagesToFitPageWidth-boolean-}
```
@Deprecated public final void setScaleImagesToFitPageWidth(boolean value)
```

Sayfadaki tüm görüntüleri sayfanın genişliğine sığdırmak için ölçeklendiren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer @deprecated ScaleImagesToFitPageWidth artık kullanımdan kaldırılmıştır. |

### setSystemFontsNativeRendering {#setSystemFontsNativeRendering-boolean-}
```
public void setSystemFontsNativeRendering(boolean value)
```

Sistem yazı tiplerinin yerel olarak işlendiği bir modu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setTryToSkipDocumentErrors {#setTryToSkipDocumentErrors-boolean-}
```
public void setTryToSkipDocumentErrors(boolean value)
```

PDF dosyası işlenirken hataları atlamak için kullanılan bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setUseFontHinting {#setUseFontHinting-boolean-}
```
public void setUseFontHinting(boolean value)
```

Bu bayrağın kullanımı font ipucu (font hinting) mekanizmasını etkinleştirir. Font ipucu, bir kontur yazı tipinin görüntüsünü ayarlamak için matematiksel talimatların kullanılmasını ifade eder. Bazı durumlarda bu bayrağın açılması metin okunabilirliği sorunlarını çözebilir. Şu anda bu bayrağın kullanımı yalnızca kaynak belgede TTF yazı tipleri kullanılıyorsa etkili olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public void setUseNewImagingEngine(boolean value)
```

Yeni görüntü işleme motorunun kullanılıp kullanılmadığını belirleyen bir bayrağı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer @deprecated UseNewImagingEngine artık kullanımdan kaldırılmıştır |

### setWidthExtraUnits {#setWidthExtraUnits-float-}
```
public void setWidthExtraUnits(float value)
```

AppendRectangle operatörü için dikdörtgenin genişliğini artırmak veya azaltmak amacıyla kullanılan bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |
