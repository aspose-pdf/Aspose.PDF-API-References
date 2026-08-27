---
title: "الفئة PolylineAnnotation"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Annotations.PolylineAnnotation. تمثّل التعليق التوضيحي للخط المتعدد النقاط الذي يشبه المضلع باستثناء أن القمة الأولى والأخيرة غير متصلة ضمنيًا."
type: docs
weight: 2410
url: /ar/net/aspose.pdf.annotations/polylineannotation/
---
## PolylineAnnotation class

تمثل تعليق توضيحي خط متعدد يشبه المضلع، باستثناء أن القمة الأولى والأخيرة غير متصلة ضمنيًا.

```csharp
public sealed class PolylineAnnotation : PolyAnnotation
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PolylineAnnotation](polylineannotation/)(Page, Rectangle, Point[]) | ينشئ تعليقًا توضيحيًا جديدًا من نوع Polyline على الصفحة المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | يحصل على قائمة إجراءات التعليق التوضيحي. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل أو يعيّن حالة مظهر التعليق الحالية. |
| override [AnnotationType](../../aspose.pdf.annotations/polylineannotation/annotationtype/) { get; } | الحصول على نوع التعليقة. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | الحصول على قاموس المظهر للتعليقة. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | يحصل أو يضبط خصائص حدود التعليق. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | الحصول على خصائص التعليقة. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | الحصول على أو تعيين لون التعليقة. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | الحصول على أو تعيين نص التعليقة. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | يحصل على التاريخ والوقت عندما تم إنشاء التعليق. |
| [EndingStyle](../../aspose.pdf.annotations/polyannotation/endingstyle/) { get; set; } | يحصل أو يضبط نمط نهاية السطر الثاني. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | علامات التعليقة. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | الحصول على الاسم المؤهل بالكامل للتعليقة. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | الحصول على أو تعيين ارتفاع التعليقة. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | الحصول على أو تعيين ارتباط الفقرة (لمولد PDF). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | إشارة إلى التعليق الذي يكون هذا التعليق "رداً على". يجب أن يكون كلا التعليقين على نفس صفحة المستند. |
| [Intent](../../aspose.pdf.annotations/polyannotation/intent/) { get; set; } | يحصل أو يضبط نية التعليق المضلع أو المتعدد الخطوط. |
| [InteriorColor](../../aspose.pdf.annotations/polyannotation/interiorcolor/) { get; set; } | يحصل أو يضبط اللون الداخلي الذي يُملأ به نهايات خطوط التعليق. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كان هذا الفقرة سيظهر في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | الحصول على أو تعيين ما إذا كانت الفقرة مضمنة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | الحصول على أو تعيين قيمة bool تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يعيّن هامشًا خارجيًا للفقرة (لإنشاء PDF) |
| [Measure](../../aspose.pdf.annotations/polyannotation/measure/) { get; set; } | وحدات القياس المحددة لهذا التعليق. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل أو يعيّن التاريخ والوقت عندما تم تعديل التعليق مؤخرًا. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل أو يعيّن اسم التعليق على الصفحة. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | يحصل أو يضبط قيمة الشفافية الثابتة المستخدمة في رسم التعليق. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على التعليق التوضيحي. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | تعليق منبثق لإدخال أو تعديل النص المرتبط بهذا التعليق. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | يحصل أو يعيّن مستطيل التعليق التوضيحي. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | سلسلة تحدد العلاقة ("نوع الرد") بين هذا التعليق وتلك المحددة بـ InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | يحصل أو يضبط سلسلة نص غني لتُعرض في النافذة المنبثقة عندما يُفتح التعليق. |
| [StartingStyle](../../aspose.pdf.annotations/polyannotation/startingstyle/) { get; set; } | يحصل أو يضبط نمط نهاية السطر الأول. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس مظهر التعليق. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | يحصل على النص الذي يمثل وصف الكائن. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل أو يعيّن محاذاة النص للتعليق. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | يحصل أو يضبط تسمية نصية تُعرض في شريط عنوان نافذة التعليق المنبثقة عندما تكون مفتوحة ونشطة. يجب أن يحدد هذا الإدخال المستخدم الذي أضاف التعليق. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة عمودية للفقرة |
| [Vertices](../../aspose.pdf.annotations/polyannotation/vertices/) { get; set; } | يحصل أو يضبط مصفوفة من النقاط التي تمثل الإحداثيات الأفقية والعمودية لكل رأس. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل أو يعيّن عرض التعليق. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/polylineannotation/accept/)(AnnotationSelector) | يقبل كائن الزائر لمعالجة التعليق. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/polyannotation/changeafterresize/)(Matrix) | يقوم بتحديث النقاط في Vertices وفقًا لتحويل المصفوفة. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | يمسح الحالة ونموذج الحالة للتعليق. على سبيل المثال، يمسح حالة المراجعة لتعليق. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه الحالة. طريقة افتراضية. دائمًا تُعيد null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | يضع محتويات التعليق التوضيحي مباشرة على الصفحة، سيتم إزالة كائن التعليق التوضيحي. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يعيد مستطيل التعليق مع مراعاة دوران الصفحة. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | يحصل على حالة التعليق. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | يحصل على نموذج الحالة للتعليق. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | يضبط حالة 'محدد' و'غير محدد' للتعليق. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | يضبط حالة المراجعة لتعليق. يتم تجاهل حالات 'محدد' و'غير محدد' لأنها لا تنتمي إلى نموذج حالة المراجعة (Review StateModel). يتم تعيين الحالة من قبل المستخدم الذي أنشأ التعليق المستهدف. يتم أخذ القيمة من خاصية Title للتعليق المستهدف. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | يضبط حالة المراجعة لتعليق. يتم تجاهل حالات 'محدد' و'غير محدد' لأنها لا تنتمي إلى نموذج حالة المراجعة (Review StateModel). ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |

### انظر أيضًا

* class [PolyAnnotation](../polyannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


