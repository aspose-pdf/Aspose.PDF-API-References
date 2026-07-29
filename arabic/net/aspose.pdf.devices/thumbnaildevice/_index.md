---
title: "الفئة ThumbnailDevice"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Devices.ThumbnailDevice. تمثل جهاز صورة يحفظ صفحات مستند pdf كصورة مصغرة Thumbnail."
type: docs
weight: 3810
url: /ar/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice class

يمثل جهاز صورة يحفظ صفحات مستند pdf كصورة مصغرة Thumbnail.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | يُنشئ مثيلاً جديدًا لفئة `ThumbnailDevice` بالحجم الافتراضي لصورة المصغرة (200×200 بكسل). |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | يُنشئ مثيلاً جديدًا لفئة `ThumbnailDevice`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | يحصل أو يعيّن نوع إحداثيات الصفحة (صناديق Media/Crop). تُستخدم قيمة CropBox كإعداد افتراضي. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | يحصل أو يعيّن وضع عرض النموذج. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | يحصل على ارتفاع مخرجات الصورة. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | يحصل أو يعيّن خيارات العرض. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | يحصل على دقة الصورة. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | يحصل على عرض مخرجات الصورة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | يحوّل الصفحة إلى Bitmap. |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | يحوِّل الصفحة إلى صورة مصغرة بصيغة png ويحفظها في تدفق الإخراج. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | ينفّذ بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

### انظر أيضًا

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


