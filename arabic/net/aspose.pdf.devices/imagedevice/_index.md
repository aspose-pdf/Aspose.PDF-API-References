---
title: "الفئة ImageDevice"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Devices.ImageDevice. فئة تجريدية لأجهزة الصور"
type: docs
weight: 3730
url: /ar/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice class

فئة مجردة لأجهزة الصورة.

```csharp
public abstract class ImageDevice : PageDevice
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | مُهيئ تجريدي لسلالات `ImageDevice`، يحدد الدقة إلى 150×150. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | ينشئ مثيلاً جديداً للفئة [`JpegDevice`](../jpegdevice/) بالأبعاد الصورة المقدمة والدقة الافتراضية (=150). |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | مُهيئ تجريدي لسلالات `ImageDevice`. الدقة لملف الصورة الناتج، راجع فئة [`Resolution`](./resolution/). |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | ينشئ مثيلاً جديداً للفئة [`JpegDevice`](../jpegdevice/) بالأبعاد الصورة المقدمة والدقة الافتراضية (=150). |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | ينشئ مثيلاً جديداً للفئة [`JpegDevice`](../jpegdevice/) بالأبعاد الصورة المقدمة والدقة. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | ينشئ مثيلاً جديداً للفئة [`JpegDevice`](../jpegdevice/) بالأبعاد الصورة المقدمة والدقة. |

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
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | يقوم بأداء بعض العمليات على الصفحة المحددة، مثل تحويل الصفحة إلى صورة رسومية. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | ينفّذ بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

### انظر أيضًا

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


