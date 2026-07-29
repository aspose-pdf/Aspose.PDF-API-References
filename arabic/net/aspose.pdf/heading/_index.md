---
title: "فئة Heading"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Heading. تمثل العنوان"
type: docs
weight: 5590
url: /ar/net/aspose.pdf/heading/
---
## Heading class

يمثل العنوان.

```csharp
public sealed class Heading : TextFragment
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Heading](heading/)(int) | ينشئ مثالًا جديدًا من فئة Cell. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | يحصل على موضع النص للنص، المُمثل باستخدام كائن [`TextFragment`](../../aspose.pdf.text/textfragment/). يمثل YIndent في بنية Position إحداثيات الخط الأساسي لمقاطع النص. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | يحصل على صفحة الوجهة. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | يحصل أو يعيّن ملاحظة نهاية الفقرة. (لإنشاء pdf فقط) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | يحصل أو يعيّن حاشية الفقرة. (لإنشاء pdf فقط) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | يحصل على كائن النموذج الذي يحتوي على TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | يحصل أو يعيّن محاذاة أفقية لجزء النص. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | يعيّن الارتباط التشعبي للجزء. |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | يحصل على ما إذا كان العنوان يجب أن يُرقم تلقائيًا. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كان هذا الفقرة سيظهر في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | الحصول على أو تعيين ما إذا كانت الفقرة مضمنة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | يحصل على ما إذا كان العنوان يجب أن يكون في قائمة الفهرس. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | الحصول على أو تعيين قيمة bool تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | يحصل على المستوى. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يعيّن هامشًا خارجيًا للفقرة (لإنشاء PDF) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | يحصل على الصفحة التي تحتوي على TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | يحصل أو يضبط موضع النص للنص، المُمثل باستخدام كائن [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | يحصل على المستطيل الخاص بـ TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | يحصل على خيارات استبدال النص. تحدد الخيارات السلوك عندما يتم استبدال نص الجزء إلى أقصر أو أطول. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | يحصل على مقاطع النص للـ[`TextFragment`](../../aspose.pdf.text/textfragment/) الحالي. |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | يحصل على رقم بدء العنوان. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | يحصل أو يضبط النمط. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | يحصل أو يضبط كائن النص من نوع String الذي يمثله كائن [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | يحصل أو يعيّن خيارات تحرير النص. تحدد الخيارات سلوكًا خاصًا عندما لا يمكن كتابة الرمز المطلوب باستخدام الخط. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | يحصل أو يضبط حالة النص للنص الذي يمثله كائن [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | يحصل على الصفحة التي تحتوي على هذا العنوان. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | يحصل على إحداثي Y العلوي لهذا العنوان. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | يحصل أو يضبط تسمية المستخدم. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة رأسية لجزء النص. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | يحصل أو يعيّن عدد أسطر الالتفاف لهذه الفقرة (لإنشاء pdf فقط) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | استنساخ العنوان. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | استنساخ العنوان مع جميع المقاطع. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | يحصل على [`TextSegment`](../../aspose.pdf.text/textsegment/)(s) التي تمثل الجزء المحدد من نص الـ[`TextFragment`](../../aspose.pdf.text/textfragment/). |

### انظر أيضًا

* class [TextFragment](../../aspose.pdf.text/textfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


