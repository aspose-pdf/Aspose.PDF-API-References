---
title: "الفئة RedactionAnnotation"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Annotations.RedactionAnnotation. تمثل تعليقة الحذف"
type: docs
weight: 2490
url: /ar/net/aspose.pdf.annotations/redactionannotation/
---
## RedactionAnnotation class

يمثل تعليق توضيحي Redact.

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [RedactionAnnotation](redactionannotation/#constructor)(Document) | منشئ RedactionAnnotation. للاستخدام في Generator. |
| [RedactionAnnotation](redactionannotation/#constructor_1)(Page, Rectangle) | منشئ RedactAnnotation. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | يحصل على قائمة إجراءات التعليق التوضيحي. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل أو يعيّن حالة مظهر التعليق الحالية. |
| override [AnnotationType](../../aspose.pdf.annotations/redactionannotation/annotationtype/) { get; } | الحصول على نوع التعليقة. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | الحصول على قاموس المظهر للتعليقة. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | يحصل أو يضبط خصائص حدود التعليق. [`Border`](../annotation/border/) |
| [BorderColor](../../aspose.pdf.annotations/redactionannotation/bordercolor/) { get; set; } | يحصل أو يعيّن لون الحدود التي تُرسم عندما لا تكون عملية الحذف نشطة. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | الحصول على خصائص التعليقة. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | الحصول على أو تعيين لون التعليقة. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | الحصول على أو تعيين نص التعليقة. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | يحصل على التاريخ والوقت عندما تم إنشاء التعليق. |
| [DefaultAppearance](../../aspose.pdf.annotations/redactionannotation/defaultappearance/) { get; set; } | يحصل أو يعيّن سلسلة المظهر الافتراضية التي تُستخدم في تنسيق النص. |
| [FillColor](../../aspose.pdf.annotations/redactionannotation/fillcolor/) { get; set; } | يحصل أو يعيّن اللون لملء التعليقة. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | علامات التعليقة. |
| [FontSize](../../aspose.pdf.annotations/redactionannotation/fontsize/) { get; set; } | يحصل أو يعيّن حجم الخط لـ OverlayText. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | الحصول على الاسم المؤهل بالكامل للتعليقة. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | الحصول على أو تعيين ارتفاع التعليقة. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | الحصول على أو تعيين ارتباط الفقرة (لمولد PDF). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | إشارة إلى التعليق الذي يكون هذا التعليق "رداً على". يجب أن يكون كلا التعليقين على نفس صفحة المستند. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كان هذا الفقرة سيظهر في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | الحصول على أو تعيين ما إذا كانت الفقرة مضمنة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | الحصول على أو تعيين قيمة bool تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يعيّن هامشًا خارجيًا للفقرة (لإنشاء PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل أو يعيّن التاريخ والوقت عندما تم تعديل التعليق مؤخرًا. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل أو يعيّن اسم التعليق على الصفحة. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | يحصل أو يضبط قيمة الشفافية الثابتة المستخدمة في رسم التعليق. |
| [OverlayText](../../aspose.pdf.annotations/redactionannotation/overlaytext/) { get; set; } | يحصل أو يعيّن النص للطباعة على التعليق المحذوف. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على التعليق التوضيحي. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | تعليق منبثق لإدخال أو تعديل النص المرتبط بهذا التعليق. |
| [QuadPoint](../../aspose.pdf.annotations/redactionannotation/quadpoint/) { get; set; } | مصفوفة من أعداد 8xN تحدد إحداثيات منطقة المحتوى التي يُقصد إزالتها. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | يحصل أو يعيّن مستطيل التعليق التوضيحي. |
| [Repeat](../../aspose.pdf.annotations/redactionannotation/repeat/) { get; set; } | إذا كان صحيحًا، سيتكرر نص التراكب على التعليق. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | سلسلة تحدد العلاقة ("نوع الرد") بين هذا التعليق وتلك المحددة بـ InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | يحصل أو يضبط سلسلة نص غني لتُعرض في النافذة المنبثقة عندما يُفتح التعليق. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس مظهر التعليق. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | يحصل على النص الذي يمثل وصف الكائن. |
| [TextAlignment](../../aspose.pdf.annotations/redactionannotation/textalignment/) { get; set; } | يحصل أو يعيّن. محاذاة نص التراكب. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل أو يعيّن محاذاة النص للتعليق. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | يحصل أو يضبط تسمية نصية تُعرض في شريط عنوان نافذة التعليق المنبثقة عندما تكون مفتوحة ونشطة. يجب أن يحدد هذا الإدخال المستخدم الذي أضاف التعليق. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة عمودية للفقرة |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل أو يعيّن عرض التعليق. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/redactionannotation/accept/)(AnnotationSelector) | يقبل كائن الزائر لمعالجة التعليق. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | تحديث المعلمات والمظهر وفقًا لتحويل المصفوفة. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | يمسح الحالة ونموذج الحالة للتعليق. على سبيل المثال، يمسح حالة المراجعة لتعليق. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه الحالة. طريقة افتراضية. دائمًا تُعيد null. |
| override [Flatten](../../aspose.pdf.annotations/redactionannotation/flatten/)() | يقوم بتسطيح التعليق أي يزيل التعليق ويضيف ما له |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يعيد مستطيل التعليق مع مراعاة دوران الصفحة. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | يحصل على حالة التعليق. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | يحصل على نموذج الحالة للتعليق. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| [Redact](../../aspose.pdf.annotations/redactionannotation/redact/)() | يقوم بتسطيح التعليق ويحذف محتويات الصفحة (أي يزيل النص والصورة تحت التعليق المحذوف). |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | يضبط حالة 'محدد' و'غير محدد' للتعليق. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | يضبط حالة المراجعة لتعليق. يتم تجاهل حالات 'محدد' و'غير محدد' لأنها لا تنتمي إلى نموذج حالة المراجعة (Review StateModel). يتم تعيين الحالة من قبل المستخدم الذي أنشأ التعليق المستهدف. يتم أخذ القيمة من خاصية Title للتعليق المستهدف. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | يضبط حالة المراجعة لتعليق. يتم تجاهل حالات 'محدد' و'غير محدد' لأنها لا تنتمي إلى نموذج حالة المراجعة (Review StateModel). ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |

### انظر أيضًا

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


