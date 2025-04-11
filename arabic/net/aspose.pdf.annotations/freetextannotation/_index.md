---
title: Class FreeTextAnnotation
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Annotations.FreeTextAnnotation. تمثل تعليق نص حر يعرض النص مباشرة على الصفحة. على عكس تعليق النص العادي، لا يحتوي تعليق النص الحر على حالة مفتوحة أو مغلقة؛ بدلاً من عرضه في نافذة منبثقة، يكون النص مرئيًا دائمًا.
type: docs
weight: 1810
url: /ar/net/aspose.pdf.annotations/freetextannotation/
---
## فئة FreeTextAnnotation

تمثل تعليق نص حر يعرض النص مباشرة على الصفحة. على عكس تعليق النص العادي، لا يحتوي تعليق النص الحر على حالة مفتوحة أو مغلقة؛ بدلاً من عرضه في نافذة منبثقة، يكون النص مرئيًا دائمًا.

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FreeTextAnnotation](freetextannotation/#constructor)(Document, DefaultAppearance) | منشئ للاستخدام مع المولد. |
| [FreeTextAnnotation](freetextannotation/#constructor_1)(Page, Rectangle, DefaultAppearance) | ينشئ تعليق نص حر جديد على الصفحة المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | يحصل على قائمة إجراءات التعليق. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل أو يحدد حالة ظهور التعليق الحالية. |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype/) { get; } | يحصل على نوع التعليق. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | يحصل على قاموس مظهر التعليق. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | يحصل أو يحدد خصائص حدود التعليق. [`Border`](../annotation/border/) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout/) { get; set; } | مصفوفة من النقاط تحدد خط الاستدعاء. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | يحصل على خصائص التعليق. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | يحصل أو يحدد لون التعليق. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | يحصل أو يحدد نص التعليق. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | يحصل على التاريخ والوقت الذي تم فيه إنشاء التعليق. |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance/) { get; set; } | يحصل أو يحدد سلسلة المظهر الافتراضية التي سيتم استخدامها في تنسيق النص. |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject/) { get; } | كائن يمثل المظهر الافتراضي لتعليق النص الحر. |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle/) { get; set; } | يحصل أو يحدد سلسلة نمط افتراضي. |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle/) { get; set; } | يحصل أو يحدد نمط نهاية الخط لنقطة نهاية الخط. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | أعلام التعليق. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | يحصل على الاسم المؤهل الكامل للتعليق. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | يحصل أو يحدد ارتفاع التعليق. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | يحصل أو يحدد رابط الجزء (للمولد PDF). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | مرجع إلى التعليق الذي "يرد عليه" هذا التعليق. يجب أن يكون كلا التعليقين على نفس صفحة الوثيقة. |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent/) { get; set; } | يحصل أو يحدد نية تعليق النص الحر. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية هي false.(لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل أو يحدد ما إذا كانت الفقرة في السطر. القيمة الافتراضية هي false.(لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل أو يحدد قيمة بوليانية تجبر هذه الفقرة على التوليد في صفحة جديدة. القيمة الافتراضية هي false.(لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false.(لإنشاء PDF) |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification/) { get; set; } | يحصل أو يحدد رمزًا يحدد شكل التبرير (التبرير) الذي سيتم استخدامه في عرض نص التعليق. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يحدد هامش خارجي للفقرة (لإنشاء PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل أو يحدد التاريخ والوقت الذي تم فيه تعديل التعليق مؤخرًا. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل أو يحدد اسم التعليق على الصفحة. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | يحصل أو يحدد قيمة الشفافية الثابتة التي سيتم استخدامها في رسم التعليق. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على التعليق. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | تعليق منبثق لإدخال أو تحرير النص المرتبط بهذا التعليق. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | يحصل أو يحدد مستطيل التعليق. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | سلسلة تحدد العلاقة (نوع "الرد") بين هذا التعليق وآخر محدد بواسطة InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | يحصل أو يحدد سلسلة نص غنية سيتم عرضها في النافذة المنبثقة عند فتح التعليق. |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate/) { get; set; } | زاوية دوران التعليق. |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle/) { get; set; } | يحصل أو يحدد نمط بداية الخط لنقطة نهاية الخط. هذه الخاصية قديمة، يرجى استخدام EndingStyle. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس مظهر التعليق. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | يحصل على نص يمثل وصف الكائن. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل أو يحدد محاذاة النص للتعليق. |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle/) { get; set; } | مستطيل يصف الفروق العددية بين مستطيلين: إدخال Rect للتعليق ومستطيل يحتوي داخل ذلك المستطيل. المستطيل الداخلي هو المكان الذي يجب عرض نص التعليق فيه. |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle/) { get; set; } | يحصل أو يحدد نمط النص في المظهر. عند تغيير نمط النص، يتم تحديث مظهر النص. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | يحصل أو يحدد نصًا سيتم عرضه في شريط عنوان التعليق. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يحدد محاذاة عمودية للفقرة |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل أو يحدد عرض التعليق. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يحدد قيمة صحيحة تشير إلى ترتيب Z للرسم. سيتم وضع رسم ذو ZIndex أكبر فوق الرسم ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. سيتم وضع الرسم ذو ZIndex سالب خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept/)(AnnotationSelector) | يقبل كائن الزائر لمعالجة التعليق. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | تحديث المعلمات والمظهر، وفقًا لتحويل المصفوفة. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Clears state and state model for the annotation. For example, clears the review status for an annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه النسخة. طريقة افتراضية. دائمًا ما تعيد null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | يضع محتويات التعليق مباشرة على الصفحة، وسيتم إزالة كائن التعليق. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يعيد مستطيل التعليق مع الأخذ في الاعتبار دوران الصفحة. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | يحصل على حالة التعليق. لاحظ أن الحالة مخزنة في تعليق نص آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | يحصل على نموذج الحالة للتعليق. لاحظ أن الحالة مخزنة في تعليق نص آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | يحدد الحالة المميزة وغير المميزة للتعليق. لاحظ أن الحالة مخزنة في تعليق نص آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | يحدد حالة المراجعة لتعليق. يتم تجاهل الحالات المميزة وغير المميزة لأنها لا تنتمي إلى نموذج حالة المراجعة. يتم تعيين الحالة بواسطة المستخدم الذي أنشأ التعليق المستهدف. يتم أخذ القيمة من خاصية العنوان للتعليق المستهدف. لاحظ أن الحالة مخزنة في تعليق نص آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | يحدد حالة المراجعة لتعليق. يتم تجاهل الحالات المميزة وغير المميزة لأنها لا تنتمي إلى نموذج حالة المراجعة. لاحظ أن الحالة مخزنة في تعليق نص آخر يحتوي على مفاتيح الحالة ونموذج الحالة. |

### انظر أيضًا

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)