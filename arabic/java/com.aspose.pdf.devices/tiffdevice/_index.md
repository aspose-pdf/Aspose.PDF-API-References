---
title: "TiffDevice"
linktitle: "TiffDevice"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تساعد هذه الفئة على حفظ صفحات مستند PDF صفحةً بصفحة في صورة TIFF واحدة."
type: docs
weight: 210
url: /ar/java/com.aspose.pdf.devices/tiffdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.TiffDevice

```
public final class TiffDevice extends DocumentDevice
```

تساعد هذه الفئة على حفظ صفحات مستند PDF صفحةً بصفحة في صورة TIFF واحدة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TiffDevice](#TiffDevice--) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-int-int-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice}. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [binarizeBradley](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | قم بعملية التحويل الثنائي Bradley لتدفق الإدخال. |
| [getCropRectangle](#getCropRectangle--) | احصل على المستطيل الذي يحدد المنطقة التي سيتم تحويلها إلى صورة. القيمة الافتراضية هي null، وفي هذه الحالة يتم تحويل الصورة بالكامل إلى صفحة. |
| [getFormPresentationMode](#getFormPresentationMode--) | يحصل على وضع عرض النموذج. |
| [getHeight](#getHeight--) | يحصل على ارتفاع إخراج الصورة. |
| [getRenderingOptions](#getRenderingOptions--) | يحصل على خيارات العرض. |
| [getResolution](#getResolution--) | يحصل على دقة الصورة. |
| [getSettings](#getSettings--) | يحصل على الإعدادات لتعيين ملف PDF إلى صورة TIFF. |
| [getWidth](#getWidth--) | يحصل على عرض إخراج الصورة. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | يحوّل صفحات معينة من المستند إلى TIFF ويحفظها في تدفق الإخراج. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | يحوّل صفحات معينة من المستند إلى TIFF ويحفظها في تدفق الإخراج. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | ينفّذ عملية ما على الصفحة المحددة، على سبيل المثال. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | حدد المستطيل الذي يحدد المنطقة التي سيتم تحويلها إلى صورة. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | يحصل على وضع عرض النموذج. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | يضبط خيارات العرض. |

### TiffDevice {#TiffDevice--}
```
public TiffDevice()
```

يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-int-int-}
```
public TiffDevice(int width, int height)
```

يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض |  | عرض إخراج الصورة. |
| الارتفاع |  | ارتفاع إخراج الصورة. |

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffDevice} بالإعدادات الافتراضية.

### binarizeBradley {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
قم بعملية التحويل الثنائي Bradley لتدفق الإدخال.

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

احصل على المستطيل الذي يحدد المنطقة التي سيتم تحويلها إلى صورة. القيمة الافتراضية هي null، وفي هذه الحالة يتم تحويل الصورة بالكامل إلى صفحة.

**Returns:**
كائن Rectangle

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

يحصل على وضع عرض النموذج.

**Returns:**
قيمة FormPresentationMode @see FormPresentationMode

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
خيارات العرض.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

يحصل على دقة الصورة.

**Returns:**
عنصر الدقة

### getSettings {#getSettings--}
```
public TiffSettings getSettings()
```

يحصل على الإعدادات لتعيين ملف PDF إلى صورة TIFF.

**Returns:**
عنصر TiffSettings

### getWidth {#getWidth--}
```
public int getWidth()
```

يحصل على عرض إخراج الصورة.

**Returns:**
قيمة int

### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
يحوّل صفحات معينة من المستند إلى TIFF ويحفظها في تدفق الإخراج.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
يحوّل صفحات معينة من المستند إلى TIFF ويحفظها في تدفق الإخراج.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
ينفّذ عملية ما على الصفحة المحددة، على سبيل المثال.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
حدد المستطيل الذي يحدد المنطقة التي سيتم تحويلها إلى صورة.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

يحصل على وضع عرض النموذج.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
يضبط خيارات العرض.
