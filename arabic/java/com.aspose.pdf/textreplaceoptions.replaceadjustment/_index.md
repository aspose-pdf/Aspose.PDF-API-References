---
title: "TextReplaceOptions.ReplaceAdjustment"
linktitle: "TextReplaceOptions.ReplaceAdjustment"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يحدد الإجراء الذي سيتم بعد استبدال جزء النص إلى أقصر. لا شيء - لا إجراء، قد يتداخل النص المستبدل مع باقي السطر؛ AdjustSpaceWidth - يحاول ذلك."
type: docs
weight: 5270
url: /ar/java/com.aspose.pdf/textreplaceoptions.replaceadjustment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.Enum, com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment

```
public static final class TextReplaceOptions.ReplaceAdjustment extends com.aspose.ms.System.Enum
```

يحدد الإجراء الذي سيتم بعد استبدال جزء من النص بجزء أقصر. None - لا إجراء، قد يتداخل النص المستبدل مع باقي السطر؛ AdjustSpaceWidth - يحاول تعديل المسافات بين الكلمات للحفاظ على طول السطر؛ WholeWordsHyphenation - يحاول توزيع الكلمات بين أسطر الفقرة للحفاظ على الحقل الأيمن للفقرة؛ ShiftRestOfLine - يحرك باقي السطر وفقًا لتغيير طول النص، قد يتغير طول السطر؛ القيمة الافتراضية هي ShiftRestOfLine.

## الحقول

| حقل | الوصف |
| --- | --- |
| [AdjustSpaceWidth](#AdjustSpaceWidth) | يحاول ضبط المسافات بين الكلمات للحفاظ على طول السطر |
| [IsFormFillingMode](#IsFormFillingMode) | يحاول توزيع الكلمات في المساحة البيضاء المتاحة باستخدام عرض الفقرة. إذا تجاوز النص الحد، سيتم إخفاؤه. |
| [None](#None) | لا إجراء، قد يتداخل النص المستبدل مع باقي السطر |
| [ShiftRestOfLine](#ShiftRestOfLine) | (افتراضي) ينقل باقي السطر وفقًا لتغير طول النص، قد يتغير طول السطر |
| [WholeWordsHyphenation](#WholeWordsHyphenation) | يحاول توزيع الكلمات بين أسطر الفقرة للحفاظ على الحقل الأيمن للفقرة |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) |  |

### AdjustSpaceWidth {#AdjustSpaceWidth}
```
public static final int AdjustSpaceWidth
```

يحاول ضبط المسافات بين الكلمات للحفاظ على طول السطر

### IsFormFillingMode {#IsFormFillingMode}
```
public static final int IsFormFillingMode
```

يحاول توزيع الكلمات في المساحة البيضاء المتاحة باستخدام عرض الفقرة. إذا تجاوز النص الحد، سيتم إخفاؤه.

### None {#None}
```
public static final int None
```

لا إجراء، قد يتداخل النص المستبدل مع باقي السطر

### ShiftRestOfLine {#ShiftRestOfLine}
```
public static final int ShiftRestOfLine
```

(افتراضي) ينقل باقي السطر وفقًا لتغير طول النص، قد يتغير طول السطر

### WholeWordsHyphenation {#WholeWordsHyphenation}
```
public static final int WholeWordsHyphenation
```

يحاول توزيع الكلمات بين أسطر الفقرة للحفاظ على الحقل الأيمن للفقرة

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| flag |  |  |
| flagToCheck |  |  |
