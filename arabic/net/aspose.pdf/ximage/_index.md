---
title: "الفئة XImage"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.XImage. فئة تمثل كائن XObject للصور."
type: docs
weight: 11540
url: /ar/net/aspose.pdf/ximage/
---
## XImage class

الفئة تمثل كائن X-Object للصور.

```csharp
public sealed class XImage
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | إذا كانت الصورة تحتوي على شفافية فترجع true؛ وإلا false. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | يحصل على نوع مرشح الصورة. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | يحصل على نسخة رمادية اللون من الصورة. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | يحصل على ارتفاع الصورة. |
| [ImageMask](../../aspose.pdf/ximage/imagemask/) { get; } | يحصل على علم يحدد ما إذا كان يجب معالجة الصورة كقناع صورة (انظر 8.9.6، \"Masked Images\"). إذا كان هذا العلم true، يجب أن تكون قيمة BitsPerComponent مساوية لـ 1 ولا يجب تحديد Mask و ColorSpace؛ يجب رسم المناطق غير القنعية باستخدام اللون غير المتصل الحالي. القيمة الافتراضية: false. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | بيانات التعريف الخاصة بالصورة. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | يحصل أو يضبط اسم الصورة. يرجى ملاحظة أنه إذا قمت بتغيير اسم الصورة التي لديها مراجع في محتويات الصفحات، قد يصبح المستند غير صحيح. يرجى استخدام طريقة XImage.Rename في هذه الحالة. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | يحصل على عرض الصورة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddStencilMask](../../aspose.pdf/ximage/addstencilmask/)(Stream) | يضيف قناع ستنسل إلى XImage. |
| [GetAlternativeText](../../aspose.pdf/ximage/getalternativetext/)(Page) | يرجع قائمة من السلاسل النصية تحتوي على النص البديل لـ XImage. |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | يرجع نوع لون الصورة. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | يرجع اسم الصورة في مجموعتها. |
| [GetRawImageData](../../aspose.pdf/ximage/getrawimagedata/)() | يسترجع البيانات الخام للصورة من الصورة المصدر. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | يرجع true إذا كانت مراجع الصورتين تشير إلى نفس الكائن. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | يعيد تسمية الصورة ويستبدل جميع الإشارات إلى الصورة بالاسم الجديد |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | يحفظ بيانات الصورة في التدفق كصورة JPEG. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | يحفظ الصورة في التدفق بالتنسيق المطلوب. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | يحفظ بيانات الصورة في التدفق كصورة JPEG بدقة محددة. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | يحفظ الصورة في التدفق بالتنسيق المطلوب بدقة محددة. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | يعيد تدفق الصورة الأصلي. |
| [TrySetAlternativeText](../../aspose.pdf/ximage/trysetalternativetext/)(string, Page) | يضبط النص البديل لـ XImage على الصفحة. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### انظر أيضًا

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


