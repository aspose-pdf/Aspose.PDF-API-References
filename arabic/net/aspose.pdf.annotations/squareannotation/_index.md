---
title: SquareAnnotation
second_title: Aspose.PDF لمرجع .NET API
description: فئة تمثل شرحًا توضيحيًا مربعًا .
type: docs
weight: 1140
url: /ar/net/aspose.pdf.annotations/squareannotation/
---
## SquareAnnotation class

فئة تمثل شرحًا توضيحيًا مربعًا .

```csharp
public sealed class SquareAnnotation : CommonFigureAnnotation
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [SquareAnnotation](squareannotation#constructor)(Document) | مُنشئ للاستخدام مع المولد. |
| [SquareAnnotation](squareannotation#constructor_1)(Page, Rectangle) | إنشاء تعليق توضيحي مربع جديد في الصفحة المحددة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | الحصول على قائمة بإجراءات التعليقات التوضيحية . |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | الحصول على حالة مظهر التعليق التوضيحي الحالية أو تعيينها. |
| override [AnnotationType](../../aspose.pdf.annotations/squareannotation/annotationtype) { get; } | يحصل على نوع التعليق التوضيحي . |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | الحصول على قاموس مظهر التعليق التوضيحي. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | الحصول على أو تعيين خصائص حدود التعليق التوضيحي.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | الحصول على خصائص التعليقات التوضيحية . |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | الحصول على لون التعليق التوضيحي أو تعيينه. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | الحصول على نص التعليق التوضيحي أو تعيينه. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | الحصول على التاريخ والوقت اللذين تم فيهما إنشاء التعليق التوضيحي. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | إشارات التعليق التوضيحي . |
| [Frame](../../aspose.pdf.annotations/commonfigureannotation/frame) { get; set; } | المستطيل الذي يصف الاختلافات العددية بين مستطيلين: إدخال المستطيل للتعليق التوضيحي والحدود الفعلية للمربع أو الدائرة الأساسية . |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | الحصول على الاسم الكامل للتعليق التوضيحي. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | الحصول على ارتفاع التعليق التوضيحي أو تعيينه. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | الحصول على أو تعيين الارتباط التشعبي للجزء (لمولد pdf) . |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | إشارة إلى التعليق التوضيحي بأن هذا التعليق التوضيحي "ردًا على" . يجب أن يكون كلا التعليقين على نفس الصفحة من المستند. |
| [InteriorColor](../../aspose.pdf.annotations/commonfigureannotation/interiorcolor) { get; set; } | اللون الداخلي المراد به ملء مستطيل التعليق التوضيحي أو القطع الناقص. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية خطأ. (لتوليد pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | الحصول على فقرة مضمنة أو تعيينها . الإعداد الافتراضي خطأ. (لإنشاء ملف pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | الحصول على أو تعيين قيمة منطقية تفرض إنشاء هذه الفقرة في صفحة جديدة. القيمة الافتراضية خطأ. (لتوليد pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كانت الفقرة الحالية ستبقى في نفس الصفحة مع الفقرة التالية. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | الحصول على أو تعيين هامش خارجي للفقرة (لتوليد pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | تحديد أو تحديد التاريخ والوقت اللذين تم فيهما تعديل التعليق التوضيحي مؤخرًا. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | الحصول على أو تعيين اسم التعليق التوضيحي على الصفحة. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | الحصول على أو تعيين قيمة العتامة الثابتة لاستخدامها في رسم التعليق التوضيحي. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | يحصل على فهرس للصفحة التي تحتوي على تعليق توضيحي. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | تعليق توضيحي منبثق لإدخال النص المرتبط بهذا التعليق التوضيحي أو تحريره. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | الحصول على مستطيل التعليق التوضيحي أو تعيينه. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | سلسلة تحدد العلاقة ("نوع الرد") بين هذا التعليق التوضيحي والآخر المحدد بواسطة InReplyTo . |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | الحصول على سلسلة نصية منسقة أو تعيينها ليتم عرضها في النافذة المنبثقة عند فتح التعليق التوضيحي. |
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
| override [Accept](../../aspose.pdf.annotations/squareannotation/accept)(AnnotationSelector) | يقبل الزائر معالجة التعليق التوضيحي . |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | تحديث المعلمات والمظهر ، وفقًا لتحويل المصفوفة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | استنساخ هذا المثال. طريقة افتراضية. العودة دائما فارغة. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | وضع محتويات التعليق التوضيحي مباشرة على الصفحة ، ستتم إزالة كائن التعليق التوضيحي . |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | إرجاع مستطيل التعليق التوضيحي مع مراعاة تدوير الصفحة. |

### أنظر أيضا

* class [CommonFigureAnnotation](../commonfigureannotation)
* مساحة الاسم [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
