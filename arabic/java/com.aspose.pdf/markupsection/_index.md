---
title: "MarkupSection"
linktitle: "MarkupSection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل قسم العلامة - المنطقة المستطيلة في صفحة تحتوي على نص ويمكن فصلها بصريًا عن كتل النص الأخرى."
type: docs
weight: 2890
url: /ar/java/com.aspose.pdf/markupsection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MarkupSection

```
public final class MarkupSection extends Object
```

يمثل قسم العلامة - المنطقة المستطيلة في صفحة تحتوي على نص ويمكن فصلها بصريًا عن كتل النص الأخرى.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFragments](#getFragments--) | <p> مجموعة من كائنات {@code TextFragment} غير الفارغة الموجودة داخل القسم. </p><hr> يوفّر كائن {@code TextFragment} إمكانية الوصول إلى نص نتيجة البحث، خصائص النص، ويسمح بتحرير النص وتغيير حالة النص (الخط، حجم الخط، اللون إلخ). |
| [getParagraphs](#getParagraphs--) | مجموعة من كائنات {@code MarkupParagraph} الموجودة داخل القسم. |
| [getRectangle](#getRectangle--) | مستطيل القسم |

### getFragments {#getFragments--}
```
public List < TextFragment > getFragments()
```

<p> مجموعة من كائنات {@code TextFragment} غير الفارغة الموجودة داخل القسم. </p><hr> يوفّر كائن {@code TextFragment} إمكانية الوصول إلى نص نتيجة البحث، خصائص النص، ويسمح بتحرير النص وتغيير حالة النص (الخط، حجم الخط، اللون إلخ).

**Returns:**
قائمة من مثيلات TextFragment

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

مجموعة من كائنات {@code MarkupParagraph} الموجودة داخل القسم.

**Returns:**
قائمة من مثيلات MarkupParagraph

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

مستطيل القسم

**Returns:**
مثيل Rectangle
