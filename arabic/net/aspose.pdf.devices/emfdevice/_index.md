---
title: EmfDevice
second_title: Aspose.PDF لمرجع .NET API
description: يمثل جهاز صورة يساعد على حفظ صفحات مستند pdf في emf.
type: docs
weight: 1680
url: /ar/net/aspose.pdf.devices/emfdevice/
---
## EmfDevice class

يمثل جهاز صورة يساعد على حفظ صفحات مستند pdf في emf.

```csharp
public sealed class EmfDevice : ImageDevice
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [EmfDevice](emfdevice#constructor)() | يقوم بتهيئة مثيل جديد لملف[`EmfDevice`](../emfdevice) فئة ذات الدقة الافتراضية للصورة النقطية المكتوبة على emf. |
| [EmfDevice](emfdevice#constructor_2)(PageSize) | يقوم بتهيئة مثيل جديد لملف[`EmfDevice`](../emfdevice) فئة بحجم الصفحة المقدم ، والدقة الافتراضية للصورة النقطية المكتوبة على emf (= 150) |
| [EmfDevice](emfdevice#constructor_1)(Resolution) | يقوم بتهيئة مثيل جديد لملف[`EmfDevice`](../emfdevice) فئة .  دقة الصورة النقطية المكتوبة إلى emf ، راجع[`Resolution`](../resolution) فئة . |
| [EmfDevice](emfdevice#constructor_4)(int, int) | يقوم بتهيئة مثيل جديد لملف[`EmfDevice`](../emfdevice) فئة بأبعاد الصورة المقدمة ، ودقة الوضوح الافتراضية للصورة النقطية المكتوبة على emf (= 150) |
| [EmfDevice](emfdevice#constructor_3)(PageSize, Resolution) | يقوم بتهيئة مثيل جديد لملف[`JpegDevice`](../jpegdevice)فئة بحجم الصفحة المقدم ، ودقة الصورة النقطية المكتوبة على emf. |
| [EmfDevice](emfdevice#constructor_5)(int, int, Resolution) | يقوم بتهيئة مثيل جديد لملف[`JpegDevice`](../jpegdevice) فئة بأبعاد الصورة المقدمة ، ودقة الصورة النقطية المكتوبة على emf. |

## الخصائص

| اسم | وصف |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype) { get; set; } | الحصول على نوع إحداثيات الصفحة أو تعيينه (مربعات الوسائط / الاقتصاص). يتم استخدام قيمة كروبوكس افتراضيًا. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode) { get; set; } | الحصول على أو تعيين وضع العرض التقديمي . |
| [Height](../../aspose.pdf.devices/imagedevice/height) { get; } | الحصول على ارتفاع إخراج الصورة . |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions) { get; set; } | الحصول على خيارات التقديم أو تعيينها . |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution) { get; } | يحصل على دقة الصورة . |
| [Width](../../aspose.pdf.devices/imagedevice/width) { get; } | الحصول على عرض إخراج الصورة . |

## طُرق

| اسم | وصف |
| --- | --- |
| override [Process](../../aspose.pdf.devices/emfdevice/process#process)(Page, Stream) | يحول الصفحة إلى emf ويحفظها في تدفق الإخراج. |
| [Process](../../aspose.pdf.devices/pagedevice/process)(Page, string) | يقوم ببعض العمليات على الصفحة المحددة ويحفظ النتائج في الملف. |

### أنظر أيضا

* class [ImageDevice](../imagedevice)
* مساحة الاسم [Aspose.Pdf.Devices](../../aspose.pdf.devices)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
