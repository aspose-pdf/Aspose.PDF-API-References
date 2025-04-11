---
title: Class ImageDevice
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Devices.ImageDevice. فئة مجردة لأجهزة الصور
type: docs
weight: 3610
url: /ar/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice class

فئة مجردة لأجهزة الصور.

```csharp
public abstract class ImageDevice : PageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | مُهيئ مجرد لوراثات `ImageDevice`، يحدد الدقة إلى 150x150. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | يقوم بتهيئة مثيل جديد من فئة [`JpegDevice`](../jpegdevice/) مع أبعاد الصورة المقدمة والدقة الافتراضية (=150). |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | مُهيئ مجرد لوراثات `ImageDevice`. دقة ملف الصورة الناتج، انظر فئة [`Resolution`](./resolution/). |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | يقوم بتهيئة مثيل جديد من فئة [`JpegDevice`](../jpegdevice/) مع أبعاد الصورة المقدمة والدقة الافتراضية (=150). |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | يقوم بتهيئة مثيل جديد من فئة [`JpegDevice`](../jpegdevice/) مع أبعاد الصورة المقدمة والدقة. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | يقوم بتهيئة مثيل جديد من فئة [`JpegDevice`](../jpegdevice/) مع أبعاد الصورة المقدمة والدقة. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | يحصل أو يحدد نوع إحداثيات الصفحة (صناديق الوسائط/القص). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | يحصل أو يحدد وضع تقديم النموذج. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | يحصل على ارتفاع مخرجات الصورة. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | يحصل أو يحدد خيارات العرض. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | يحصل على دقة الصورة. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | يحصل على عرض مخرجات الصورة. |

## Methods

| Name | Description |
| --- | --- |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | يقوم بإجراء بعض العمليات على الصفحة المعطاة، مثل تحويل الصفحة إلى صورة رسومية. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | يقوم بإجراء بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

### See Also

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)