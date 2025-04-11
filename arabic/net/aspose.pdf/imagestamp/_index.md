---
title: Class ImageStamp
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.ImageStamp. تمثل ختمًا رسوميًا
type: docs
weight: 5930
url: /ar/net/aspose.pdf/imagestamp/
---
## ImageStamp class

تمثل ختمًا رسوميًا.

```csharp
public sealed class ImageStamp : Stamp
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageStamp](imagestamp/#constructor)(Stream) | يقوم بتهيئة مثيل جديد من فئة `ImageStamp`. |
| [ImageStamp](imagestamp/#constructor_1)(string) | ينشئ ختم صورة من الصورة في الملف المحدد. |

## Properties

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.pdf/imagestamp/alternativetext/) { get; set; } | يحصل أو يحدد النص البديل لختم الصورة. |
| [Background](../../aspose.pdf/stamp/background/) { get; set; } | يحدد أو يحصل على قيمة بوليانية تشير إلى أن المحتوى مختوم كخلفية. إذا كانت القيمة صحيحة، يتم وضع محتوى الختم في الأسفل. بشكل افتراضي، تكون القيمة خاطئة، يتم وضع محتوى الختم في الأعلى. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin/) { get; set; } | يحصل أو يحدد الهامش السفلي للختم. |
| override [Height](../../aspose.pdf/imagestamp/height/) { get; set; } | يحصل أو يحدد ارتفاع الصورة. يسمح تعيين هذه الصورة بتغيير حجم الصورة عموديًا. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment/) { get; set; } | يحصل أو يحدد المحاذاة الأفقية للختم على الصفحة. |
| [Image](../../aspose.pdf/imagestamp/image/) { get; } | يحصل على تدفق الصورة المستخدم للختم. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin/) { get; set; } | يحصل أو يحدد الهامش الأيسر للختم. |
| [Opacity](../../aspose.pdf/stamp/opacity/) { get; set; } | يحصل أو يحدد قيمة تشير إلى شفافية الختم. القيمة تتراوح من 0.0 إلى 1.0. بشكل افتراضي، تكون القيمة 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity/) { get; set; } | يحصل أو يحدد قيمة تشير إلى شفافية محيط الختم. القيمة تتراوح من 0.0 إلى 1.0. بشكل افتراضي، تكون القيمة 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth/) { get; set; } | يحصل أو يحدد قيمة عرض محيط الختم. بشكل افتراضي، تكون القيمة 1.0. |
| [Quality](../../aspose.pdf/imagestamp/quality/) { get; set; } | يحصل أو يحدد جودة ختم الصورة بالنسبة المئوية. القيم الصالحة هي 0..100%. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin/) { get; set; } | يحصل أو يحدد الهامش الأيمن للختم. |
| [Rotate](../../aspose.pdf/stamp/rotate/) { get; set; } | يحدد أو يحصل على دوران محتوى الختم وفقًا لقيم [`Rotation`](../rotation/). ملاحظة. هذه الخاصية مخصصة لتعيين الزوايا التي هي مضاعفات 90 درجة (0، 90، 180، 270 درجة). لتعيين زاوية عشوائية، استخدم خاصية RotateAngle. إذا كانت الزاوية المحددة بواسطة ArbitraryAngle ليست مضاعفًا لـ 90، فإن خاصية Rotate تعيد Rotation.None. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle/) { get; set; } | يحصل أو يحدد زاوية دوران الختم بالدرجات. تسمح هذه الخاصية بتعيين زاوية دوران عشوائية. |
| [TopMargin](../../aspose.pdf/stamp/topmargin/) { get; set; } | يحصل أو يحدد الهامش العلوي للختم. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment/) { get; set; } | يحصل أو يحدد المحاذاة الرأسية للختم على الصفحة. |
| override [Width](../../aspose.pdf/imagestamp/width/) { get; set; } | يحصل أو يحدد عرض الصورة. يسمح تعيين هذه الخاصية بتغيير حجم الصورة أفقيًا. |
| override [XIndent](../../aspose.pdf/imagestamp/xindent/) { get; set; } | يحصل ويحدد إحداثي الختم الأفقي، بدءًا من اليسار. |
| override [YIndent](../../aspose.pdf/imagestamp/yindent/) { get; set; } | يحصل ويحدد إحداثي الختم الرأسي، بدءًا من الأسفل. |
| [Zoom](../../aspose.pdf/stamp/zoom/) { get; set; } | عامل تكبير الختم. يسمح بتغيير حجم الختم. يرجى ملاحظة أن زوج الخصائص ZoomX و ZoomY يسمح بتعيين عامل التكبير لكل محور بشكل منفصل. يؤدي تعيين هذه الخاصية إلى تغيير كل من خصائص ZoomX و ZoomY. إذا كانت ZoomX و ZoomY مختلفتين، فإن خاصية Zoom تعيد قيمة ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx/) { get; set; } | عامل التكبير الأفقي للختم. يسمح بتغيير حجم الختم أفقيًا. |
| [ZoomY](../../aspose.pdf/stamp/zoomy/) { get; set; } | عامل التكبير الرأسي للختم. يسمح بتغيير حجم الختم عموديًا. |

## Methods

| Name | Description |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid/)() | يعيد معرف الختم. |
| override [Put](../../aspose.pdf/imagestamp/put/)(Page) | يضيف ختمًا رسوميًا على الصفحة. |
| [setStampId](../../aspose.pdf/stamp/setstampid/)(int) | يحدد معرف الختم. |

### See Also

* class [Stamp](../stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)