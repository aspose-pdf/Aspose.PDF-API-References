---
title: Class XImage
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.XImage. فئة تمثل كائن الصورة X
type: docs
weight: 11350
url: /ar/net/aspose.pdf/ximage/
---
## XImage class

فئة تمثل كائن الصورة X.

```csharp
public sealed class XImage
```

## Properties

| Name | Description |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | إذا كانت الصورة تحتوي على شفافية، فإنها تعيد true؛ وإلا، false. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | يحصل على نوع فلتر الصورة. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | يحصل على النسخة الرمادية من الصورة. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | يحصل على ارتفاع الصورة. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | يحصل على علامة تشير إلى ما إذا كانت الصورة يجب أن تُعتبر كقناع صورة (انظر 8.9.6، "الصور المقنعة"). إذا كانت هذه العلامة true، يجب أن تكون قيمة BitsPerComponent 1 ولا يجب تحديد Mask و ColorSpace؛ يجب أن تُرسم المناطق غير المقنعة باستخدام اللون الحالي غير المرسوم. القيمة الافتراضية: false. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | بيانات التعريف للصورة. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | يحصل أو يحدد اسم الصورة. يرجى ملاحظة أنه إذا قمت بتغيير اسم الصورة التي لها مراجع في محتويات الصفحة، قد يصبح المستند غير صحيح. يرجى استخدام طريقة XImage.Rename في هذه الحالة. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | يحصل على عرض الصورة. |

## Methods

| Name | Description |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | يضيف قناع استنسل إلى XImage. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | يعيد نوع لون الصورة. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | يعيد اسم الصورة في مجموعتها. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | يسترجع بيانات الصورة الخام من الصورة المصدر. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | يعيد true إذا كانت كلتا الصورتين تشير إلى نفس الكائن. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | يعيد تسمية الصورة ويستبدل جميع المراجع للصورة بالاسم الجديد |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | يحفظ بيانات الصورة في التدفق كصورة JPEG. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | يحفظ الصورة في التدفق بالتنسيق المطلوب. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | يحفظ بيانات الصورة في التدفق كصورة JPEG مع الدقة المحددة. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | يحفظ الصورة في التدفق بالتنسيق المطلوب مع الدقة المحددة. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | يعيد تدفق الصورة الأصلية. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)