---
title: "SvgSaveOptions"
linktitle: "SvgSaveOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "خيارات الحفظ للتصدير إلى صيغة SVG."
type: docs
weight: 4720
url: /ar/java/com.aspose.pdf/svgsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.SvgSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SvgSaveOptions

```
public class SvgSaveOptions extends UnifiedSaveOptions
```

خيارات الحفظ للتصدير إلى صيغة SVG.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SvgSaveOptions](#SvgSaveOptions--) | منشئ |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCustomStrategyOfEmbeddedImagesSaving](#getCustomStrategyOfEmbeddedImagesSaving--) | يمكن لهذا الحقل أن يحتوي على استراتيجية حفظ يجب استخدامها (إذا وجدت) أثناء التحويل للتعامل المخصص مع ملفات الصور الخارجية المرجعية التي تم إنشاؤها (مثل BMP أو JPEG المضمنة) المضمنة في SVG المحفوظ. يجب على تلك الاستراتيجية معالجة الموارد وإرجاع سلسلة تمثل URI المرغوب للموارد المحفوظة في SVG المُولد. إذا كان يجب معالجة هذا الملف أو ذاك الملف لسبب ما بواسطة شفرة المحول نفسها، وليس في الشفرة المخصصة، يرجى ضبط علامة 'CustomProcessingCancelled' في متغير المعامل 'imageSavingInfo' في الشفرة المخصصة. هذا يُشير إلى المحول بأن جميع الخطوات اللازمة لمعالجة ذلك المورد يجب أن تُنفذ في المحول نفسه كما لو لم يكن هناك أي شفرة مخصصة خارجية. |
| [isCompressOutputToZipArchive](#isCompressOutputToZipArchive--) | يحدد ما إذا كان سيتم إنشاء المخرجات كأرشيف zip واحد. يرجى الرجوع إلى التعليق الخاص بخيار 'TreatTargetFileNameAsDirectory' لمعرفة قواعد تسمية ملفات svg للصفحات في المستند المصدر متعدد الصفحات، والتي تُطبق أيضًا على مجموعة الملفات المضغوطة الناتجة. |
| [isScaleToPixels](#isScaleToPixels--) | يحدد ما إذا كان سيتم تحويل مقياس المستند الناتج من النقاط الطباعية إلى البكسلات. |
| [isTreatTargetFileNameAsDirectory](#isTreatTargetFileNameAsDirectory--) | هذا الخيار يحدد ما إذا كان سيتم إنشاء دليل الهدف (إذا لم يكن موجودًا بعد) بنفس اسم ملف الإخراج المطلوب بدلاً من ملف الإخراج نفسه. وبالتالي، سيحتوي ذلك الدليل على جميع صور SVG الناتجة للصفحات (كما هو موضح أدناه). إذا كان لا، فسيتم إنشاء ملفات إخراج الصفحات غير الأولى بالضبط في الدليل المطلوب كملف الإخراج الرئيسي، ولكن سيحتوي اسم الملف على اللاحقة _[2...n]، التي تُحدد برقم الصفحة، على سبيل المثال إذا قمت بتحديد ملف الإخراج "C:\\AsposeTests\\output.svg" وكان الإخراج يحتوي على عدة ملفات svg للصفحات، فسيتم إنشاء ملفات الصفحات أيضًا في الدليل "C:\\AsposeTests\\" وتكون أسماؤها 'output.svg'، 'output_2.svg'، 'output_3.svg' إلخ. |
| [setCompressOutputToZipArchive](#setCompressOutputToZipArchive-boolean-) | يحدد ما إذا كان سيتم إنشاء المخرجات كأرشيف zip واحد. يرجى الرجوع إلى التعليق الخاص بخيار 'TreatTargetFileNameAsDirectory' لمعرفة قواعد تسمية ملفات svg للصفحات في المستند المصدر متعدد الصفحات، والتي تُطبق أيضًا على مجموعة الملفات المضغوطة الناتجة. |
| [setCustomStrategyOfEmbeddedImagesSaving](#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-) | يمكن لهذا الحقل أن يحتوي على استراتيجية الحفظ التي يجب استخدامها (إذا كانت موجودة) أثناء التحويل للتعامل المخصص مع ملفات الصور الخارجية المرجعية التي تم إنشاؤها (مثل BMP أو JPEG المدمجة) المدمجة في SVG المحفوظ. |
| [setScaleToPixels](#setScaleToPixels-boolean-) | يحدد ما إذا كان سيتم تحويل مقياس المستند الناتج من النقاط الطباعية إلى البكسلات. |
| [setTreatTargetFileNameAsDirectory](#setTreatTargetFileNameAsDirectory-boolean-) | هذا الخيار يحدد ما إذا كان سيتم إنشاء دليل الهدف (إذا لم يكن موجودًا بعد) بنفس اسم ملف الإخراج المطلوب بدلاً من ملف الإخراج نفسه. وبالتالي، سيحتوي ذلك الدليل على جميع صور SVG الناتجة للصفحات (كما هو موضح أدناه). إذا كان لا، فسيتم إنشاء ملفات إخراج الصفحات غير الأولى بالضبط في الدليل المطلوب كملف الإخراج الرئيسي، ولكن سيحتوي اسم الملف على اللاحقة _[2...n]، التي تُحدد برقم الصفحة، على سبيل المثال إذا قمت بتحديد ملف الإخراج "C:\\AsposeTests\\output.svg" وكان الإخراج يحتوي على عدة ملفات svg للصفحات، فسيتم إنشاء ملفات الصفحات أيضًا في الدليل "C:\\AsposeTests\\" وتكون أسماؤها 'output.svg'، 'output_2.svg'، 'output_3.svg' إلخ. |

### SvgSaveOptions {#SvgSaveOptions--}
```
public SvgSaveOptions()
```

منشئ

### getCustomStrategyOfEmbeddedImagesSaving {#getCustomStrategyOfEmbeddedImagesSaving--}
```
public SvgSaveOptions.EmbeddedImagesSavingStrategy getCustomStrategyOfEmbeddedImagesSaving()
```

يمكن لهذا الحقل أن يحتوي على استراتيجية حفظ يجب استخدامها (إذا وجدت) أثناء التحويل للتعامل المخصص مع ملفات الصور الخارجية المرجعية التي تم إنشاؤها (مثل BMP أو JPEG المضمنة) المضمنة في SVG المحفوظ. يجب على تلك الاستراتيجية معالجة الموارد وإرجاع سلسلة تمثل URI المرغوب للموارد المحفوظة في SVG المُولد. إذا كان يجب معالجة هذا الملف أو ذاك الملف لسبب ما بواسطة شفرة المحول نفسها، وليس في الشفرة المخصصة، يرجى ضبط علامة 'CustomProcessingCancelled' في متغير المعامل 'imageSavingInfo' في الشفرة المخصصة. هذا يُشير إلى المحول بأن جميع الخطوات اللازمة لمعالجة ذلك المورد يجب أن تُنفذ في المحول نفسه كما لو لم يكن هناك أي شفرة مخصصة خارجية.

**Returns:**
مثيل EmbeddedImagesSavingStrategy

### isCompressOutputToZipArchive {#isCompressOutputToZipArchive--}
```
public boolean isCompressOutputToZipArchive()
```

يحدد ما إذا كان سيتم إنشاء المخرجات كأرشيف zip واحد. يرجى الرجوع إلى التعليق الخاص بخيار 'TreatTargetFileNameAsDirectory' لمعرفة قواعد تسمية ملفات svg للصفحات في المستند المصدر متعدد الصفحات، والتي تُطبق أيضًا على مجموعة الملفات المضغوطة الناتجة.

**Returns:**
قيمة منطقية

### isScaleToPixels {#isScaleToPixels--}
```
public boolean isScaleToPixels()
```

يحدد ما إذا كان سيتم تحويل مقياس المستند الناتج من النقاط الطباعية إلى البكسلات.

**Returns:**
قيمة منطقية

### isTreatTargetFileNameAsDirectory {#isTreatTargetFileNameAsDirectory--}
```
public boolean isTreatTargetFileNameAsDirectory()
```

هذا الخيار يحدد ما إذا كان سيتم إنشاء دليل الهدف (إذا لم يكن موجودًا بعد) بنفس اسم ملف الإخراج المطلوب بدلاً من ملف الإخراج نفسه. وبالتالي، سيحتوي ذلك الدليل على جميع صور SVG الناتجة للصفحات (كما هو موضح أدناه). إذا كان لا، فسيتم إنشاء ملفات إخراج الصفحات غير الأولى بالضبط في الدليل المطلوب كملف الإخراج الرئيسي، ولكن سيحتوي اسم الملف على اللاحقة _[2...n]، التي تُحدد برقم الصفحة، على سبيل المثال إذا قمت بتحديد ملف الإخراج "C:\AsposeTests\output.svg" وكان الإخراج يحتوي على عدة ملفات svg للصفحات، فسيتم إنشاء ملفات الصفحات أيضًا في الدليل "C:\AsposeTests\" وتكون أسماؤها 'output.svg'، 'output_2.svg'، 'output_3.svg' إلخ.

**Returns:**
قيمة منطقية

### setCompressOutputToZipArchive {#setCompressOutputToZipArchive-boolean-}
```
public void setCompressOutputToZipArchive(boolean compressOutputToZipArchive)
```

يحدد ما إذا كان سيتم إنشاء المخرجات كأرشيف zip واحد. يرجى الرجوع إلى التعليق الخاص بخيار 'TreatTargetFileNameAsDirectory' لمعرفة قواعد تسمية ملفات svg للصفحات في المستند المصدر متعدد الصفحات، والتي تُطبق أيضًا على مجموعة الملفات المضغوطة الناتجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| compressOutputToZipArchive |  | قيمة منطقية |

### setCustomStrategyOfEmbeddedImagesSaving {#setCustomStrategyOfEmbeddedImagesSaving-com.aspose.pdf.SvgSaveOptions.EmbeddedImagesSavingStrategy-}
يمكن لهذا الحقل أن يحتوي على استراتيجية الحفظ التي يجب استخدامها (إذا كانت موجودة) أثناء التحويل للتعامل المخصص مع ملفات الصور الخارجية المرجعية التي تم إنشاؤها (مثل BMP أو JPEG المدمجة) المدمجة في SVG المحفوظ.

### setScaleToPixels {#setScaleToPixels-boolean-}
```
public void setScaleToPixels(boolean scaleToPixels)
```

يحدد ما إذا كان سيتم تحويل مقياس المستند الناتج من النقاط الطباعية إلى البكسلات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| scaleToPixels |  | قيمة منطقية |

### setTreatTargetFileNameAsDirectory {#setTreatTargetFileNameAsDirectory-boolean-}
```
public void setTreatTargetFileNameAsDirectory(boolean treatTargetFileNameAsDirectory)
```

هذا الخيار يحدد ما إذا كان سيتم إنشاء دليل الهدف (إذا لم يكن موجودًا بعد) بنفس اسم ملف الإخراج المطلوب بدلاً من ملف الإخراج نفسه. وبالتالي، سيحتوي ذلك الدليل على جميع صور SVG الناتجة للصفحات (كما هو موضح أدناه). إذا كان لا، فسيتم إنشاء ملفات إخراج الصفحات غير الأولى بالضبط في الدليل المطلوب كملف الإخراج الرئيسي، ولكن سيحتوي اسم الملف على اللاحقة _[2...n]، التي تُحدد برقم الصفحة، على سبيل المثال إذا قمت بتحديد ملف الإخراج "C:\AsposeTests\output.svg" وكان الإخراج يحتوي على عدة ملفات svg للصفحات، فسيتم إنشاء ملفات الصفحات أيضًا في الدليل "C:\AsposeTests\" وتكون أسماؤها 'output.svg'، 'output_2.svg'، 'output_3.svg' إلخ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| treatTargetFileNameAsDirectory |  | قيمة منطقية |
