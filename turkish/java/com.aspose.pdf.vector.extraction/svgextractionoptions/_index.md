---
title: "SvgExtractionOptions"
linktitle: "SvgExtractionOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belge sayfasından vektör grafiklerini çıkarmak için bir seçenek sınıfını temsil eder."
type: docs
weight: 30
url: /tr/java/com.aspose.pdf.vector.extraction/svgextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SvgExtractionOptions

```
public class SvgExtractionOptions extends Object
```

PDF belge sayfasından vektör grafiklerini çıkarmak için bir seçenek sınıfını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SvgExtractionOptions](#SvgExtractionOptions--) | SvgExtractionOptions sınıfının bir örneğini oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAutoGrouping](#getAutoGrouping--) | Alt yolları otomatik olarak görüntülere gruplama seçeneğini alır ve ayarlar. Bu seçenek {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) seçeneğini hariç tutar. |
| [getExtractEverySubPathToSvg](#getExtractEverySubPathToSvg--) | PDF belgesindeki her alt yolu ayrı SVG görüntülerine çıkarmak için seçeneği alır ve ayarlar. |
| [getExtractionAreaBound](#getExtractionAreaBound--) | SVG çıkarma için çıkarma alanını tanımlayan sınırlayıcı dikdörtgeni alır ve ayarlar. |
| [getGroupStrength](#getGroupStrength--) | Alt yolları görüntülere gruplama gücünü belirleyen seçeneği alır ve ayarlar. Alt yolların gruplama derecesini yapılandırmanıza olanak tanır. Değer aralığı 0 ile 1 arasındadır. 0 değeri, {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) seçeneğinin etkin olmasına karşılık gelir. 1 değeri, sayfadaki tüm vektör yolları için tek bir görüntü oluşturur. Bu seçenek, {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) false olduğunda etkili olur. Varsayılan değer {@code 0.8}'tir. |
| [getMinStrokeWidth](#getMinStrokeWidth--) | Sonuç SVG'sinde kullanılacak minimum çizgi kalınlığını alır ve ayarlar. PDF daha ince bir çizgi kalınlığı kullanıyorsa, bu kalınlıkla değiştirilir. Varsayılan değer 0.5'tir. Değer, dönüştürülmüş PDF sayfasının kullanıcı uzayı birimlerinde ifade edilir. Varsayılan olarak 1 kullanıcı uzayı birimi 1/72 inç (0.35 mm) olur, ancak bu PDF belgesi tarafından değiştirilebilir. Dönüşümler, oluşturulan SVG'deki gerçek minimum genişliği etkileyebilir. |
| [getStrictExtractionAreaBoundCheck](#getStrictExtractionAreaBoundCheck--) | Alt yolların {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) içinde belirtilen dikdörtgen içinde olup olmadığını kesin olarak kontrol eden bir seçeneği alır ve ayarlar. False olarak ayarlanırsa, {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) içinde tamamen bulunmayan alt yollar da çıkarılır. Varsayılan değer {@code True}'tir. |
| [getUnpackPageContentXForm](#getUnpackPageContentXForm--) | Sayfalarda bulunan XFrom öğelerinin açılıp açılmayacağını belirleyen bir bayrağı alır ve ayarlar. XFrom öğeleri farklı SVG dosyalarına yerleşebilir. Sayfa içeriğindeki Do ifadeleriyle render edilen XForm'lar yalnızca açılır. İç içe XForm'lar açılmaz. |
| [getUnpackXFormPredicate](#getUnpackXFormPredicate--) | Belirtilen koşula karşılık gelen XForm'u yalnızca açmak için seçeneği alır ve ayarlar. |
| [setAutoGrouping](#setAutoGrouping-boolean-) | Alt yolları otomatik olarak görüntülere gruplama seçeneğini alır ve ayarlar. Bu seçenek {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) seçeneğini hariç tutar. |
| [setExtractEverySubPathToSvg](#setExtractEverySubPathToSvg-boolean-) | PDF belgesindeki her alt yolu ayrı SVG görüntülerine çıkarmak için seçeneği alır ve ayarlar. |
| [setExtractionAreaBound](#setExtractionAreaBound-com.aspose.pdf.Rectangle-) | SVG çıkarma için çıkarma alanını tanımlayan sınırlayıcı dikdörtgeni alır ve ayarlar. |
| [setGroupStrength](#setGroupStrength-double-) | Alt yolları görüntülere gruplama gücünü belirleyen seçeneği alır ve ayarlar. Alt yolların gruplama derecesini yapılandırmanıza olanak tanır. Değer aralığı 0 ile 1 arasındadır. 0 değeri, {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) seçeneğinin etkin olmasına karşılık gelir. 1 değeri, sayfadaki tüm vektör yolları için tek bir görüntü oluşturur. Bu seçenek, {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) false olduğunda etkili olur. Varsayılan değer {@code 0.8}'tir. |
| [setMinStrokeWidth](#setMinStrokeWidth-double-) | Sonuç SVG'sinde kullanılacak minimum çizgi kalınlığını alır ve ayarlar. PDF daha ince bir çizgi kalınlığı kullanıyorsa, bu kalınlıkla değiştirilir. Varsayılan değer 0.5'tir. Değer, dönüştürülmüş PDF sayfasının kullanıcı uzayı birimlerinde ifade edilir. Varsayılan olarak 1 kullanıcı uzayı birimi 1/72 inç (0.35 mm) olur, ancak bu PDF belgesi tarafından değiştirilebilir. Dönüşümler, oluşturulan SVG'deki gerçek minimum genişliği etkileyebilir. |
| [setStrictExtractionAreaBoundCheck](#setStrictExtractionAreaBoundCheck-boolean-) | Alt yolların {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) içinde belirtilen dikdörtgen içinde olup olmadığını kesin olarak kontrol eden bir seçeneği alır ve ayarlar. False olarak ayarlanırsa, {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) içinde tamamen bulunmayan alt yollar da çıkarılır. Varsayılan değer {@code True}'tir. |
| [setUnpackPageContentXForm](#setUnpackPageContentXForm-boolean-) | Sayfalarda bulunan XFrom öğelerinin açılıp açılmayacağını belirleyen bir bayrağı alır ve ayarlar. XFrom öğeleri farklı SVG dosyalarına yerleşebilir. Sayfa içeriğindeki Do ifadeleriyle render edilen XForm'lar yalnızca açılır. İç içe XForm'lar açılmaz. |
| [setUnpackXFormPredicate](#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-) | Belirtilen koşula karşılık gelen XForm'u yalnızca açmak için seçeneği alır ve ayarlar. |

### SvgExtractionOptions {#SvgExtractionOptions--}
```
public SvgExtractionOptions()
```

SvgExtractionOptions sınıfının bir örneğini oluşturur.

### getAutoGrouping {#getAutoGrouping--}
```
public final boolean getAutoGrouping()
```

Alt yolları otomatik olarak görüntülere gruplama seçeneğini alır ve ayarlar. Bu seçenek {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) seçeneğini hariç tutar.

**Returns:**
boolean değer

### getExtractEverySubPathToSvg {#getExtractEverySubPathToSvg--}
```
public final boolean getExtractEverySubPathToSvg()
```

PDF belgesindeki her alt yolu ayrı SVG görüntülerine çıkarmak için seçeneği alır ve ayarlar.

**Returns:**
boolean değer

### getExtractionAreaBound {#getExtractionAreaBound--}
```
public final Rectangle getExtractionAreaBound()
```

SVG çıkarma için çıkarma alanını tanımlayan sınırlayıcı dikdörtgeni alır ve ayarlar.

**Returns:**
Dikdörtgen örneği

### getGroupStrength {#getGroupStrength--}
```
public final double getGroupStrength()
```

Alt yolları görüntülere gruplama gücünü belirleyen seçeneği alır ve ayarlar. Alt yolların gruplama derecesini yapılandırmanıza olanak tanır. Değer aralığı 0 ile 1 arasındadır. 0 değeri, {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) seçeneğinin etkin olmasına karşılık gelir. 1 değeri, sayfadaki tüm vektör yolları için tek bir görüntü oluşturur. Bu seçenek, {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) false olduğunda etkili olur. Varsayılan değer {@code 0.8}'tir.

**Returns:**
double değer

### getMinStrokeWidth {#getMinStrokeWidth--}
```
public final double getMinStrokeWidth()
```

Sonuç SVG'sinde kullanılacak minimum çizgi kalınlığını alır ve ayarlar. PDF daha ince bir çizgi kalınlığı kullanıyorsa, bu kalınlıkla değiştirilir. Varsayılan değer 0.5'tir. Değer, dönüştürülmüş PDF sayfasının kullanıcı uzayı birimlerinde ifade edilir. Varsayılan olarak 1 kullanıcı uzayı birimi 1/72 inç (0.35 mm) olur, ancak bu PDF belgesi tarafından değiştirilebilir. Dönüşümler, oluşturulan SVG'deki gerçek minimum genişliği etkileyebilir.

**Returns:**
double değer

### getStrictExtractionAreaBoundCheck {#getStrictExtractionAreaBoundCheck--}
```
public final boolean getStrictExtractionAreaBoundCheck()
```

Alt yolların {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) içinde belirtilen dikdörtgen içinde olup olmadığını kesin olarak kontrol eden bir seçeneği alır ve ayarlar. False olarak ayarlanırsa, {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) içinde tamamen bulunmayan alt yollar da çıkarılır. Varsayılan değer {@code True}'tir.

**Returns:**
boolean değer

### getUnpackPageContentXForm {#getUnpackPageContentXForm--}
```
public final boolean getUnpackPageContentXForm()
```

Sayfalarda bulunan XFrom öğelerinin açılıp açılmayacağını belirleyen bir bayrağı alır ve ayarlar. XFrom öğeleri farklı SVG dosyalarına yerleşebilir. Sayfa içeriğindeki Do ifadeleriyle render edilen XForm'lar yalnızca açılır. İç içe XForm'lar açılmaz.

**Returns:**
boolean değer

### getUnpackXFormPredicate {#getUnpackXFormPredicate--}
```
public final com.aspose.ms.System.Predicate< XFormPlacement > getUnpackXFormPredicate()
```

Belirtilen koşula karşılık gelen XForm'u yalnızca açmak için seçeneği alır ve ayarlar.

**Returns:**
XFormPlacement örneğinin dahili Predicate örneği

### setAutoGrouping {#setAutoGrouping-boolean-}
```
public final void setAutoGrouping(boolean value)
```

Alt yolları otomatik olarak görüntülere gruplama seçeneğini alır ve ayarlar. Bu seçenek {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) seçeneğini hariç tutar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setExtractEverySubPathToSvg {#setExtractEverySubPathToSvg-boolean-}
```
public final void setExtractEverySubPathToSvg(boolean value)
```

PDF belgesindeki her alt yolu ayrı SVG görüntülerine çıkarmak için seçeneği alır ve ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setExtractionAreaBound {#setExtractionAreaBound-com.aspose.pdf.Rectangle-}
SVG çıkarma için çıkarma alanını tanımlayan sınırlayıcı dikdörtgeni alır ve ayarlar.

### setGroupStrength {#setGroupStrength-double-}
```
public final void setGroupStrength(double value)
```

Alt yolları görüntülere gruplama gücünü belirleyen seçeneği alır ve ayarlar. Alt yolların gruplama derecesini yapılandırmanıza olanak tanır. Değer aralığı 0 ile 1 arasındadır. 0 değeri, {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) seçeneğinin etkin olmasına karşılık gelir. 1 değeri, sayfadaki tüm vektör yolları için tek bir görüntü oluşturur. Bu seçenek, {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) false olduğunda etkili olur. Varsayılan değer {@code 0.8}'tir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setMinStrokeWidth {#setMinStrokeWidth-double-}
```
public final void setMinStrokeWidth(double value)
```

Sonuç SVG'sinde kullanılacak minimum çizgi kalınlığını alır ve ayarlar. PDF daha ince bir çizgi kalınlığı kullanıyorsa, bu kalınlıkla değiştirilir. Varsayılan değer 0.5'tir. Değer, dönüştürülmüş PDF sayfasının kullanıcı uzayı birimlerinde ifade edilir. Varsayılan olarak 1 kullanıcı uzayı birimi 1/72 inç (0.35 mm) olur, ancak bu PDF belgesi tarafından değiştirilebilir. Dönüşümler, oluşturulan SVG'deki gerçek minimum genişliği etkileyebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setStrictExtractionAreaBoundCheck {#setStrictExtractionAreaBoundCheck-boolean-}
```
public final void setStrictExtractionAreaBoundCheck(boolean value)
```

Alt yolların {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) içinde belirtilen dikdörtgen içinde olup olmadığını kesin olarak kontrol eden bir seçeneği alır ve ayarlar. False olarak ayarlanırsa, {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}) içinde tamamen bulunmayan alt yollar da çıkarılır. Varsayılan değer {@code True}'tir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setUnpackPageContentXForm {#setUnpackPageContentXForm-boolean-}
```
public final void setUnpackPageContentXForm(boolean value)
```

Sayfalarda bulunan XFrom öğelerinin açılıp açılmayacağını belirleyen bir bayrağı alır ve ayarlar. XFrom öğeleri farklı SVG dosyalarına yerleşebilir. Sayfa içeriğindeki Do ifadeleriyle render edilen XForm'lar yalnızca açılır. İç içe XForm'lar açılmaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setUnpackXFormPredicate {#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-}
Belirtilen koşula karşılık gelen XForm'u yalnızca açmak için seçeneği alır ve ayarlar.
