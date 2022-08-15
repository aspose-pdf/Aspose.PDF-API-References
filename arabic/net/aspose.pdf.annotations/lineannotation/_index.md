---
title: LineAnnotation
second_title: Aspose.PDF لمرجع .NET API
description: فئة تمثل التعليق التوضيحي للسطر .
type: docs
weight: 600
url: /ar/net/aspose.pdf.annotations/lineannotation/
---
## LineAnnotation class

فئة تمثل التعليق التوضيحي للسطر .

```csharp
public sealed class LineAnnotation : MarkupAnnotation
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [LineAnnotation](lineannotation#constructor)(Document, Point, Point) | مُنشئ للاستخدام مع المولد. |
| [LineAnnotation](lineannotation#constructor_1)(Page, Rectangle, Point, Point) | إنشاء تعليق توضيحي على السطر الجديد في الصفحة المحددة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | الحصول على قائمة بإجراءات التعليقات التوضيحية . |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | الحصول على حالة مظهر التعليق التوضيحي الحالية أو تعيينها. |
| override [AnnotationType](../../aspose.pdf.annotations/lineannotation/annotationtype) { get; } | يحصل على نوع التعليق التوضيحي . |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | الحصول على قاموس مظهر التعليق التوضيحي. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | الحصول على أو تعيين خصائص حدود التعليق التوضيحي.[`Border`](../annotation/border) |
| [CaptionOffset](../../aspose.pdf.annotations/lineannotation/captionoffset) { get; set; } | الحصول على أو تعيين إزاحة نص التسمية التوضيحية من موضعها الطبيعي. |
| [CaptionPosition](../../aspose.pdf.annotations/lineannotation/captionposition) { get; set; } | الحصول على موضع التعليق التوضيحي أو تعيينه. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | الحصول على خصائص التعليقات التوضيحية . |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | الحصول على لون التعليق التوضيحي أو تعيينه. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | الحصول على نص التعليق التوضيحي أو تعيينه. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | الحصول على التاريخ والوقت اللذين تم فيهما إنشاء التعليق التوضيحي. |
| [Ending](../../aspose.pdf.annotations/lineannotation/ending) { get; set; } | الحصول على نقطة نهاية السطر أو تعيينها . |
| [EndingStyle](../../aspose.pdf.annotations/lineannotation/endingstyle) { get; set; } | الحصول على أو تعيين نمط النهاية لنقطة نهاية السطر. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | إشارات التعليق التوضيحي . |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | الحصول على الاسم الكامل للتعليق التوضيحي. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | الحصول على ارتفاع التعليق التوضيحي أو تعيينه. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | الحصول على أو تعيين الارتباط التشعبي للجزء (لمولد pdf) . |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | إشارة إلى التعليق التوضيحي بأن هذا التعليق التوضيحي "ردًا على" . يجب أن يكون كلا التعليقين على نفس الصفحة من المستند. |
| [Intent](../../aspose.pdf.annotations/lineannotation/intent) { get; set; } | الحصول على الغرض من التعليق التوضيحي للسطر أو تعيينه. |
| [InteriorColor](../../aspose.pdf.annotations/lineannotation/interiorcolor) { get; set; } | الحصول على اللون الداخلي للتعليق التوضيحي أو تعيينه. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية خطأ. (لتوليد pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | الحصول على فقرة مضمنة أو تعيينها . الإعداد الافتراضي خطأ. (لإنشاء ملف pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | الحصول على أو تعيين قيمة منطقية تفرض إنشاء هذه الفقرة في صفحة جديدة. القيمة الافتراضية خطأ. (لتوليد pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كانت الفقرة الحالية ستبقى في نفس الصفحة مع الفقرة التالية. |
| [LeaderLine](../../aspose.pdf.annotations/lineannotation/leaderline) { get; set; } | الحصول على أو تحديد طول خط القائد. |
| [LeaderLineExtension](../../aspose.pdf.annotations/lineannotation/leaderlineextension) { get; set; } | الحصول على أو تحديد طول امتداد خط القائد. |
| [LeaderLineOffset](../../aspose.pdf.annotations/lineannotation/leaderlineoffset) { get; set; } | الحصول على أو تعيين إزاحة خط القائد . |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | الحصول على أو تعيين هامش خارجي للفقرة (لتوليد pdf) |
| [Measure](../../aspose.pdf.annotations/lineannotation/measure) { get; set; } | وحدات القياس المحددة لهذا التعليق التوضيحي . |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | تحديد أو تحديد التاريخ والوقت اللذين تم فيهما تعديل التعليق التوضيحي مؤخرًا. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | الحصول على أو تعيين اسم التعليق التوضيحي على الصفحة. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | الحصول على أو تعيين قيمة العتامة الثابتة لاستخدامها في رسم التعليق التوضيحي. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | يحصل على فهرس للصفحة التي تحتوي على تعليق توضيحي. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | تعليق توضيحي منبثق لإدخال النص المرتبط بهذا التعليق التوضيحي أو تحريره. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | الحصول على مستطيل التعليق التوضيحي أو تعيينه. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | سلسلة تحدد العلاقة ("نوع الرد") بين هذا التعليق التوضيحي والآخر المحدد بواسطة InReplyTo . |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | الحصول على سلسلة نصية منسقة أو تعيينها ليتم عرضها في النافذة المنبثقة عند فتح التعليق التوضيحي. |
| [ShowCaption](../../aspose.pdf.annotations/lineannotation/showcaption) { get; set; } | الحصول على علامة منطقية أو تعيينها والتي يجب أن تظهر المحددات على أنها محتويات كتسمية توضيحية. |
| [Starting](../../aspose.pdf.annotations/lineannotation/starting) { get; set; } | الحصول على نقطة البداية للخط أو تعيينها . |
| [StartingStyle](../../aspose.pdf.annotations/lineannotation/startingstyle) { get; set; } | الحصول على أو تعيين نمط نهاية السطر لنقطة بداية السطر. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | الحصول على قاموس مظهر التعليق التوضيحي. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | يحصل على نص يمثل وصف الكائن. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | الحصول على محاذاة النص للتعليق التوضيحي أو تعيينها. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | الحصول على أو تعيين النص الذي سيتم عرضه في شريط عنوان التعليق التوضيحي. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | الحصول على محاذاة عمودية للفقرة أو تعيينها |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | الحصول على عرض التعليق التوضيحي أو تعيينه. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | الحصول على أو تحديد قيمة int التي تشير إلى ترتيب Z للرسم البياني. سيتم وضع رسم بياني به ZIndex أكبر فوق الرسم البياني باستخدام ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني بالسالب سيتم وضع مؤشر Z خلف النص في الصفحة. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/lineannotation/accept)(AnnotationSelector) | يقبل الزائر بمعالجة التعليقات التوضيحية . |
| override [ChangeAfterResize](../../aspose.pdf.annotations/lineannotation/changeafterresize)(Matrix) | يحدّث نقطتي البداية والنهاية وفقًا لتحويل المصفوفة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | استنساخ هذا المثال. طريقة افتراضية. العودة دائما فارغة. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | وضع محتويات التعليق التوضيحي مباشرة على الصفحة ، ستتم إزالة كائن التعليق التوضيحي . |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | إرجاع مستطيل التعليق التوضيحي مع مراعاة تدوير الصفحة. |

### أنظر أيضا

* class [MarkupAnnotation](../markupannotation)
* مساحة الاسم [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
