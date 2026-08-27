---
title: "BmpDevice"
linktitle: "BmpDevice"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل جهاز صورة يساعد على حفظ صفحات مستند PDF كملفات BMP."
type: docs
weight: 10
url: /ar/java/com.aspose.pdf.devices/bmpdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.BmpDevice

```
public final class BmpDevice extends ImageDevice
```

يمثل جهاز صورة يساعد على حفظ صفحات مستند PDF كملفات BMP.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [BmpDevice](#BmpDevice--) | ينشئ مثيلاً جديداً من الفئة {@code BmpDevice} باستخدام الدقة الافتراضية. |
| [BmpDevice](#BmpDevice-int-int-) | ينشئ مثيلاً جديداً من الفئة {@code BmpDevice} بأبعاد الصورة المقدمة، الدقة الافتراضية (=150). |
| [BmpDevice](#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-) | ينشئ مثيلاً جديداً من الفئة {@code BmpDevice} باستخدام الدقة الافتراضية. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-) | ينشئ مثيلاً جديداً من الفئة {@code BmpDevice} باستخدام الدقة الافتراضية. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | ينشئ مثيلاً جديداً من الفئة {@code BmpDevice} باستخدام الدقة الافتراضية. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.devices.Resolution-) | ينشئ مثيلاً جديداً من الفئة {@code BmpDevice} باستخدام الدقة الافتراضية. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | يرسم الصفحة على الرسومات |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | يحوّل الصفحة إلى bmp ويحفظها في تدفق الإخراج. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | للاستخدام الداخلي فقط! |

### BmpDevice {#BmpDevice--}
```
public BmpDevice()
```

ينشئ مثيلاً جديداً من الفئة {@code BmpDevice} باستخدام الدقة الافتراضية.

### BmpDevice {#BmpDevice-int-int-}
```
public BmpDevice(int width, int height)
```

ينشئ مثيلاً جديداً من الفئة {@code BmpDevice} بأبعاد الصورة المقدمة، الدقة الافتراضية (=150).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض |  | عرض إخراج الصورة. |
| الارتفاع |  | ارتفاع إخراج الصورة. |

### BmpDevice {#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-}
ينشئ مثيلاً جديداً من الفئة {@code BmpDevice} باستخدام الدقة الافتراضية.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-}
ينشئ مثيلاً جديداً من الفئة {@code BmpDevice} باستخدام الدقة الافتراضية.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
ينشئ مثيلاً جديداً من الفئة {@code BmpDevice} باستخدام الدقة الافتراضية.

### BmpDevice {#BmpDevice-com.aspose.pdf.devices.Resolution-}
ينشئ مثيلاً جديداً من الفئة {@code BmpDevice} باستخدام الدقة الافتراضية.

### process {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
يرسم الصفحة على الرسومات

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
يحوّل الصفحة إلى bmp ويحفظها في تدفق الإخراج.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
للاستخدام الداخلي فقط!
