---
title: "TextSegment"
linktitle: "TextSegment"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل جزءًا من نص Pdf. </p> <hr> <pre> يوضح المثال كيفية تغيير لون النص وحجم الخط للنص باستخدام كائن {@code TextState} من {@code."
type: docs
weight: 5300
url: /ar/java/com.aspose.pdf/textsegment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextSegment

```
public final class TextSegment extends Object
```

<p> يمثل جزءًا من نص Pdf. </p> <hr> <pre> يوضح المثال كيفية تغيير لون النص وحجم الخط للنص باستخدام كائن {@code TextState} من كائن {@code TextSegment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text segment of the first text occurrence absorber.getTextFragments().get(1).getSegments().get(1).getTextState().setForegroundColor ( java.awt.Color.RED); // Change font size of the first text segment of the first text occurrence absorber.getTextFragments().get(1).getSegments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <pre> باختصار، كائنات {@code TextSegment} هي أبناء كائن {@code TextFragment}. بالتفصيل: نص مستند pdf في {@code Aspose.Pdf} يُمثَّل بواسطة كائنين أساسيين: {@code TextFragment} و {@code TextSegment}. الاختلافات بينهما تعتمد في الغالب على السياق. لننظر في السيناريو التالي. يبحث المستخدم عن النص "hello world" للتعامل معه، وتغيير خصائصه، وما إلى ذلك. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> <p> تمثيل نص pdf فعليًا معقد جدًا. قد يتكون النص "hello world" من عدة أقسام نصية مستقلة ماديًا. يحدد نموذج نص Aspose.PDF أساسًا أن كائن {@code TextFragment} يوفر مجموعة عمليات منطقية واحدة على مجموعة كائنات {@code TextSegment} الفيزيائية التي تمثل استعلام المستخدم. في سيناريو البحث عن النص، يكون {@code TextFragment} تمثيلًا منطقيًا للنص "hello world"، وتجمع كائنات {@code TextSegment} يمثل جميع الأقسام الفيزيائية التي تُكوِّن كائن النص "hello world". لذا، فإن {@code TextFragment} قريب من تمثيل النص المنطقي. و{@code TextSegment} قريب من تمثيل النص الفيزيائي. من الواضح أن كل كائن {@code TextSegment} قد يمتلك خطه، لونه، وخصائص التموقع الخاصة به. يوفر {@code TextFragment} طريقة بسيطة لتغيير النص بخصائصه: تعيين الخط، تعيين حجم الخط، تعيين لون الخط، إلخ. في الوقت نفسه، يمكن الوصول إلى كائنات {@code TextSegment} ويستطيع المستخدمون التعامل مع كائنات {@code TextSegment} بشكل مستقل. </p>

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextSegment](#TextSegment--) | <p> ينشئ كائن TextSegment. </p> <hr> <pre> يوضح المثال كيفية إنشاء كائن مقطع نصي، إضافة مقطع نص إلى مجموعة مقاطع النص وإلحاقه بصفحة PDF. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // إنشاء مقطع نصي TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // تعيين خصائص النص tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // إضافة مقطع آخر إلى مجموعة مقاطع النص TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // إنشاء كائن TextBuilder TextBuilder builder = new TextBuilder(page); // إلحاق مقطع النص بصفحة PDF builder.appendText(tf); // حفظ المستند doc.save(outFile); </pre> |
| [TextSegment](#TextSegment-java.lang.String-) | <p> ينشئ كائن TextSegment. </p> <hr> <pre> يوضح المثال كيفية إنشاء كائن مقطع نصي، إضافة مقطع نص إلى مجموعة مقاطع النص وإلحاقه بصفحة PDF. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // إنشاء مقطع نصي TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // تعيين خصائص النص tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // إضافة مقطع آخر إلى مجموعة مقاطع النص TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // إنشاء كائن TextBuilder TextBuilder builder = new TextBuilder(page); // إلحاق مقطع النص بصفحة PDF builder.appendText(tf); // حفظ المستند doc.save(outFile); </pre> |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBaselinePosition](#getBaselinePosition--) | يحصل على موضع النص للنص، الممثل بكائن {@code TextSegment}. يمثل YIndent في بنية Position إحداثيات الخط الأساسي لمقطع النص. |
| [getCharacters](#getCharacters--) | يحصل على مجموعة من كائنات CharInfo التي تمثل معلومات عن الأحرف في مقطع النص. |
| [getEndCharIndex](#getEndCharIndex--) | يحصل على فهرس الحرف النهائي للمقطع الحالي في عامل إظهار النص (Tj, TJ). |
| [getHyperlink](#getHyperlink--) | يحصل أو يعيّن ارتباط المقطع (لمنشئ PDF). |
| [getPosition](#getPosition--) | يحصل على موضع النص للنص، الممثل بكائن {@code TextSegment}. |
| [getRectangle](#getRectangle--) | يحصل على مستطيل الـ TextSegment |
| [getStartCharIndex](#getStartCharIndex--) | يحصل على فهرس الحرف الابتدائي للمقطع الحالي في عامل إظهار النص (Tj, TJ). |
| [getText](#getText--) | يحصل على كائن النص {@code string} الذي يمثله كائن {@code TextSegment}. |
| [getTextEditOptions](#getTextEditOptions--) | يحصل على خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط. |
| [getTextState](#getTextState--) | <p> يحصل أو يعيّن حالة النص للنص الذي يمثله كائن {@code TextSegment}. </p> <hr> <p> يوفر طريقة لتغيير الخصائص التالية للنص: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | يعيّن موضع النص للنص، الممثل بكائن {@code TextSegment}. يمثل YIndent في بنية Position إحداثيات الخط الأساسي لمقطع النص. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | يحصل أو يعيّن ارتباط المقطع (لمنشئ PDF). |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | يعيّن موضع النص للنص، الممثل بكائن {@code TextSegment}. |
| [setText](#setText-java.lang.String-) | يعيّن كائن النص {@code string} الذي يمثله كائن {@code TextSegment}. |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | يضبط خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | <p> يعيّن حالة النص للنص الذي يمثله كائن {@code TextSegment}. </p> <hr> <p> يوفر طريقة لتغيير الخصائص التالية للنص: Font FontSize FontStyle ForegroundColor BackgroundColor </p> |
| [setTextSuppressedUpdate](#setTextSuppressedUpdate-java.lang.String-) | يعيّن كائن النص {@code string} الذي يمثله كائن {@code TextSegment} مع تحديث مكبوت. |

### TextSegment {#TextSegment--}
```
public TextSegment()
```

<p> ينشئ كائن TextSegment. </p> <hr> <pre> يوضح المثال كيفية إنشاء كائن مقطع نصي، إضافة مقطع نص إلى مجموعة مقاطع النص وإلحاقه بصفحة PDF. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // إنشاء مقطع نصي TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // تعيين خصائص النص tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // إضافة مقطع آخر إلى مجموعة مقاطع النص TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // إنشاء كائن TextBuilder TextBuilder builder = new TextBuilder(page); // إلحاق مقطع النص بصفحة PDF builder.appendText(tf); // حفظ المستند doc.save(outFile); </pre>

### TextSegment {#TextSegment-java.lang.String-}
<p> ينشئ كائن TextSegment. </p> <hr> <pre> يوضح المثال كيفية إنشاء كائن مقطع نصي، إضافة مقطع نص إلى مجموعة مقاطع النص وإلحاقه بصفحة PDF. Document doc = new Document(inFile); Page page = (Page)doc.getPages().get(1); // إنشاء مقطع نصي TextFragment tf = new TextFragment("main text"); tf.setPosition ( new Position(100, 600)); // تعيين خصائص النص tf.getTextState().setFontSize ( 5); tf.getTextState().setFont ( FontRepository.FindFont("TimesNewRoman")); tf.getTextState().setBackgroundColor ( Color.GRAY); tf.getTextState().setForegroundColor ( Color.RED); // إضافة مقطع آخر إلى مجموعة مقاطع النص TextSegment segment2 = new TextSegment(); segment2.setText ( "another segment"); tf.getSegments().add(segment2); // إنشاء كائن TextBuilder TextBuilder builder = new TextBuilder(page); // إلحاق مقطع النص بصفحة PDF builder.appendText(tf); // حفظ المستند doc.save(outFile); </pre>

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

يحصل على موضع النص للنص، الممثل بكائن {@code TextSegment}. يمثل YIndent في بنية Position إحداثيات الخط الأساسي لمقطع النص.

**Returns:**
قيمة الموضع

### getCharacters {#getCharacters--}
```
public CharInfoCollection getCharacters()
```

يحصل على مجموعة من كائنات CharInfo التي تمثل معلومات عن الأحرف في مقطع النص.

**Returns:**
كائن CharInfoCollection

### getEndCharIndex {#getEndCharIndex--}
```
public int getEndCharIndex()
```

يحصل على فهرس الحرف النهائي للمقطع الحالي في عامل إظهار النص (Tj, TJ).

**Returns:**
قيمة int

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

يحصل أو يعيّن ارتباط المقطع (لمنشئ PDF).

**Returns:**
كائن Hyperlink

### getPosition {#getPosition--}
```
public Position getPosition()
```

يحصل على موضع النص للنص، الممثل بكائن {@code TextSegment}.

**Returns:**
قيمة الموضع

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

يحصل على مستطيل الـ TextSegment

**Returns:**
كائن Rectangle

### getStartCharIndex {#getStartCharIndex--}
```
public int getStartCharIndex()
```

يحصل على فهرس الحرف الابتدائي للمقطع الحالي في عامل إظهار النص (Tj, TJ).

**Returns:**
قيمة int

### getText {#getText--}
```
public String getText()
```

يحصل على كائن النص {@code string} الذي يمثله كائن {@code TextSegment}.

**Returns:**
قيمة سلسلة

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

يحصل على خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط.

**Returns:**
قيمة TextEditOptions

### getTextState {#getTextState--}
```
public TextState getTextState()
```

<p> يحصل أو يعيّن حالة النص للنص الذي يمثله كائن {@code TextSegment}. </p> <hr> <p> يوفر طريقة لتغيير الخصائص التالية للنص: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

**Returns:**
قيمة TextState

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
يعيّن موضع النص للنص، الممثل بكائن {@code TextSegment}. يمثل YIndent في بنية Position إحداثيات الخط الأساسي لمقطع النص.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
يحصل أو يعيّن ارتباط المقطع (لمنشئ PDF).

### setPosition {#setPosition-com.aspose.pdf.Position-}
يعيّن موضع النص للنص، الممثل بكائن {@code TextSegment}.

### setText {#setText-java.lang.String-}
يعيّن كائن النص {@code string} الذي يمثله كائن {@code TextSegment}.

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
يضبط خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
<p> يعيّن حالة النص للنص الذي يمثله كائن {@code TextSegment}. </p> <hr> <p> يوفر طريقة لتغيير الخصائص التالية للنص: Font FontSize FontStyle ForegroundColor BackgroundColor </p>

### setTextSuppressedUpdate {#setTextSuppressedUpdate-java.lang.String-}
يعيّن كائن النص {@code string} الذي يمثله كائن {@code TextSegment} مع تحديث مكبوت.
