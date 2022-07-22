---
title: RedactionAnnotation
second_title: Aspose.PDF لمرجع .NET API
description: يمثل التعليق التوضيحي المنقح .
type: docs
weight: 960
url: /ar/net/aspose.pdf.annotations/redactionannotation/
---
## RedactionAnnotation class

يمثل التعليق التوضيحي المنقح .

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [RedactionAnnotation](redactionannotation#constructor)(Document) | مُنشئ RedactionAnnotation. لاستخدامها في المولد. |
| [RedactionAnnotation](redactionannotation#constructor_1)(Page, Rectangle) | مُنشئ RedactAnnotation . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | الحصول على قائمة بإجراءات التعليقات التوضيحية . |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | الحصول على حالة مظهر التعليق التوضيحي الحالية أو تعيينها. |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype) { get; } | يحصل على نوع التعليق التوضيحي . |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | الحصول على قاموس مظهر التعليق التوضيحي. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | الحصول على أو تعيين خصائص حدود التعليق التوضيحي.[`Border`](../annotation/border) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor) { get; set; } | الحصول على أو تعيين لون الحد الذي يتم رسمه عندما لا يكون التنقيح نشطًا. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | الحصول على خصائص التعليقات التوضيحية . |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | الحصول على لون التعليق التوضيحي أو تعيينه. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | الحصول على نص التعليق التوضيحي أو تعيينه. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | الحصول على التاريخ والوقت اللذين تم فيهما إنشاء التعليق التوضيحي. |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance) { get; set; } | الحصول على سلسلة المظهر الافتراضية أو تعيينها لاستخدامها في تنسيق النص. |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor) { get; set; } | الحصول على اللون أو تعيينه لملء التعليق التوضيحي. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | إشارات التعليق التوضيحي . |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | الحصول على الاسم الكامل للتعليق التوضيحي. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | الحصول على ارتفاع التعليق التوضيحي أو تعيينه. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | الحصول على أو تعيين الارتباط التشعبي للجزء (لمولد pdf) . |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | إشارة إلى التعليق التوضيحي بأن هذا التعليق التوضيحي "ردًا على" . يجب أن يكون كلا التعليقين على نفس الصفحة من المستند. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية خطأ. (لتوليد pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | الحصول على فقرة مضمنة أو تعيينها . الإعداد الافتراضي خطأ. (لإنشاء ملف pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | الحصول على أو تعيين قيمة منطقية تفرض إنشاء هذه الفقرة في صفحة جديدة. القيمة الافتراضية خطأ. (لتوليد pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كانت الفقرة الحالية ستبقى في نفس الصفحة مع الفقرة التالية. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | الحصول على أو تعيين هامش خارجي للفقرة (لتوليد pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | تحديد أو تحديد التاريخ والوقت اللذين تم فيهما تعديل التعليق التوضيحي مؤخرًا. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | الحصول على أو تعيين اسم التعليق التوضيحي على الصفحة. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | الحصول على أو تعيين قيمة العتامة الثابتة لاستخدامها في رسم التعليق التوضيحي. |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext) { get; set; } | نص للطباعة على التعليقات التوضيحية المنقحة . |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | يحصل على فهرس للصفحة التي تحتوي على تعليق توضيحي. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | تعليق توضيحي منبثق لإدخال النص المرتبط بهذا التعليق التوضيحي أو تحريره. |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint) { get; set; } | مصفوفة من أرقام 8xN تحدد إحداثيات منطقة المحتوى المراد إزالتها. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | الحصول على مستطيل التعليق التوضيحي أو تعيينه. |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat) { get; set; } | إذا تم تكرار نص التراكب الحقيقي في التعليق التوضيحي. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | سلسلة تحدد العلاقة ("نوع الرد") بين هذا التعليق التوضيحي والآخر المحدد بواسطة InReplyTo . |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | الحصول على سلسلة نصية منسقة أو تعيينها ليتم عرضها في النافذة المنبثقة عند فتح التعليق التوضيحي. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | الحصول على قاموس مظهر التعليق التوضيحي. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | يحصل على نص يمثل وصف الكائن. |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment) { get; set; } | يحصل أو يحدد. محاذاة نص التراكب. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | الحصول على محاذاة النص للتعليق التوضيحي أو تعيينها. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | الحصول على أو تعيين النص الذي سيتم عرضه في شريط عنوان التعليق التوضيحي. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | الحصول على محاذاة عمودية للفقرة أو تعيينها |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | الحصول على عرض التعليق التوضيحي أو تعيينه. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | الحصول على أو تحديد قيمة int التي تشير إلى ترتيب Z للرسم البياني. سيتم وضع رسم بياني به ZIndex أكبر فوق الرسم البياني باستخدام ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني بالسالب سيتم وضع مؤشر Z خلف النص في الصفحة. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept)(AnnotationSelector) | يقبل كائن الزائر لمعالجة التعليق التوضيحي. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | تحديث المعلمات والمظهر ، وفقًا لتحويل المصفوفة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | استنساخ هذا المثال. طريقة افتراضية. العودة دائما فارغة. |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten)() | تسوية التعليق التوضيحي ، أي إزالة التعليق التوضيحي وإضافة تعليقاته |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | إرجاع مستطيل التعليق التوضيحي مع مراعاة تدوير الصفحة. |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact)() | تسوية التعليقات التوضيحية وتنقيح محتويات الصفحة (على سبيل المثال ، إزالة النص والصورة تحت التعليق التوضيحي المنقح) |

### أنظر أيضا

* class [MarkupAnnotation](../markupannotation)
* مساحة الاسم [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
