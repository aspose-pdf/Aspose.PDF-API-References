---
title: "ImageDevice"
linktitle: "ImageDevice"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة مجردة لأجهزة الصورة."
type: docs
weight: 110
url: /ar/java/com.aspose.pdf.devices/imagedevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice

```
public abstract class ImageDevice extends PageDevice
```

فئة مجردة لأجهزة الصورة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ImageDevice](#ImageDevice--) | مُهيئ تجريدي للوراثيات {@code ImageDevice}، يحدد الدقة إلى 150x150. |
| [ImageDevice](#ImageDevice-int-int-) | ينشئ مثيلًا جديدًا للفئة {@code JpegDevice} بالأبعاد المقدمة للصورة والدقة الافتراضية (=150). |
| [ImageDevice](#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-) | مُهيئ تجريدي للوراثيات {@code ImageDevice}، يحدد الدقة إلى 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-) | مُهيئ تجريدي للوراثيات {@code ImageDevice}، يحدد الدقة إلى 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | مُهيئ تجريدي للوراثيات {@code ImageDevice}، يحدد الدقة إلى 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.devices.Resolution-) | مُهيئ تجريدي للوراثيات {@code ImageDevice}، يحدد الدقة إلى 150x150. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBitmap](#getBitmap-com.aspose.pdf.Page-) | يحوّل الصفحة إلى {@link java.awt.image.BufferedImage}. |
| [getCoordinateType](#getCoordinateType--) | يحصل على نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [getCropRectangle](#getCropRectangle--) | احصل على المستطيل الذي يحدد المنطقة التي ستحول إلى صورة. القيمة الافتراضية هي null، وفي هذه الحالة يتم تحويل الصفحة بالكامل إلى صورة. |
| [getFormPresentationMode](#getFormPresentationMode--) | يحصل على وضع عرض النموذج. |
| [getHeight](#getHeight--) | يحصل على ارتفاع إخراج الصورة. |
| [getRenderingOptions](#getRenderingOptions--) | يحصل على خيارات العرض. |
| [getResolution](#getResolution--) | يحصل على دقة الصورة. |
| [getWidth](#getWidth--) | يحصل على عرض إخراج الصورة. |
| [isShadingPerformanceHigh](#isShadingPerformanceHigh--) | هل أداء عمليات التظليل عالي. القيمة الافتراضية هي true. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | يضبط نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | حدد المستطيل الذي يحدد المنطقة التي سيتم تحويلها إلى صورة. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | يضبط وضع عرض النموذج. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | يضبط خيارات العرض. |
| [setShadingPerformanceHigh](#setShadingPerformanceHigh-boolean-) | يضبط ما إذا كان أداء عمليات التظليل عاليًا أم لا. |

### ImageDevice {#ImageDevice--}
```
public ImageDevice()
```

مُهيئ تجريدي للوراثيات {@code ImageDevice}، يحدد الدقة إلى 150x150.

### ImageDevice {#ImageDevice-int-int-}
```
public ImageDevice(int width, int height)
```

ينشئ مثيلًا جديدًا للفئة {@code JpegDevice} بالأبعاد المقدمة للصورة والدقة الافتراضية (=150).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض |  | عرض إخراج الصورة. |
| الارتفاع |  | ارتفاع إخراج الصورة. |

### ImageDevice {#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-}
مُهيئ تجريدي للوراثيات {@code ImageDevice}، يحدد الدقة إلى 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-}
مُهيئ تجريدي للوراثيات {@code ImageDevice}، يحدد الدقة إلى 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
مُهيئ تجريدي للوراثيات {@code ImageDevice}، يحدد الدقة إلى 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.devices.Resolution-}
مُهيئ تجريدي للوراثيات {@code ImageDevice}، يحدد الدقة إلى 150x150.

### getBitmap {#getBitmap-com.aspose.pdf.Page-}
يحوّل الصفحة إلى {@link java.awt.image.BufferedImage}.

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

يحصل على نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي.

**Returns:**
عنصر PageCoordinateType @see PageCoordinateType

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

احصل على المستطيل الذي يحدد المنطقة التي ستحول إلى صورة. القيمة الافتراضية هي null، وفي هذه الحالة يتم تحويل الصفحة بالكامل إلى صورة.

**Returns:**
كائن Rectangle

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

يحصل على وضع عرض النموذج.

**Returns:**
عنصر FormPresentationMode @see FormPresentationMode

### getHeight {#getHeight--}
```
public int getHeight()
```

يحصل على ارتفاع إخراج الصورة.

**Returns:**
قيمة int

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

يحصل على خيارات العرض.

**Returns:**
عنصر RenderingOptions

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

يحصل على دقة الصورة.

**Returns:**
عنصر الدقة

### getWidth {#getWidth--}
```
public int getWidth()
```

يحصل على عرض إخراج الصورة.

**Returns:**
قيمة int

### isShadingPerformanceHigh {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```

هل أداء عمليات التظليل عالي. القيمة الافتراضية هي true.

**Returns:**
قيمة منطقية

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
يضبط نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
حدد المستطيل الذي يحدد المنطقة التي سيتم تحويلها إلى صورة.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

يضبط وضع عرض النموذج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر FormPresentationMode @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
يضبط خيارات العرض.

### setShadingPerformanceHigh {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```

يضبط ما إذا كان أداء عمليات التظليل عاليًا أم لا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
