---
title: "PsLoadOptions"
linktitle: "PsLoadOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خيارات تحميل/استيراد ملف .mht إلى مستند pdf."
type: docs
weight: 4060
url: /ar/java/com.aspose.pdf/psloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PsLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PsLoadOptions

```
public final class PsLoadOptions extends LoadOptions
```

يمثل خيارات تحميل/استيراد ملف .mht إلى مستند pdf.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PsLoadOptions](#PsLoadOptions--) | ينشئ خيارات التحميل لتحويل PostScript إلى مستند pdf مع مسار أساسي فارغ. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFontsFolders](#getFontsFolders--) | يحصل على مسارات مجلدات الخطوط. المجلدات التي تحتوي على خطوط إضافية للتحويل. |
| [isConvertFontsToTTF](#isConvertFontsToTTF--) | يحدد ما إذا كان يجب حفظ الخطوط غير TrueType إلى TTF. يقلل ذلك بشكل كبير من حجم المستند الناتج في تحويل PS إلى PDF ويزيد من سرعة تحويل ملفات PS التي تحتوي على كمية كبيرة من النص بخطوط غير TrueType إلى أي تنسيق إخراج. ومع ذلك، هناك إزاحة رأسية صغيرة للنص عند تحويل ملف PostSctipt إلى صورة. |
| [setConvertFontsToTTF](#setConvertFontsToTTF-boolean-) | يحدد ما إذا كان يجب حفظ الخطوط غير TrueType إلى TTF. يقلل ذلك بشكل كبير من حجم المستند الناتج في تحويل PS إلى PDF ويزيد من سرعة تحويل ملفات PS التي تحتوي على كمية كبيرة من النص بخطوط غير TrueType إلى أي تنسيق إخراج. ومع ذلك، هناك إزاحة رأسية صغيرة للنص عند تحويل ملف PostSctipt إلى صورة. |
| [setFontsFolders](#setFontsFolders-java.lang.String:A-) | يضبط مسارات مجلدات الخطوط. المجلدات التي تحتوي على خطوط إضافية للتحويل. |

### PsLoadOptions {#PsLoadOptions--}
```
public PsLoadOptions()
```

ينشئ خيارات التحميل لتحويل PostScript إلى مستند pdf مع مسار أساسي فارغ.

### getFontsFolders {#getFontsFolders--}
```
public String [] getFontsFolders()
```

يحصل على مسارات مجلدات الخطوط. المجلدات التي تحتوي على خطوط إضافية للتحويل.

**Returns:**
مصفوفة من قيم String

### isConvertFontsToTTF {#isConvertFontsToTTF--}
```
public final boolean isConvertFontsToTTF()
```

يحدد ما إذا كان يجب حفظ الخطوط غير TrueType إلى TTF. يقلل ذلك بشكل كبير من حجم المستند الناتج في تحويل PS إلى PDF ويزيد من سرعة تحويل ملفات PS التي تحتوي على كمية كبيرة من النص بخطوط غير TrueType إلى أي تنسيق إخراج. ومع ذلك، هناك إزاحة رأسية صغيرة للنص عند تحويل ملف PostSctipt إلى صورة.

**Returns:**
قيمة منطقية

### setConvertFontsToTTF {#setConvertFontsToTTF-boolean-}
```
public final void setConvertFontsToTTF(boolean value)
```

يحدد ما إذا كان يجب حفظ الخطوط غير TrueType إلى TTF. يقلل ذلك بشكل كبير من حجم المستند الناتج في تحويل PS إلى PDF ويزيد من سرعة تحويل ملفات PS التي تحتوي على كمية كبيرة من النص بخطوط غير TrueType إلى أي تنسيق إخراج. ومع ذلك، هناك إزاحة رأسية صغيرة للنص عند تحويل ملف PostSctipt إلى صورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setFontsFolders {#setFontsFolders-java.lang.String:A-}
يضبط مسارات مجلدات الخطوط. المجلدات التي تحتوي على خطوط إضافية للتحويل.
