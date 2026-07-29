---
title: "TextFragment"
linktitle: "TextFragment"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> تمثّل جزءًا من نص PDF. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص وخطّه. // Open document."
type: docs
weight: 5110
url: /ar/java/com.aspose.pdf/textfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TextFragment extends BaseParagraph
```

<p> يمثل جزءًا من نص Pdf. </p> <hr> <pre> يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF واستبدال النص وخطّه. // فتح المستند Document doc = new Document("input.pdf"); // العثور على الخط الذي سيُستخدم لتغيير خط نص المستند Font font = FontRepository.findFont("Arial"); // إنشاء كائن TextFragmentAbsorber للعثور على جميع مرات ظهور النص "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // قبول الـ absorber للصفحة الأولى doc.getPages().get(1).accept(absorber); // تغيير النص وخط أول مرة ظهور للنص absorber.getTextFragments().get_Item(1).setText ( "hi world"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // حفظ المستند doc.save("output.pdf"); </pre> <hr> <pre> في بضع كلمات، يحتوي كائن {@code TextFragment} على قائمة من كائنات {@code TextSegment}. بالتفصيل: نص مستند pdf في {@code com.aspose.pdf} يُمثَّل بواسطة كائنين أساسيين: {@code TextFragment} و {@code TextSegment} الاختلافات بينهما تعتمد في الغالب على السياق. لننظر في السيناريو التالي. يقوم المستخدم بالبحث عن النص "hello world" للتعامل معه، وتغيير خصائصه، وما إلى ذلك. Document doc = new Document(docFile); TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); doc.getPages().get(1).accept(absorber); </pre> تمثيل النص pdf الفيزيائي معقد جدًا. قد يتكون النص "hello world" من عدة مقاطع نصية مستقلة فيزيائيًا. نموذج نص Aspose.Pdf يوضح أساسًا أن كائن {@code TextFragment} يوفر مجموعة عمليات منطقية واحدة فوق مجموعة {@code TextSegment} الفيزيائية التي تمثل استعلام المستخدم. في سيناريو البحث النصي، يمثل {@code TextFragment} تمثيل النص "hello world" المنطقي، وتجمع كائنات {@code TextSegment} يمثل جميع المقاطع الفيزيائية التي تُكوّن كائن النص "hello world". لذلك، فإن {@code TextFragment} قريب من تمثيل النص المنطقي. و {@code TextSegment} قريب من تمثيل النص الفيزيائي. من الواضح أن كل كائن {@code TextSegment} قد يمتلك خطه الخاص، وتلوينه، وخصائص التموقع. يوفر {@code TextFragment} طريقة بسيطة لتغيير النص بخصائصه: تعيين الخط، تعيين حجم الخط، تعيين لون الخط، إلخ. في الوقت نفسه، يمكن الوصول إلى كائنات {@code TextSegment} ويستطيع المستخدمون التعامل مع كائنات {@code TextSegment} بشكل مستقل. <p> لاحظ أن تغيير خصائص TextFragment قد يغيّر مجموعة {@code Segments} الداخلية لأن TextFragment هو كائن تجميعي وقد يعيد ترتيب المقاطع الداخلية أو يدمجها في مقطع واحد. إذا كان متطلبك هو ترك مجموعة {@code Segments} دون تغيير، يرجى تغيير المقاطع الداخلية بشكل فردي. </p>

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextFragment](#TextFragment--) | يُهيئ نسخة جديدة من كائن {@code TextFragment}. |
| [TextFragment](#TextFragment-java.lang.String-) | يُهيئ نسخة جديدة من كائن {@code TextFragment}. |
| [TextFragment](#TextFragment-java.lang.String-com.aspose.pdf.TabStops-) | يُهيئ نسخة جديدة من كائن {@code TextFragment}. |
| [TextFragment](#TextFragment-com.aspose.pdf.TabStops-) | يُهيئ نسخة جديدة من كائن {@code TextFragment}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | استنساخ القطعة مع جميع المقاطع. |
| [deepClone](#deepClone--) | استنساخ القطعة. |
| [getBaselinePosition](#getBaselinePosition--) | يحصل على موضع النص للنص، الممثَّل بكائن {@code TextFragment}. يمثل YIndent في بنية Position إحداثي خط الأساس لقطعة النص. |
| [getEndNote](#getEndNote--) | يحصل على ملاحظة نهاية الفقرة (لإنشاء PDF فقط). |
| [getFootNote](#getFootNote--) | يحصل على ملاحظة تذييل الفقرة (لإنشاء PDF فقط). |
| [getForm](#getForm--) | يحصل على كائن النموذج الذي يحتوي على TextFragment. يمكن أن تكون القيمة فارغة إذا لم يكن كائن TextFragment ينتمي إلى نموذج. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | يحصل على محاذاة أفقية لقطعة النص. |
| [getPage](#getPage--) | يحصل على الصفحة التي تحتوي على TextFragment. يمكن أن تكون القيمة فارغة إذا لم يكن كائن TextFragment ينتمي إلى أي صفحة. |
| [getPosition](#getPosition--) | <p> يحصل على موضع النص للنص، الممثَّل بكائن {@code TextFragment}. </p> |
| [getRectangle](#getRectangle--) | يحصل على المستطيل الخاص بـ TextFragment |
| [getReplaceOptions](#getReplaceOptions--) | يحصل على خيارات استبدال النص. تحدد الخيارات السلوك عند استبدال نص القطعة إلى أقصر أو أطول. |
| [getSegments](#getSegments--) | <p> يحصل على مقاطع النص للـ {@code TextFragment} الحالي. </p> |
| [getText](#getText--) | <p> يحصل على كائن النص {@code string} الذي يمثله كائن {@code TextFragment}. </p> |
| [getTextEditOptions](#getTextEditOptions--) | يحصل أو يضبط خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط. |
| [getTextState](#getTextState--) | <p> يحصل أو يضبط حالة النص للنص الذي يمثله كائن {@code TextFragment}. </p> |
| [getVerticalAlignment](#getVerticalAlignment--) | يحصل على محاذاة عمودية لقطعة النص. |
| [getWrapLinesCount](#getWrapLinesCount--) | يحصل على عدد أسطر الالتفاف لهذه الفقرة (لإنشاء PDF فقط) |
| [isolateTextSegments](#isolateTextSegments-int-int-) | يحصل على {@code TextSegment}(s) التي تمثل الجزء المحدد من نص {@code TextFragment}. |
| [setBaselinePosition](#setBaselinePosition-com.aspose.pdf.Position-) | يضبط موضع النص للنص، الممثَّل بكائن {@code TextFragment}. يمثل YIndent في بنية Position إحداثي خط الأساس لقطعة النص. |
| [setEndNote](#setEndNote-com.aspose.pdf.Note-) | يضبط ملاحظة نهاية الفقرة (لإنشاء PDF فقط). |
| [setFootNote](#setFootNote-com.aspose.pdf.Note-) | يضبط ملاحظة تذييل الفقرة (لإنشاء PDF فقط). |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | يضبط محاذاة أفقية لقطعة النص. |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | يضبط الارتباط التشعبي للقطعة |
| [setMarkedContentProperties](#setMarkedContentProperties-java.lang.String-int-) |  |
| [setPosition](#setPosition-com.aspose.pdf.Position-) | <p> يضبط موضع النص للنص، الممثَّل بكائن {@code TextFragment}. </p> |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | يحصل على المستطيل الخاص بـ TextFragment |
| [setSegments](#setSegments-com.aspose.pdf.TextSegmentCollection-) | تمثيل طريقة setSegments |
| [setText](#setText-java.lang.String-) | <p> يحدد كائن النص {@code string} الذي تمثله كائن {@code TextFragment}. </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | يحصل أو يضبط خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | يضبط محاذاة عمودية لجزء النص. |
| [setWrapLinesCount](#setWrapLinesCount-int-) | يضبط عدد أسطر الالتفاف لهذه الفقرة (لإنشاء PDF فقط) |

### TextFragment {#TextFragment--}
```
public TextFragment()
```

يُهيئ نسخة جديدة من كائن {@code TextFragment}.

### TextFragment {#TextFragment-java.lang.String-}
يُهيئ نسخة جديدة من كائن {@code TextFragment}.

### TextFragment {#TextFragment-java.lang.String-com.aspose.pdf.TabStops-}
يُهيئ نسخة جديدة من كائن {@code TextFragment}.

### TextFragment {#TextFragment-com.aspose.pdf.TabStops-}
يُهيئ نسخة جديدة من كائن {@code TextFragment}.

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

استنساخ القطعة مع جميع المقاطع.

**Returns:**
الكائن المستنسخ

### deepClone {#deepClone--}
```
public Object deepClone()
```

استنساخ القطعة.

**Returns:**
الكائن المستنسخ

### getBaselinePosition {#getBaselinePosition--}
```
public Position getBaselinePosition()
```

يحصل على موضع النص للنص، الممثَّل بكائن {@code TextFragment}. يمثل YIndent في بنية Position إحداثي خط الأساس لقطعة النص.

**Returns:**
قيمة الموضع

### getEndNote {#getEndNote--}
```
public Note getEndNote()
```

يحصل على ملاحظة نهاية الفقرة (لإنشاء PDF فقط).

**Returns:**
قيمة الملاحظة

### getFootNote {#getFootNote--}
```
public Note getFootNote()
```

يحصل على ملاحظة تذييل الفقرة (لإنشاء PDF فقط).

**Returns:**
قيمة الملاحظة

### getForm {#getForm--}
```
public XForm getForm()
```

يحصل على كائن النموذج الذي يحتوي على TextFragment. يمكن أن تكون القيمة فارغة إذا لم يكن كائن TextFragment ينتمي إلى نموذج.

**Returns:**
قيمة XForm

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

يحصل على محاذاة أفقية لقطعة النص.

**Returns:**
قيمة HorizontalAlignment @see HorizontalAlignment

### getPage {#getPage--}
```
public Page getPage()
```

يحصل على الصفحة التي تحتوي على TextFragment. يمكن أن تكون القيمة فارغة إذا لم يكن كائن TextFragment ينتمي إلى أي صفحة.

**Returns:**
كائن Page

### getPosition {#getPosition--}
```
public Position getPosition()
```

<p> يحصل على موضع النص للنص، الممثَّل بكائن {@code TextFragment}. </p>

**Returns:**
قيمة الموضع <hr> <pre> يوضح المثال كيفية عرض موضع نص ممثل بواسطة كائن {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // View text and placement info of first text occurrence TextFragment firstOccurrence = absorber.getTextFragments().get_Item(1); System.out.println("fragment text: " + firstOccurrence.getText())); System.out.println("fragment X indent: "+ firstOccurrence.getPosition().getXIndent())); System.out.println("fragment Y indent: "+ firstOccurrence.getPosition().getYIndent())); </pre> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

يحصل على المستطيل الخاص بـ TextFragment

**Returns:**
كائن Rectangle

### getReplaceOptions {#getReplaceOptions--}
```
public final TextReplaceOptions getReplaceOptions()
```

يحصل على خيارات استبدال النص. تحدد الخيارات السلوك عند استبدال نص القطعة إلى أقصر أو أطول.

**Returns:**
مثيل TextReplaceOptions

### getSegments {#getSegments--}
```
public TextSegmentCollection getSegments()
```

<p> يحصل على مقاطع النص للـ {@code TextFragment} الحالي. </p>

**Returns:**
قيمة TextSegmentCollection <hr> <pre> يوضح المثال كيفية التنقل عبر جميع كائنات {@code TextSegment} داخل {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Navigate all text segments and out their text and placement info for (TextSegment segment : ({@code Iterable<TextSegment>})absorber.getTextFragments().get_Item(1).getSegments()) { System.out.println("segment text: "+ segment.getText())); System.out.println("segment X indent: "+ segment.getPosition().getXIndent())); System.out.println("segment Y indent: "+ segment.getPosition().getYIndent())); } </pre> <hr> <p> بكلمات قليلة، كائنات {@code TextSegment} هي أبناء كائن {@code TextFragment}. قد يتمكن المستخدمون المتقدمون من الوصول إلى المقاطع مباشرةً لتنفيذ سيناريوهات تحرير نص أكثر تعقيدًا. للحصول على تفاصيل، يرجى الاطلاع على وصف كائن {@code TextFragment}. </p> @see TextFragmentAbsorber @see IDocument @see TextSegment

### getText {#getText--}
```
public String getText()
```

<p> يحصل على كائن النص {@code string} الذي يمثله كائن {@code TextFragment}. </p>

**Returns:**
قيمة String <hr> <pre> يوضح المثال كيفية البحث عن نص واستبدال أول ظهور ممثل بواسطة كائن {@code TextFragment}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

### getTextEditOptions {#getTextEditOptions--}
```
public final TextEditOptions getTextEditOptions()
```

يحصل أو يضبط خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط.

**Returns:**
مثيل TextEditOptions

### getTextState {#getTextState--}
```
public TextFragmentState getTextState()
```

<p> يحصل أو يضبط حالة النص للنص الذي يمثله كائن {@code TextFragment}. </p>

**Returns:**
كائن TextFragmentState <hr> <pre> يوضح المثال كيفية تغيير لون النص وحجم الخط للنص باستخدام كائن {@code TextState}. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change foreground color of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setForegroundColor(Color.RED); // Change font size of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFontSize ( 15); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> يوفر طريقة لتغيير الخصائص التالية للنص: Font FontSize FontStyle ForegroundColor BackgroundColor </p> @see TextFragmentAbsorber @see IDocument

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

يحصل على محاذاة عمودية لقطعة النص.

**Returns:**
قيمة int @see VerticalAlignment

### getWrapLinesCount {#getWrapLinesCount--}
```
public int getWrapLinesCount()
```

يحصل على عدد أسطر الالتفاف لهذه الفقرة (لإنشاء PDF فقط)

**Returns:**
قيمة int

### isolateTextSegments {#isolateTextSegments-int-int-}
```
public TextSegmentCollection isolateTextSegments(int startIndex, int length)
```

يحصل على {@code TextSegment}(s) التي تمثل الجزء المحدد من نص {@code TextFragment}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startIndex |  | الموضع في النص الذي سيبدأ منه {@code TextSegment}(s) الجديد. |
| length |  | طول النص الذي سيُعزل في {@code TextSegment}(s). |

**Returns:**
{@code TextSegmentCollection} التي تحتوي على مقاطع نصية تمثل جزءًا من النص يبدأ من موضع محدد ويملك طولًا محددًا.

### setBaselinePosition {#setBaselinePosition-com.aspose.pdf.Position-}
يضبط موضع النص للنص، الممثَّل بكائن {@code TextFragment}. يمثل YIndent في بنية Position إحداثي خط الأساس لقطعة النص.

### setEndNote {#setEndNote-com.aspose.pdf.Note-}
يضبط ملاحظة نهاية الفقرة (لإنشاء PDF فقط).

### setFootNote {#setFootNote-com.aspose.pdf.Note-}
يضبط ملاحظة تذييل الفقرة (لإنشاء PDF فقط).

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
يضبط محاذاة أفقية لقطعة النص.

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
يضبط الارتباط التشعبي للقطعة

### setMarkedContentProperties {#setMarkedContentProperties-java.lang.String-int-}


### setPosition {#setPosition-com.aspose.pdf.Position-}
<p> يضبط موضع النص للنص، الممثَّل بكائن {@code TextFragment}. </p>

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
يحصل على المستطيل الخاص بـ TextFragment

### setSegments {#setSegments-com.aspose.pdf.TextSegmentCollection-}
تمثيل طريقة setSegments

### setText {#setText-java.lang.String-}
<p> يحدد كائن النص {@code string} الذي تمثله كائن {@code TextFragment}. </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
يحصل أو يضبط خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
يضبط محاذاة عمودية لجزء النص.

### setWrapLinesCount {#setWrapLinesCount-int-}
```
public void setWrapLinesCount(int value)
```

يضبط عدد أسطر الالتفاف لهذه الفقرة (لإنشاء PDF فقط)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |
