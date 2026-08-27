---
title: "فئة ColorBarAnnotation"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Annotations.ColorBarAnnotation. فئة تمثل تعليقة ColorBarAnnotation. الخاصية Color يتم تجاهلها ويُستخدم بدلاً منها لون ColorsOfCMYK. عند الإنشاء، تحدد نسبة العرض إلى الارتفاع اتجاه التعليقة (أفقي أو عمودي). بعد ذلك يتحقق مما إذا كان مستطيل التعليقة خارج TrimBox، وإذا لم يكن كذلك يتم إزاحته إلى أقرب موقع خارج TrimBox مع مراعاة اتجاه التعليقة. يمكن تقليل العرض والارتفاع بحيث تتناسب التعليقة خارج TrimBox. إذا لم يتوفر مساحة للتخطيط، يمكن ضبط العرض/الارتفاع على الصفر؛ في هذه الحالة تكون التعليقة موجودة على الصفحة لكنها غير معروضة."
type: docs
weight: 1690
url: /ar/net/aspose.pdf.annotations/colorbarannotation/
---
## ColorBarAnnotation class

فئة تمثل تعليقًا توضيحيًا من نوع ColorBarAnnotation. يتم تجاهل الخاصية Color، ويتم استخدام لون ColorsOfCMYK بدلاً منها. عند الإنشاء، يحدد نسبة العرض إلى الارتفاع اتجاه التعليق — أفقي أو عمودي. بعد ذلك، يتم التحقق من أن مستطيل التعليق خارج TrimBox، وإذا لم يكن كذلك، يتم إزاحته إلى أقرب موقع خارج TrimBox مع مراعاة اتجاه التعليق. يمكن تقليل العرض (الارتفاع) بحيث يتناسب التعليق خارج TrimBox. إذا لم يتوفر مساحة للتخطيط، يمكن ضبط العرض/الارتفاع على الصفر (في هذه الحالة، يكون التعليق موجودًا على الصفحة لكنه غير معروض).

```csharp
public sealed class ColorBarAnnotation : PrinterMarkAnnotation
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ColorBarAnnotation](colorbarannotation/)(Page, Rectangle, ColorsOfCMYK) | ينشئ تعليقة ColorBar جديدة على الصفحة المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | يحصل على قائمة إجراءات التعليق التوضيحي. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل أو يعيّن حالة مظهر التعليق الحالية. |
| override [AnnotationType](../../aspose.pdf.annotations/colorbarannotation/annotationtype/) { get; } | الحصول على نوع التعليقة. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | الحصول على قاموس المظهر للتعليقة. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | يحصل أو يضبط خصائص حدود التعليق. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | الحصول على خصائص التعليقة. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | الحصول على أو تعيين لون التعليقة. |
| [ColorOfCMYK](../../aspose.pdf.annotations/colorbarannotation/colorofcmyk/) { get; set; } | يحصل أو يعيّن اللون (واحد من السماوي، الأرجواني، الأصفر، الأسود) الذي تُرسم به التعليقة. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | الحصول على أو تعيين نص التعليقة. |
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
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | يحصل أو يعيّن مستطيل التعليق التوضيحي. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس مظهر التعليق. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل أو يعيّن محاذاة النص للتعليق. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يعيّن محاذاة عمودية للفقرة |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل أو يعيّن عرض التعليق. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يعيّن قيمة عددية تشير إلى ترتيب Z للرسم البياني. الرسم البياني ذو ZIndex أكبر سيُوضع فوق الرسم البياني ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. الرسم البياني ذو ZIndex سالب سيُوضع خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/colorbarannotation/accept/)(AnnotationSelector) | يقبل كائن الزائر لمعالجة التعليق. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/colorbarannotation/changeafterresize/)(Matrix) | تحديث المعلمات والمظهر وفقًا لتحويل المصفوفة والتحرك خارج TrimBox إذا لزم الأمر. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه الحالة. طريقة افتراضية. دائمًا تُعيد null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | يضع محتويات التعليق التوضيحي مباشرة على الصفحة، سيتم إزالة كائن التعليق التوضيحي. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يعيد مستطيل التعليق مع مراعاة دوران الصفحة. |

### انظر أيضًا

* class [PrinterMarkAnnotation](../printermarkannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


