---
title: "الخط"
linktitle: "الخط"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل كائن الخط. </p> <hr> <pre> يوضح المثال كيفية البحث عن النص في الصفحة الأولى وتغيير خط أول ظهور للبحث. // Open document Document doc.</pre>"
type: docs
weight: 1650
url: /ar/java/com.aspose.pdf/font/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Font

**All Implemented Interfaces:**
قابل للنسخ

```
public final class Font extends Object implements Cloneable
```

<p> يمثل كائن الخط. </p> <hr> <pre> يوضح المثال كيفية البحث عن النص في الصفحة الأولى وتغيير خط أول ظهور للبحث. // Open document Document doc = new Document("input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Create font and mark it to be embedded Font font = FontRepository.findFont("Arial"); font.isEmbedded(true); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Save document doc.save("output.pdf"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument

## الطرق

| طريقة | الوصف |
| --- | --- |
| [doesFontContainAllCharacters](#doesFontContainAllCharacters-java.lang.String-) | يحدد ما إذا كان الخط يحتوي على الأحرف المحددة |
| [getActualFontName](#getActualFontName--) | <p> يحصل على اسم الخط الفعلي لكائن {@code Font} إذا تم تهيئته. حتى عندما يتم استبدال الخط أو لديه اسم داخلي للـ pdf. أو سلسلة فارغة إذا لم يتم تهيئة الخط. </p> |
| [getAscentPoint](#getAscentPoint-java.lang.String-float-) | يقيس أقصى نقطة صعود. |
| [getBaseFont](#getBaseFont--) | يحصل على قيمة BaseFont لكائن خط PDF. وتعرف أيضًا باسم PostScript للخط. |
| [getDecodedFontName](#getDecodedFontName--) | في بعض الأحيان قد تحتوي خطوط PDF (عادةً خطوط صينية/يابانية/كورية) على اسم خط محدد. هذا الاسم هو قيمة خاصية الخط في PDF "BaseFont" وأحيانًا قد يتم تمثيل هذه الخاصية بصيغة سداسية عشرية. إذا قرأت هذا الاسم مباشرة قد يكون غير قابل للقراءة. للحصول على صيغة قابلة للقراءة من الضروري فك تشفير اسم الخط وفقًا للقواعد الخاصة بهذا الخط. تُعيد هذه الخاصية اسم الخط المفكوك، لذا استخدمها في الحالات التي تواجه فيها {@code FontName} غير قابل للقراءة. إذا كان للخاصية {@code FontName} صيغة قابلة للقراءة فستكون هذه الخاصية هي نفسها {@code FontName}، لذا يمكنك استخدام هذه الخاصية في أي حالة تحتاج فيها إلى الحصول على اسم الخط بصيغة قابلة للقراءة. |
| [getDescentPoint](#getDescentPoint-java.lang.String-float-) | يقيس أقصى نقطة هبوط. |
| [getFontName](#getFontName--) | <p> يحصل على اسم الخط لكائن {@code Font}. </p> |
| [getFontOptions](#getFontOptions--) | خصائص مفيدة لضبط سلوك الخط |
| [getIFont](#getIFont--) | <p> كائن خط النظام. </p> <hr> <p> للاستخدام الداخلي فقط </p> |
| [getIPdfFont](#getIPdfFont--) | <p> كائن خط PDF. </p> <hr> <p> للاستخدام الداخلي فقط </p> |
| [getLastFontEmbeddingError](#getLastFontEmbeddingError--) | هدف هذه الطريقة - إرجاع وصف الخطأ إذا فشلت محاولة تضمين الخط. إذا لم توجد حالات خطأ تُرجع سلسلة فارغة. |
| [getType](#getType--) | اسم نوع الخط |
| [isAccessible](#isAccessible--) | <p> يحصل على مؤشر ما إذا كان الخط موجودًا (مثبتًا) في النظام. </p> |
| [isEmbedded](#isEmbedded--) | <p> يحصل على قيمة تشير إلى ما إذا كان الخط مضمّنًا. الخط المستند إلى IFont سيتم تقسيمه وتضمينه تلقائيًا </p> <hr> <pre> يوضح المثال التالي كيفية العثور على خط، وضع علامة عليه كمدمج، البحث عن نص في صفحة المستند واستبدال خط النص. // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\\\Tests\\\\input.pdf"); // create TextFragmentAbsorber object to find all "hello world" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [isSubset](#isSubset--) | <p> يحصل على قيمة تشير إلى ما إذا كان الخط مجموعة فرعية. الخط المستند إلى IFont سيتم تقسيمه وتضمينه تلقائيًا </p> <hr> <pre> يوضح المثال كيفية البحث عن نص في الصفحة الأولى والحصول على القيمة التي تشير إلى ما إذا كان الخط مجموعة فرعية. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("the font is a subset"); </pre> |
| [measureString](#measureString-java.lang.String-float-) | يقيس السلسلة. |
| [save](#save-java.io.OutputStream-) | يحفظ الخط في الدفق. لاحظ أن الخط يُحفظ بتنسيق TTF وسيط يُقصد استخدامه فقط في نسخة محوّلة من المستند الأصلي. ملف الخط غير مخصص للاستخدام خارج سياق المستند الأصلي. |
| [setEmbedded](#setEmbedded-boolean-) | يضبط قيمة تشير إلى ما إذا كان الخط مضمّنًا. الخط المستند إلى IFont سيتم تقسيمه وتضمينه تلقائيًا |
| [setSubset](#setSubset-boolean-) | يضبط قيمة تشير إلى ما إذا كان الخط مجموعة فرعية. الخط المستند إلى IFont سيتم تقسيمه وتضمينه تلقائيًا |

### doesFontContainAllCharacters {#doesFontContainAllCharacters-java.lang.String-}
يحدد ما إذا كان الخط يحتوي على الأحرف المحددة

### getActualFontName {#getActualFontName--}
```
public String getActualFontName()
```

<p> يحصل على اسم الخط الفعلي لكائن {@code Font} إذا تم تهيئته. حتى عندما يتم استبدال الخط أو لديه اسم داخلي للـ pdf. أو سلسلة فارغة إذا لم يتم تهيئة الخط. </p>

**Returns:**
قيمة السلسلة <hr> <pre> The example demonstrates how to search text on first page and view actual font name of a first text occurrence. // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View actual font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getActualFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getAscentPoint {#getAscentPoint-java.lang.String-float-}
يقيس أقصى نقطة صعود.

### getBaseFont {#getBaseFont--}
```
public final String getBaseFont()
```

يحصل على قيمة BaseFont لكائن خط PDF. وتعرف أيضًا باسم PostScript للخط.

**Returns:**
قيمة سلسلة

### getDecodedFontName {#getDecodedFontName--}
```
public String getDecodedFontName()
```

في بعض الأحيان قد تحتوي خطوط PDF (عادةً خطوط صينية/يابانية/كورية) على اسم خط محدد. هذا الاسم هو قيمة خاصية الخط في PDF "BaseFont" وأحيانًا قد يتم تمثيل هذه الخاصية بصيغة سداسية عشرية. إذا قرأت هذا الاسم مباشرة قد يكون غير قابل للقراءة. للحصول على صيغة قابلة للقراءة من الضروري فك تشفير اسم الخط وفقًا للقواعد الخاصة بهذا الخط. تُعيد هذه الخاصية اسم الخط المفكوك، لذا استخدمها في الحالات التي تواجه فيها {@code FontName} غير قابل للقراءة. إذا كان للخاصية {@code FontName} صيغة قابلة للقراءة فستكون هذه الخاصية هي نفسها {@code FontName}، لذا يمكنك استخدام هذه الخاصية في أي حالة تحتاج فيها إلى الحصول على اسم الخط بصيغة قابلة للقراءة.

**Returns:**
قيمة سلسلة

### getDescentPoint {#getDescentPoint-java.lang.String-float-}
يقيس أقصى نقطة هبوط.

### getFontName {#getFontName--}
```
public String getFontName()
```

<p> يحصل على اسم الخط لكائن {@code Font}. </p>

**Returns:**
قيمة السلسلة <hr> <pre> The example demonstrates how to search text on first page and view font name of a first text occurrence. // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getFontOptions {#getFontOptions--}
```
public IFontOptions getFontOptions()
```

خصائص مفيدة لضبط سلوك الخط

**Returns:**
كائن IFontOptions

### getIFont {#getIFont--}
```
public com.aspose.font.IFont getIFont()
```

<p> كائن خط النظام. </p> <hr> <p> للاستخدام الداخلي فقط </p>

**Returns:**
كائن IFont

### getIPdfFont {#getIPdfFont--}
```
public com.aspose.pdf.engine.commondata.text.fonts.IPdfFont getIPdfFont()
```

<p> كائن خط PDF. </p> <hr> <p> للاستخدام الداخلي فقط </p>

**Returns:**
كائن IPdfFont

### getLastFontEmbeddingError {#getLastFontEmbeddingError--}
```
public String getLastFontEmbeddingError()
```

هدف هذه الطريقة - إرجاع وصف الخطأ إذا فشلت محاولة تضمين الخط. إذا لم توجد حالات خطأ تُرجع سلسلة فارغة.

**Returns:**
وصف الخطأ

### getType {#getType--}
```
public String getType()
```

اسم نوع الخط

**Returns:**
كائن String

### isAccessible {#isAccessible--}
```
public boolean isAccessible()
```

<p> يحصل على مؤشر ما إذا كان الخط موجودًا (مثبتًا) في النظام. </p>

**Returns:**
قيمة منطقية <hr> <pre> The example demonstrates how to search text on first page and get the value that indicates whether the font is installed in the system. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if (absorber.getTextFragments().get_Item(1).getTextState().getFont() .isAccessible()) System.out.println(\"the font is installed in the system\"); </pre> <hr> <p> بعض العمليات غير متاحة مع الخطوط التي لا يمكن العثور عليها في النظام. </p>

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

<p> يحصل على قيمة تشير إلى ما إذا كان الخط مضمنًا. الخط المستند إلى IFont سيتم تقسيمه وتضمينه تلقائيًا </p> <hr> <pre> The following example demonstrates how to find a font, mark it as embedded, search text on the document's page and replace the text font. // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont(\"Arial\"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document(\"D:\\\\Tests\\\\input.pdf\"); // create TextFragmentAbsorber object to find all \"hello world\" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber(\"hello world\"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

**Returns:**
قيمة منطقية @see TextFragmentAbsorber @see FontRepository @see IDocument

### isSubset {#isSubset--}
```
public boolean isSubset()
```

<p> يحصل على قيمة تشير إلى ما إذا كان الخط جزءًا فرعيًا. الخط المستند إلى IFont سيتم تقسيمه وتضمينه تلقائيًا </p> <hr> <pre> The example demonstrates how to search text on first page and get the value that indicates whether the font is a subset. // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println(\"the font is a subset\"); </pre>

**Returns:**
قيمة منطقية @see TextFragmentAbsorber @see IDocument

### measureString {#measureString-java.lang.String-float-}
يقيس السلسلة.

### save {#save-java.io.OutputStream-}
يحفظ الخط في الدفق. لاحظ أن الخط يُحفظ بتنسيق TTF وسيط يُقصد استخدامه فقط في نسخة محوّلة من المستند الأصلي. ملف الخط غير مخصص للاستخدام خارج سياق المستند الأصلي.

### setEmbedded {#setEmbedded-boolean-}
```
public void setEmbedded(boolean value)
```

يضبط قيمة تشير إلى ما إذا كان الخط مضمّنًا. الخط المستند إلى IFont سيتم تقسيمه وتضمينه تلقائيًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSubset {#setSubset-boolean-}
```
public void setSubset(boolean value)
```

يضبط قيمة تشير إلى ما إذا كان الخط مجموعة فرعية. الخط المستند إلى IFont سيتم تقسيمه وتضمينه تلقائيًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
