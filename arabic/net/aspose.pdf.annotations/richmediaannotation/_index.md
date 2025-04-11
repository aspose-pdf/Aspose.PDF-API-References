---
title: Class RichMediaAnnotation
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Annotations.RichMediaAnnotation. تصف الفئة RichMediaAnnotation التي تسمح بإدراج بيانات الفيديو/الصوت في مستند PDF
type: docs
weight: 2480
url: /ar/net/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation class

تصف الفئة RichMediaAnnotation التي تسمح بإدراج بيانات الفيديو/الصوت في مستند PDF.

```csharp
public class RichMediaAnnotation : Annotation
```

## Constructors

| Name | Description |
| --- | --- |
| [RichMediaAnnotation](richmediaannotation/)(Page, Rectangle) | Initializes RichMediaAnnotation. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | يحصل على قائمة إجراءات التعليق. |
| [ActivateOn](../../aspose.pdf.annotations/richmediaannotation/activateon/) { get; set; } | الحدث الذي ينشط التطبيق. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل على أو يحدد حالة مظهر التعليق الحالي. |
| override [AnnotationType](../../aspose.pdf.annotations/richmediaannotation/annotationtype/) { get; } | يحصل على نوع التعليق. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | يحصل على قاموس مظهر التعليق. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | يحصل على أو يحدد خصائص حدود التعليق. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | يحصل على خصائص التعليق. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | يحصل على أو يحدد لون التعليق. |
| [Content](../../aspose.pdf.annotations/richmediaannotation/content/) { get; } | بيانات محتوى الوسائط الغنية. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | يحصل على أو يحدد نص التعليق. |
| [CustomFlashVariables](../../aspose.pdf.annotations/richmediaannotation/customflashvariables/) { get; set; } | يحدد أو يحصل على متغيرات فلاش التي تم تمريرها إلى المشغل. |
| [CustomPlayer](../../aspose.pdf.annotations/richmediaannotation/customplayer/) { get; set; } | يحدد أو يحصل على مشغل فلاش مخصص لتشغيل بيانات الفيديو/الصوت. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | أعلام التعليق. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | يحصل على الاسم المؤهل بالكامل للتعليق. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | يحصل على أو يحدد ارتفاع التعليق. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | يحصل على أو يحدد رابط الشريحة (لإنشاء PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل على أو يحدد قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل على أو يحدد ما إذا كانت الفقرة في السطر. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل على أو يحدد قيمة بوليانية تجبر هذه الفقرة على التوليد في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل على أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل على أو يحدد هامش خارجي للفقرة (لإنشاء PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل على أو يحدد التاريخ والوقت عندما تم تعديل التعليق مؤخرًا. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل على أو يحدد اسم التعليق على الصفحة. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على التعليق. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | يحصل على أو يحدد مستطيل التعليق. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس مظهر التعليق. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل على أو يحدد محاذاة النص للتعليق. |
| [Type](../../aspose.pdf.annotations/richmediaannotation/type/) { get; set; } | يحصل على أو يحدد نوع المحتوى. القيم الممكنة: صوت، فيديو. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل على أو يحدد محاذاة عمودية للفقرة |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل على أو يحدد عرض التعليق. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل على أو يحدد قيمة صحيحة تشير إلى ترتيب Z للرسم. سيتم وضع الرسم الذي له ZIndex أكبر فوق الرسم الذي له ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. سيتم وضع الرسم الذي له ZIndex سالب خلف النص في الصفحة. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/richmediaannotation/accept/)(AnnotationSelector) | يقبل الزائر لهذا التعليق. |
| [AddCustomData](../../aspose.pdf.annotations/richmediaannotation/addcustomdata/)(string, Stream) | إضافة بيانات مخصصة مسماة (على سبيل المثال المطلوبة لبرنامج فلاش). |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | تحديث المعلمات والمظهر، وفقًا لتحويل المصفوفة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه النسخة. طريقة افتراضية. دائمًا ما تعيد null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | يضع محتويات التعليق مباشرة على الصفحة، وسيتم إزالة كائن التعليق. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يعيد مستطيل التعليق مع الأخذ في الاعتبار دوران الصفحة. |
| [SetContent](../../aspose.pdf.annotations/richmediaannotation/setcontent/)(string, Stream) | تعيين تدفق المحتوى. |
| [SetPoster](../../aspose.pdf.annotations/richmediaannotation/setposter/)(Stream) | تعيين ملصق التعليق. |
| [Update](../../aspose.pdf.annotations/richmediaannotation/update/)() | يقوم بتحديث البيانات بالمعلمات المحددة. |

## Other Members

| Name | Description |
| --- | --- |
| enum [ActivationEvent](../../aspose.pdf.annotations/richmediaannotation.activationevent) | الحدث الذي ينشط التعليق. |
| enum [ContentType](../../aspose.pdf.annotations/richmediaannotation.contenttype) | نوع الوسائط المتعددة. |

### See Also

* class [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)