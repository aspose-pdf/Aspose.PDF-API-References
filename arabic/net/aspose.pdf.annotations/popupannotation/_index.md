---
title: Class PopupAnnotation
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Annotations.PopupAnnotation. تمثل التعليق المنبثق الذي يعرض النص في نافذة منبثقة للإدخال والتحرير
type: docs
weight: 2330
url: /ar/net/aspose.pdf.annotations/popupannotation/
---
## فئة PopupAnnotation

تمثل التعليق المنبثق الذي يعرض النص في نافذة منبثقة للإدخال والتحرير.

```csharp
public sealed class PopupAnnotation : Annotation
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PopupAnnotation](popupannotation/#constructor)(Document) | المنشئ. للاستخدام في المولد. |
| [PopupAnnotation](popupannotation/#constructor_1)(Page, Rectangle) | ينشئ تعليق منبثق جديد على الصفحة المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | يحصل على قائمة إجراءات التعليق. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | يحصل أو يحدد حالة مظهر التعليق الحالي. |
| override [AnnotationType](../../aspose.pdf.annotations/popupannotation/annotationtype/) { get; } | يحصل على نوع التعليق. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | يحصل على قاموس مظهر التعليق. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | يحصل أو يحدد خصائص حدود التعليق. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | يحصل على خصائص التعليق. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | يحصل أو يحدد لون التعليق. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | يحصل أو يحدد نص التعليق. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | أعلام التعليق. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | يحصل على الاسم المؤهل بالكامل للتعليق. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | يحصل أو يحدد ارتفاع التعليق. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | يحصل أو يحدد رابط الفقرة (للمولد PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت هذه الفقرة ستكون في العمود التالي. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | يحصل أو يحدد ما إذا كانت الفقرة في السطر. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | يحصل أو يحدد قيمة بوليانية تجبر هذه الفقرة على التوليد في صفحة جديدة. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | يحصل أو يحدد قيمة بوليانية تشير إلى ما إذا كانت الفقرة الحالية تبقى في نفس الصفحة مع الفقرة التالية. القيمة الافتراضية هي false. (لإنشاء PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | يحصل أو يحدد هامش خارجي للفقرة (لإنشاء PDF) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | يحصل أو يحدد التاريخ والوقت عندما تم تعديل التعليق مؤخرًا. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | يحصل أو يحدد اسم التعليق على الصفحة. |
| [Open](../../aspose.pdf.annotations/popupannotation/open/) { get; set; } | يحصل أو يحدد علمًا يحدد ما إذا كان يجب عرض التعليق المنبثق مفتوحًا في البداية. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | يحصل على فهرس الصفحة التي تحتوي على التعليق. |
| [Parent](../../aspose.pdf.annotations/popupannotation/parent/) { get; set; } | يحصل أو يحدد التعليق الأب الذي يجب أن يرتبط به هذا التعليق المنبثق. إذا كانت هذه المدخلة موجودة، فإن محتويات التعليق الأب، M، C، و T ستتجاوز تلك الخاصة بالتعليق المنبثق نفسه. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | يحصل أو يحدد مستطيل التعليق. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | يحصل على قاموس مظهر التعليق. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | يحصل أو يحدد محاذاة النص للتعليق. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | يحصل أو يحدد محاذاة عمودية للفقرة |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | يحصل أو يحدد عرض التعليق. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | يحصل أو يحدد قيمة صحيحة تشير إلى ترتيب Z للرسم. سيتم وضع رسم ذو ZIndex أكبر فوق الرسم ذو ZIndex أصغر. يمكن أن يكون ZIndex سالبًا. سيتم وضع الرسم ذو ZIndex سالب خلف النص في الصفحة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/popupannotation/accept/)(AnnotationSelector) | يقبل كائن الزائر لمعالجة التعليق. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | تحديث المعلمات والمظهر، وفقًا لتحويل المصفوفة. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | ينسخ هذه النسخة. طريقة افتراضية. دائمًا ما تعيد null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | يضع محتويات التعليق مباشرة على الصفحة، وسيتم إزالة كائن التعليق. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | يعيد مستطيل التعليق مع الأخذ في الاعتبار دوران الصفحة. |

### انظر أيضًا

* فئة [Annotation](../annotation/)
* مساحة الأسماء [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* التجميع [Aspose.PDF](../../)