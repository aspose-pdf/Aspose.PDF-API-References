---
title: Class TextAnnotation
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Annotations.TextAnnotation. تمثل تعليق نصي هو ملاحظة لاصقة مرتبطة بنقطة في مستند PDF
type: docs
weight: 2650
url: /ar/net/aspose.pdf.annotations/textannotation/
---
## TextAnnotation class

تمثل تعليق نصي هو "ملاحظة لاصقة" مرتبطة بنقطة في مستند PDF.

```csharp
public sealed class TextAnnotation : MarkupAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [TextAnnotation](textannotation/#constructor)(Document) | مُنشئ للتعليق عند استخدامه في المُولد. |
| [TextAnnotation](textannotation/#constructor_1)(Page, Rectangle) | ينشئ تعليق نصي جديد على الصفحة المحددة. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | يحصل على قائمة إجراءات التعليق. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل أو يحدد حالة ظهور التعليق الحالية. |
| override [AnnotationType](../../aspose.pdf.annotations/textannotation/annotationtype/) { get; } | يحصل على نوع التعليق. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | يحصل على قاموس مظهر التعليق. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | يحصل أو يحدد خصائص حدود التعليق. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | يحصل على خصائص التعليق. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | يحصل أو يحدد لون التعليق. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | يحصل أو يحدد نص التعليق. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | يحصل على التاريخ والوقت عندما تم إنشاء التعليق. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | علامات التعليق. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | يحصل على الاسم المؤهل الكامل للتعليق. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | يحصل أو يحدد ارتفاع التعليق. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | يحصل أو يحدد رابط الجزء (للمولد PDF). |
| [Icon](../../aspose.pdf.annotations/textannotation/icon/) { get; set; } | يحصل أو يحدد أيقونة لاستخدامها في عرض التعليق. |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | مرجع إلى التعليق الذي "يرد عليه" هذا التعليق. يجب أن يكون كلا التعليقين على نفس الصفحة من المستند. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية هي false.(لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل أو يحدد ما إذا كانت الفقرة داخل السطر. القيمة الافتراضية هي false.(لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل أو يحدد قيمة بوليانية تجبر هذه الفقرة على التوليد في صفحة جديدة. القيمة الافتراضية هي false.(لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false.(لإنشاء PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يحدد هامش خارجي للفقرة (لإنشاء PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل أو يحدد التاريخ والوقت عندما تم تعديل التعليق مؤخرًا. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل أو يحدد اسم التعليق على الصفحة. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | يحصل أو يحدد قيمة الشفافية الثابتة التي ستستخدم في رسم التعليق. |
| [Open](../../aspose.pdf.annotations/textannotation/open/) { get; set; } | يحصل أو يحدد علامة تحدد ما إذا كان يجب عرض التعليق مفتوحًا في البداية. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على التعليق. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | تعليق منبثق لإدخال أو تعديل النص المرتبط بهذا التعليق. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | يحصل أو يحدد مستطيل التعليق. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | سلسلة تحدد العلاقة (نوع "الرد") بين هذا التعليق وواحد محدد بواسطة InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | يحصل أو يحدد سلسلة نصية غنية سيتم عرضها في نافذة منبثقة عند فتح التعليق. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس مظهر التعليق. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | يحصل على نص يمثل وصف الكائن. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل أو يحدد محاذاة النص للتعليق. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | يحصل أو يحدد نصًا سيتم عرضه في شريط عنوان التعليق. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يحدد محاذاة عمودية للفقرة |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل أو يحدد عرض التعليق. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يحدد قيمة صحيحة تشير إلى ترتيب Z للرسم. سيتم وضع الرسم الذي لديه ZIndex أكبر فوق الرسم الذي لديه ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. سيتم وضع الرسم الذي لديه ZIndex سالب خلف النص في الصفحة. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/textannotation/accept/)(AnnotationSelector) | يقبل كائن الزائر لمعالجة التعليق. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/textannotation/changeafterresize/)(Matrix) | يتجاوز التعريف في الفئة الأساسية بجسم فارغ. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Clears state and state model for the annotation. For example, clears the review status for an annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه النسخة. طريقة افتراضية. دائمًا ما تعيد null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | يضع محتويات التعليق مباشرة على الصفحة، وسيتم إزالة كائن التعليق. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يعيد مستطيل التعليق مع الأخذ في الاعتبار دوران الصفحة. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | يحصل على حالة التعليق. لاحظ أن الحالة مخزنة في تعليق نصي آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | يحصل على نموذج الحالة للتعليق. لاحظ أن الحالة مخزنة في تعليق نصي آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | يحدد الحالة المميزة وغير المميزة للتعليق. لاحظ أن الحالة مخزنة في تعليق نصي آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | يحدد حالة المراجعة لتعليق. يتم تجاهل الحالات المميزة وغير المميزة لأنها لا تنتمي إلى نموذج حالة المراجعة. يتم تعيين الحالة بواسطة المستخدم الذي أنشأ التعليق المستهدف. يتم أخذ القيمة من خاصية العنوان للتعليق المستهدف. لاحظ أن الحالة مخزنة في تعليق نصي آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | يحدد حالة المراجعة لتعليق. يتم تجاهل الحالات المميزة وغير المميزة لأنها لا تنتمي إلى نموذج حالة المراجعة. لاحظ أن الحالة مخزنة في تعليق نصي آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |

### See Also

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)