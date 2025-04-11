---
title: Class ThumbnailDevice
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Devices.ThumbnailDevice. تمثل جهاز صورة يقوم بحفظ صفحات مستند PDF في صورة مصغرة
type: docs
weight: 3690
url: /ar/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice class

تمثل جهاز صورة يقوم بحفظ صفحات مستند PDF في صورة مصغرة.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | يقوم بتهيئة مثيل جديد من فئة `ThumbnailDevice` بحجم افتراضي لصورة المصغرة (200x200 بكسل). |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | يقوم بتهيئة مثيل جديد من فئة `ThumbnailDevice`. |

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
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | يقوم بتحويل الصفحة إلى صورة مصغرة بصيغة PNG ويحفظها في تدفق المخرجات. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | يقوم بإجراء بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

### See Also

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)