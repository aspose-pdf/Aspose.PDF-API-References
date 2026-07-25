---
title: "ParagraphAbsorber"
linktitle: "ParagraphAbsorber"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل كائن ماص لهيكل الصفحة مثل الأقسام والفقرات. يقوم بالبحث عن الأقسام والفقرات في النص ويوفر الوصول إلى."
type: docs
weight: 3470
url: /ar/java/com.aspose.pdf/paragraphabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ParagraphAbsorber

```
public class ParagraphAbsorber extends Object
```

<p> يمثل كائن ماص لهيكل الصفحة مثل الأقسام والفقرات. يقوم بالبحث عن الأقسام والفقرات النصية ويوفر الوصول إلى المستطيلات والمتعددات التي تصفه في مساحة إحداثيات النص. كما يقوم بالبحث عن مقاطع النص ويوفر الوصول إلى نتائج البحث عبر مجموعات {@code TextFragments} المجمعة حسب عناصر الهيكل. </p> يوضح المثال كيفية العثور على أول مقطع نصي لكل فقرة في الصفحة الأولى من مستند PDF وتظليله. <p> // Open document Document doc = new Document("input.pdf"); // Create ParagraphAbsorber object ParagraphAbsorber absorber = new ParagraphAbsorber(); // Accept the absorber for first page absorber.visit(doc.getPages.get_Item(1)); // Get markup object of first page PageMarkup markup = absorber.getPageMarkups().get(0); // Loop through structure elements of the page text to find first text fragment of each paragraph for (MarkupSection section : markup.getSections()) { for (MarkupParagraph paragraph : section.getParagraphs()) { TextFragment fragment = paragraph.getFragments().get_Item(0); // Update text properties fragment.getTextState().setBackgroundColor (Color.getLightBlue()); } } // Save document doc.save(GetOutputPath("output.pdf")); </p> <hr> عند إكمال البحث ستحتوي مجموعة {@code ParagraphAbsorber.PageMarkups} على كائنات {@code PageMarkup} التي تمثل هيكل الصفحة بواسطة مجموعات {@code MarkupSection} و {@code MarkupParagraph}. يوفر كائن {@code TextFragment} الوصول إلى نص نتيجة البحث، وخصائص النص، ويسمح بتحرير النص وتغيير حالة النص (الخط، حجم الخط، اللون، إلخ).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ParagraphAbsorber](#ParagraphAbsorber--) | ينشئ مثيلًا جديدًا من {@code ParagraphAbsorber} الذي يقوم بالبحث عن الأقسام/الفقرات في المستند أو الصفحة. |
| [ParagraphAbsorber](#ParagraphAbsorber-int-) | <p> ينشئ مثيلًا جديدًا من {@code ParagraphAbsorber} الذي يقوم بالبحث عن الأقسام/الفقرات في المستند أو الصفحة. </p> |
| [ParagraphAbsorber](#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-) | ينشئ مثيلًا جديدًا من {@code ParagraphAbsorber} الذي يقوم بالبحث عن الأقسام/الفقرات في المستند أو الصفحة. |
| [ParagraphAbsorber](#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-) | ينشئ مثيلًا جديدًا من {@code ParagraphAbsorber} الذي يقوم بالبحث عن الأقسام/الفقرات في المستند أو الصفحة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getPageMarkups](#getPageMarkups--) | يحصل على مجموعة {@code PageMarkup} التي تم امتصاصها. |
| [getParagraphAbsorberOptions](#getParagraphAbsorberOptions--) | يحصل على ParagraphAbsorberOptions. |
| [getSectionsSearchDepth](#getSectionsSearchDepth--) | <p> يحصل أو يضبط القيمة التي تحدد عدد مرات إجراء عمليات البحث المتسلسلة للعناصر الدقيقة للهيكل. العمق الافتراضي للبحث هو 3. يعني ذلك ثلاث عمليات بحث للأقسام المقسمة أفقيًا (العناوين، الفقرات، إلخ) وثلاث عمليات بحث للأقسام المقسمة عموديًا (الأعمدة). </p><hr> قد يؤدي زيادة هذه القيمة إلى انخفاض طفيف في الأداء دون أي تغييرات مرئية في نتائج البحث. قد يؤدي تقليل هذه القيمة إلى تحديد غير صحيح للفقرات داخل الأقسام. لا نوصي بتعيين قيمة أقل من القيمة الافتراضية إذا لم تكن ترغب في الحصول فقط على العناصر 'خامة' لهياكل الصفحة. |
| [getTextReplaceOptions](#getTextReplaceOptions--) | يحصل أو يضبط TextReplaceOptions. |
| [isMulticolumnParagraphsAllowed](#isMulticolumnParagraphsAllowed--) | يحصل أو يعيّن القيمة التي تشير إلى ما إذا كان يمكن اعتبار سطور النص الأولية للقسم التالي استمرارًا للفقرة الأخيرة في القسم السابق. |
| [setMulticolumnParagraphsAllowed](#setMulticolumnParagraphsAllowed-boolean-) | يحصل أو يعيّن القيمة التي تشير إلى ما إذا كان يمكن اعتبار سطور النص الأولية للقسم التالي استمرارًا للفقرة الأخيرة في القسم السابق. |
| [setParagraphAbsorberOptions](#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-) | يضبط ParagraphAbsorberOptions. |
| [setSectionsSearchDepth](#setSectionsSearchDepth-int-) | <p> يحصل أو يضبط القيمة التي تحدد عدد مرات إجراء عمليات البحث المتسلسلة للعناصر الدقيقة للهيكل. العمق الافتراضي للبحث هو 3. يعني ذلك ثلاث عمليات بحث للأقسام المقسمة أفقيًا (العناوين، الفقرات، إلخ) وثلاث عمليات بحث للأقسام المقسمة عموديًا (الأعمدة). </p><hr> قد يؤدي زيادة هذه القيمة إلى انخفاض طفيف في الأداء دون أي تغييرات مرئية في نتائج البحث. قد يؤدي تقليل هذه القيمة إلى تحديد غير صحيح للفقرات داخل الأقسام. لا نوصي بتعيين قيمة أقل من القيمة الافتراضية إذا لم تكن ترغب في الحصول فقط على العناصر 'خامة' لهياكل الصفحة. |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | يحصل أو يضبط TextReplaceOptions. |
| [visit](#visit-com.aspose.pdf.Document-) | ينفذ البحث عن الأقسام والفقرات في {@link Document} المحدد. |
| [visit](#visit-com.aspose.pdf.Page-) | ينفذ البحث في {@code Page} المحدد. |

### ParagraphAbsorber {#ParagraphAbsorber--}
```
public ParagraphAbsorber()
```

ينشئ مثيلًا جديدًا من {@code ParagraphAbsorber} الذي يقوم بالبحث عن الأقسام/الفقرات في المستند أو الصفحة.

### ParagraphAbsorber {#ParagraphAbsorber-int-}
```
public ParagraphAbsorber(int sectionsSearchDepth)
```

<p> ينشئ مثيلًا جديدًا من {@code ParagraphAbsorber} الذي يقوم بالبحث عن الأقسام/الفقرات في المستند أو الصفحة. </p>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sectionsSearchDepth |  | عدد عمليات البحث المتسلسلة للعناصر الدقيقة للهيكل التي سيتم تنفيذها. <hr> راجع خاصية {@code ParagraphAbsorber.SectionsSearchDepth} لمزيد من الإرشادات حول المعامل. <hr> |

### ParagraphAbsorber {#ParagraphAbsorber-int-com.aspose.pdf.ParagraphAbsorberOptions-}
ينشئ مثيلًا جديدًا من {@code ParagraphAbsorber} الذي يقوم بالبحث عن الأقسام/الفقرات في المستند أو الصفحة.

### ParagraphAbsorber {#ParagraphAbsorber-com.aspose.pdf.ParagraphAbsorberOptions-}
ينشئ مثيلًا جديدًا من {@code ParagraphAbsorber} الذي يقوم بالبحث عن الأقسام/الفقرات في المستند أو الصفحة.

### getPageMarkups {#getPageMarkups--}
```
public List < PageMarkup > getPageMarkups()
```

يحصل على مجموعة {@code PageMarkup} التي تم امتصاصها.

**Returns:**
قائمة كائنات PageMarkup

### getParagraphAbsorberOptions {#getParagraphAbsorberOptions--}
```
public final ParagraphAbsorberOptions getParagraphAbsorberOptions()
```

يحصل على ParagraphAbsorberOptions.

**Returns:**
كائن ParagraphAbsorberOptions

### getSectionsSearchDepth {#getSectionsSearchDepth--}
```
public int getSectionsSearchDepth()
```

<p> يحصل أو يضبط القيمة التي تحدد عدد مرات إجراء عمليات البحث المتسلسلة للعناصر الدقيقة للهيكل. العمق الافتراضي للبحث هو 3. يعني ذلك ثلاث عمليات بحث للأقسام المقسمة أفقيًا (العناوين، الفقرات، إلخ) وثلاث عمليات بحث للأقسام المقسمة عموديًا (الأعمدة). </p><hr> قد يؤدي زيادة هذه القيمة إلى انخفاض طفيف في الأداء دون أي تغييرات مرئية في نتائج البحث. قد يؤدي تقليل هذه القيمة إلى تحديد غير صحيح للفقرات داخل الأقسام. لا نوصي بتعيين قيمة أقل من القيمة الافتراضية إذا لم تكن ترغب في الحصول فقط على العناصر 'خامة' لهياكل الصفحة.

**Returns:**
قيمة int

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public final TextReplaceOptions getTextReplaceOptions()
```

يحصل أو يضبط TextReplaceOptions.

**Returns:**
مثيل TextReplaceOptions

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

### setParagraphAbsorberOptions {#setParagraphAbsorberOptions-com.aspose.pdf.ParagraphAbsorberOptions-}
يضبط ParagraphAbsorberOptions.

### setSectionsSearchDepth {#setSectionsSearchDepth-int-}
```
public void setSectionsSearchDepth(int value)
```

<p> يحصل أو يضبط القيمة التي تحدد عدد مرات إجراء عمليات البحث المتسلسلة للعناصر الدقيقة للهيكل. العمق الافتراضي للبحث هو 3. يعني ذلك ثلاث عمليات بحث للأقسام المقسمة أفقيًا (العناوين، الفقرات، إلخ) وثلاث عمليات بحث للأقسام المقسمة عموديًا (الأعمدة). </p><hr> قد يؤدي زيادة هذه القيمة إلى انخفاض طفيف في الأداء دون أي تغييرات مرئية في نتائج البحث. قد يؤدي تقليل هذه القيمة إلى تحديد غير صحيح للفقرات داخل الأقسام. لا نوصي بتعيين قيمة أقل من القيمة الافتراضية إذا لم تكن ترغب في الحصول فقط على العناصر 'خامة' لهياكل الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
يحصل أو يضبط TextReplaceOptions.

### visit {#visit-com.aspose.pdf.Document-}
ينفذ البحث عن الأقسام والفقرات في {@link Document} المحدد.

### visit {#visit-com.aspose.pdf.Page-}
ينفذ البحث في {@code Page} المحدد.
