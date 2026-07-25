---
title: "PageMarkup"
linktitle: "PageMarkup"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تمثيل تنسيق الصفحة بواسطة مجموعات من {@code MarkupSection} و {@code MarkupParagraph}."
type: docs
weight: 3420
url: /ar/java/com.aspose.pdf/pagemarkup/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageMarkup

```
public final class PageMarkup extends Object
```

تمثيل تنسيق الصفحة بواسطة مجموعات من {@code MarkupSection} و {@code MarkupParagraph}.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getNumber](#getNumber--) | يحصل على رقم الصفحة المعالجة. |
| [getParagraphs](#getParagraphs--) | يحصل على مجموعة {@code MarkupParagraph} التي تم العثور عليها في الصفحة. |
| [getRectangle](#getRectangle--) | يحصل على مستطيل الصفحة المعالجة. |
| [getSections](#getSections--) | يحصل على مجموعة {@code MarkupSection} التي تم العثور عليها في الصفحة. |
| [getTextFragments](#getTextFragments--) | <p> يحصل على مجموعة {@code TextFragment} التي تم العثور عليها في الصفحة. </p><hr> يوفر كائن {@code TextFragment} إمكانية الوصول إلى نص نتيجة البحث، وخصائص النص، ويسمح بتحرير النص وتغيير حالة النص (الخط، حجم الخط، اللون، إلخ). |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | يحصل أو يعيّن القيمة التي تشير إلى ما إذا كان يمكن اعتبار سطور النص الأولية للقسم التالي استمرارًا للفقرة الأخيرة في القسم السابق. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | يحصل أو يعيّن القيمة التي تشير إلى ما إذا كان يمكن اعتبار سطور النص الأولية للقسم التالي استمرارًا للفقرة الأخيرة في القسم السابق. |

### getNumber {#getNumber--}
```
public int getNumber()
```

يحصل على رقم الصفحة المعالجة.

**Returns:**
قيمة int

### getParagraphs {#getParagraphs--}
```
public List < MarkupParagraph > getParagraphs()
```

يحصل على مجموعة {@code MarkupParagraph} التي تم العثور عليها في الصفحة.

**Returns:**
قائمة من مثيلات MarkupParagraph

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

يحصل على مستطيل الصفحة المعالجة.

**Returns:**
كائن Rectangle

### getSections {#getSections--}
```
public List < MarkupSection > getSections()
```

يحصل على مجموعة {@code MarkupSection} التي تم العثور عليها في الصفحة.

**Returns:**
قائمة من مثيلات MarkupSection

### getTextFragments {#getTextFragments--}
```
public List < TextFragment > getTextFragments()
```

<p> يحصل على مجموعة {@code TextFragment} التي تم العثور عليها في الصفحة. </p><hr> يوفر كائن {@code TextFragment} إمكانية الوصول إلى نص نتيجة البحث، وخصائص النص، ويسمح بتحرير النص وتغيير حالة النص (الخط، حجم الخط، اللون، إلخ).

**Returns:**
قائمة من مثيلات TextFragment

### isMulticolumnParagraphsAllowed {#isMulticolumnParagraphsAllowed--}
```
public final boolean isMulticolumnParagraphsAllowed()
```

يحصل أو يعيّن القيمة التي تشير إلى ما إذا كان يمكن اعتبار سطور النص الأولية للقسم التالي استمرارًا للفقرة الأخيرة في القسم السابق.

**Returns:**
قيمة منطقية

### setMulticolumnParagraphsAllowed {#setMulticolumnParagraphsAllowed-boolean-}
```
public final void setMulticolumnParagraphsAllowed(boolean value)
```

يحصل أو يعيّن القيمة التي تشير إلى ما إذا كان يمكن اعتبار سطور النص الأولية للقسم التالي استمرارًا للفقرة الأخيرة في القسم السابق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
