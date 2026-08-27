---
title: "TextReplaceOptions.ReplaceAdjustment"
linktitle: "TextReplaceOptions.ReplaceAdjustment"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metin parçacığının daha kısa bir şekilde değiştirilmesinden sonra yapılacak eylemi belirler. None - hiçbir işlem yapılmaz, değiştirilen metin satırın geri kalanıyla çakışabilir; AdjustSpaceWidth - denemeye çalışır."
type: docs
weight: 5270
url: /tr/java/com.aspose.pdf/textreplaceoptions.replaceadjustment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.Enum, com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment

```
public static final class TextReplaceOptions.ReplaceAdjustment extends com.aspose.ms.System.Enum
```

Metin parçacığının daha kısa bir hale getirilmesinden sonra yapılacak eylemi belirler. None - hiçbir eylem yok, değiştirilen metin satırın geri kalanıyla çakışabilir; AdjustSpaceWidth - satır uzunluğunu korumak için kelimeler arasındaki boşlukları ayarlamaya çalışır; WholeWordsHyphenation - paragrafın sağ alanını korumak için kelimeleri paragraf satırları arasında dağıtmaya çalışır; ShiftRestOfLine - metnin uzunluğundaki değişime göre satırın geri kalanını kaydırır, satır uzunluğu değişebilir; Varsayılan değer ShiftRestOfLine'dir.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [AdjustSpaceWidth](#AdjustSpaceWidth) | Satır uzunluğunu korumak için kelimeler arasındaki boşlukları ayarlamaya çalışır |
| [IsFormFillingMode](#IsFormFillingMode) | Paragraf genişliğini kullanarak kelimeleri mevcut boşlukta yaymaya çalışır. Metin taşarsa, gizlenecektir. |
| [None](#None) | Hiçbir işlem yapılmaz, değiştirilen metin satırın geri kalanıyla çakışabilir |
| [ShiftRestOfLine](#ShiftRestOfLine) | (Varsayılan) Metnin değişen uzunluğuna göre satırın geri kalanını kaydırır, satır uzunluğu değişebilir |
| [WholeWordsHyphenation](#WholeWordsHyphenation) | Paragrafın sağ kenarını korumak için kelimeleri paragraf satırları arasında dağıtmaya çalışır |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) |  |

### AdjustSpaceWidth {#AdjustSpaceWidth}
```
public static final int AdjustSpaceWidth
```

Satır uzunluğunu korumak için kelimeler arasındaki boşlukları ayarlamaya çalışır

### IsFormFillingMode {#IsFormFillingMode}
```
public static final int IsFormFillingMode
```

Paragraf genişliğini kullanarak kelimeleri mevcut boşlukta yaymaya çalışır. Metin taşarsa, gizlenecektir.

### None {#None}
```
public static final int None
```

Hiçbir işlem yapılmaz, değiştirilen metin satırın geri kalanıyla çakışabilir

### ShiftRestOfLine {#ShiftRestOfLine}
```
public static final int ShiftRestOfLine
```

(Varsayılan) Metnin değişen uzunluğuna göre satırın geri kalanını kaydırır, satır uzunluğu değişebilir

### WholeWordsHyphenation {#WholeWordsHyphenation}
```
public static final int WholeWordsHyphenation
```

Paragrafın sağ kenarını korumak için kelimeleri paragraf satırları arasında dağıtmaya çalışır

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bayrak |  |  |
| flagToCheck |  |  |
