---
title: Class Heading
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Heading. تمثل العنوان
type: docs
weight: 5470
url: /ar/net/aspose.pdf/heading/
---
## فئة العنوان

تمثل العنوان.

```csharp
public sealed class Heading : TextFragment
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Heading](heading/)(int) | يقوم بتهيئة مثيل جديد من فئة Cell. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | يحصل على موضع النص للنص، الممثل بواسطة كائن [`TextFragment`](../../aspose.pdf.text/textfragment/). يمثل YIndent في هيكل Position إحداثيات خط الأساس لجزء النص. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | يحصل على صفحة الوجهة. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | يحصل أو يحدد ملاحظة نهاية الفقرة. (لإنشاء PDF فقط) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | يحصل أو يحدد ملاحظة قدم الفقرة. (لإنشاء PDF فقط) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | يحصل على كائن النموذج الذي يحتوي على TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | يحصل أو يحدد محاذاة أفقية لجزء النص. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | يحدد رابط الجزء |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | يحصل على العنوان الذي يجب أن يتم ترقيمه تلقائيًا. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل أو يحدد ما إذا كانت الفقرة في السطر. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | يحصل على العنوان الذي يجب أن يكون في قائمة جدول المحتويات. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل أو يحدد قيمة بوليانية تجبر هذه الفقرة على التوليد في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | يحصل على المستوى. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يحدد هامش خارجي للفقرة (لإنشاء PDF) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | يحصل على الصفحة التي تحتوي على TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | يحصل أو يحدد موضع النص للنص، الممثل بواسطة كائن [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | يحصل على مستطيل TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | يحصل على خيارات استبدال النص. تحدد الخيارات السلوك عند استبدال نص الجزء بنص أقصر/أطول. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | يحصل على أجزاء النص للـ [`TextFragment`](../../aspose.pdf.text/textfragment/) الحالي. |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | يحصل على رقم بدء العنوان. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | يحصل أو يحدد النمط. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | يحصل أو يحدد كائن نص السلسلة الذي يمثله كائن [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | يحصل أو يحدد خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | يحصل أو يحدد حالة النص للنص الذي يمثله كائن [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | يحصل على الصفحة التي تحتوي على هذا العنوان. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | يحصل على أعلى Y لهذه العناوين. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | يحصل أو يحدد تسمية المستخدم. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | يحصل أو يحدد محاذاة عمودية لجزء النص. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | يحصل أو يحدد عدد الأسطر الملتفة لهذه الفقرة (لإنشاء PDF فقط) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يحدد قيمة صحيحة تشير إلى ترتيب Z للرسم. سيتم وضع رسم ذو ZIndex أكبر فوق الرسم ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. سيتم وضع الرسم ذو ZIndex سالب خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | استنساخ العنوان. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | استنساخ العنوان مع جميع الأجزاء. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | يحصل على [`TextSegment`](../../aspose.pdf.text/textsegment/)(s) التي تمثل الجزء المحدد من نص [`TextFragment`](../../aspose.pdf.text/textfragment/). |

### انظر أيضًا

* فئة [TextFragment](../../aspose.pdf.text/textfragment/)
* مساحة الأسماء [Aspose.Pdf](../../aspose.pdf/)
* التجميع [Aspose.PDF](../../)