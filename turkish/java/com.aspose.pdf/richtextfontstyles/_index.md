---
title: "RichTextFontStyles"
linktitle: "RichTextFontStyles"
second_title: "Aspose.PDF for Java API Referansı"
description: "RichText içinde metin parçacıklarını biçimlendirme seçenekleri."
type: docs
weight: 4300
url: /tr/java/com.aspose.pdf/richtextfontstyles/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.Enum, com.aspose.pdf.RichTextFontStyles

```
public final class RichTextFontStyles extends com.aspose.ms.System.Enum
```

RichText içinde metin parçacıklarını biçimlendirme seçenekleri.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Bold](#Bold) | Kalınlığı belirten seçenek. |
| [ClearExisting](#ClearExisting) | Ayarlanırsa, ek stiller uygulanmadan önce mevcut tüm stilleri temizler. Diğer stil bayraklarıyla (ör. {@code RichTextFontStyles#Bold}) birleştirildiğinde, önce stilleri sıfırlar, ardından belirtilen stilleri uygular. Bu bayrak olmadan, yeni stiller mevcut olanlara eklenir. |
| [Italic](#Italic) | İtalik belirten seçenek. |
| [Underline](#Underline) | Alt çizgiyi belirten seçenek. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) | Belirtilen bayrağın ayarlanıp ayarlanmadığını kontrol eder. |

### Bold {#Bold}
```
public static final int Bold
```

Kalınlığı belirten seçenek.

### ClearExisting {#ClearExisting}
```
public static final int ClearExisting
```

Ayarlanırsa, ek stiller uygulanmadan önce mevcut tüm stilleri temizler. Diğer stil bayraklarıyla (ör. {@code RichTextFontStyles#Bold}) birleştirildiğinde, önce stilleri sıfırlar, ardından belirtilen stilleri uygular. Bu bayrak olmadan, yeni stiller mevcut olanlara eklenir.

### Italic {#Italic}
```
public static final int Italic
```

İtalik belirten seçenek.

### Underline {#Underline}
```
public static final int Underline
```

Alt çizgiyi belirten seçenek.

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```

Belirtilen bayrağın ayarlanıp ayarlanmadığını kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bayrak |  | kontrol edilecek bayrağı temsil eden enum değeri |
| flagToCheck |  | kontrol edilecek bayrağı temsil eden enum değeri |

**Returns:**
Bayrak ayarlıysa {@code true}; aksi takdirde {@code false}
