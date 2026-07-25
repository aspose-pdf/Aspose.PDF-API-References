---
title: "ImagesDifference"
linktitle: "ImagesDifference"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة نتيجة مقارنة صفحتين PDF."
type: docs
weight: 20
url: /ar/java/com.aspose.pdf.comparison.graphicalcomparison/imagesdifference/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.ImagesDifference

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class ImagesDifference extends Object implements com.aspose.ms.System.IDisposable
```

يمثل فئة نتيجة مقارنة صفحتين PDF.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [differenceToImage](#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-) | يقوم بتحويل مصفوفة الفرق إلى صورة bitmap باستخدام الألوان المحددة. |
| [dispose](#dispose--) | ينفّذ أي عمليات تنظيف ضرورية قبل تدمير الكائن. |
| [getDestinationImage](#getDestinationImage--) | يعيد صورة bitmap جديدة تمثل الصورة الوجهة عن طريق تطبيق مصفوفة الفرق على الصورة المصدر. |
| [getDifference](#getDifference--) | يحصل على مصفوفة الفرق. هذه المصفوفة مشابهة لمصفوفة بيانات الصورة الأصلية التي تم الحصول عليها نتيجةً لطريقة LockBits. |
| [getHeight](#getHeight--) | ارتفاع الفرق. |
| [getSourceImage](#getSourceImage--) | يحصل على صورة الصفحة الأولى التي تم مقارنتها. الصورة ذات تنسيق بكسل 24bpp. |
| [getStride](#getStride--) | خطوة (stride) بيانات صورة الفرق. |

### differenceToImage {#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-}
يقوم بتحويل مصفوفة الفرق إلى صورة bitmap باستخدام الألوان المحددة.

### dispose {#dispose--}
```
public final void dispose()
```

ينفّذ أي عمليات تنظيف ضرورية قبل تدمير الكائن.

### getDestinationImage {#getDestinationImage--}
```
public final BufferedImage getDestinationImage()
```

يعيد صورة bitmap جديدة تمثل الصورة الوجهة عن طريق تطبيق مصفوفة الفرق على الصورة المصدر.

**Returns:**
صورة الوجهة.

### getDifference {#getDifference--}
```
public final int[] getDifference()
```

يحصل على مصفوفة الفرق. هذه المصفوفة مشابهة لمصفوفة بيانات الصورة الأصلية التي تم الحصول عليها نتيجةً لطريقة LockBits.

**Returns:**
int[] array

### getHeight {#getHeight--}
```
public final int getHeight()
```

ارتفاع الفرق.

**Returns:**
قيمة int

### getSourceImage {#getSourceImage--}
```
public final BufferedImage getSourceImage()
```

يحصل على صورة الصفحة الأولى التي تم مقارنتها. الصورة ذات تنسيق بكسل 24bpp.

**Returns:**
BufferedImage instance

### getStride {#getStride--}
```
public final int getStride()
```

خطوة (stride) بيانات صورة الفرق.

**Returns:**
قيمة int
