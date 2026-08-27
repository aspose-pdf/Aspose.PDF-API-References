---
title: "الفئة DicomDevice"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.Devices.DicomDevice. تمثّل جهاز صورة يساعد على حفظ صفحات مستند PDF إلى تنسيق Dicom"
type: docs
weight: 3680
url: /ar/net/aspose.pdf.devices/dicomdevice/
---
## DicomDevice class

يمثل جهاز صورة يساعد على حفظ صفحات مستند pdf بصيغة Dicom.

```csharp
public sealed class DicomDevice : ImageDevice
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | ينشئ مثيلاً جديداً لفئة `DicomDevice` بالدقة الافتراضية. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | ينشئ مثيلاً جديداً لفئة `DicomDevice` بحجم الصفحة المقدم، وبالدقة الافتراضية (=150). |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | ينشئ مثيلاً جديداً لفئة `DicomDevice`. الدقة لملف الصورة الناتج، راجع فئة [`Resolution`](../resolution/). |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | ينشئ مثيلاً جديداً لفئة `DicomDevice` بأبعاد الصورة المقدمة، وبالدقة الافتراضية (=150). |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | ينشئ مثيلاً جديداً لفئة `DicomDevice` بحجم الصفحة المقدم والدقة. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | ينشئ مثيلاً جديداً لفئة `DicomDevice` بأبعاد الصورة المقدمة والدقة. |

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
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | يحوّل الصفحة إلى Dicom ويحفظها في تدفق الإخراج. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | ينفّذ بعض العمليات على الصفحة المعطاة ويحفظ النتائج في الملف. |

### انظر أيضًا

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


