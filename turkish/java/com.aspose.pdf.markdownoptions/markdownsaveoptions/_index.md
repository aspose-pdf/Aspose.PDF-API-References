---
title: "MarkdownSaveOptions"
linktitle: "MarkdownSaveOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Markdown formatında belge kaydetme seçeneği sınıfını temsil eder."
type: docs
weight: 60
url: /tr/java/com.aspose.pdf.markdownoptions/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.markdownoptions.MarkdownSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.markdownoptions.MarkdownSaveOptions

```
public class MarkdownSaveOptions extends UnifiedSaveOptions
```

Markdown formatında belge kaydetme seçeneği sınıfını temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MarkdownSaveOptions](#MarkdownSaveOptions--) | Bir belgeyi markdown formatında kaydetmek için bir örnek seçenek oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAreaToExtract](#getAreaToExtract--) | İçeriği markdown'a çıkarmak için bir dikdörtgen alanı alın veya ayarlayın. |
| [getEmphasisStyle](#getEmphasisStyle--) | Oluşturulan belge için vurgu stilini alır veya ayarlar. |
| [getExtractVectorGraphics](#getExtractVectorGraphics--) | Vektör grafiklerinin çıkarılıp çıkarılmayacağını belirten bir özelliği alır ve ayarlar. |
| [getHeadingLevels](#getHeadingLevels--) | FontSize tanıma başlık stratejisinde kullanılacak beklenen başlık seviyelerini tanımlar. Bu özellik değeri ayarlanırsa, belge yer imleri içeriyor olsa bile {@link HeadingRecognitionStrategy#Heuristic} başlık tanıma stratejisi, {@link HeadingRecognitionStrategy#Auto} stratejileri ayarlandığında seçilecektir. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | Başlık tanıma stratejisini alır veya ayarlar. |
| [getHeadingStyle](#getHeadingStyle--) | Oluşturulan belge için başlık stilini alır veya ayarlar. |
| [getLineBreakStyle](#getLineBreakStyle--) | Oluşturulan belge için satır sonu stilini alır veya ayarlar. |
| [getResourcesDirectoryName](#getResourcesDirectoryName--) | Görüntüler gibi belge kaynaklarını kaydetmek için dizin adını alır ve ayarlar. Değer belirtilmezse, görüntüler markdown dosyasının bulunduğu aynı dizine yazılacaktır. Bu bir yol değil, sadece bir isimdir! Bu dizin, kaydedilen markdown dosyasının bulunduğu dizinde otomatik olarak oluşturulacaktır. |
| [getResourcesDirectoryPath](#getResourcesDirectoryPath--) | Görüntüler gibi belge kaynaklarını kaydetmek için dizin adını alır ve ayarlar. Bu dizin, kaydedilen markdown dosyasının bulunduğu dizinde otomatik olarak oluşturulacaktır. |
| [getSubscriptAndSuperscriptConversion](#getSubscriptAndSuperscriptConversion--) | Alt ve üst simgeye dönüştürme iznini alır ve ayarlar. Bu değer varsayılan olarak doğrudur. |
| [getUseImageHtmlTag](#getUseImageHtmlTag--) | Metnin sol ve sağına görüntü eklemek için bir img etiketi kullanım iznini alır ve ayarlar. Bu durumda, markdown görüntüleyicide metin görüntünün etrafında kayacaktır. |
| [setAreaToExtract](#setAreaToExtract-com.aspose.pdf.Rectangle-) | İçeriği markdown'a çıkarmak için bir dikdörtgen alanı alın veya ayarlayın. |
| [setEmphasisStyle](#setEmphasisStyle-int-) | Oluşturulan belge için vurgu stilini alır veya ayarlar. |
| [setExtractVectorGraphics](#setExtractVectorGraphics-boolean-) | Vektör grafiklerinin çıkarılıp çıkarılmayacağını belirten bir özelliği alır ve ayarlar. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | FontSize tanıma başlık stratejisinde kullanılacak beklenen başlık seviyelerini tanımlar. Bu özellik değeri ayarlanırsa, belge yer imleri içeriyor olsa bile {@link HeadingRecognitionStrategy#Heuristic} başlık tanıma stratejisi, {@link HeadingRecognitionStrategy#Auto} stratejileri ayarlandığında seçilecektir. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | Başlık tanıma stratejisini alır veya ayarlar. |
| [setHeadingStyle](#setHeadingStyle-int-) | Oluşturulan belge için başlık stilini alır veya ayarlar. |
| [setLineBreakStyle](#setLineBreakStyle-int-) | Oluşturulan belge için satır sonu stilini alır veya ayarlar. |
| [setResourcesDirectoryName](#setResourcesDirectoryName-java.lang.String-) | Görüntüler gibi belge kaynaklarını kaydetmek için dizin adını alır ve ayarlar. Değer belirtilmezse, görüntüler markdown dosyasının bulunduğu aynı dizine yazılacaktır. Bu bir yol değil, sadece bir isimdir! Bu dizin, kaydedilen markdown dosyasının bulunduğu dizinde otomatik olarak oluşturulacaktır. |
| [setResourcesDirectoryPath](#setResourcesDirectoryPath-java.lang.String-) | Görüntüler gibi belge kaynaklarını kaydetmek için dizin adını alır ve ayarlar. Bu dizin, kaydedilen markdown dosyasının bulunduğu dizinde otomatik olarak oluşturulacaktır. |
| [setSubscriptAndSuperscriptConversion](#setSubscriptAndSuperscriptConversion-boolean-) | Alt ve üst simgeye dönüştürme iznini alır ve ayarlar. Bu değer varsayılan olarak doğrudur. |
| [setUseImageHtmlTag](#setUseImageHtmlTag-boolean-) | Metnin sol ve sağına görüntü eklemek için bir img etiketi kullanım iznini alır ve ayarlar. Bu durumda, markdown görüntüleyicide metin görüntünün etrafında kayacaktır. |

### MarkdownSaveOptions {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

Bir belgeyi markdown formatında kaydetmek için bir örnek seçenek oluşturur.

### getAreaToExtract {#getAreaToExtract--}
```
public final Rectangle getAreaToExtract()
```

İçeriği markdown'a çıkarmak için bir dikdörtgen alanı alın veya ayarlayın.

**Returns:**
Dikdörtgen örneği

### getEmphasisStyle {#getEmphasisStyle--}
```
public final int getEmphasisStyle()
```

Oluşturulan belge için vurgu stilini alır veya ayarlar.

**Returns:**
EmphasisStyle öğesi

### getExtractVectorGraphics {#getExtractVectorGraphics--}
```
public final boolean getExtractVectorGraphics()
```

Vektör grafiklerinin çıkarılıp çıkarılmayacağını belirten bir özelliği alır ve ayarlar.

**Returns:**
boolean değer

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

FontSize tanıma başlık stratejisinde kullanılacak beklenen başlık seviyelerini tanımlar. Bu özellik değeri ayarlanırsa, belge yer imleri içeriyor olsa bile {@link HeadingRecognitionStrategy#Heuristic} başlık tanıma stratejisi, {@link HeadingRecognitionStrategy#Auto} stratejileri ayarlandığında seçilecektir.

**Returns:**
HeadingLevels örneği

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

Başlık tanıma stratejisini alır veya ayarlar.

**Returns:**
HeadingRecognitionStrategy öğesi

### getHeadingStyle {#getHeadingStyle--}
```
public final int getHeadingStyle()
```

Oluşturulan belge için başlık stilini alır veya ayarlar.

**Returns:**
HeadingStyle öğesi

### getLineBreakStyle {#getLineBreakStyle--}
```
public final int getLineBreakStyle()
```

Oluşturulan belge için satır sonu stilini alır veya ayarlar.

**Returns:**
LineBreakStyle öğesi

### getResourcesDirectoryName {#getResourcesDirectoryName--}
```
public final String getResourcesDirectoryName()
```

Görüntüler gibi belge kaynaklarını kaydetmek için dizin adını alır ve ayarlar. Değer belirtilmezse, görüntüler markdown dosyasının bulunduğu aynı dizine yazılacaktır. Bu bir yol değil, sadece bir isimdir! Bu dizin, kaydedilen markdown dosyasının bulunduğu dizinde otomatik olarak oluşturulacaktır.

**Returns:**
String değeri

### getResourcesDirectoryPath {#getResourcesDirectoryPath--}
```
public final String getResourcesDirectoryPath()
```

Görüntüler gibi belge kaynaklarını kaydetmek için dizin adını alır ve ayarlar. Bu dizin, kaydedilen markdown dosyasının bulunduğu dizinde otomatik olarak oluşturulacaktır.

**Returns:**
String değeri

### getSubscriptAndSuperscriptConversion {#getSubscriptAndSuperscriptConversion--}
```
public final boolean getSubscriptAndSuperscriptConversion()
```

Alt ve üst simgeye dönüştürme iznini alır ve ayarlar. Bu değer varsayılan olarak doğrudur.

**Returns:**
boolean değer

### getUseImageHtmlTag {#getUseImageHtmlTag--}
```
public final boolean getUseImageHtmlTag()
```

Metnin sol ve sağına görüntü eklemek için bir img etiketi kullanım iznini alır ve ayarlar. Bu durumda, markdown görüntüleyicide metin görüntünün etrafında kayacaktır.

**Returns:**
boolean değer

### setAreaToExtract {#setAreaToExtract-com.aspose.pdf.Rectangle-}
İçeriği markdown'a çıkarmak için bir dikdörtgen alanı alın veya ayarlayın.

### setEmphasisStyle {#setEmphasisStyle-int-}
```
public final void setEmphasisStyle(int value)
```

Oluşturulan belge için vurgu stilini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | EmphasisStyle öğesi |

### setExtractVectorGraphics {#setExtractVectorGraphics-boolean-}
```
public final void setExtractVectorGraphics(boolean value)
```

Vektör grafiklerinin çıkarılıp çıkarılmayacağını belirten bir özelliği alır ve ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
FontSize tanıma başlık stratejisinde kullanılacak beklenen başlık seviyelerini tanımlar. Bu özellik değeri ayarlanırsa, belge yer imleri içeriyor olsa bile {@link HeadingRecognitionStrategy#Heuristic} başlık tanıma stratejisi, {@link HeadingRecognitionStrategy#Auto} stratejileri ayarlandığında seçilecektir.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

Başlık tanıma stratejisini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | HeadingRecognitionStrategy öğesi |

### setHeadingStyle {#setHeadingStyle-int-}
```
public final void setHeadingStyle(int value)
```

Oluşturulan belge için başlık stilini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | HeadingStyle öğesi |

### setLineBreakStyle {#setLineBreakStyle-int-}
```
public final void setLineBreakStyle(int value)
```

Oluşturulan belge için satır sonu stilini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | LineBreakStyle öğesi |

### setResourcesDirectoryName {#setResourcesDirectoryName-java.lang.String-}
Görüntüler gibi belge kaynaklarını kaydetmek için dizin adını alır ve ayarlar. Değer belirtilmezse, görüntüler markdown dosyasının bulunduğu aynı dizine yazılacaktır. Bu bir yol değil, sadece bir isimdir! Bu dizin, kaydedilen markdown dosyasının bulunduğu dizinde otomatik olarak oluşturulacaktır.

### setResourcesDirectoryPath {#setResourcesDirectoryPath-java.lang.String-}
Görüntüler gibi belge kaynaklarını kaydetmek için dizin adını alır ve ayarlar. Bu dizin, kaydedilen markdown dosyasının bulunduğu dizinde otomatik olarak oluşturulacaktır.

### setSubscriptAndSuperscriptConversion {#setSubscriptAndSuperscriptConversion-boolean-}
```
public final void setSubscriptAndSuperscriptConversion(boolean value)
```

Alt ve üst simgeye dönüştürme iznini alır ve ayarlar. Bu değer varsayılan olarak doğrudur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setUseImageHtmlTag {#setUseImageHtmlTag-boolean-}
```
public final void setUseImageHtmlTag(boolean value)
```

Metnin sol ve sağına görüntü eklemek için bir img etiketi kullanım iznini alır ve ayarlar. Bu durumda, markdown görüntüleyicide metin görüntünün etrafında kayacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
