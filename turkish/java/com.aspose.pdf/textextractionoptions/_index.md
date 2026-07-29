---
title: "TextExtractionOptions"
linktitle: "TextExtractionOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metin çıkarma seçeneklerini temsil eder"
type: docs
weight: 5060
url: /tr/java/com.aspose.pdf/textextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextExtractionOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextExtractionOptions

```
public final class TextExtractionOptions extends TextOptions
```

Metin çıkarma seçeneklerini temsil eder

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TextExtractionOptions](#TextExtractionOptions-int-) | {@code TextExtractionOptions} nesnesinin belirtilen metin biçimlendirme modu için yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormattingMode](#getFormattingMode--) | Biçimlendirme modunu alır. |
| [getScaleFactor](#getScaleFactor--) | Saf modda çıkarma sırasında yazı tipi boyutunu ölçeklendirmek için uygulanacak faktörü alır. Daha düşük bir değer ayarlandığında çıkarılan metinde daha fazla boşluk oluşur. Varsayılan değer 1'dir - ölçeklendirme yok; Değeri sıfıra ayarlamak, algoritmanın ölçeklendirmeyi otomatik olarak seçmesine izin verir. |
| [setFormattingMode](#setFormattingMode-int-) | Biçimlendirme modunu ayarlar. |
| [setScaleFactor](#setScaleFactor-double-) | Saf modda çıkarma sırasında yazı tipi boyutunu ölçeklendirmek için uygulanacak faktörü ayarlar. Daha düşük bir değer ayarlandığında (1 ile 10 arasında) çıkarılan metinde daha fazla boşluk oluşur. Varsayılan değer 1'dir - ölçeklendirme yok; Değeri sıfıra ayarlamak, algoritmanın ölçeklendirmeyi otomatik olarak seçmesine izin verir. |

### TextExtractionOptions {#TextExtractionOptions-int-}
```
public TextExtractionOptions(int formattingMode)
```

{@code TextExtractionOptions} nesnesinin belirtilen metin biçimlendirme modu için yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formattingMode |  | Metin biçimlendirme modu değeri. @see TextFormattingMode |

### getFormattingMode {#getFormattingMode--}
```
public int getFormattingMode()
```

Biçimlendirme modunu alır.

**Returns:**
TextFormattingMode değeri @see TextFormattingMode

### getScaleFactor {#getScaleFactor--}
```
public double getScaleFactor()
```

Saf modda çıkarma sırasında yazı tipi boyutunu ölçeklendirmek için uygulanacak faktörü alır. Daha düşük bir değer ayarlandığında çıkarılan metinde daha fazla boşluk oluşur. Varsayılan değer 1'dir - ölçeklendirme yok; Değeri sıfıra ayarlamak, algoritmanın ölçeklendirmeyi otomatik olarak seçmesine izin verir.

**Returns:**
double değer

### setFormattingMode {#setFormattingMode-int-}
```
public void setFormattingMode(int value)
```

Biçimlendirme modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | TextFormattingMode değeri @see TextFormattingMode |

### setScaleFactor {#setScaleFactor-double-}
```
public void setScaleFactor(double value)
```

Saf modda çıkarma sırasında yazı tipi boyutunu ölçeklendirmek için uygulanacak faktörü ayarlar. Daha düşük bir değer ayarlandığında (1 ile 10 arasında) çıkarılan metinde daha fazla boşluk oluşur. Varsayılan değer 1'dir - ölçeklendirme yok; Değeri sıfıra ayarlamak, algoritmanın ölçeklendirmeyi otomatik olarak seçmesine izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |
