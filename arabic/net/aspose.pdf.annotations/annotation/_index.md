---
title: Class Annotation
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Annotations.Annotation. فئة تمثل كائن التوضيح
type: docs
weight: 1410
url: /ar/net/aspose.pdf.annotations/annotation/
---
## فئة التوضيح

فئة تمثل كائن التوضيح.

```csharp
public abstract class Annotation : BaseParagraph
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | يحصل على قائمة إجراءات التوضيح. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل أو يحدد حالة مظهر التوضيح الحالي. |
| abstract [AnnotationType](../../aspose.pdf.annotations/annotation/annotationtype/) { get; } | يحصل على نوع التوضيح. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | يحصل على قاموس مظهر التوضيح. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | يحصل أو يحدد خصائص حدود التوضيح. [`Border`](./border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | يحصل على خصائص التوضيح. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | يحصل أو يحدد لون التوضيح. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | يحصل أو يحدد نص التوضيح. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | أعلام التوضيح. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | يحصل على الاسم المؤهل بالكامل للتوضيح. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | يحصل أو يحدد ارتفاع التوضيح. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | يحصل أو يحدد رابط الجزء (لإنشاء PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل أو يحدد ما إذا كانت الفقرة في السطر. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل أو يحدد قيمة بوليانية تجبر هذه الفقرة على التوليد في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يحدد هامش خارجي للفقرة (لإنشاء PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل أو يحدد التاريخ والوقت عندما تم تعديل التوضيح مؤخرًا. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل أو يحدد اسم التوضيح على الصفحة. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على التوضيح. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | يحصل أو يحدد مستطيل التوضيح. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس مظهر التوضيح. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل أو يحدد محاذاة النص للتوضيح. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يحدد محاذاة عمودية للفقرة |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل أو يحدد عرض التوضيح. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يحدد قيمة صحيحة تشير إلى ترتيب Z للرسم. سيتم وضع رسم ذو ZIndex أكبر فوق الرسم ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. سيتم وضع الرسم ذو ZIndex سالب خلف النص في الصفحة. |
| static [UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/updateappearanceonconvert/) { get; set; } | إذا كانت القيمة true، سيتم تحديث مظهر التوضيح قبل تحويل مستند PDF إلى صورة. هذا يسمح بتحويل الحقول بشكل صحيح ولكنه قد يتطلب المزيد من الوقت. |
| static [UseFontSubset](../../aspose.pdf.annotations/annotation/usefontsubset/) { get; set; } | إذا تم تعيين هذه الخاصية إلى true، سيتم إضافة الخطوط إلى المستند كأجزاء فرعية. القيمة الافتراضية هي true. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| abstract [Accept](../../aspose.pdf.annotations/annotation/accept/)(AnnotationSelector) | يقبل الزائر لمعالجة التوضيح. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | تحديث المعلمات والمظهر، وفقًا لتحويل المصفوفة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه النسخة. طريقة افتراضية. دائمًا ما تعيد null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | يضع محتويات التوضيح مباشرة على الصفحة، وسيتم إزالة كائن التوضيح. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يعيد مستطيل التوضيح مع الأخذ في الاعتبار دوران الصفحة. |

### انظر أيضًا

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)