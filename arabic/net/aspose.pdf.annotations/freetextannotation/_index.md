---
title: "الفئة FreeTextAnnotation"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "Aspose.Pdf.Annotations.FreeTextAnnotation class. تمثل تعليقة نص حر تعرض النص مباشرةً على الصفحة. على عكس تعليقة نص عادية، لا تمتلك تعليقة النص الحر حالة مفتوحة أو مغلقة؛ بدلاً من عرضها في نافذة منبثقة، يكون النص دائمًا مرئيًا."
type: docs
weight: 1900
url: /ar/net/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation class

يمثل ملاحظة نص حر تعرض النص مباشرة على الصفحة. على عكس ملاحظة النص العادية، لا تمتلك ملاحظة النص الحر حالة فتح أو إغلاق؛ بدلاً من عرضها في نافذة منبثقة، يكون النص دائماً مرئياً.

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [FreeTextAnnotation](freetextannotation/#constructor)(Document, DefaultAppearance) | المنشئ للاستخدام مع Generator. |
| [FreeTextAnnotation](freetextannotation/#constructor_1)(Page, Rectangle, DefaultAppearance) | ينشئ تعليقة FreeText جديدة على الصفحة المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | يحصل على قائمة إجراءات التعليق التوضيحي. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل أو يعيّن حالة مظهر التعليق الحالية. |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype/) { get; } | الحصول على نوع التعليقة. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | الحصول على قاموس المظهر للتعليقة. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | يحصل أو يضبط خصائص حدود التعليق. [`Border`](../annotation/border/) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout/) { get; set; } | مصفوفة من النقاط تحدد خط الإشارة. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | الحصول على خصائص التعليقة. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | الحصول على أو تعيين لون التعليقة. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | الحصول على أو تعيين نص التعليقة. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | يحصل على التاريخ والوقت عندما تم إنشاء التعليق. |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance/) { get; set; } | يحصل أو يعيّن سلسلة المظهر الافتراضية التي تُستخدم في تنسيق النص. |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject/) { get; } | كائن يمثل المظهر الافتراضي لتعليقة FreeText. |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle/) { get; set; } | يحصل أو يعيّن سلسلة النمط الافتراضية. |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle/) { get; set; } | يحصل أو يعيّن نمط نهاية الخط لنقطة النهاية. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | علامات التعليقة. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | الحصول على الاسم المؤهل بالكامل للتعليقة. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | الحصول على أو تعيين ارتفاع التعليقة. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | الحصول على أو تعيين ارتباط الفقرة (لمولد PDF). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | إشارة إلى التعليق الذي يكون هذا التعليق "رداً على". يجب أن يكون كلا التعليقين على نفس صفحة المستند. |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent/) { get; set; } | يحصل أو يعيّن نية تعليقة النص الحر. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كان هذا الفقرة سيظهر في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | الحصول على أو تعيين ما إذا كانت الفقرة مضمنة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | الحصول على أو تعيين قيمة bool تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification/) { get; set; } | يحصل أو يعيّن رمزًا يحدد شكل التوزيع (المحاذاة) الذي يُستخدم في عرض نص التعليقة. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يعيّن هامشًا خارجيًا للفقرة (لإنشاء PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل أو يعيّن التاريخ والوقت عندما تم تعديل التعليق مؤخرًا. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل أو يعيّن اسم التعليق على الصفحة. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | يحصل أو يضبط قيمة الشفافية الثابتة المستخدمة في رسم التعليق. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على التعليق التوضيحي. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | تعليق منبثق لإدخال أو تعديل النص المرتبط بهذا التعليق. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | يحصل أو يعيّن مستطيل التعليق التوضيحي. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | سلسلة تحدد العلاقة ("نوع الرد") بين هذا التعليق وتلك المحددة بـ InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | يحصل أو يضبط سلسلة نص غني لتُعرض في النافذة المنبثقة عندما يُفتح التعليق. |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate/) { get; set; } | زاوية دوران التعليق. |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle/) { get; set; } | يحصل أو يضبط نمط نهاية الخط لنقطة نهاية الخط. هذه الخاصية قديمة، يرجى استخدام EndingStyle. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس مظهر التعليق. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | يحصل على النص الذي يمثل وصف الكائن. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل أو يعيّن محاذاة النص للتعليق. |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle/) { get; set; } | مستطيل يصف الفروق العددية بين مستطيلين: مدخل Rect للتعليق ومستطيل داخل ذلك المستطيل. المستطيل الداخلي هو المكان الذي يجب عرض نص التعليق فيه. |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle/) { get; set; } | يحصل أو يضبط نمط النص في المظهر. عندما يتغير نمط النص، يتم تحديث مظهر النص. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | يحصل أو يضبط تسمية نصية تُعرض في شريط عنوان نافذة التعليق المنبثقة عندما تكون مفتوحة ونشطة. يجب أن يحدد هذا الإدخال المستخدم الذي أضاف التعليق. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة عمودية للفقرة |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل أو يعيّن عرض التعليق. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept/)(AnnotationSelector) | يقبل كائن الزائر لمعالجة التعليق. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | تحديث المعلمات والمظهر وفقًا لتحويل المصفوفة. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | يمسح الحالة ونموذج الحالة للتعليق. على سبيل المثال، يمسح حالة المراجعة لتعليق. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه الحالة. طريقة افتراضية. دائمًا تُعيد null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | يضع محتويات التعليق التوضيحي مباشرة على الصفحة، سيتم إزالة كائن التعليق التوضيحي. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يعيد مستطيل التعليق مع مراعاة دوران الصفحة. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | يحصل على حالة التعليق. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | يحصل على نموذج الحالة للتعليق. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | يضبط حالة 'محدد' و'غير محدد' للتعليق. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | يضبط حالة المراجعة لتعليق. يتم تجاهل حالات 'محدد' و'غير محدد' لأنها لا تنتمي إلى نموذج حالة المراجعة (Review StateModel). يتم تعيين الحالة من قبل المستخدم الذي أنشأ التعليق المستهدف. يتم أخذ القيمة من خاصية Title للتعليق المستهدف. ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | يضبط حالة المراجعة لتعليق. يتم تجاهل حالات 'محدد' و'غير محدد' لأنها لا تنتمي إلى نموذج حالة المراجعة (Review StateModel). ملاحظة، يتم تخزين الحالة في تعليقات نصية أخرى تحتوي على مفاتيح state و statemodel. |
| [SetTextStyle](../../aspose.pdf.annotations/freetextannotation/settextstyle/#settextstyle_1)(int, int, RichTextFontStyles) | يضبط التنسيق المحدد بواسطة المعامل textStyle لجزء نص من الفهرس fromInd إلى الفهرس toInd. |
| [SetTextStyle](../../aspose.pdf.annotations/freetextannotation/settextstyle/#settextstyle)(RichTextFontStyles, string, double, Color) | يضبط التنسيق المحدد بواسطة المعامل textStyle لجميع نصوص التعليق. |

### انظر أيضًا

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


