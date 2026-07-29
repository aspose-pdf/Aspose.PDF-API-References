---
title: "الفئة PdfPageStamp"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.PdfPageStamp. تمثل الفئة طابعًا يستخدم صفحة PDF كطابع"
type: docs
weight: 8560
url: /ar/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp class

الفئة تمثل ختمًا يستخدم صفحة PDF كختم.

```csharp
public sealed class PdfPageStamp : Stamp
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | منشئ PdfPageStamp. |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | ينشئ طابع صفحة Pdf من الصفحة المحددة في المستند من الدفق. |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | ينشئ طابع صفحة Pdf من الصفحة المحددة في المستند داخل الملف المحدد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | يضبط أو يحصل على قيمة bool تشير إلى أن المحتوى تم وضعه كخلفية. إذا كانت القيمة true، يتم وضع محتوى الطابع في الأسفل. بشكل افتراضي، تكون القيمة false، ويتم وضع محتوى الطابع في الأعلى. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | يحصل أو يضبط الهامش السفلي للطابع. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | الارتفاع المطلوب للطابع على الصفحة. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | يحصل أو يضبط محاذاة الطابع الأفقية على الصفحة. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | يحصل أو يضبط الهامش الأيسر للطابع. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | يحصل أو يضبط قيمة لتحديد شفافية الطابع. القيمة تتراوح بين 0.0 إلى 1.0. بشكل افتراضي القيمة هي 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | يحصل أو يضبط قيمة لتحديد شفافية حدود الطابع. القيمة تتراوح بين 0.0 إلى 1.0. بشكل افتراضي القيمة هي 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | يحصل أو يضبط قيمة عرض حدود الطابع. بشكل افتراضي القيمة هي 1.0. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | يحصل أو يضبط الصفحة التي ستُستخدم كطابع. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | يحصل أو يضبط الهامش الأيمن للطابع. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | يضبط أو يحصل على دوران محتوى الطابع وفق قيم [`Rotation`](../rotation/). ملاحظة. هذه الخاصية مخصصة لتعيين الزوايا التي هي مضاعفات 90 درجة (0، 90، 180، 270 درجة). لتعيين زاوية عشوائية استخدم الخاصية RotateAngle. إذا كانت الزاوية التي تم تعيينها بواسطة ArbitraryAngle ليست مضاعفًا للـ 90 فإن خاصية Rotate تُعيد Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | يحصل أو يضبط زاوية دوران الطابع بالدرجات. تسمح هذه الخاصية بتعيين زاوية دوران عشوائية. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | يحصل أو يضبط الهامش العلوي للطابع. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | يحصل أو يضبط محاذاة الطابع العمودية على الصفحة. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | العرض المطلوب للطابع على الصفحة. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | إحداثي الطابع الأفقي، يبدأ من اليسار. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | إحداثي الطابع العمودي، يبدأ من الأسفل. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | عامل التكبير للطابع. يسمح بتكبير الطابع. يرجى ملاحظة أن زوج الخصائص ZoomX و ZoomY يسمح بتعيين عامل التكبير لكل محور على حدة. تغيير هذه الخاصية يغير كل من خصائص ZoomX و ZoomY. إذا كانت ZoomX و ZoomY مختلفة فإن خاصية Zoom تُعيد قيمة ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | عامل التكبير الأفقي للطابع. يسمح بتكبير الطابع أفقيًا. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | عامل التكبير العمودي للطابع. يسمح بتكبير الطابع عموديًا. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | يعيد معرف الطابع. |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | ضع الطابع على الصفحة المحددة. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | يضبط معرف الطابع. |

### انظر أيضًا

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


