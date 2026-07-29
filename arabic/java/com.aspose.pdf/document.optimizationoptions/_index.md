---
title: "Document.OptimizationOptions"
linktitle: "Document.OptimizationOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة التي تصف خوارزمية تحسين المستند. يمكن استخدام نسخة من هذه الفئة كمعامل لطريقة OptimizeResources(). @deprecated هذه الفئة قديمة. يرجى."
type: docs
weight: 1110
url: /ar/java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions com.aspose.pdf.Document.OptimizationOptions, com.aspose.pdf.optimization.OptimizationOptions, com.aspose.pdf.Document.OptimizationOptions

```
@Deprecated public static class Document.OptimizationOptions extends OptimizationOptions
```

فئة تصف خوارزمية تحسين المستند. يمكن استخدام نسخة من هذه الفئة كمعامل لطريقة OptimizeResources(). @deprecated هذه الفئة مهجورة. يرجى استخدام com.aspose.pdf.optimization.OptimizationOptions بدلاً من ذلك.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) | مهمل. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [all](#all--) | ينشئ استراتيجية تحسين مع تفعيل جميع الخيارات. |
| [getMaximumImageDimension](#getMaximumImageDimension--) | يحدد الحد الأقصى لأبعاد الصورة. إذا كان عرض أو ارتفاع الصورة الحالية أكبر من هذه القيمة - سيتم تقليل حجم الصورة بشكل متناسب. |
| [getResolution](#getResolution--) | يحدد قيمة الـ dpi الجديدة للصورة عند استخدام علامة CompressIamges. |
| [setMaximumImageDimension](#setMaximumImageDimension-int-) | يحدد الحد الأقصى لأبعاد الصورة. إذا كان عرض أو ارتفاع الصورة الحالية أكبر من هذه القيمة - سيتم تقليل حجم الصورة بشكل متناسب. |
| [setResolution](#setResolution-int-) | يحدد قيمة الـ dpi الجديدة للصورة عند استخدام علامة CompressIamges. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```

مهمل.

### all {#all--}
```
public static Document.OptimizationOptions all()
```

ينشئ استراتيجية تحسين مع تفعيل جميع الخيارات.

**Returns:**
كائن OptimizationOptions.

### getMaximumImageDimension {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```

يحدد الحد الأقصى لأبعاد الصورة. إذا كان عرض أو ارتفاع الصورة الحالية أكبر من هذه القيمة - سيتم تقليل حجم الصورة بشكل متناسب.

**Returns:**
الحد الأقصى لأبعاد الصورة

### getResolution {#getResolution--}
```
public int getResolution()
```

يحدد قيمة الـ dpi الجديدة للصورة عند استخدام علامة CompressIamges.

**Returns:**
دقة الصورة

### setMaximumImageDimension {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```

يحدد الحد الأقصى لأبعاد الصورة. إذا كان عرض أو ارتفاع الصورة الحالية أكبر من هذه القيمة - سيتم تقليل حجم الصورة بشكل متناسب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البُعد |  | الحد الأقصى لأبعاد الصورة |

### setResolution {#setResolution-int-}
```
public void setResolution(int dpi)
```

يحدد قيمة الـ dpi الجديدة للصورة عند استخدام علامة CompressIamges.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dpi |  | دقة الصورة |
