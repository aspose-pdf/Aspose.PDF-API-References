---
title: "الفئة ImageStamp"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.ImageStamp. تمثل ختمًا رسوميًا"
type: docs
weight: 6060
url: /ar/net/aspose.pdf/imagestamp/
---
## ImageStamp class

يمثل ختمًا رسوميًا.

```csharp
public sealed class ImageStamp : Stamp
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | تهيئة نسخة جديدة من الفئة `ImageStamp`. |
| [ImageStamp](imagestamp/#constructor_1)(string) | إنشاء ختم صورة باستخدام الصورة الموجودة في الملف المحدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | الحصول على أو تعيين النص البديل لختم الصورة. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | يضبط أو يحصل على قيمة bool تشير إلى أن المحتوى تم وضعه كخلفية. إذا كانت القيمة true، يتم وضع محتوى الطابع في الأسفل. بشكل افتراضي، تكون القيمة false، ويتم وضع محتوى الطابع في الأعلى. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | يحصل أو يضبط الهامش السفلي للطابع. |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | الحصول على أو تعيين ارتفاع الصورة. ضبط هذه الصورة يسمح بتكبير الصورة عموديًا. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | يحصل أو يضبط محاذاة الطابع الأفقية على الصفحة. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | الحصول على تدفق الصورة المستخدم للختم. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | يحصل أو يضبط الهامش الأيسر للطابع. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | يحصل أو يضبط قيمة لتحديد شفافية الطابع. القيمة تتراوح بين 0.0 إلى 1.0. بشكل افتراضي القيمة هي 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | يحصل أو يضبط قيمة لتحديد شفافية حدود الطابع. القيمة تتراوح بين 0.0 إلى 1.0. بشكل افتراضي القيمة هي 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | يحصل أو يضبط قيمة عرض حدود الطابع. بشكل افتراضي القيمة هي 1.0. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | الحصول على أو تعيين جودة ختم الصورة بالنسبة المئوية. القيم الصالحة هي 0..100%. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | يحصل أو يضبط الهامش الأيمن للطابع. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | يضبط أو يحصل على دوران محتوى الطابع وفق قيم [`Rotation`](../rotation/). ملاحظة. هذه الخاصية مخصصة لتعيين الزوايا التي هي مضاعفات 90 درجة (0، 90، 180، 270 درجة). لتعيين زاوية عشوائية استخدم الخاصية RotateAngle. إذا كانت الزاوية التي تم تعيينها بواسطة ArbitraryAngle ليست مضاعفًا للـ 90 فإن خاصية Rotate تُعيد Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | يحصل أو يضبط زاوية دوران الطابع بالدرجات. تسمح هذه الخاصية بتعيين زاوية دوران عشوائية. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | يحصل أو يضبط الهامش العلوي للطابع. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | يحصل أو يضبط محاذاة الطابع العمودية على الصفحة. |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | الحصول على أو تعيين عرض الصورة. ضبط هذه الخاصية يسمح بتكبير الصورة أفقيًا. |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | الحصول على وتعيين إحداثي الختم الأفقي، بدءًا من اليسار. |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | الحصول على وتعيين إحداثي الختم العمودي، بدءًا من الأسفل. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | عامل التكبير للطابع. يسمح بتكبير الطابع. يرجى ملاحظة أن زوج الخصائص ZoomX و ZoomY يسمح بتعيين عامل التكبير لكل محور على حدة. تغيير هذه الخاصية يغير كل من خصائص ZoomX و ZoomY. إذا كانت ZoomX و ZoomY مختلفة فإن خاصية Zoom تُعيد قيمة ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | عامل التكبير الأفقي للطابع. يسمح بتكبير الطابع أفقيًا. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | عامل التكبير العمودي للطابع. يسمح بتكبير الطابع عموديًا. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | يعيد معرف الطابع. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | إضافة ختم رسومي إلى الصفحة. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | يضبط معرف الطابع. |

### انظر أيضًا

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


