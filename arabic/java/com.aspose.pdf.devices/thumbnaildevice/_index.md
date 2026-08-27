---
title: "ThumbnailDevice"
linktitle: "ThumbnailDevice"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل جهاز صورة يحفظ صفحات مستند PDF كصورة مصغرة."
type: docs
weight: 200
url: /ar/java/com.aspose.pdf.devices/thumbnaildevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.ThumbnailDevice

```
public final class ThumbnailDevice extends ImageDevice
```

يمثل جهاز صورة يحفظ صفحات مستند PDF كصورة مصغرة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ThumbnailDevice](#ThumbnailDevice--) | ينشئ مثيلاً جديداً من الفئة {@link ThumbnailDevice} بالحجم الافتراضي لصورة المصغرة (200×200 بكسل). |
| [ThumbnailDevice](#ThumbnailDevice-int-int-) | ينشئ مثيلاً جديداً من الفئة {@link ThumbnailDevice}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [processInternal](#processInternal-com.aspose.pdf.Page-java.io.OutputStream-) | يحوّل الصفحة إلى صورة مصغرة بصيغة png ويحفظها في تدفق الإخراج. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | ينفّذ عملية ما على الصفحة المحددة، على سبيل المثال. |

### ThumbnailDevice {#ThumbnailDevice--}
```
public ThumbnailDevice()
```

ينشئ مثيلاً جديداً من الفئة {@link ThumbnailDevice} بالحجم الافتراضي لصورة المصغرة (200×200 بكسل).

### ThumbnailDevice {#ThumbnailDevice-int-int-}
```
public ThumbnailDevice(int width, int height)
```

ينشئ مثيلاً جديداً من الفئة {@link ThumbnailDevice}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض |  | عرض إخراج صورة المصغرة. |
| الارتفاع |  | ارتفاع إخراج صورة المصغرة. |

### processInternal {#processInternal-com.aspose.pdf.Page-java.io.OutputStream-}
يحوّل الصفحة إلى صورة مصغرة بصيغة png ويحفظها في تدفق الإخراج.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
ينفّذ عملية ما على الصفحة المحددة، على سبيل المثال.
