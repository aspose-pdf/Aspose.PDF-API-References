---
title: "الفئة TextSegment"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Text.TextSegment. تمثل جزءًا من نص Pdf"
type: docs
weight: 11240
url: /ar/net/aspose.pdf.text/textsegment/
---
## TextSegment class

يمثل جزءًا من نص Pdf.

```csharp
public sealed class TextSegment
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | ينشئ كائن TextSegment. |
| [TextSegment](textsegment/#constructor_1)(string) | ينشئ كائن TextSegment. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | يحصل على موضع النص للنص، ممثلًا بكائن `TextSegment`. يمثل YIndent في بنية Position إحداثيات الخط الأساسي لمقطع النص. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | يحصل على مجموعة من كائنات CharInfo التي تمثل معلومات عن الأحرف في مقطع النص. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | يحصل على فهرس الحرف النهائي للمقطع الحالي في مشغل إظهار النص (Tj, TJ). |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | يحصل أو يضبط ارتباط المقطع (لمنشئ PDF). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | يحصل على موضع النص للنص، ممثلًا بكائن `TextSegment`. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | يحصل على مستطيل الـ TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | يحصل على فهرس الحرف الابتدائي للمقطع الحالي في مشغل إظهار النص (Tj, TJ). |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | يحصل أو يضبط كائن النص String الذي يمثله كائن `TextSegment`. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | يحصل أو يعيّن خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | يحصل أو يضبط حالة النص للنص الذي يمثله كائن `TextSegment`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | يقوم بترميز السلسلة كـ html. |

## ملاحظات

بكلمات قليلة، كائنات `TextSegment` هي أبناء كائن [`TextFragment`](../textfragment/). بالتفصيل: نص مستند PDF في Pdf يُمثَّل بواسطة كائنين أساسيين: [`TextFragment`](../textfragment/) و`TextSegment`. الاختلافات بينهما تعتمد في الغالب على السياق. لننظر إلى السيناريو التالي. يبحث المستخدم عن النص \"hello world\" للتعامل معه، وتغيير خصائصه، وما إلى ذلك.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

تمثيل نص PDF فعليًا معقد جدًا. قد يتكون النص \"hello world\" من عدة مقاطع نصية مستقلة فعليًا. نموذج نص Aspose.Pdf يحدد أساسًا أن كائن [`TextFragment`](../textfragment/) يوفر مجموعة عمليات منطقية واحدة على مجموعة كائنات `TextSegment` الفعلية التي تمثل استعلام المستخدم. في سيناريو البحث النصي، يكون [`TextFragment`](../textfragment/) تمثيلًا منطقيًا للنص \"hello world\"، وتجمع كائنات `TextSegment` يمثل جميع المقاطع الفعلية التي تُنشئ كائن النص \"hello world\". لذا، فإن [`TextFragment`](../textfragment/) قريب من تمثيل النص المنطقي. و`TextSegment` قريب من تمثيل النص الفعلي. من الواضح أن كل كائن `TextSegment` قد يمتلك خطه، لونه، وخصائص التموضع الخاصة به. يوفر [`TextFragment`](../textfragment/) طريقة بسيطة لتغيير النص بخصائصه: ضبط الخط، ضبط حجم الخط، ضبط لون الخط، إلخ. في حين أن كائنات `TextSegment` قابلة للوصول ويمكن للمستخدمين التعامل معها بشكل مستقل.

## أمثلة

يوضح المثال كيفية تغيير لون النص وحجم الخط للنص باستخدام كائن [`TextState`](./textstate/) الخاص بكائن `TextSegment`.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// غيّر لون المقدمة للمقطع النصي الأول في أول ظهور للنص
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// غيّر حجم الخط للمقطع النصي الأول في أول ظهور للنص
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf");  
```

### انظر أيضًا

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


