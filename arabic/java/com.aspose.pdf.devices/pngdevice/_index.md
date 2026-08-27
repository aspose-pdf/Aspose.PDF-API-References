---
title: "PngDevice"
linktitle: "PngDevice"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل جهاز صورة يساعد على حفظ صفحات مستند PDF بصيغة png."
type: docs
weight: 160
url: /ar/java/com.aspose.pdf.devices/pngdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PngDevice

```
public final class PngDevice extends ImageDevice
```

يمثل جهاز صورة يساعد على حفظ صفحات مستند PDF بصيغة png.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PngDevice](#PngDevice--) | ينشئ مثيلاً جديداً من الفئة {@code PngDevice} باستخدام الدقة الافتراضية. |
| [PngDevice](#PngDevice-int-int-) | ينشئ مثيلاً جديداً من الفئة {@code PngDevice} بأبعاد الصورة المقدمة، الدقة الافتراضية (=150). |
| [PngDevice](#PngDevice-int-int-com.aspose.pdf.devices.Resolution-) | ينشئ مثيلاً جديداً من الفئة {@code PngDevice} باستخدام الدقة الافتراضية. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-) | ينشئ مثيلاً جديداً من الفئة {@code PngDevice} باستخدام الدقة الافتراضية. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | ينشئ مثيلاً جديداً من الفئة {@code PngDevice} باستخدام الدقة الافتراضية. |
| [PngDevice](#PngDevice-com.aspose.pdf.devices.Resolution-) | ينشئ مثيلاً جديداً من الفئة {@code PngDevice} باستخدام الدقة الافتراضية. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [isTransparentBackground](#isTransparentBackground--) | يحصل أو يعيّن ما إذا كانت الصورة ذات خلفية شفافة. |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | يحوّل الصفحة إلى png ويحفظها في تدفق الإخراج. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | يحوّل الصفحة إلى png ويحفظها في تدفق الإخراج. |
| [processToBufferedImage](#processToBufferedImage-com.aspose.pdf.Page-) | يقوم بتحويل الصفحة إلى BufferedImage. |
| [processToBufferedImageBinarized](#processToBufferedImageBinarized-com.aspose.pdf.Page-double-) | يقوم بتحويل الصفحة إلى BufferedImage مع Bradley binarization. |
| [setTransparentBackground](#setTransparentBackground-boolean-) | يحصل أو يعيّن ما إذا كانت الصورة ذات خلفية شفافة. |

### PngDevice {#PngDevice--}
```
public PngDevice()
```

ينشئ مثيلاً جديداً من الفئة {@code PngDevice} باستخدام الدقة الافتراضية.

### PngDevice {#PngDevice-int-int-}
```
public PngDevice(int width, int height)
```

ينشئ مثيلاً جديداً من الفئة {@code PngDevice} بأبعاد الصورة المقدمة، الدقة الافتراضية (=150).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض |  | عرض إخراج الصورة. |
| الارتفاع |  | ارتفاع إخراج الصورة. |

### PngDevice {#PngDevice-int-int-com.aspose.pdf.devices.Resolution-}
ينشئ مثيلاً جديداً من الفئة {@code PngDevice} باستخدام الدقة الافتراضية.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-}
ينشئ مثيلاً جديداً من الفئة {@code PngDevice} باستخدام الدقة الافتراضية.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
ينشئ مثيلاً جديداً من الفئة {@code PngDevice} باستخدام الدقة الافتراضية.

### PngDevice {#PngDevice-com.aspose.pdf.devices.Resolution-}
ينشئ مثيلاً جديداً من الفئة {@code PngDevice} باستخدام الدقة الافتراضية.

### isTransparentBackground {#isTransparentBackground--}
```
public final boolean isTransparentBackground()
```

يحصل أو يعيّن ما إذا كانت الصورة ذات خلفية شفافة.

**Returns:**
قيمة منطقية

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
يحوّل الصفحة إلى png ويحفظها في تدفق الإخراج.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
يحوّل الصفحة إلى png ويحفظها في تدفق الإخراج.

### processToBufferedImage {#processToBufferedImage-com.aspose.pdf.Page-}
يقوم بتحويل الصفحة إلى BufferedImage.

### processToBufferedImageBinarized {#processToBufferedImageBinarized-com.aspose.pdf.Page-double-}
يقوم بتحويل الصفحة إلى BufferedImage مع Bradley binarization.

### setTransparentBackground {#setTransparentBackground-boolean-}
```
public final void setTransparentBackground(boolean value)
```

يحصل أو يعيّن ما إذا كانت الصورة ذات خلفية شفافة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
