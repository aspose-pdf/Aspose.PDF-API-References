---
title: LinkAnnotation
second_title: Aspose.PDF لمرجع .NET API
description: يمثل إما ارتباط نص تشعبي إلى وجهة في مكان آخر في المستند أو إجراء يتعين تنفيذه.
type: docs
weight: 630
url: /ar/net/aspose.pdf.annotations/linkannotation/
---
## LinkAnnotation class

يمثل إما ارتباط نص تشعبي إلى وجهة في مكان آخر في المستند أو إجراء يتعين تنفيذه.

```csharp
public sealed class LinkAnnotation : Annotation
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [LinkAnnotation](linkannotation)(Page, Rectangle) | إنشاء تعليق توضيحي جديد للرابط في الصفحة المحددة. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Action](../../aspose.pdf.annotations/linkannotation/action) { get; set; } | إجراء يتم تنفيذه عند تنشيط التعليق التوضيحي للرابط. |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | الحصول على قائمة بإجراءات التعليقات التوضيحية . |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | الحصول على حالة مظهر التعليق التوضيحي الحالية أو تعيينها. |
| override [AnnotationType](../../aspose.pdf.annotations/linkannotation/annotationtype) { get; } | يحصل على نوع التعليق التوضيحي . |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | الحصول على قاموس مظهر التعليق التوضيحي. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | الحصول على أو تعيين خصائص حدود التعليق التوضيحي.[`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | الحصول على خصائص التعليقات التوضيحية . |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | الحصول على لون التعليق التوضيحي أو تعيينه. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | الحصول على نص التعليق التوضيحي أو تعيينه. |
| [Destination](../../aspose.pdf.annotations/linkannotation/destination) { get; set; } | وجهة يتم عرضها عند تنشيط التعليق التوضيحي. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | إشارات التعليق التوضيحي . |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | الحصول على الاسم الكامل للتعليق التوضيحي. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | الحصول على ارتفاع التعليق التوضيحي أو تعيينه. |
| [Highlighting](../../aspose.pdf.annotations/linkannotation/highlighting) { get; set; } | التأثير المرئي الذي سيتم استخدامه عند الضغط على زر الماوس أو الضغط باستمرار داخل المنطقة النشطة. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | الحصول على أو تعيين الارتباط التشعبي للجزء (لمولد pdf) . |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية خطأ. (لتوليد pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | الحصول على فقرة مضمنة أو تعيينها . الإعداد الافتراضي خطأ. (لإنشاء ملف pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | الحصول على أو تعيين قيمة منطقية تفرض إنشاء هذه الفقرة في صفحة جديدة. القيمة الافتراضية خطأ. (لتوليد pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | الحصول على أو تعيين قيمة منطقية تشير إلى ما إذا كانت الفقرة الحالية ستبقى في نفس الصفحة مع الفقرة التالية. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | الحصول على أو تعيين هامش خارجي للفقرة (لتوليد pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | تحديد أو تحديد التاريخ والوقت اللذين تم فيهما تعديل التعليق التوضيحي مؤخرًا. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | الحصول على أو تعيين اسم التعليق التوضيحي على الصفحة. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | يحصل على فهرس للصفحة التي تحتوي على تعليق توضيحي. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | الحصول على مستطيل التعليق التوضيحي أو تعيينه. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | الحصول على قاموس مظهر التعليق التوضيحي. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | الحصول على محاذاة النص للتعليق التوضيحي أو تعيينها. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | الحصول على محاذاة عمودية للفقرة أو تعيينها |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | الحصول على عرض التعليق التوضيحي أو تعيينه. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | الحصول على أو تحديد قيمة int التي تشير إلى ترتيب Z للرسم البياني. سيتم وضع رسم بياني به ZIndex أكبر فوق الرسم البياني باستخدام ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني بالسالب سيتم وضع مؤشر Z خلف النص في الصفحة. |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/linkannotation/accept)(AnnotationSelector) | يقبل كائن الزائر لمعالجة التعليق التوضيحي. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | تحديث المعلمات والمظهر ، وفقًا لتحويل المصفوفة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | استنساخ هذا المثال. طريقة افتراضية. العودة دائما فارغة. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | وضع محتويات التعليق التوضيحي مباشرة على الصفحة ، ستتم إزالة كائن التعليق التوضيحي . |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | إرجاع مستطيل التعليق التوضيحي مع مراعاة تدوير الصفحة. |

### أنظر أيضا

* class [Annotation](../annotation)
* مساحة الاسم [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
