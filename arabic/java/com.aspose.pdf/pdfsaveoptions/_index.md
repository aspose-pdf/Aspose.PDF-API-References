---
title: "PdfSaveOptions"
linktitle: "PdfSaveOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "خيارات الحفظ للتصدير إلى صيغة Pdf."
type: docs
weight: 3790
url: /ar/java/com.aspose.pdf/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.PdfSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.PdfSaveOptions

```
public class PdfSaveOptions extends SaveOptions
```

خيارات الحفظ للتصدير إلى صيغة Pdf.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfSaveOptions](#PdfSaveOptions--) | منشئ |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDefaultFontName](#getDefaultFontName--) | اسم الخط المستخدم افتراضيًا للخطوط التي لا توجد على الحاسوب. عندما يحتوي مستند PDF الذي يتم حفظه في PDF على خطوط غير متوفرة في المستند نفسه وعلى الجهاز، تقوم API باستبدال هذه الخطوط بالخط الافتراضي (إذا تم العثور على خط باسم {@code DefaultFontName} على الجهاز). |
| [getTempPath](#getTempPath--) | المسار للملفات المؤقتة. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | اسم الخط المستخدم افتراضيًا للخطوط التي لا توجد على الحاسوب. عندما يحتوي مستند PDF الذي يتم حفظه في PDF على خطوط غير متوفرة في المستند نفسه وعلى الجهاز، تقوم API باستبدال هذه الخطوط بالخط الافتراضي (إذا تم العثور على خط باسم {@code DefaultFontName} على الجهاز). |
| [setTempPath](#setTempPath-java.lang.String-) | المسار للملفات المؤقتة. |

### PdfSaveOptions {#PdfSaveOptions--}
```
public PdfSaveOptions()
```

منشئ

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

اسم الخط المستخدم افتراضيًا للخطوط التي لا توجد على الحاسوب. عندما يحتوي مستند PDF الذي يتم حفظه في PDF على خطوط غير متوفرة في المستند نفسه وعلى الجهاز، تقوم API باستبدال هذه الخطوط بالخط الافتراضي (إذا تم العثور على خط باسم {@code DefaultFontName} على الجهاز).

**Returns:**
قيمة سلسلة

### getTempPath {#getTempPath--}
```
public final String getTempPath()
```

المسار للملفات المؤقتة.

**Returns:**
قيمة سلسلة

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
اسم الخط المستخدم افتراضيًا للخطوط التي لا توجد على الحاسوب. عندما يحتوي مستند PDF الذي يتم حفظه في PDF على خطوط غير متوفرة في المستند نفسه وعلى الجهاز، تقوم API باستبدال هذه الخطوط بالخط الافتراضي (إذا تم العثور على خط باسم {@code DefaultFontName} على الجهاز).

### setTempPath {#setTempPath-java.lang.String-}
المسار للملفات المؤقتة.
