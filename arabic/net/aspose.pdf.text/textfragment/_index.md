---
title: TextFragment
second_title: Aspose.PDF لمرجع .NET API
description: يمثل جزءًا من نص Pdf.
type: docs
weight: 7100
url: /ar/net/aspose.pdf.text/textfragment/
---
## TextFragment class

يمثل جزءًا من نص Pdf.

```csharp
public class TextFragment : BaseParagraph
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [TextFragment](textfragment#constructor)() | تهيئة مثيل جديد لملف[`TextFragment`](../textfragment) الكائن . |
| [TextFragment](textfragment#constructor_2)(string) | يخلق[`TextFragment`](../textfragment) كائن واحد[`TextSegment`](../textsegment) داخل الكائن. تحديد سلسلة نصية داخل المقطع . |
| [TextFragment](textfragment#constructor_1)(TabStops) | تهيئة مثيل جديد لملف[`TextFragment`](../textfragment) معرّف مسبقًا[`TabStops`](../tabstops) المواقف . |
| [TextFragment](textfragment#constructor_3)(string, TabStops) | يخلق[`TextFragment`](../textfragment) كائن واحد[`TextSegment`](../textsegment) كائن داخلي ومحدّد مسبقًا[`TabStops`](../tabstops) المواقف . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | الحصول على موضع النص للنص ، ممثلاً بامتداد[`TextFragment`](../textfragment) object. تمثل نهاية Y لهيكل الموضع إحداثيات خط الأساس لجزء النص. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | الحصول على أو تعيين ملاحظة نهاية الفقرة. (لإنشاء ملف pdf فقط) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | الحصول على حاشية الفقرة السفلية أو تعيينها. (لإنشاء ملف pdf فقط) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | الحصول على كائن النموذج الذي يحتوي على TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | الحصول على محاذاة أفقية لجزء النص أو تعيينها. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | تعيين الارتباط التشعبي للجزء |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية خطأ. (لتوليد pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | الحصول على فقرة مضمنة أو تعيينها . الإعداد الافتراضي خطأ. (لإنشاء ملف pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | الحصول على أو تعيين قيمة منطقية تفرض إنشاء هذه الفقرة في صفحة جديدة. القيمة الافتراضية خطأ. (لتوليد pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كانت الفقرة الحالية ستبقى في نفس الصفحة مع الفقرة التالية. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | الحصول على أو تعيين هامش خارجي للفقرة (لتوليد pdf) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | يحصل على الصفحة التي تحتوي على TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | الحصول على أو تعيين موضع النص للنص ، ممثلاً بامتداد[`TextFragment`](../textfragment) الكائن . |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | يحصل على مستطيل من TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | يحصل على خيارات استبدال النص. تحدد الخيارات السلوك عند استبدال نص الجزء بمزيد من الاختصار / الطويل. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | الحصول على مقاطع نصية للتيار[`TextFragment`](../textfragment) . |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | يحصل أو يحددString كائن النص الذي[`TextFragment`](../textfragment) يمثل الكائن . |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | الحصول على أو تعيين حالة النص للنص الذي[`TextFragment`](../textfragment) يمثل الكائن . |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | الحصول على محاذاة عمودية لجزء النص أو تعيينها. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | الحصول على عدد سطور الالتفاف لهذه الفقرة أو تعيينه (لإنشاء ملف pdf فقط) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | الحصول على أو تحديد قيمة int التي تشير إلى ترتيب Z للرسم البياني. سيتم وضع رسم بياني به ZIndex أكبر فوق الرسم البياني باستخدام ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني بالسالب سيتم وضع مؤشر Z خلف النص في الصفحة. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone)() | استنساخ الجزء . |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments)() | استنساخ الجزء بكل المقاطع. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | يحصل[`TextSegment`](../textsegment) (ق) تمثل جزءًا محددًا من[`TextFragment`](../textfragment) نص . |

### ملاحظات

في بضع كلمات ،[`TextFragment`](../textfragment) يحتوي الكائن على قائمة[`TextSegment`](../textsegment) objects. بالتفصيل: نص مستند pdf بتنسيقPdf يتم تمثيله بواسطة كائنين أساسيين:[`TextFragment`](../textfragment) و[`TextSegment`](../textsegment) معظم الاختلافات بينهما تعتمد على السياق . لنفكر في السيناريو التالي. يبحث المستخدم عن نص "hello world" للعمل به ، وتغيير خصائصه ، والبحث وما إلى ذلك. تمثيل نص pdf Phisycally معقد للغاية. قد يتكون النص "hello world" من عدة مقاطع نصية مستقلة phisycally.[`TextFragment`](../textfragment) يوفر object عملية منطقية واحدة فوق مادي[`TextSegment`](../textsegment) مجموعة الكائنات التي تمثل استعلام المستخدم. في سيناريو البحث عن النص ،[`TextFragment`](../textfragment) هو تمثيل نصي منطقي "hello world" ، و[`TextSegment`](../textsegment)تمثل مجموعة الكائنات جميع الأجزاء المادية التي تنشئ كائن نص "hello world". لذا ،[`TextFragment`](../textfragment) يقترب من تمثيل النص المنطقي . و[`TextSegment`](../textsegment) هو قريب من تمثيل النص المادي. من الواضح أن كل منهما[`TextSegment`](../textsegment) قد يكون للكائن خط خاص به ، ولونه ، وخصائص تحديد الموضع.[`TextFragment`](../textfragment) يوفر طريقة بسيطة لتغيير النص بخصائصه: ضبط الخط ، ضبط حجم الخط ، ضبط لون الخط وما إلى ذلك. في غضون ذلك[`TextSegment`](../textsegment) كائنات يمكن الوصول إليها ويمكن للمستخدمين العمل معها[`TextSegment`](../textsegment) بشكل مستقل. لاحظ أن تغيير خصائص TextFragment قد يغير الجزء الداخلي[`Segments`](./segments) لأن TextFragment عبارة عن كائن مجمع وقد يعيد ترتيب المقاطع الداخلية أو يدمجها في مقطع واحد. إذا كان مطلبك هو ترك[`Segments`](./segments)المجموعة دون تغيير ، يرجى تغيير الأجزاء الداخلية بشكل فردي.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### أمثلة

يوضح المثال كيفية البحث عن نص في صفحة مستند PDF الأولى واستبدال النص والخط.

```csharp
// افتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// ابحث عن الخط الذي سيتم استخدامه لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات نص "أهلًا بالعالم"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير النص والخط عند ظهور النص الأول
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// حفظ الوثيقة
doc.Save(@"D:\Tests\output.pdf");  
```

### أنظر أيضا

* class [BaseParagraph](../../aspose.pdf/baseparagraph)
* مساحة الاسم [Aspose.Pdf.Text](../../aspose.pdf.text)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
