---
title: "SvgLoadOptions"
linktitle: "SvgLoadOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خيارات تحميل/استيراد ملف SVG إلى مستند PDF."
type: docs
weight: 4700
url: /ar/java/com.aspose.pdf/svgloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.SvgLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.SvgLoadOptions

```
public final class SvgLoadOptions extends LoadOptions
```

يمثل خيارات تحميل/استيراد ملف SVG إلى مستند PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SvgLoadOptions](#SvgLoadOptions--) | ينشئ كائن {@code SvgLoadOptions}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getConversionEngine](#getConversionEngine--) | يسمح باختيار محرك التحويل الذي سيُستخدم أثناء التحويل. حاليًا المحرك الجديد في مرحلة B-testing، لذا يتم تعيين هذه القيمة افتراضيًا إلى ConversionEngines.LegacyEngine |
| [getPageInfo](#getPageInfo--) | يحصل على معلومات الصفحة التي يجب تطبيقها أثناء تحميل المستند. |
| [isAdjustPageSize](#isAdjustPageSize--) | ضبط حجم صفحة pdf ليتناسب مع حجم svg |
| [setAdjustPageSize](#setAdjustPageSize-boolean-) | ضبط حجم صفحة pdf ليتناسب مع حجم svg |
| [setConversionEngine](#setConversionEngine-int-) | يسمح باختيار محرك التحويل الذي سيُستخدم أثناء التحويل. حاليًا المحرك الجديد في مرحلة B-testing، لذا يتم تعيين هذه القيمة افتراضيًا إلى ConversionEngines.LegacyEngine |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | يضبط معلومات الصفحة التي يجب تطبيقها أثناء تحميل المستند. |

### SvgLoadOptions {#SvgLoadOptions--}
```
public SvgLoadOptions()
```

ينشئ كائن {@code SvgLoadOptions}.

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

يسمح باختيار محرك التحويل الذي سيُستخدم أثناء التحويل. حاليًا المحرك الجديد في مرحلة B-testing، لذا يتم تعيين هذه القيمة افتراضيًا إلى ConversionEngines.LegacyEngine

**Returns:**
عنصر ConversionEngines @see ConversionEngines

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

يحصل على معلومات الصفحة التي يجب تطبيقها أثناء تحميل المستند.

**Returns:**
كائن PageInfo

### isAdjustPageSize {#isAdjustPageSize--}
```
public boolean isAdjustPageSize()
```

ضبط حجم صفحة pdf ليتناسب مع حجم svg

**Returns:**
قيمة منطقية

### setAdjustPageSize {#setAdjustPageSize-boolean-}
```
public void setAdjustPageSize(boolean value)
```

ضبط حجم صفحة pdf ليتناسب مع حجم svg

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

يسمح باختيار محرك التحويل الذي سيُستخدم أثناء التحويل. حاليًا المحرك الجديد في مرحلة B-testing، لذا يتم تعيين هذه القيمة افتراضيًا إلى ConversionEngines.LegacyEngine

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| conversionEngine |  | عنصر ConversionEngines @see ConversionEngines |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
يضبط معلومات الصفحة التي يجب تطبيقها أثناء تحميل المستند.
