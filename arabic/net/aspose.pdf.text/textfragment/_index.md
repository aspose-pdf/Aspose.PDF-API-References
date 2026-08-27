---
title: "الفئة TextFragment"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Text.TextFragment. تمثّل جزءًا من نص Pdf"
type: docs
weight: 11120
url: /ar/net/aspose.pdf.text/textfragment/
---
## TextFragment class

يمثل جزءًا من نص Pdf.

```csharp
public class TextFragment : BaseParagraph
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextFragment](textfragment/#constructor)() | يُهيئ نسخة جديدة من الكائن `TextFragment`. |
| [TextFragment](textfragment/#constructor_2)(string) | ينشئ كائن `TextFragment` مع كائن [`TextSegment`](../textsegment/) واحد بداخله. يحدد سلسلة النص داخل الجزء. |
| [TextFragment](textfragment/#constructor_1)(TabStops) | يُهيئ نسخة جديدة من كائن `TextFragment` مع مواضع [`TabStops`](../tabstops/) معرفة مسبقًا. |
| [TextFragment](textfragment/#constructor_3)(string, TabStops) | ينشئ كائن `TextFragment` مع كائن [`TextSegment`](../textsegment/) واحد بداخله ومواضع [`TabStops`](../tabstops/) معرفة مسبقًا. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | يحصل على موضع النص للنص الممثَّل بكائن `TextFragment`. يمثل YIndent في بنية Position إحداثية الخط الأساسي لجزء النص. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | يحصل أو يعيّن ملاحظة نهاية الفقرة. (لإنشاء pdf فقط) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | يحصل أو يعيّن حاشية الفقرة. (لإنشاء pdf فقط) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | يحصل على كائن النموذج الذي يحتوي على TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | يحصل أو يعيّن محاذاة أفقية لجزء النص. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | يعيّن الارتباط التشعبي للجزء. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كان هذا الفقرة سيظهر في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | الحصول على أو تعيين ما إذا كانت الفقرة مضمنة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | الحصول على أو تعيين قيمة bool تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يعيّن هامشًا خارجيًا للفقرة (لإنشاء PDF) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | يحصل على الصفحة التي تحتوي على TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | يحصل أو يعيّن موضع النص للنص الممثَّل بكائن `TextFragment`. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | يحصل على المستطيل الخاص بـ TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | يحصل على خيارات استبدال النص. تحدد الخيارات السلوك عندما يتم استبدال نص الجزء إلى أقصر أو أطول. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | يحصل على مقاطع النص للـ `TextFragment` الحالي. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | يحصل أو يعيّن كائن النص من نوع String الذي يمثله كائن `TextFragment`. |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | يحصل أو يعيّن خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | يحصل أو يعيّن حالة النص للنص الذي يمثله كائن `TextFragment`. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة رأسية لجزء النص. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | يحصل أو يعيّن عدد أسطر الالتفاف لهذه الفقرة (لإنشاء pdf فقط) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone/)() | استنسخ الجزء. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments/)() | استنسخ الجزء مع جميع المقاطع. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | يحصل على [`TextSegment`](../textsegment/)(s) التي تمثل الجزء المحدد من نص `TextFragment`. |

## ملاحظات

باختصار، كائن `TextFragment` يحتوي على قائمة من كائنات [`TextSegment`](../textsegment/). بالتفصيل: نص مستند pdf في Pdf يُمثَّل بواسطة كائنين أساسيين: `TextFragment` و[`TextSegment`](../textsegment/). الاختلاف بينهما يعتمد في الغالب على السياق. لننظر إلى السيناريو التالي. يبحث المستخدم عن النص \"hello world\" للتعامل معه، وتغيير خصائصه، وعرضه، إلخ.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

تمثيل نص pdf فعليًا معقد جدًا. قد يتكون النص \"hello world\" من عدة مقاطع نصية مستقلة ماديًا. يحدد نموذج نص Aspose.Pdf أساسًا أن كائن `TextFragment` يوفر مجموعة عمليات منطقية واحدة على مجموعة كائنات [`TextSegment`](../textsegment/) الفيزيائية التي تمثل استعلام المستخدم. في سيناريو البحث النصي، يمثل `TextFragment` تمثيلًا منطقيًا للنص \"hello world\"، وتجمع كائنات [`TextSegment`](../textsegment/) يمثل جميع المقاطع الفيزيائية التي تُكوِّن كائن النص \"hello world\". لذا، `TextFragment` قريب من تمثيل النص المنطقي. و[`TextSegment`](../textsegment/) قريب من تمثيل النص الفيزيائي. من الواضح أن كل كائن [`TextSegment`](../textsegment/) قد يمتلك خطه، لونه، وخصائص التموضع الخاصة به. يوفر `TextFragment` طريقة بسيطة لتغيير النص مع خصائصه: تعيين الخط، حجم الخط، لون الخط، إلخ. في الوقت نفسه، يمكن الوصول إلى كائنات [`TextSegment`](../textsegment/) ويستطيع المستخدمون التعامل معها بشكل مستقل. لاحظ أن تغيير خصائص `TextFragment` قد يغيّر مجموعة [`Segments`](./segments/) الداخلية لأن `TextFragment` هو كائن تجميعي وقد يعيد ترتيب المقاطع الداخلية أو يدمجها في مقطع واحد. إذا كان متطلبك هو ترك مجموعة [`Segments`](./segments/) دون تغيير، يرجى تعديل المقاطع الداخلية بشكل فردي.

## أمثلة

يوضح المثال كيفية العثور على النص في الصفحة الأولى من مستند PDF وتبديل النص وخطه.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// العثور على الخط الذي سيُستخدم لتغيير خط نص المستند
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير النص والخط لأول تكرار نص
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


