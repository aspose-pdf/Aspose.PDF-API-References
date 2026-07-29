---
title: "الفئة MovieAnnotation"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Annotations.MovieAnnotation. تمثل توضيح فيلم يحتوي على رسومات متحركة وصوت يُعرض على شاشة الكمبيوتر ومن خلال السماعات. عند تفعيل التوضيح يتم تشغيل الفيلم."
type: docs
weight: 2200
url: /ar/net/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation class

يمثل تعليقا للفيلم يحتوي على رسومات متحركة وصوت يُعرض على شاشة الكمبيوتر ومن خلال السماعات. عند تفعيل التعليق، يتم تشغيل الفيلم.

```csharp
public sealed class MovieAnnotation : Annotation
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MovieAnnotation](movieannotation/#constructor)(Document, string) | منشئ للاستخدام مع Generator. |
| [MovieAnnotation](movieannotation/#constructor_1)(Page, Rectangle, string) | ينشئ توضيح صوت جديد على الصفحة المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | يحصل على قائمة إجراءات التعليق التوضيحي. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل أو يعيّن حالة مظهر التعليق الحالية. |
| override [AnnotationType](../../aspose.pdf.annotations/movieannotation/annotationtype/) { get; } | الحصول على نوع التعليقة. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | الحصول على قاموس المظهر للتعليقة. |
| [Aspect](../../aspose.pdf.annotations/movieannotation/aspect/) { get; set; } | يحصل أو يضبط عرض وارتفاع صندوق حدود الفيلم، بالبكسل. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | يحصل أو يضبط خصائص حدود التعليق. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | الحصول على خصائص التعليقة. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | الحصول على أو تعيين لون التعليقة. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | الحصول على أو تعيين نص التعليقة. |
| [File](../../aspose.pdf.annotations/movieannotation/file/) { get; set; } | يحصل أو يضبط مواصفة ملف تحدد ملف فيلم ذاتي الوصف. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | علامات التعليقة. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | الحصول على الاسم المؤهل بالكامل للتعليقة. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | الحصول على أو تعيين ارتفاع التعليقة. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | الحصول على أو تعيين ارتباط الفقرة (لمولد PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كان هذا الفقرة سيظهر في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | الحصول على أو تعيين ما إذا كانت الفقرة مضمنة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | الحصول على أو تعيين قيمة bool تجبر هذه الفقرة على الإنشاء في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | الحصول على أو تعيين قيمة bool تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يعيّن هامشًا خارجيًا للفقرة (لإنشاء PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل أو يعيّن التاريخ والوقت عندما تم تعديل التعليق مؤخرًا. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل أو يعيّن اسم التعليق على الصفحة. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على التعليق التوضيحي. |
| [Poster](../../aspose.pdf.annotations/movieannotation/poster/) { get; set; } | يحصل أو يضبط علامة أو تدفق يحدد ما إذا كان وكيف سيتم عرض صورة ملصق تمثل الفيلم. إذا كانت true، سيتم جلب صورة الملصق من ملف الفيلم؛ إذا كانت false، لن يتم عرض أي ملصق. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | يحصل أو يعيّن مستطيل التعليق التوضيحي. |
| [Rotate](../../aspose.pdf.annotations/movieannotation/rotate/) { get; set; } | يحصل أو يضبط عدد الدرجات التي سيُدور بها الفيلم باتجاه عقارب الساعة بالنسبة للصفحة. يجب أن تكون القيمة مضاعفًا للعدد 90. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس مظهر التعليق. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل أو يعيّن محاذاة النص للتعليق. |
| [Title](../../aspose.pdf.annotations/movieannotation/title/) { get; set; } | يحصل أو يعيّن عنوان التعليق التوضيحي للفيلم. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة عمودية للفقرة |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل أو يعيّن عرض التعليق. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/movieannotation/accept/)(AnnotationSelector) | يقبل كائن الزائر لمعالجة التعليق. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | تحديث المعلمات والمظهر وفقًا لتحويل المصفوفة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه الحالة. طريقة افتراضية. دائمًا تُعيد null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | يضع محتويات التعليق التوضيحي مباشرة على الصفحة، سيتم إزالة كائن التعليق التوضيحي. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يعيد مستطيل التعليق مع مراعاة دوران الصفحة. |

### انظر أيضًا

* class [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


