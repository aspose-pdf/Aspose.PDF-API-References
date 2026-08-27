---
title: "XpsSaveOptions"
linktitle: "XpsSaveOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "خيارات الحفظ للتصدير إلى تنسيق Xps"
type: docs
weight: 5770
url: /ar/java/com.aspose.pdf/xpssaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.XpsSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.XpsSaveOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public class XpsSaveOptions extends UnifiedSaveOptions implements IPipelineOptions
```

خيارات الحفظ للتصدير إلى تنسيق Xps

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [XpsSaveOptions](#XpsSaveOptions--) | منشئ |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBatchSize](#getBatchSize--) | يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة. |
| [getDefaultFont](#getDefaultFont--) | يحصل/يضبط اسم الخط الافتراضي. يُستخدم إذا لم يتم العثور على اسم الخط المضمّن في النظام. |
| [getSaveTransparentTexts](#getSaveTransparentTexts--) | يشير إلى ما إذا كان يجب الحفاظ على النص الشفاف (المعروف بـ OCR). |
| [getUseEmbeddedTrueTypeFonts](#getUseEmbeddedTrueTypeFonts--) | يحصل/يضبط العلامة لاستخدام خطوط TrueType المضمّنة. تجنّب استخدام خطوط TrueType المضمّنة يمكن أن يقلل من زمن التحويل. |
| [isUseNewImagingEngine](#isUseNewImagingEngine--) | يحصل أو يضبط خيار UseNewImagingEngine. |
| [setBatchSize](#setBatchSize-int-) | يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة. |
| [setDefaultFont](#setDefaultFont-java.lang.String-) | يحصل/يضبط اسم الخط الافتراضي. يُستخدم إذا لم يتم العثور على اسم الخط المضمّن في النظام. |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | يشير إلى ما إذا كان يجب الحفاظ على النص الشفاف (المعروف بـ OCR). |
| [setUseEmbeddedTrueTypeFonts](#setUseEmbeddedTrueTypeFonts-boolean-) | يحصل/يضبط العلامة لاستخدام خطوط TrueType المضمّنة. تجنّب استخدام خطوط TrueType المضمّنة يمكن أن يقلل من زمن التحويل. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | يحصل أو يضبط خيار UseNewImagingEngine. |

### XpsSaveOptions {#XpsSaveOptions--}
```
public XpsSaveOptions()
```

منشئ

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة.

**Returns:**
قيمة int

### getDefaultFont {#getDefaultFont--}
```
public final String getDefaultFont()
```

يحصل/يضبط اسم الخط الافتراضي. يُستخدم إذا لم يتم العثور على اسم الخط المضمّن في النظام.

**Returns:**
قيمة سلسلة

### getSaveTransparentTexts {#getSaveTransparentTexts--}
```
public final boolean getSaveTransparentTexts()
```

يشير إلى ما إذا كان يجب الحفاظ على النص الشفاف (المعروف بـ OCR).

**Returns:**
قيمة منطقية

### getUseEmbeddedTrueTypeFonts {#getUseEmbeddedTrueTypeFonts--}
```
public final boolean getUseEmbeddedTrueTypeFonts()
```

يحصل/يضبط العلامة لاستخدام خطوط TrueType المضمّنة. تجنّب استخدام خطوط TrueType المضمّنة يمكن أن يقلل من زمن التحويل.

**Returns:**
قيمة منطقية

### isUseNewImagingEngine {#isUseNewImagingEngine--}
```
@Deprecated public final boolean isUseNewImagingEngine()
```

يحصل أو يضبط خيار UseNewImagingEngine.

**Returns:**
قيمة منطقية @deprecated UseNewImagingEngine تم إهمالها

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setDefaultFont {#setDefaultFont-java.lang.String-}
يحصل/يضبط اسم الخط الافتراضي. يُستخدم إذا لم يتم العثور على اسم الخط المضمّن في النظام.

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public final void setSaveTransparentTexts(boolean value)
```

يشير إلى ما إذا كان يجب الحفاظ على النص الشفاف (المعروف بـ OCR).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setUseEmbeddedTrueTypeFonts {#setUseEmbeddedTrueTypeFonts-boolean-}
```
public final void setUseEmbeddedTrueTypeFonts(boolean value)
```

يحصل/يضبط العلامة لاستخدام خطوط TrueType المضمّنة. تجنّب استخدام خطوط TrueType المضمّنة يمكن أن يقلل من زمن التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public final void setUseNewImagingEngine(boolean value)
```

يحصل أو يضبط خيار UseNewImagingEngine.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية @deprecated UseNewImagingEngine تم إهمالها |
