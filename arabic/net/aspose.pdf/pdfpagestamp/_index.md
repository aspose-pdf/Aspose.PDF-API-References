---
title: PdfPageStamp
second_title: Aspose.PDF لمرجع .NET API
description: تمثل الفئة طابعًا يستخدم صفحة PDF كختم.
type: docs
weight: 6070
url: /ar/net/aspose.pdf/pdfpagestamp/
---
## PdfPageStamp class

تمثل الفئة طابعًا يستخدم صفحة PDF كختم.

```csharp
public sealed class PdfPageStamp : Stamp
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfPageStamp](pdfpagestamp#constructor)(Page) | منشئ PdfPageStamp. |
| [PdfPageStamp](pdfpagestamp#constructor_1)(Stream, int) | ينشئ طابع صفحة Pdf من صفحة محددة في المستند من الدفق. |
| [PdfPageStamp](pdfpagestamp#constructor_2)(string, int) | إنشاء طابع صفحة PDF من صفحة محددة من المستند في ملف محدد. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Background](../../aspose.pdf/stamp/background) { get; set; } | تعيين أو الحصول على قيمة منطقية تشير إلى أن المحتوى مختوم كخلفية. إذا كانت القيمة صحيحة ، يتم وضع محتوى الختم في الأسفل. بالقيمة غير صحيحة ، يتم وضع محتوى الختم في الأعلى. |
| [BottomMargin](../../aspose.pdf/stamp/bottommargin) { get; set; } | الحصول على الهامش السفلي للطوابع أو تعيينه. |
| virtual [Height](../../aspose.pdf/stamp/height) { get; set; } | الارتفاع المطلوب للختم على الصفحة. |
| [HorizontalAlignment](../../aspose.pdf/stamp/horizontalalignment) { get; set; } | الحصول على أو تعيين المحاذاة الأفقية للطابع على الصفحة. |
| [LeftMargin](../../aspose.pdf/stamp/leftmargin) { get; set; } | الحصول على الهامش الأيسر للطوابع أو تعيينه. |
| [Opacity](../../aspose.pdf/stamp/opacity) { get; set; } | الحصول على أو تعيين قيمة للإشارة إلى عتامة الختم. القيمة من 0.0 إلى 1.0. القيمة الافتراضية هي 1.0. |
| [OutlineOpacity](../../aspose.pdf/stamp/outlineopacity) { get; set; } | الحصول على أو تعيين قيمة للإشارة إلى تعتيم مخطط الختم. القيمة من 0.0 إلى 1.0. القيمة الافتراضية هي 1.0. |
| [OutlineWidth](../../aspose.pdf/stamp/outlinewidth) { get; set; } | الحصول على قيمة عرض المخطط التفصيلي للطابع أو تعيينها. القيمة الافتراضية هي 1.0. |
| [PdfPage](../../aspose.pdf/pdfpagestamp/pdfpage) { get; set; } | الحصول على أو تعيين الصفحة التي سيتم استخدامها كختم. |
| [RightMargin](../../aspose.pdf/stamp/rightmargin) { get; set; } | الحصول على الهامش الأيمن للطوابع أو تعيينه. |
| [Rotate](../../aspose.pdf/stamp/rotate) { get; set; } | يضبط أو يحصل على تدوير محتوى الطوابع وفقًا[`Rotation`](../rotation) القيم . ملاحظة. هذه الخاصية مخصصة للزوايا المحددة التي تكون مضاعفات 90 درجة (0 ، 90 ، 180 ، 270 درجة) . لتعيين زاوية عشوائية ، استخدم خاصية RotateAngle. إذا كانت الزاوية التي تم تعيينها بواسطة ArbitraryAngle ليست من مضاعفات 90 ، فإن خاصية Rotate ترجع Rotation. |
| [RotateAngle](../../aspose.pdf/stamp/rotateangle) { get; set; } | الحصول على أو تعيين زاوية تدوير الختم بالدرجات . تسمح هذه الخاصية بتعيين زاوية تدوير عشوائية. |
| [TopMargin](../../aspose.pdf/stamp/topmargin) { get; set; } | الحصول على الهامش العلوي للطوابع أو تعيينه. |
| [VerticalAlignment](../../aspose.pdf/stamp/verticalalignment) { get; set; } | الحصول على أو تعيين المحاذاة الرأسية للطابع على الصفحة. |
| virtual [Width](../../aspose.pdf/stamp/width) { get; set; } | العرض المرغوب للختم على الصفحة. |
| [XIndent](../../aspose.pdf/stamp/xindent) { get; set; } | إحداثيات ختم أفقي ، تبدأ من اليسار. |
| [YIndent](../../aspose.pdf/stamp/yindent) { get; set; } | إحداثيات الختم العمودي ، بدءًا من الأسفل. |
| [Zoom](../../aspose.pdf/stamp/zoom) { get; set; } | عامل تكبير الختم. يسمح بقياس الختم . يرجى ملاحظة أن زوجًا من الخصائص ZoomX و ZoomY يسمحان بتعيين عامل التكبير لكل فأس على حدة. يغير إعداد هذه الخاصية كلاً من خصائص ZoomX و ZoomY. إذا كانت ZoomX و ZoomY مختلفة ، فإن خاصية Zoom تقوم بإرجاع قيمة ZoomX. |
| [ZoomX](../../aspose.pdf/stamp/zoomx) { get; set; } | عامل التكبير الأفقي للختم. يسمح بقياس الطوابع أفقيًا. |
| [ZoomY](../../aspose.pdf/stamp/zoomy) { get; set; } | عامل التكبير الرأسي للختم. يسمح بقياس الطوابع عموديًا. |

## طُرق

| اسم | وصف |
| --- | --- |
| [getStampId](../../aspose.pdf/stamp/getstampid)() | إرجاع معرف الطابع . |
| override [Put](../../aspose.pdf/pdfpagestamp/put)(Page) | ضع الختم على الصفحة المحددة . |
| [setStampId](../../aspose.pdf/stamp/setstampid)(int) | تعيين معرف الختم. |

### أنظر أيضا

* class [Stamp](../stamp)
* مساحة الاسم [Aspose.Pdf](../../aspose.pdf)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->