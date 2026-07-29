---
title: "TextDefaults.DefaultFontStrategy"
linktitle: "TextDefaults.DefaultFontStrategy"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يحدد نوع القيم الافتراضية لنظام النص الفرعي"
type: docs
weight: 4960
url: /ar/java/com.aspose.pdf/textdefaults.defaultfontstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.TextDefaults.DefaultFontStrategy

```
public static class TextDefaults.DefaultFontStrategy extends com.aspose.ms.System.Enum
```

يحدد نوع القيم الافتراضية لنظام النص الفرعي

## الحقول

| حقل | الوصف |
| --- | --- |
| [ListOfFonts](#ListOfFonts) | استخدم الخط الافتراضي من القائمة المحددة مسبقًا من كائنات Font. يمكن تعيينه باستخدام setDefaultFonts(List of Font instances) سيُستخدم أول خط يُعثر عليه يحتوي على جميع الأحرف المطلوبة للنص. إذا لم يُعثر على مثل هذا الخط - سيتم استخدام خط النظام. |
| [PredefinedFont](#PredefinedFont) | استخدم الخط الافتراضي. يمكن تعيينه باستخدام set/get PredefinedFont(Font) إذا كان PredefinedFont فارغًا - سيتم استخدام SystemFont. |
| [SystemFont](#SystemFont) | استخدم خط النظام الافتراضي Helvetica، أو نظيره البديل. |
| [TheFirstSuitableFoundFont](#TheFirstSuitableFoundFont) | سيُستخدم أول خط يُعثر عليه، يحتوي على جميع الأحرف الضرورية للنص. سيتم تضمين جميع الخطوط التي تم العثور عليها. إذا لم يُعثر على مثل هذا الخط - سيتم استخدام خط النظام. |

### ListOfFonts {#ListOfFonts}
```
public static final int ListOfFonts
```

استخدم الخط الافتراضي من القائمة المحددة مسبقًا من كائنات Font. يمكن تعيينه باستخدام setDefaultFonts(List of Font instances) سيُستخدم أول خط يُعثر عليه يحتوي على جميع الأحرف المطلوبة للنص. إذا لم يُعثر على مثل هذا الخط - سيتم استخدام خط النظام.

### PredefinedFont {#PredefinedFont}
```
public static final int PredefinedFont
```

استخدم الخط الافتراضي. يمكن تعيينه باستخدام set/get PredefinedFont(Font) إذا كان PredefinedFont فارغًا - سيتم استخدام SystemFont.

### SystemFont {#SystemFont}
```
public static final int SystemFont
```

استخدم خط النظام الافتراضي Helvetica، أو نظيره البديل.

### TheFirstSuitableFoundFont {#TheFirstSuitableFoundFont}
```
public static final int TheFirstSuitableFoundFont
```

سيُستخدم أول خط يُعثر عليه، يحتوي على جميع الأحرف الضرورية للنص. سيتم تضمين جميع الخطوط التي تم العثور عليها. إذا لم يُعثر على مثل هذا الخط - سيتم استخدام خط النظام.
