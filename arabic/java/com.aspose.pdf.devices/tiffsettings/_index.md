---
title: "TiffSettings"
linktitle: "TiffSettings"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تمثل هذه الفئة إعدادات استيراد PDF إلى TIFF."
type: docs
weight: 220
url: /ar/java/com.aspose.pdf.devices/tiffsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.TiffSettings

```
public final class TiffSettings extends Object
```

تمثل هذه الفئة إعدادات استيراد PDF إلى TIFF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TiffSettings](#TiffSettings--) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-boolean-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.ColorDepth-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}. |
| [TiffSettings](#TiffSettings-com.aspose.pdf.devices.Margins-) | يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBrightness](#getBrightness--) | احصل على حد القيمة لتحويل الألوان بين الأبيض والأسود. يمكن تطبيق هذا المعامل مع EncoderValue.CompressionCCITT4، EncoderValue.CompressionCCITT3، EncoderValue.CompressionRle أو ColorDepth.Format1bpp == 1 |
| [getCompression](#getCompression--) | <p> يحصل على نوع الضغط. </p> Value: نوع الضغط. <hr> <p> القيمة الافتراضية هي CompressionType.LZW </p> |
| [getCoordinateType](#getCoordinateType--) | يحصل على نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [getDepth](#getDepth--) | <p> يحصل على عمق اللون. </p> Value: عمق اللون. <hr> <p> القيمة الافتراضية هي ColorDepth.Default </p> |
| [getIndexedConversionType](#getIndexedConversionType--) | يحصل على IndexedConversionType. القيمة الافتراضية هي Simple. |
| [getMargins](#getMargins--) | يحصل على الهوامش. |
| [getShape](#getShape--) | <p> يحصل على نوع الشكل. </p> Value: نوع الشكل. <hr> <p> القيمة الافتراضية هي ShapeType.None </p> |
| [getSkipBlankPages](#getSkipBlankPages--) | <p> يحصل على قيمة تشير إلى ما إذا كان يجب تخطي الصفحات الفارغة. </p> Value: {@code true} إذا كان هناك حاجة لتخطي الصفحات الفارغة؛ وإلا {@code false}. <hr> <p> القيمة الافتراضية هي false </p> |
| [isUseAlternativeImageEngine](#isUseAlternativeImageEngine--) | يحصل على علم يحدد ما إذا كان محرك التصوير البديل يُستخدم أم لا. القيمة true تُستخدم افتراضيًا لنظام Linux. بالنسبة لنظام Windows القيمة الافتراضية هي false. |
| [setBrightness](#setBrightness-float-) | اضبط حد القيمة لتحويل الألوان بين الأبيض والأسود. يمكن تطبيق هذا المعامل مع EncoderValue.CompressionCCITT4، EncoderValue.CompressionCCITT3، EncoderValue.CompressionRle أو ColorDepth.Format1bpp == 1 |
| [setCompression](#setCompression-com.aspose.pdf.devices.CompressionType-) | <p> يضبط نوع الضغط. </p> Value: نوع الضغط. <hr> <p> القيمة الافتراضية هي CompressionType.LZW </p> |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | يضبط نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي. |
| [setDepth](#setDepth-com.aspose.pdf.devices.ColorDepth-) | <p> يحصل على عمق اللون. </p> Value: عمق اللون. <hr> <p> القيمة الافتراضية هي ColorDepth.Default </p> |
| [setIndexedConversionType](#setIndexedConversionType-int-) | يضبط IndexedConversionType. |
| [setShape](#setShape-com.aspose.pdf.devices.ShapeType-) | <p> يحدد نوع الشكل. </p> القيمة: نوع الشكل. <hr> <p> القيمة الافتراضية هي ShapeType.None </p> |
| [setSkipBlankPages](#setSkipBlankPages-boolean-) | <p> يحدد قيمة تشير إلى ما إذا كان يجب تخطي الصفحات الفارغة. </p> القيمة: {@code true} إذا كان هناك حاجة لتخطي الصفحات الفارغة؛ وإلا {@code false}. <hr> <p> القيمة الافتراضية هي false </p> |
| [setUseAlternativeImageEngine](#setUseAlternativeImageEngine-boolean-) | يضبط علامة تحدد ما إذا كان محرك التصوير البديل يُستخدم أم لا. |

### TiffSettings {#TiffSettings--}
```
public TiffSettings()
```

يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}.

### TiffSettings {#TiffSettings-boolean-}
```
public TiffSettings(boolean skipBlankPages)
```

يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| skipBlankPages |  | إذا تم ضبطه على {@code true} [تخطي الصفحات الفارغة]. |

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.ColorDepth-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.CompressionType-com.aspose.pdf.devices.ColorDepth-com.aspose.pdf.devices.Margins-boolean-com.aspose.pdf.devices.ShapeType-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}.

### TiffSettings {#TiffSettings-com.aspose.pdf.devices.Margins-}
يُنشئ مثيلاً جديدًا من الفئة {@code TiffSettings}.

### getBrightness {#getBrightness--}
```
public float getBrightness()
```

احصل على حد القيمة لتحويل الألوان بين الأبيض والأسود. يمكن تطبيق هذا المعامل مع EncoderValue.CompressionCCITT4، EncoderValue.CompressionCCITT3، EncoderValue.CompressionRle أو ColorDepth.Format1bpp == 1

**Returns:**
يجب أن تكون القيمة العائمة للسطوع في النطاق من 0 إلى 1. القيمة الافتراضية تساوي 0.33f

### getCompression {#getCompression--}
```
public CompressionType getCompression()
```

<p> يحصل على نوع الضغط. </p> Value: نوع الضغط. <hr> <p> القيمة الافتراضية هي CompressionType.LZW </p>

**Returns:**
عنصر CompressionType @see CompressionType

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

يحصل على نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي.

**Returns:**
قيمة PageCoordinateType @see PageCoordinateType

### getDepth {#getDepth--}
```
public ColorDepth getDepth()
```

<p> يحصل على عمق اللون. </p> Value: عمق اللون. <hr> <p> القيمة الافتراضية هي ColorDepth.Default </p>

**Returns:**
عنصر ColorDepth @see ColorDepth

### getIndexedConversionType {#getIndexedConversionType--}
```
public int getIndexedConversionType()
```

يحصل على IndexedConversionType. القيمة الافتراضية هي Simple.

**Returns:**
عنصر IndexedConversionType @see IndexedConversionType

### getMargins {#getMargins--}
```
public Margins getMargins()
```

يحصل على الهوامش.

**Returns:**
كائن Margins

### getShape {#getShape--}
```
public ShapeType getShape()
```

<p> يحصل على نوع الشكل. </p> Value: نوع الشكل. <hr> <p> القيمة الافتراضية هي ShapeType.None </p>

**Returns:**
عنصر ShapeType @see ShapeType

### getSkipBlankPages {#getSkipBlankPages--}
```
public boolean getSkipBlankPages()
```

<p> يحصل على قيمة تشير إلى ما إذا كان يجب تخطي الصفحات الفارغة. </p> Value: {@code true} إذا كان هناك حاجة لتخطي الصفحات الفارغة؛ وإلا {@code false}. <hr> <p> القيمة الافتراضية هي false </p>

**Returns:**
قيمة منطقية

### isUseAlternativeImageEngine {#isUseAlternativeImageEngine--}
```
public boolean isUseAlternativeImageEngine()
```

يحصل على علم يحدد ما إذا كان محرك التصوير البديل يُستخدم أم لا. القيمة true تُستخدم افتراضيًا لنظام Linux. بالنسبة لنظام Windows القيمة الافتراضية هي false.

**Returns:**
قيمة منطقية

### setBrightness {#setBrightness-float-}
```
public void setBrightness(float value)
```

اضبط حد القيمة لتحويل الألوان بين الأبيض والأسود. يمكن تطبيق هذا المعامل مع EncoderValue.CompressionCCITT4، EncoderValue.CompressionCCITT3، EncoderValue.CompressionRle أو ColorDepth.Format1bpp == 1

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | : يجب أن تكون قيمة السطوع في النطاق من 0 إلى 1. القيمة الافتراضية تساوي 0.33f |

### setCompression {#setCompression-com.aspose.pdf.devices.CompressionType-}
<p> يضبط نوع الضغط. </p> Value: نوع الضغط. <hr> <p> القيمة الافتراضية هي CompressionType.LZW </p>

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
يضبط نوع إحداثيات الصفحة (صناديق Media/Crop). يتم استخدام قيمة CropBox بشكل افتراضي.

### setDepth {#setDepth-com.aspose.pdf.devices.ColorDepth-}
<p> يحصل على عمق اللون. </p> Value: عمق اللون. <hr> <p> القيمة الافتراضية هي ColorDepth.Default </p>

### setIndexedConversionType {#setIndexedConversionType-int-}
```
public void setIndexedConversionType(int value)
```

يضبط IndexedConversionType.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر IndexedConversionType @see IndexedConversionType |

### setShape {#setShape-com.aspose.pdf.devices.ShapeType-}
<p> يحدد نوع الشكل. </p> القيمة: نوع الشكل. <hr> <p> القيمة الافتراضية هي ShapeType.None </p>

### setSkipBlankPages {#setSkipBlankPages-boolean-}
```
public void setSkipBlankPages(boolean value)
```

<p> يحدد قيمة تشير إلى ما إذا كان يجب تخطي الصفحات الفارغة. </p> القيمة: {@code true} إذا كان هناك حاجة لتخطي الصفحات الفارغة؛ وإلا {@code false}. <hr> <p> القيمة الافتراضية هي false </p>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setUseAlternativeImageEngine {#setUseAlternativeImageEngine-boolean-}
```
public void setUseAlternativeImageEngine(boolean useAlternativeImageEngine)
```

يضبط علامة تحدد ما إذا كان محرك التصوير البديل يُستخدم أم لا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| useAlternativeImageEngine |  | قيمة منطقية |
