---
title: Class TextFragment
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Text.TextFragment. تمثل جزء من نص PDF
type: docs
weight: 10940
url: /ar/net/aspose.pdf.text/textfragment/
---
## فئة TextFragment

تمثل جزء من نص PDF.

```csharp
public class TextFragment : BaseParagraph
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | يقوم بتهيئة مثيل جديد من كائن `TextFragment`. |
| [TextFragment](textfragment/#constructor_2)(string) | ينشئ كائن `TextFragment` مع كائن [`TextSegment`](../textsegment/) واحد بداخله. يحدد سلسلة النص داخل الجزء. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | يقوم بتهيئة مثيل جديد من كائن `TextFragment` مع مواضع [`TabStops`](../tabstops/) محددة مسبقًا. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | ينشئ كائن `TextFragment` مع كائن [`TextSegment`](../textsegment/) واحد بداخله ومواضع [`TabStops`](../tabstops/) محددة مسبقًا. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | يحصل على موضع النص للنص، الممثل بكائن `TextFragment`. يمثل YIndent في هيكل Position إحداثيات خط الأساس لجزء النص. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | يحصل أو يحدد ملاحظة نهاية الفقرة. (لإنشاء PDF فقط) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | يحصل أو يحدد ملاحظة أسفل الفقرة. (لإنشاء PDF فقط) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | يحصل على كائن النموذج الذي يحتوي على TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | يحصل أو يحدد محاذاة أفقية لجزء النص. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | يحدد رابط الجزء |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل أو يحدد ما إذا كانت الفقرة في السطر. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل أو يحدد قيمة بوليانية تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يحدد هامش خارجي للفقرة (لإنشاء PDF) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | يحصل على الصفحة التي تحتوي على TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | يحصل أو يحدد موضع النص للنص، الممثل بكائن `TextFragment`. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | يحصل على مستطيل TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | يحصل على خيارات استبدال النص. تحدد الخيارات السلوك عند استبدال نص الجزء بنص أقصر/أطول. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | يحصل على أجزاء النص للـ `TextFragment` الحالي. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | يحصل أو يحدد كائن نص السلسلة الذي يمثله كائن `TextFragment`. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | يحصل أو يحدد خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | يحصل أو يحدد حالة النص للنص الذي يمثله كائن `TextFragment`. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | يحصل أو يحدد محاذاة عمودية لجزء النص. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | يحصل أو يحدد عدد الأسطر الملتفة لهذه الفقرة (لإنشاء PDF فقط) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يحدد قيمة صحيحة تشير إلى ترتيب Z للرسم. سيتم وضع رسم مع ZIndex أكبر فوق الرسم مع ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. سيتم وضع الرسم مع ZIndex سالب خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | استنساخ الجزء. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | استنساخ الجزء مع جميع الأجزاء. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | يحصل على [`TextSegment`](../textsegment/)(s) التي تمثل الجزء المحدد من نص `TextFragment`. |

## الملاحظات

باختصار، يحتوي كائن `TextFragment` على قائمة من كائنات [`TextSegment`](../textsegment/). بالتفصيل: يتم تمثيل نص مستند PDF في PDF بواسطة كائنين أساسيين: `TextFragment` و [`TextSegment`](../textsegment/) الاختلافات بينهما تعتمد في الغالب على السياق. دعونا نعتبر السيناريو التالي. يبحث المستخدم عن النص "hello world" للتعامل معه، وتغيير خصائصه، والنظر وما إلى ذلك.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

تمثيل النص في PDF معقد للغاية. قد يتكون النص "hello world" من عدة أجزاء نصية مستقلة ماديًا. يحدد نموذج نص Aspose.Pdf أساسًا أن كائن `TextFragment` يوفر مجموعة عمليات منطقية واحدة على مجموعة كائنات [`TextSegment`](../textsegment/) المادية التي تمثل استعلام المستخدم. في سيناريو بحث النص، يمثل `TextFragment` التمثيل المنطقي للنص "hello world"، ومجموعة كائنات [`TextSegment`](../textsegment/) تمثل جميع الأجزاء المادية التي تشكل كائن النص "hello world". لذا، فإن `TextFragment` قريب من التمثيل النصي المنطقي. و [`TextSegment`](../textsegment/) قريب من التمثيل النصي المادي. من الواضح أن كل كائن [`TextSegment`](../textsegment/) قد يكون له خطه الخاص، وألوانه، وخصائص موضعه. يوفر `TextFragment` طريقة بسيطة لتغيير النص مع خصائصه: تعيين الخط، تعيين حجم الخط، تعيين لون الخط، إلخ. في الوقت نفسه، تكون كائنات [`TextSegment`](../textsegment/) متاحة ويمكن للمستخدمين التعامل مع كائنات [`TextSegment`](../textsegment/) بشكل مستقل. لاحظ أن تغيير خصائص TextFragment قد يغير مجموعة [`Segments`](./segments/) الداخلية لأن TextFragment هو كائن تجميعي وقد يعيد ترتيب الأجزاء الداخلية أو دمجها في جزء واحد. إذا كانت متطلباتك هي ترك مجموعة [`Segments`](./segments/) دون تغيير، يرجى تغيير الأجزاء الداخلية بشكل فردي.

## أمثلة

توضح المثال كيفية العثور على نص في الصفحة الأولى من مستند PDF واستبدال النص وخطه.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* فئة [BaseParagraph](../../aspose.pdf/baseparagraph/)
* مساحة الأسماء [Aspose.Pdf.Text](../../aspose.pdf.text/)
* التجميع [Aspose.PDF](../../)