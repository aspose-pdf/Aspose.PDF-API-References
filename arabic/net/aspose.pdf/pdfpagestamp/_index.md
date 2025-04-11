---
title: Class PdfPageStamp
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.PdfPageStamp. تمثل الفئة ختمًا يستخدم صفحة PDF كختم
type: docs
weight: 8420
url: /ar/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp class

تمثل الفئة ختمًا يستخدم صفحة PDF كختم.

```csharp
public sealed class PdfPageStamp : Stamp
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfPageStamp](pdfpagestamp/#constructor)(Page) | مُنشئ PdfPageStamp. |
| [PdfPageStamp](pdfpagestamp/#constructor_1)(Stream, int) | ينشئ ختم صفحة PDF من الصفحة المحددة في المستند من الدفق. |
| [PdfPageStamp](pdfpagestamp/#constructor_2)(string, int) | ينشئ ختم صفحة PDF من الصفحة المحددة من المستند في الملف المحدد. |

## Properties

| Name | Description |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | يحدد أو يحصل على قيمة بوليانية تشير إلى أن المحتوى مختوم كخلفية. إذا كانت القيمة صحيحة، يتم وضع محتوى الختم في الأسفل. بشكل افتراضي، تكون القيمة خاطئة، يتم وضع محتوى الختم في الأعلى. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | يحصل أو يحدد الهامش السفلي للختم. |
| virtual [Height](../../aspose.pdf/stamp/height/) { get; set; } | الارتفاع المرغوب للختم على الصفحة. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | يحصل أو يحدد المحاذاة الأفقية للختم على الصفحة. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | يحصل أو يحدد الهامش الأيسر للختم. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | يحصل أو يحدد قيمة تشير إلى شفافية الختم. القيمة تتراوح من 0.0 إلى 1.0. بشكل افتراضي، تكون القيمة 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | يحصل أو يحدد قيمة تشير إلى شفافية محيط الختم. القيمة تتراوح من 0.0 إلى 1.0. بشكل افتراضي، تكون القيمة 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | يحصل أو يحدد قيمة عرض محيط الختم. بشكل افتراضي، تكون القيمة 1.0. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage/) { get; set; } | يحصل أو يحدد الصفحة التي ستستخدم كختم. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | يحصل أو يحدد الهامش الأيمن للختم. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | يحدد أو يحصل على دوران محتوى الختم وفقًا لقيم [`Rotation`](../rotation/). ملاحظة. هذه الخاصية مخصصة لتعيين الزوايا التي هي مضاعفات 90 درجة (0، 90، 180، 270 درجة). لتعيين زاوية عشوائية، استخدم خاصية RotateAngle. إذا كانت الزاوية المحددة بواسطة ArbitraryAngle ليست مضاعفًا لـ 90، فإن خاصية Rotate ترجع Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | يحصل أو يحدد زاوية دوران الختم بالدرجات. تتيح هذه الخاصية تعيين زاوية دوران عشوائية. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | يحصل أو يحدد الهامش العلوي للختم. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | يحصل أو يحدد المحاذاة الرأسية للختم على الصفحة. |
| virtual [Width](../../aspose.pdf/stamp/width/) { get; set; } | العرض المرغوب للختم على الصفحة. |
| virtual [XIndent](../../aspose.pdf/stamp/xindent/) { get; set; } | إحداثي الختم الأفقي، بدءًا من اليسار. |
| virtual [YIndent](../../aspose.pdf/stamp/yindent/) { get; set; } | إحداثي الختم العمودي، بدءًا من الأسفل. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | عامل تكبير الختم. يسمح بتكبير الختم. يرجى ملاحظة أن زوج الخصائص ZoomX و ZoomY يسمح بتعيين عامل التكبير لكل محور بشكل منفصل. تعيين هذه الخاصية يغير كل من خصائص ZoomX و ZoomY. إذا كانت ZoomX و ZoomY مختلفتين، فإن خاصية Zoom ترجع قيمة ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | عامل التكبير الأفقي للختم. يسمح بتكبير الختم أفقيًا. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | عامل التكبير العمودي للختم. يسمح بتكبير الختم عموديًا. |

## Methods

| Name | Description |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | ترجع معرف الختم. |
| override [Put](../../aspose.pdf/pdfpagestamp/put/)(Page) | يضع الختم على الصفحة المحددة. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | يحدد معرف الختم. |

### See Also

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)