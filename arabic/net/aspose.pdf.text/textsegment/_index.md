---
title: Class TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextSegment class. يمثل جزء من نص Pdf
type: docs
weight: 11050
url: /ar/net/aspose.pdf.text/textsegment/
---
## TextSegment class

يمثل جزء من نص Pdf.

```csharp
public sealed class TextSegment
```

## Constructors

| Name | Description |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | ينشئ كائن TextSegment. |
| [TextSegment](textsegment/#constructor_1)(string) | ينشئ كائن TextSegment. |

## Properties

| Name | Description |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | يحصل على موضع النص للنص، الممثل بكائن `TextSegment`. يمثل YIndent في هيكل Position إحداثيات خط الأساس لجزء النص. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | يحصل على مجموعة من كائنات CharInfo التي تمثل معلومات عن الأحرف في جزء النص. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | يحصل على فهرس الحرف النهائي للجزء الحالي في مشغل النص المعروض (Tj, TJ). |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | يحصل على أو يحدد رابط الجزء (لمنشئ pdf). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | يحصل على موضع النص للنص، الممثل بكائن `TextSegment`. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | يحصل على مستطيل الـ TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | يحصل على فهرس الحرف الابتدائي للجزء الحالي في مشغل النص المعروض (Tj, TJ). |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | يحصل على أو يحدد كائن نص السلسلة الذي يمثله كائن `TextSegment`. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | يحصل على أو يحدد خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | يحصل على أو يحدد حالة النص للنص الذي يمثله كائن `TextSegment`. |

## Methods

| Name | Description |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | يقوم بترميز السلسلة كـ html. |

## Remarks

باختصار، كائنات `TextSegment` هي أطفال لكائن [`TextFragment`](../textfragment/). بالتفصيل: يتم تمثيل نص مستند pdf في Pdf بواسطة كائنين أساسيين: [`TextFragment`](../textfragment/) و `TextSegment`. الاختلافات بينهما تعتمد في الغالب على السياق. دعونا نعتبر السيناريو التالي. يبحث المستخدم عن النص "hello world" للتعامل معه، وتغيير خصائصه، والنظر وما إلى ذلك.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

تمثيل النص في pdf معقد جدًا. قد يتكون النص "hello world" من عدة أجزاء نصية مستقلة ماديًا. يحدد نموذج نص Aspose.Pdf أساسًا أن كائن [`TextFragment`](../textfragment/) يوفر مجموعة عمليات منطقية واحدة على مجموعة كائنات `TextSegment` المادية التي تمثل استعلام المستخدم. في سيناريو بحث النص، يمثل [`TextFragment`](../textfragment/) التمثيل المنطقي للنص "hello world"، ومجموعة كائنات `TextSegment` تمثل جميع الأجزاء المادية التي تشكل كائن النص "hello world". لذا، فإن [`TextFragment`](../textfragment/) قريب من التمثيل النصي المنطقي. و `TextSegment` قريب من التمثيل النصي المادي. من الواضح أن كل كائن `TextSegment` قد يكون له خطه الخاص، وألوانه، وخصائص موضعه. يوفر [`TextFragment`](../textfragment/) طريقة بسيطة لتغيير النص مع خصائصه: تعيين الخط، تعيين حجم الخط، تعيين لون الخط، إلخ. في الوقت نفسه، تكون كائنات `TextSegment` قابلة للوصول ويمكن للمستخدمين التعامل مع كائنات `TextSegment` بشكل مستقل.

## Examples

توضح المثال كيفية تغيير لون النص وحجم الخط للنص باستخدام كائن [`TextState`](./textstate/) لكائن `TextSegment`.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)