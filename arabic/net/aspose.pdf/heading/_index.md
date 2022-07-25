---
title: Heading
second_title: Aspose.PDF لمرجع .NET API
description: يمثل العنوان.
type: docs
weight: 3360
url: /ar/net/aspose.pdf/heading/
---
## Heading class

يمثل العنوان.

```csharp
public sealed class Heading : TextFragment
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Heading](heading)(int) | تهيئة مثيل جديد لفئة الخلية. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | الحصول على موضع النص للنص ، ممثلاً بامتداد[`TextFragment`](../../aspose.pdf.text/textfragment) object. تمثل نهاية Y لهيكل الموضع إحداثيات خط الأساس لجزء النص. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage) { get; set; } | يحصل على صفحة الوجهة . |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | الحصول على أو تعيين ملاحظة نهاية الفقرة. (لإنشاء ملف pdf فقط) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | الحصول على حاشية الفقرة السفلية أو تعيينها. (لإنشاء ملف pdf فقط) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | الحصول على كائن النموذج الذي يحتوي على TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | الحصول على محاذاة أفقية لجزء النص أو تعيينها. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | تعيين الارتباط التشعبي للجزء |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence) { get; set; } | الحصول على العنوان يجب ترقيمه تلقائيًا . |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية خطأ. (لتوليد pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | الحصول على فقرة مضمنة أو تعيينها . الإعداد الافتراضي خطأ. (لإنشاء ملف pdf) |
| [IsInList](../../aspose.pdf/heading/isinlist) { get; set; } | الحصول على العنوان يجب أن يكون في قائمة toc . |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | الحصول على أو تعيين قيمة منطقية تفرض إنشاء هذه الفقرة في صفحة جديدة. القيمة الافتراضية خطأ. (لتوليد pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كانت الفقرة الحالية ستبقى في نفس الصفحة مع الفقرة التالية. |
| [Level](../../aspose.pdf/heading/level) { get; set; } | يحصل على المستوى . |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | الحصول على أو تعيين هامش خارجي للفقرة (لتوليد pdf) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | يحصل على الصفحة التي تحتوي على TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | الحصول على أو تعيين موضع النص للنص ، ممثلاً بامتداد[`TextFragment`](../../aspose.pdf.text/textfragment) الكائن . |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | يحصل على مستطيل من TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | يحصل على خيارات استبدال النص. تحدد الخيارات السلوك عند استبدال نص الجزء بمزيد من الاختصار / الطويل. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | الحصول على مقاطع نصية للتيار[`TextFragment`](../../aspose.pdf.text/textfragment) . |
| [StartNumber](../../aspose.pdf/heading/startnumber) { get; set; } | الحصول على رقم بداية العنوان . |
| [Style](../../aspose.pdf/heading/style) { get; set; } | الحصول على النمط أو تعيينه . |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | يحصل أو يحددString كائن النص الذي[`TextFragment`](../../aspose.pdf.text/textfragment) يمثل الكائن . |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | الحصول على أو تعيين حالة النص للنص الذي[`TextFragment`](../../aspose.pdf.text/textfragment) يمثل الكائن . |
| [TocPage](../../aspose.pdf/heading/tocpage) { get; set; } | الحصول على الصفحة التي تحتوي على هذا العنوان . |
| [Top](../../aspose.pdf/heading/top) { get; set; } | الحصول على رأس Y من هذه العناوين . |
| [UserLabel](../../aspose.pdf/heading/userlabel) { get; set; } | الحصول على تسمية المستخدم أو تعيينها. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | الحصول على محاذاة عمودية لجزء النص أو تعيينها. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | الحصول على عدد سطور الالتفاف لهذه الفقرة أو تعيينه (لإنشاء ملف pdf فقط) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | الحصول على أو تحديد قيمة int التي تشير إلى ترتيب Z للرسم البياني. سيتم وضع رسم بياني به ZIndex أكبر فوق الرسم البياني باستخدام ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني بالسالب سيتم وضع مؤشر Z خلف النص في الصفحة. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone)() | استنساخ العنوان. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments)() | استنساخ العنوان بكل المقاطع. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | يحصل[`TextSegment`](../../aspose.pdf.text/textsegment) (ق) تمثل جزءًا محددًا من[`TextFragment`](../../aspose.pdf.text/textfragment) نص . |

### أنظر أيضا

* class [TextFragment](../../aspose.pdf.text/textfragment)
* مساحة الاسم [Aspose.Pdf](../../aspose.pdf)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
