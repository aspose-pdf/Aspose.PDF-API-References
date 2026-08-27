---
title: "TextParagraphAbsorber"
linktitle: "TextParagraphAbsorber"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل كائن ماص لفقرات النص. ينفذ بحثًا نصيًا ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextParagraphAbsorber.TextParagraphs}."
type: docs
weight: 5220
url: /ar/java/com.aspose.pdf/textparagraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextParagraphAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextParagraphAbsorber

```
public final class TextParagraphAbsorber extends TextAbsorber
```

يمثل كائن ماص لفقرات النص. ينفذ بحثًا نصيًا ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TextParagraphAbsorber.TextParagraphs}.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextParagraphAbsorber](#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-) | <p> يهيئ مثيلاً جديداً من {@code TextParagraphAbsorber} مع مجموعة المستطيلات. </p> |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getRectangles](#getRectangles--) | يحصل على المستطيلات التي يستخدمها {@code TextParagraphAbsorber} للبحث عن فقرات النص في مستند PDF أو الصفحة. |
| [getTextParagraphs](#getTextParagraphs--) | يحصل على مجموعة من حالات البحث التي يتم تقديمها بكائنات {@code TextParagraph}. |
| [setRectangles](#setRectangles-com.aspose.pdf.Rectangle:A-) | يضبط المستطيلات التي يستخدمها {@code TextParagraphAbsorber} للبحث عن فقرات النص في مستند PDF أو الصفحة. |
| [setTextParagraphs](#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-) | يضبط مجموعة حالات البحث التي يتم تقديمها بكائنات {@code TextParagraph}. |
| [visit](#visit-com.aspose.pdf.Page-) | ينفذ البحث على الصفحة المحددة. |

### TextParagraphAbsorber {#TextParagraphAbsorber-com.aspose.pdf.Rectangle:A-}
<p> يهيئ مثيلاً جديداً من {@code TextParagraphAbsorber} مع مجموعة المستطيلات. </p>

### getRectangles {#getRectangles--}
```
public Rectangle [] getRectangles()
```

يحصل على المستطيلات التي يستخدمها {@code TextParagraphAbsorber} للبحث عن فقرات النص في مستند PDF أو الصفحة.

**Returns:**
مصفوفة المستطيلات

### getTextParagraphs {#getTextParagraphs--}
```
public TextParagraphCollection getTextParagraphs()
```

يحصل على مجموعة من حالات البحث التي يتم تقديمها بكائنات {@code TextParagraph}.

**Returns:**
قيمة TextParagraphCollection

### setRectangles {#setRectangles-com.aspose.pdf.Rectangle:A-}
يضبط المستطيلات التي يستخدمها {@code TextParagraphAbsorber} للبحث عن فقرات النص في مستند PDF أو الصفحة.

### setTextParagraphs {#setTextParagraphs-com.aspose.pdf.TextParagraphCollection-}
يضبط مجموعة حالات البحث التي يتم تقديمها بكائنات {@code TextParagraph}.

### visit {#visit-com.aspose.pdf.Page-}
ينفذ البحث على الصفحة المحددة.
