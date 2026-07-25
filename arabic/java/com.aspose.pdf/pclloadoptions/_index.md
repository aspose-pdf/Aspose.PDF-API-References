---
title: "PclLoadOptions"
linktitle: "PclLoadOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خيارات لتحميل (استيراد) ملف PCL إلى مستند pdf."
type: docs
weight: 3530
url: /ar/java/com.aspose.pdf/pclloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PclLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PclLoadOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public final class PclLoadOptions extends LoadOptions implements IPipelineOptions
```

يمثل خيارات لتحميل (استيراد) ملف PCL إلى مستند pdf.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PclLoadOptions](#PclLoadOptions--) | ينشئ كائن {@code PclLoadOptions}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBatchSize](#getBatchSize--) | يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة. |
| [getConversionEngine](#getConversionEngine--) | يحدد محرك التحويل الذي سيُستخدم في التحويل |
| [getExceptions](#getExceptions--) | قائمة بأخطاء التحويل. |
| [isSupressErrors](#isSupressErrors--) | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا كان يجب قمع أخطاء تحويل PCL. |
| [setBatchSize](#setBatchSize-int-) | يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة. |
| [setConversionEngine](#setConversionEngine-int-) | يحدد محرك التحويل الذي سيُستخدم في التحويل |
| [setSupressErrors](#setSupressErrors-boolean-) | يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا كان يجب قمع أخطاء تحويل PCL. |

### PclLoadOptions {#PclLoadOptions--}
```
public PclLoadOptions()
```

ينشئ كائن {@code PclLoadOptions}.

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة.

**Returns:**
قيمة int

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

يحدد محرك التحويل الذي سيُستخدم في التحويل

**Returns:**
عنصر ConversionEngines @see ConversionEngines

### getExceptions {#getExceptions--}
```
public List < Exception > getExceptions()
```

قائمة بأخطاء التحويل.

**Returns:**
قائمة الاستثناءات

### isSupressErrors {#isSupressErrors--}
```
public boolean isSupressErrors()
```

يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا كان يجب قمع أخطاء تحويل PCL.

**Returns:**
قيمة منطقية

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

يحدد حجم الدفعة إذا كان التحويل المجمع قابلًا للتطبيق على زوج صيغ المصدر والوجهة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

يحدد محرك التحويل الذي سيُستخدم في التحويل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| conversionEngine |  | عنصر ConversionEngines @see ConversionEngines |

### setSupressErrors {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```

يحصل أو يعيّن قيمة منطقية تشير إلى ما إذا كان يجب قمع أخطاء تحويل PCL.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| supressErrors |  | قيمة منطقية |
