---
title: "TeXLoadOptions"
linktitle: "TeXLoadOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خيارات تحميل/استيراد ملف TeX إلى مستند PDF."
type: docs
weight: 4870
url: /ar/java/com.aspose.pdf/texloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.TeXLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.TeXLoadOptions

```
public class TeXLoadOptions extends LoadOptions
```

يمثل خيارات تحميل/استيراد ملف TeX إلى مستند PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TeXLoadOptions](#TeXLoadOptions--) | ينشئ خيارات التحميل الافتراضية لتحويل ملف TeX إلى مستند PDF. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDateTime](#getDateTime--) | يحصل/يضبط قيمة معينة للأنواع الأولية للتاريخ/الوقت مثل السنة والشهر واليوم والوقت. |
| [getInputDirectory](#getInputDirectory--) | يحصل/يضبط دليل إدخال TeX. |
| [getJobName](#getJobName--) | يحصل/يضبط اسم المهمة. |
| [getLoadResult](#getLoadResult--) | يحصل على النتيجة لتحميل TeX وتكوينه - هل سارت الأمور بسلاسة أم كان هناك أي تعليقات/أخطاء. |
| [getNoLigatures](#getNoLigatures--) | يحصل/يضبط علامة تلغي الحروف المتصلة في جميع الخطوط. |
| [getOutputDirectory](#getOutputDirectory--) | يحصل/يضبط دليل إخراج TeX. |
| [getRasterizeFormulas](#getRasterizeFormulas--) | يحصل/يضبط علامة تسمح بتحويل صيغ الرياضيات إلى نقطية. |
| [getRepeat](#getRepeat--) | يحصل/يضبط العلامة التي تشير إلى ما إذا كان من الضروري تشغيل مهمة TeX مرتين في حالة، على سبيل المثال، وجود مراجع في ملفات TeX المدخلة. بشكل عام، هذا السلوك مفيد عندما يجمع المحرك بعض البيانات أثناء عملية التنضيد ويخزنها في ملف مساعد، كل ذلك في التشغيل الأول. وفي التشغيل الثاني، يستخدم المحرك تلك البيانات بطريقة ما. |
| [getRequiredInputDirectory](#getRequiredInputDirectory--) | يحصل/يضبط دليل الإدخال المطلوب لـ TeX. الإدخال المطلوب هو الملفات التي يتم تضمينها بطريقة ما في الملف الرئيسي .tex، مثل الحزم التي لا يوجد لها دعم مدمج. |
| [getShowTerminalOutput](#getShowTerminalOutput--) | يحصل/يضبط العلامة التي تشير إلى ما إذا كان يجب عرض مخرجات الطرفية على وحدة التحكم. |
| [getSubsetFonts](#getSubsetFonts--) | يحصل/يضبط العلامة التي تشير إلى ما إذا كان سيتم تقليص الخطوط في ملف الإخراج أم لا. |
| [setDateTime](#setDateTime-java.util.Date-) | يحصل/يضبط قيمة معينة للأنواع الأولية للتاريخ/الوقت مثل السنة والشهر واليوم والوقت. |
| [setInputDirectory](#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | يحصل/يضبط دليل إدخال TeX. |
| [setJobName](#setJobName-java.lang.String-) | يحصل/يضبط اسم المهمة. |
| [setNoLigatures](#setNoLigatures-boolean-) | يحصل/يضبط علامة تلغي الحروف المتصلة في جميع الخطوط. |
| [setOutputDirectory](#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-) | يحصل/يضبط دليل إخراج TeX. |
| [setRasterizeFormulas](#setRasterizeFormulas-boolean-) | يحصل/يضبط علامة تسمح بتحويل صيغ الرياضيات إلى نقطية. |
| [setRepeat](#setRepeat-boolean-) | يحصل/يضبط العلامة التي تشير إلى ما إذا كان من الضروري تشغيل مهمة TeX مرتين في حالة، على سبيل المثال، وجود مراجع في ملفات TeX المدخلة. بشكل عام، هذا السلوك مفيد عندما يجمع المحرك بعض البيانات أثناء عملية التنضيد ويخزنها في ملف مساعد، كل ذلك في التشغيل الأول. وفي التشغيل الثاني، يستخدم المحرك تلك البيانات بطريقة ما. |
| [setRequiredInputDirectory](#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | يحصل/يضبط دليل الإدخال المطلوب لـ TeX. الإدخال المطلوب هو الملفات التي يتم تضمينها بطريقة ما في الملف الرئيسي .tex، مثل الحزم التي لا يوجد لها دعم مدمج. |
| [setShowTerminalOutput](#setShowTerminalOutput-boolean-) | يحصل/يضبط العلامة التي تشير إلى ما إذا كان يجب عرض مخرجات الطرفية على وحدة التحكم. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | يحصل/يضبط العلامة التي تشير إلى ما إذا كان سيتم تقليص الخطوط في ملف الإخراج أم لا. |

### TeXLoadOptions {#TeXLoadOptions--}
```
public TeXLoadOptions()
```

ينشئ خيارات التحميل الافتراضية لتحويل ملف TeX إلى مستند PDF.

### getDateTime {#getDateTime--}
```
public final Date getDateTime()
```

يحصل/يضبط قيمة معينة للأنواع الأولية للتاريخ/الوقت مثل السنة والشهر واليوم والوقت.

**Returns:**
مثيل Date

### getInputDirectory {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```

يحصل/يضبط دليل إدخال TeX.

**Returns:**
مثيل ITeXInputDirectory

### getJobName {#getJobName--}
```
public final String getJobName()
```

يحصل/يضبط اسم المهمة.

**Returns:**
قيمة سلسلة

### getLoadResult {#getLoadResult--}
```
public final int getLoadResult()
```

يحصل على النتيجة لتحميل TeX وتكوينه - هل سارت الأمور بسلاسة أم كان هناك أي تعليقات/أخطاء.

**Returns:**
عنصر TeXLoadResult

### getNoLigatures {#getNoLigatures--}
```
public final boolean getNoLigatures()
```

يحصل/يضبط علامة تلغي الحروف المتصلة في جميع الخطوط.

**Returns:**
قيمة منطقية

### getOutputDirectory {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```

يحصل/يضبط دليل إخراج TeX.

**Returns:**
مثيل ITeXOutputDirectory

### getRasterizeFormulas {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```

يحصل/يضبط علامة تسمح بتحويل صيغ الرياضيات إلى نقطية.

**Returns:**
قيمة منطقية

### getRepeat {#getRepeat--}
```
public final boolean getRepeat()
```

يحصل/يضبط العلامة التي تشير إلى ما إذا كان من الضروري تشغيل مهمة TeX مرتين في حالة، على سبيل المثال، وجود مراجع في ملفات TeX المدخلة. بشكل عام، هذا السلوك مفيد عندما يجمع المحرك بعض البيانات أثناء عملية التنضيد ويخزنها في ملف مساعد، كل ذلك في التشغيل الأول. وفي التشغيل الثاني، يستخدم المحرك تلك البيانات بطريقة ما.

**Returns:**
قيمة منطقية

### getRequiredInputDirectory {#getRequiredInputDirectory--}
```
public final ITeXInputDirectory getRequiredInputDirectory()
```

يحصل/يضبط دليل الإدخال المطلوب لـ TeX. الإدخال المطلوب هو الملفات التي يتم تضمينها بطريقة ما في الملف الرئيسي .tex، مثل الحزم التي لا يوجد لها دعم مدمج.

**Returns:**
مثيل ITeXInputDirectory

### getShowTerminalOutput {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```

يحصل/يضبط العلامة التي تشير إلى ما إذا كان يجب عرض مخرجات الطرفية على وحدة التحكم.

**Returns:**
قيمة منطقية

### getSubsetFonts {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```

يحصل/يضبط العلامة التي تشير إلى ما إذا كان سيتم تقليص الخطوط في ملف الإخراج أم لا.

**Returns:**
قيمة منطقية

### setDateTime {#setDateTime-java.util.Date-}
يحصل/يضبط قيمة معينة للأنواع الأولية للتاريخ/الوقت مثل السنة والشهر واليوم والوقت.

### setInputDirectory {#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
يحصل/يضبط دليل إدخال TeX.

### setJobName {#setJobName-java.lang.String-}
يحصل/يضبط اسم المهمة.

### setNoLigatures {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```

يحصل/يضبط علامة تلغي الحروف المتصلة في جميع الخطوط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setOutputDirectory {#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-}
يحصل/يضبط دليل إخراج TeX.

### setRasterizeFormulas {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```

يحصل/يضبط علامة تسمح بتحويل صيغ الرياضيات إلى نقطية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRepeat {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```

يحصل/يضبط العلامة التي تشير إلى ما إذا كان من الضروري تشغيل مهمة TeX مرتين في حالة، على سبيل المثال، وجود مراجع في ملفات TeX المدخلة. بشكل عام، هذا السلوك مفيد عندما يجمع المحرك بعض البيانات أثناء عملية التنضيد ويخزنها في ملف مساعد، كل ذلك في التشغيل الأول. وفي التشغيل الثاني، يستخدم المحرك تلك البيانات بطريقة ما.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRequiredInputDirectory {#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
يحصل/يضبط دليل الإدخال المطلوب لـ TeX. الإدخال المطلوب هو الملفات التي يتم تضمينها بطريقة ما في الملف الرئيسي .tex، مثل الحزم التي لا يوجد لها دعم مدمج.

### setShowTerminalOutput {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```

يحصل/يضبط العلامة التي تشير إلى ما إذا كان يجب عرض مخرجات الطرفية على وحدة التحكم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

يحصل/يضبط العلامة التي تشير إلى ما إذا كان سيتم تقليص الخطوط في ملف الإخراج أم لا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
