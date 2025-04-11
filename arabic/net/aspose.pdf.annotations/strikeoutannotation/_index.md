---
title: Class StrikeOutAnnotation
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Annotations.StrikeOutAnnotation. تمثل تعليقًا مضروبًا يظهر كخط مضروب في نص المستند
type: docs
weight: 2630
url: /ar/net/aspose.pdf.annotations/strikeoutannotation/
---
## StrikeOutAnnotation class

تمثل تعليقًا مضروبًا يظهر كخط مضروب في نص المستند.

```csharp
public sealed class StrikeOutAnnotation : TextMarkupAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [StrikeOutAnnotation](strikeoutannotation/)(Page, Rectangle) | ينشئ تعليقًا مضروبًا جديدًا على الصفحة المحددة. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | يحصل على قائمة إجراءات التعليق. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل على حالة ظهور التعليق الحالية أو يحددها. |
| override [AnnotationType](../../aspose.pdf.annotations/strikeoutannotation/annotationtype/) { get; } | يحصل على نوع التعليق. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | يحصل على قاموس مظهر التعليق. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | يحصل على خصائص حدود التعليق أو يحددها. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | يحصل على خصائص التعليق. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | يحصل على لون التعليق أو يحدده. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | يحصل على نص التعليق أو يحدده. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | يحصل على التاريخ والوقت الذي تم فيه إنشاء التعليق. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | أعلام التعليق. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | يحصل على الاسم المؤهل الكامل للتعليق. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | يحصل على ارتفاع التعليق أو يحدده. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | يحصل على رابط الفقرة أو يحدده (لإنشاء PDF). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | مرجع إلى التعليق الذي "يرد عليه" هذا التعليق. يجب أن يكون كلا التعليقين على نفس صفحة المستند. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل على قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل على قيمة بوليانية تشير إلى ما إذا كانت الفقرة داخل السطر. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل على قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستولد في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل على قيمة بوليانية تشير إلى ما إذا كانت الفقرة الحالية ستبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل على هامش خارجي للفقرة أو يحدده (لإنشاء PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل على التاريخ والوقت الذي تم فيه تعديل التعليق مؤخرًا أو يحدده. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل على اسم التعليق على الصفحة أو يحدده. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | يحصل على قيمة الشفافية الثابتة التي ستستخدم في رسم التعليق أو يحددها. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على التعليق. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | تعليق منبثق لإدخال أو تعديل النص المرتبط بهذا التعليق. |
| [QuadPoints](../../aspose.pdf.annotations/textmarkupannotation/quadpoints/) { get; set; } | يحصل على مصفوفة من النقاط تحدد إحداثيات n رباعيات الأضلاع. كل رباعي يحيط بكلمة أو مجموعة من الكلمات المتجاورة في النص الذي تحت التعليق. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | يحصل على مستطيل التعليق أو يحدده. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | سلسلة تحدد العلاقة (نوع "الرد") بين هذا التعليق وواحد محدد بواسطة InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | يحصل على سلسلة نص غنية ليتم عرضها في نافذة منبثقة عند فتح التعليق. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس مظهر التعليق. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | يحصل على نص يمثل وصف الكائن. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل على محاذاة النص للتعليق أو يحددها. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | يحصل على نص سيتم عرضه في شريط عنوان التعليق أو يحدده. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل على محاذاة عمودية للفقرة أو يحددها |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل على عرض التعليق أو يحدده. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل على قيمة صحيحة تشير إلى ترتيب Z للرسم. سيتم وضع الرسم الذي لديه ZIndex أكبر فوق الرسم الذي لديه ZIndex أصغر. يمكن أن تكون ZIndex سالبة. سيتم وضع الرسم الذي لديه ZIndex سالب خلف النص في الصفحة. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/strikeoutannotation/accept/)(AnnotationSelector) | يقبل كائن الزائر لمعالجة التعليق. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/textmarkupannotation/changeafterresize/)(Matrix) | يقوم بتحديث QuadPoints، وفقًا لتحويل المصفوفة. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | يمسح الحالة ونموذج الحالة للتعليق. على سبيل المثال، يمسح حالة المراجعة لتعليق. لاحظ أن الحالة مخزنة في تعليق نص آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | يقوم باستنساخ هذه النسخة. طريقة افتراضية. دائمًا ما تعيد null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | يضع محتويات التعليق مباشرة على الصفحة، وسيتم إزالة كائن التعليق. |
| [GetMarkedText](../../aspose.pdf.annotations/textmarkupannotation/getmarkedtext/)() | يحصل على النص تحت تعليق التمييز كسلسلة. |
| [GetMarkedTextFragments](../../aspose.pdf.annotations/textmarkupannotation/getmarkedtextfragments/)() | يحصل على النص تحت تعليق التمييز كسلسلة [`TextFragmentCollection`](../../aspose.pdf.text/textfragmentcollection/). |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يعيد مستطيل التعليق مع الأخذ في الاعتبار دوران الصفحة. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | يحصل على حالة التعليق. لاحظ أن الحالة مخزنة في تعليق نص آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | يحصل على نموذج الحالة للتعليق. لاحظ أن الحالة مخزنة في تعليق نص آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | يحدد الحالة المميزة وغير المميزة للتعليق. لاحظ أن الحالة مخزنة في تعليق نص آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | يحدد حالة المراجعة لتعليق. يتم تجاهل الحالات المميزة وغير المميزة لأنها لا تنتمي إلى نموذج حالة المراجعة. يتم تعيين الحالة بواسطة المستخدم الذي أنشأ التعليق المستهدف. يتم أخذ القيمة من خاصية العنوان للتعليق المستهدف. لاحظ أن الحالة مخزنة في تعليق نص آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | يحدد حالة المراجعة لتعليق. يتم تجاهل الحالات المميزة وغير المميزة لأنها لا تنتمي إلى نموذج حالة المراجعة. لاحظ أن الحالة مخزنة في تعليق نص آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |

### See Also

* class [TextMarkupAnnotation](../textmarkupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)