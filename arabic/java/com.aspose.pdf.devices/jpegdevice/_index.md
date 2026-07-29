---
title: "JpegDevice"
linktitle: "JpegDevice"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل جهاز صورة يساعد على حفظ صفحات مستند PDF بصيغة jpeg."
type: docs
weight: 130
url: /ar/java/com.aspose.pdf.devices/jpegdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.JpegDevice

```
public final class JpegDevice extends ImageDevice
```

يمثل جهاز صورة يساعد على حفظ صفحات مستند PDF بصيغة jpeg.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [JpegDevice](#JpegDevice--) | ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة. |
| [JpegDevice](#JpegDevice-int-) | ينشئ مثيلاً جديدًا للفئة {@code JpegDevice}. |
| [JpegDevice](#JpegDevice-int-int-) | ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بأبعاد الصورة المقدمة، ودقة افتراضية (=150) وأعلى جودة. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-) | ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-) | ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-) | ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-) | ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-) | ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-int-) | ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | يحوّل الصفحة إلى jpeg ويحفظها في تدفق الإخراج. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | يحوّل الصفحة إلى jpeg ويحفظها في تدفق الإخراج. |

### JpegDevice {#JpegDevice--}
```
public JpegDevice()
```

ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة.

### JpegDevice {#JpegDevice-int-}
```
public JpegDevice(int quality)
```

ينشئ مثيلاً جديدًا للفئة {@code JpegDevice}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الجودة |  | يحدد مستوى الضغط لصورة. نطاق القيم المفيدة للجودة هو من 0 إلى 100. كلما كان الرقم المحدد أقل، كلما كان الضغط أعلى وبالتالي تكون جودة الصورة أقل. الصفر سيعطيك أقل جودة للصورة و100 أعلى جودة. |

### JpegDevice {#JpegDevice-int-int-}
```
public JpegDevice(int width, int height)
```

ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بأبعاد الصورة المقدمة، ودقة افتراضية (=150) وأعلى جودة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض |  | عرض إخراج الصورة. |
| الارتفاع |  | ارتفاع إخراج الصورة. |

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-}
ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة.

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-}
ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-}
ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-}
ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-}
ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-int-}
ينشئ مثيلاً جديدًا للفئة {@code JpegDevice} بدقة افتراضية وأعلى جودة.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
يحوّل الصفحة إلى jpeg ويحفظها في تدفق الإخراج.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
يحوّل الصفحة إلى jpeg ويحفظها في تدفق الإخراج.
