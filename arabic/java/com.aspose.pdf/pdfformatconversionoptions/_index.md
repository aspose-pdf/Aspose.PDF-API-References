---
title: "PdfFormatConversionOptions"
linktitle: "PdfFormatConversionOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل مجموعة من الخيارات لتحويل مستند PDF."
type: docs
weight: 3730
url: /ar/java/com.aspose.pdf/pdfformatconversionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions

```
public class PdfFormatConversionOptions extends Object
```

يمثل مجموعة من الخيارات لتحويل مستند PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | منشئ |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-) | منشئ |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | منشئ |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-) | منشئ |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | منشئ |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | منشئ |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addNotAccessibleFont](#addNotAccessibleFont-java.lang.String-) |  |
| [getAlignStrategy](#getAlignStrategy--) | استراتيجية لمحاذاة النص. هذا المعامل ذو معنى فقط عندما يتم تعيين العلامة {@code AlignText} إلى true. |
| [getAlignText](#getAlignText--) | تتحكم هذه العلامة في محاذاة النص في المستند المحول. بشكل افتراضي لا تؤثر عملية تحويل المستند على محاذاة النص وتترك النص كما هو. لكن في بعض الحالات يتسبب استبدال الخطوط في تداخل النص أو وجود مسافات إضافية في المستند المحول. عندما يتم تعيين هذه العلامة، سيتم تنفيذ عمليات محاذاة خاصة. يجب تعيين هذه العلامة فقط للمستندات التي تعاني من مشاكل تداخل النص أو مسافات نصية إضافية، لأن استخدام هذه العلامة يقلل من الأداء وقد يفسد محتوى النص في بعض الحالات. |
| [getAutoTaggingSettings](#getAutoTaggingSettings--) | يحصل أو يضبط الإعدادات للوسم التلقائي أثناء تحويل تنسيق PDF. تُستخدم إعدادات الوسم التلقائي لتكوين سلوك عملية الوسم التلقائي، والتي تُستعمل عادةً لتحسين إمكانية الوصول وبنية مستند PDF أثناء التحويل إلى تنسيق PDF محدد. |
| [getConvertSoftMaskAction](#getConvertSoftMaskAction--) | إجراء للصور ذات القناع الناعم. |
| [getDefault](#getDefault--) | يحصل على كائن PdfFormatConversionOptions مع المعلمات الافتراضية. |
| [getErrorAction](#getErrorAction--) | إجراء للكائنات التي لا يمكن تحويلها. |
| [getExcludeFontsStrategy](#getExcludeFontsStrategy--) | استراتيجية (استراتيجيات) لاستبعاد الخطوط الزائدة وتقليل حجم ملف المستند. هذا المعامل ذو معنى فقط عندما يتم تعيين العلامة {@code OptimizeFileSize} إلى true. بشكل افتراضي يتم استخدام مجموعة الاستراتيجيات {@code SubsetFonts} و {@code RemoveDuplicatedFonts}. |
| [getFontEmbeddingOptions](#getFontEmbeddingOptions--) | خيارات للحالات التي لا يمكن فيها تضمين بعض الخطوط في مستند PDF. |
| [getFormat](#getFormat--) | تنسيق PDF. |
| [getIccProfileFileName](#getIccProfileFileName--) | يحصل على اسم ملف تعريف icc. في حالة كون القيمة null يتم استخدام ملف تعريف icc الافتراضي. |
| [getLogFileName](#getLogFileName--) | المسار إلى الملف حيث سيتم تخزين التعليقات. |
| [getLogStream](#getLogStream--) | الدفق حيث سيتم تخزين التعليقات. |
| [getNonSpecificationCases](#getNonSpecificationCases--) | يحمل العلامات للتحكم في عملية تحويل PDF/A للحالات التي لا يتطابق فيها المستند المصدر مع مواصفات PDF/A. |
| [getNotAccessibleFonts](#getNotAccessibleFonts--) | هذه الخاصية هي out-property. وهي تحمل جميع الخطوط (أسماء الخطوط) التي لم يتم العثور عليها على الحاسوب في آخر تحويل PDF/A. |
| [getOptimizeFileSize](#getOptimizeFileSize--) | يحصل على علامة تمكّن/تعطّل وضع التحويل الخاص للحصول على مستند PDF/A بحجم ملف أصغر. الآن تؤثر هذه العلامة على تحسين الخطوط المستخدمة في مستند PDF، وربما في المستقبل ستُستخدم هذه العلامة لتفعيل تحسين هياكل بيانات أخرى، مثل الرسومات. مجموعة هذه العلامة والوضع يمكن أن تقلل بشكل كبير حجم الملف ولكن في الوقت نفسه قد تقلل بشكل كبير من أداء التحويل. |
| [getOutputIntent](#getOutputIntent--) | يحصل أو يضبط {@link OutputIntent} لتحويل صيغة PDF. الـ {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) يحدد جهاز الإخراج المقصود أو الحالة التي يُجهّز من أجلها مستند PDF. يُستخدم لضمان أن الألوان في المستند تُعرض بشكل صحيح على الجهاز الهدف. |
| [getPuaTextProcessingStrategy](#getPuaTextProcessingStrategy--) | استراتيجية لمعالجة الرموز من منطقة الاستخدام الخاص في Unicode (PUA). |
| [getSymbolicFontEncodingStrategy](#getSymbolicFontEncodingStrategy--) | استراتيجية لنسخ بيانات الترميز للخطوط الرمزية إذا كان الخط TrueType الرمزي يحتوي على أكثر من جدول ترميز فرعي. |
| [getTransparencyAction](#getTransparencyAction--) | إجراء للكائنات ذات القناع الصوري. |
| [getTransparencyResolution](#getTransparencyResolution--) | يضبط الدقة أثناء تحويل الصور الشفافة. كلما ارتفعت الدقة، كلما كان سرعة التحويل أبطأ. القيمة الافتراضية هي 300. |
| [getUnicodeProcessingRules](#getUnicodeProcessingRules--) | قواعد لحل المشكلات مع تخطيط Unicode. يمكن أن تكون null. |
| [isAsyncImageStreamsConversionMode](#isAsyncImageStreamsConversionMode--) | يحصل/يضبط تشغيل تدفقات الصور في وضع غير المتزامن. |
| [isLowMemoryMode](#isLowMemoryMode--) | هل تم تمكين وضع التحويل منخفض الذاكرة |
| [isPageByPageFontProcess](#isPageByPageFontProcess--) | هل تم تمكين وضع تحليل الخط على أساس كل صفحة. القيمة الافتراضية = false |
| [isTransferInfo](#isTransferInfo--) | يحصل أو يضبط ما إذا كان سيتم نقل البيانات من Info إلى Metadata عند التحويل إلى PDF 2.0. True بشكل افتراضي. |
| [isTransparencyIgnore](#isTransparencyIgnore--) | القيمة الافتراضية FALSE وسيتم معالجة لون الشفافية للحفاظ على مظهر المستند. عند القيمة TRUE سيتم تحويل لون الشفافية إلى غير شفاف، وقد يتم تغطية بعض الكائنات. |
| [setAlignStrategy](#setAlignStrategy-byte-) | استراتيجية لمحاذاة النص. هذا المعامل ذو معنى فقط عندما يتم تعيين العلامة {@code AlignText} إلى true. |
| [setAlignText](#setAlignText-boolean-) | تتحكم هذه العلامة في محاذاة النص في المستند المحول. بشكل افتراضي لا تؤثر عملية تحويل المستند على محاذاة النص وتترك النص كما هو. لكن في بعض الحالات يتسبب استبدال الخطوط في تداخل النص أو وجود مسافات إضافية في المستند المحول. عندما يتم تعيين هذه العلامة، سيتم تنفيذ عمليات محاذاة خاصة. يجب تعيين هذه العلامة فقط للمستندات التي تعاني من مشاكل تداخل النص أو مسافات نصية إضافية، لأن استخدام هذه العلامة يقلل من الأداء وقد يفسد محتوى النص في بعض الحالات. |
| [setAsyncImageStreamsConversionMode](#setAsyncImageStreamsConversionMode-boolean-) | يحصل/يضبط تشغيل تدفقات الصور في وضع غير المتزامن. |
| [setAutoTaggingSettings](#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-) | يحصل أو يضبط الإعدادات للوسم التلقائي أثناء تحويل تنسيق PDF. تُستخدم إعدادات الوسم التلقائي لتكوين سلوك عملية الوسم التلقائي، والتي تُستعمل عادةً لتحسين إمكانية الوصول وبنية مستند PDF أثناء التحويل إلى تنسيق PDF محدد. |
| [setConvertSoftMaskAction](#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-) | إجراء للصور ذات القناع الناعم. |
| [setErrorAction](#setErrorAction-com.aspose.pdf.ConvertErrorAction-) | إجراء للكائنات التي لا يمكن تحويلها. |
| [setExcludeFontsStrategy](#setExcludeFontsStrategy-byte-) | استراتيجية (استراتيجيات) لاستبعاد الخطوط الزائدة وتقليل حجم ملف المستند. هذا المعامل ذو معنى فقط عندما يتم تعيين العلامة {@code OptimizeFileSize} إلى true. بشكل افتراضي يتم استخدام مجموعة الاستراتيجيات {@code SubsetFonts} و {@code RemoveDuplicatedFonts}. |
| [setFormat](#setFormat-com.aspose.pdf.PdfFormat-) | تنسيق PDF. |
| [setIccProfileFileName](#setIccProfileFileName-java.lang.String-) | يضبط اسم ملف تعريف icc. في حالة كون القيمة null يتم استخدام ملف تعريف icc الافتراضي. |
| [setLogFileName](#setLogFileName-java.lang.String-) | المسار إلى الملف حيث سيتم تخزين التعليقات. |
| [setLogStream](#setLogStream-java.io.OutputStream-) | الدفق حيث سيتم تخزين التعليقات. |
| [setLowMemoryMode](#setLowMemoryMode-boolean-) | هل تم تمكين وضع التحويل منخفض الذاكرة |
| [setOptimizeFileSize](#setOptimizeFileSize-boolean-) | يضبط علامة تمكّن/تعطّل وضع التحويل الخاص للحصول على مستند PDF/A بحجم ملف أصغر. الآن تؤثر هذه العلامة على تحسين الخطوط المستخدمة في مستند PDF، وربما في المستقبل ستُستخدم هذه العلامة لتفعيل تحسين هياكل بيانات أخرى، مثل الرسومات. مجموعة هذه العلامة والوضع يمكن أن تقلل بشكل كبير حجم الملف ولكن في الوقت نفسه قد تقلل بشكل كبير من أداء التحويل. |
| [setOutputIntent](#setOutputIntent-com.aspose.pdf.OutputIntent-) | يحصل أو يضبط {@link OutputIntent} لتحويل صيغة PDF. الـ {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) يحدد جهاز الإخراج المقصود أو الحالة التي يُجهّز من أجلها مستند PDF. يُستخدم لضمان أن الألوان في المستند تُعرض بشكل صحيح على الجهاز الهدف. |
| [setPageByPageFontProcess](#setPageByPageFontProcess-boolean-) | ضبط وضع تحليل الخط على أساس كل صفحة مفعّل. القيمة الافتراضية = false |
| [setPuaTextProcessingStrategy](#setPuaTextProcessingStrategy-int-) | استراتيجية لمعالجة الرموز من منطقة الاستخدام الخاص في Unicode (PUA). |
| [setSymbolicFontEncodingStrategy](#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-) | استراتيجية لنسخ بيانات الترميز للخطوط الرمزية إذا كان الخط TrueType الرمزي يحتوي على أكثر من جدول ترميز فرعي. |
| [setTransferInfo](#setTransferInfo-boolean-) | يحصل أو يضبط ما إذا كان سيتم نقل البيانات من Info إلى Metadata عند التحويل إلى PDF 2.0. True بشكل افتراضي. |
| [setTransparencyAction](#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-) | إجراء للكائنات ذات القناع الصوري. |
| [setTransparencyIgnore](#setTransparencyIgnore-boolean-) | القيمة الافتراضية FALSE وسيتم معالجة لون الشفافية للحفاظ على مظهر المستند. عند القيمة TRUE سيتم تحويل لون الشفافية إلى غير شفاف، وقد يتم تغطية بعض الكائنات. |
| [setTransparencyResolution](#setTransparencyResolution-int-) | يضبط الدقة أثناء تحويل الصور الشفافة. كلما ارتفعت الدقة، كلما كان سرعة التحويل أبطأ. القيمة الافتراضية هي 300. |
| [setUnicodeProcessingRules](#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-) | قواعد لحل المشكلات مع تخطيط Unicode. يمكن أن تكون null. |

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
منشئ

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-}
منشئ

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
منشئ

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-}
منشئ

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
منشئ

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
منشئ

### addNotAccessibleFont {#addNotAccessibleFont-java.lang.String-}


### getAlignStrategy {#getAlignStrategy--}
```
public byte getAlignStrategy()
```

استراتيجية لمحاذاة النص. هذا المعامل ذو معنى فقط عندما يتم تعيين العلامة {@code AlignText} إلى true.

**Returns:**
عنصر SegmentAlignStrategy @see SegmentAlignStrategy

### getAlignText {#getAlignText--}
```
public boolean getAlignText()
```

تتحكم هذه العلامة في محاذاة النص في المستند المحول. بشكل افتراضي لا تؤثر عملية تحويل المستند على محاذاة النص وتترك النص كما هو. لكن في بعض الحالات يتسبب استبدال الخطوط في تداخل النص أو وجود مسافات إضافية في المستند المحول. عندما يتم تعيين هذه العلامة، سيتم تنفيذ عمليات محاذاة خاصة. يجب تعيين هذه العلامة فقط للمستندات التي تعاني من مشاكل تداخل النص أو مسافات نصية إضافية، لأن استخدام هذه العلامة يقلل من الأداء وقد يفسد محتوى النص في بعض الحالات.

**Returns:**
قيمة منطقية

### getAutoTaggingSettings {#getAutoTaggingSettings--}
```
public final AutoTaggingSettings getAutoTaggingSettings()
```

يحصل أو يضبط الإعدادات للوسم التلقائي أثناء تحويل تنسيق PDF. تُستخدم إعدادات الوسم التلقائي لتكوين سلوك عملية الوسم التلقائي، والتي تُستعمل عادةً لتحسين إمكانية الوصول وبنية مستند PDF أثناء التحويل إلى تنسيق PDF محدد.

**Returns:**
مثيل AutoTaggingSettings

### getConvertSoftMaskAction {#getConvertSoftMaskAction--}
```
public final ConvertSoftMaskAction getConvertSoftMaskAction()
```

إجراء للصور ذات القناع الناعم.

**Returns:**
قيمة int

### getDefault {#getDefault--}
```
public static PdfFormatConversionOptions getDefault()
```

يحصل على كائن PdfFormatConversionOptions مع المعلمات الافتراضية.

**Returns:**
كائن PdfFormatConversionOptions

### getErrorAction {#getErrorAction--}
```
public ConvertErrorAction getErrorAction()
```

إجراء للكائنات التي لا يمكن تحويلها.

**Returns:**
عنصر ConvertErrorAction @see ConvertErrorAction

### getExcludeFontsStrategy {#getExcludeFontsStrategy--}
```
public byte getExcludeFontsStrategy()
```

استراتيجية (استراتيجيات) لاستبعاد الخطوط الزائدة وتقليل حجم ملف المستند. هذا المعامل ذو معنى فقط عندما يتم تعيين العلامة {@code OptimizeFileSize} إلى true. بشكل افتراضي يتم استخدام مجموعة الاستراتيجيات {@code SubsetFonts} و {@code RemoveDuplicatedFonts}.

**Returns:**
قيمة byte @see RemoveFontsStrategy

### getFontEmbeddingOptions {#getFontEmbeddingOptions--}
```
public FontEmbeddingOptions getFontEmbeddingOptions()
```

خيارات للحالات التي لا يمكن فيها تضمين بعض الخطوط في مستند PDF.

**Returns:**
كائن FontEmbeddingOptions

### getFormat {#getFormat--}
```
public PdfFormat getFormat()
```

تنسيق PDF.

**Returns:**
عنصر PdfFormat @see PdfFormat

### getIccProfileFileName {#getIccProfileFileName--}
```
public String getIccProfileFileName()
```

يحصل على اسم ملف تعريف icc. في حالة كون القيمة null يتم استخدام ملف تعريف icc الافتراضي.

**Returns:**
كائن String

### getLogFileName {#getLogFileName--}
```
public String getLogFileName()
```

المسار إلى الملف حيث سيتم تخزين التعليقات.

**Returns:**
كائن String

### getLogStream {#getLogStream--}
```
public OutputStream getLogStream()
```

الدفق حيث سيتم تخزين التعليقات.

**Returns:**
كائن OutputStream

### getNonSpecificationCases {#getNonSpecificationCases--}
```
public PdfFormatConversionOptions.PdfANonSpecificationFlags getNonSpecificationCases()
```

يحمل العلامات للتحكم في عملية تحويل PDF/A للحالات التي لا يتطابق فيها المستند المصدر مع مواصفات PDF/A.

**Returns:**
كائن PdfANonSpecificationFlags

### getNotAccessibleFonts {#getNotAccessibleFonts--}
```
public String [] getNotAccessibleFonts()
```

هذه الخاصية هي out-property. وهي تحمل جميع الخطوط (أسماء الخطوط) التي لم يتم العثور عليها على الحاسوب في آخر تحويل PDF/A.

**Returns:**
مصفوفة من السلاسل

### getOptimizeFileSize {#getOptimizeFileSize--}
```
public boolean getOptimizeFileSize()
```

يحصل على علامة تمكّن/تعطّل وضع التحويل الخاص للحصول على مستند PDF/A بحجم ملف أصغر. الآن تؤثر هذه العلامة على تحسين الخطوط المستخدمة في مستند PDF، وربما في المستقبل ستُستخدم هذه العلامة لتفعيل تحسين هياكل بيانات أخرى، مثل الرسومات. مجموعة هذه العلامة والوضع يمكن أن تقلل بشكل كبير حجم الملف ولكن في الوقت نفسه قد تقلل بشكل كبير من أداء التحويل.

**Returns:**
قيمة منطقية

### getOutputIntent {#getOutputIntent--}
```
public final OutputIntent getOutputIntent()
```

يحصل أو يضبط {@link OutputIntent} لتحويل صيغة PDF. الـ {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) يحدد جهاز الإخراج المقصود أو الحالة التي يُجهّز من أجلها مستند PDF. يُستخدم لضمان أن الألوان في المستند تُعرض بشكل صحيح على الجهاز الهدف.

**Returns:**
مثيل OutputIntent

### getPuaTextProcessingStrategy {#getPuaTextProcessingStrategy--}
```
public int getPuaTextProcessingStrategy()
```

استراتيجية لمعالجة الرموز من منطقة الاستخدام الخاص في Unicode (PUA).

**Returns:**
عنصر PuaProcessingStrategy @see PuaProcessingStrategy

### getSymbolicFontEncodingStrategy {#getSymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy getSymbolicFontEncodingStrategy()
```

استراتيجية لنسخ بيانات الترميز للخطوط الرمزية إذا كان الخط TrueType الرمزي يحتوي على أكثر من جدول ترميز فرعي.

**Returns:**
كائن PdfASymbolicFontEncodingStrategy

### getTransparencyAction {#getTransparencyAction--}
```
public ConvertTransparencyAction getTransparencyAction()
```

إجراء للكائنات ذات القناع الصوري.

**Returns:**
عنصر ConvertTransparencyAction @see ConvertTransparencyAction

### getTransparencyResolution {#getTransparencyResolution--}
```
public int getTransparencyResolution()
```

يضبط الدقة أثناء تحويل الصور الشفافة. كلما ارتفعت الدقة، كلما كان سرعة التحويل أبطأ. القيمة الافتراضية هي 300.

**Returns:**
قيمة الدقة

### getUnicodeProcessingRules {#getUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules getUnicodeProcessingRules()
```

قواعد لحل المشكلات مع تخطيط Unicode. يمكن أن تكون null.

**Returns:**
كائن ToUnicodeProcessingRules

### isAsyncImageStreamsConversionMode {#isAsyncImageStreamsConversionMode--}
```
public final boolean isAsyncImageStreamsConversionMode()
```

يحصل/يضبط تشغيل تدفقات الصور في وضع غير المتزامن.

**Returns:**
قيمة منطقية

### isLowMemoryMode {#isLowMemoryMode--}
```
public final boolean isLowMemoryMode()
```

هل تم تمكين وضع التحويل منخفض الذاكرة

**Returns:**
قيمة منطقية

### isPageByPageFontProcess {#isPageByPageFontProcess--}
```
public boolean isPageByPageFontProcess()
```

هل تم تمكين وضع تحليل الخط على أساس كل صفحة. القيمة الافتراضية = false

**Returns:**
قيمة منطقية

### isTransferInfo {#isTransferInfo--}
```
public final boolean isTransferInfo()
```

يحصل أو يضبط ما إذا كان سيتم نقل البيانات من Info إلى Metadata عند التحويل إلى PDF 2.0. True بشكل افتراضي.

**Returns:**
قيمة منطقية

### isTransparencyIgnore {#isTransparencyIgnore--}
```
public boolean isTransparencyIgnore()
```

القيمة الافتراضية FALSE وسيتم معالجة لون الشفافية للحفاظ على مظهر المستند. عند القيمة TRUE سيتم تحويل لون الشفافية إلى غير شفاف، وقد يتم تغطية بعض الكائنات.

**Returns:**
قيمة منطقية

### setAlignStrategy {#setAlignStrategy-byte-}
```
public void setAlignStrategy(byte alignStrategy)
```

استراتيجية لمحاذاة النص. هذا المعامل ذو معنى فقط عندما يتم تعيين العلامة {@code AlignText} إلى true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| alignStrategy |  | عنصر SegmentAlignStrategy @see SegmentAlignStrategy |

### setAlignText {#setAlignText-boolean-}
```
public void setAlignText(boolean value)
```

تتحكم هذه العلامة في محاذاة النص في المستند المحول. بشكل افتراضي لا تؤثر عملية تحويل المستند على محاذاة النص وتترك النص كما هو. لكن في بعض الحالات يتسبب استبدال الخطوط في تداخل النص أو وجود مسافات إضافية في المستند المحول. عندما يتم تعيين هذه العلامة، سيتم تنفيذ عمليات محاذاة خاصة. يجب تعيين هذه العلامة فقط للمستندات التي تعاني من مشاكل تداخل النص أو مسافات نصية إضافية، لأن استخدام هذه العلامة يقلل من الأداء وقد يفسد محتوى النص في بعض الحالات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setAsyncImageStreamsConversionMode {#setAsyncImageStreamsConversionMode-boolean-}
```
public final void setAsyncImageStreamsConversionMode(boolean value)
```

يحصل/يضبط تشغيل تدفقات الصور في وضع غير المتزامن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setAutoTaggingSettings {#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-}
يحصل أو يضبط الإعدادات للوسم التلقائي أثناء تحويل تنسيق PDF. تُستخدم إعدادات الوسم التلقائي لتكوين سلوك عملية الوسم التلقائي، والتي تُستعمل عادةً لتحسين إمكانية الوصول وبنية مستند PDF أثناء التحويل إلى تنسيق PDF محدد.

### setConvertSoftMaskAction {#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-}
إجراء للصور ذات القناع الناعم.

### setErrorAction {#setErrorAction-com.aspose.pdf.ConvertErrorAction-}
إجراء للكائنات التي لا يمكن تحويلها.

### setExcludeFontsStrategy {#setExcludeFontsStrategy-byte-}
```
public void setExcludeFontsStrategy(byte value)
```

استراتيجية (استراتيجيات) لاستبعاد الخطوط الزائدة وتقليل حجم ملف المستند. هذا المعامل ذو معنى فقط عندما يتم تعيين العلامة {@code OptimizeFileSize} إلى true. بشكل افتراضي يتم استخدام مجموعة الاستراتيجيات {@code SubsetFonts} و {@code RemoveDuplicatedFonts}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setFormat {#setFormat-com.aspose.pdf.PdfFormat-}
تنسيق PDF.

### setIccProfileFileName {#setIccProfileFileName-java.lang.String-}
يضبط اسم ملف تعريف icc. في حالة كون القيمة null يتم استخدام ملف تعريف icc الافتراضي.

### setLogFileName {#setLogFileName-java.lang.String-}
المسار إلى الملف حيث سيتم تخزين التعليقات.

### setLogStream {#setLogStream-java.io.OutputStream-}
الدفق حيث سيتم تخزين التعليقات.

### setLowMemoryMode {#setLowMemoryMode-boolean-}
```
public void setLowMemoryMode(boolean value)
```

هل تم تمكين وضع التحويل منخفض الذاكرة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setOptimizeFileSize {#setOptimizeFileSize-boolean-}
```
public void setOptimizeFileSize(boolean value)
```

يضبط علامة تمكّن/تعطّل وضع التحويل الخاص للحصول على مستند PDF/A بحجم ملف أصغر. الآن تؤثر هذه العلامة على تحسين الخطوط المستخدمة في مستند PDF، وربما في المستقبل ستُستخدم هذه العلامة لتفعيل تحسين هياكل بيانات أخرى، مثل الرسومات. مجموعة هذه العلامة والوضع يمكن أن تقلل بشكل كبير حجم الملف ولكن في الوقت نفسه قد تقلل بشكل كبير من أداء التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setOutputIntent {#setOutputIntent-com.aspose.pdf.OutputIntent-}
يحصل أو يضبط {@link OutputIntent} لتحويل صيغة PDF. الـ {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) يحدد جهاز الإخراج المقصود أو الحالة التي يُجهّز من أجلها مستند PDF. يُستخدم لضمان أن الألوان في المستند تُعرض بشكل صحيح على الجهاز الهدف.

### setPageByPageFontProcess {#setPageByPageFontProcess-boolean-}
```
public void setPageByPageFontProcess(boolean b)
```

ضبط وضع تحليل الخط على أساس كل صفحة مفعّل. القيمة الافتراضية = false

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| b |  | قيمة منطقية |

### setPuaTextProcessingStrategy {#setPuaTextProcessingStrategy-int-}
```
public void setPuaTextProcessingStrategy(int value)
```

استراتيجية لمعالجة الرموز من منطقة الاستخدام الخاص في Unicode (PUA).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر PuaProcessingStrategy @see PuaProcessingStrategy |

### setSymbolicFontEncodingStrategy {#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-}
استراتيجية لنسخ بيانات الترميز للخطوط الرمزية إذا كان الخط TrueType الرمزي يحتوي على أكثر من جدول ترميز فرعي.

### setTransferInfo {#setTransferInfo-boolean-}
```
public final void setTransferInfo(boolean value)
```

يحصل أو يضبط ما إذا كان سيتم نقل البيانات من Info إلى Metadata عند التحويل إلى PDF 2.0. True بشكل افتراضي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setTransparencyAction {#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-}
إجراء للكائنات ذات القناع الصوري.

### setTransparencyIgnore {#setTransparencyIgnore-boolean-}
```
public void setTransparencyIgnore(boolean value)
```

القيمة الافتراضية FALSE وسيتم معالجة لون الشفافية للحفاظ على مظهر المستند. عند القيمة TRUE سيتم تحويل لون الشفافية إلى غير شفاف، وقد يتم تغطية بعض الكائنات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setTransparencyResolution {#setTransparencyResolution-int-}
```
public void setTransparencyResolution(int dpi)
```

يضبط الدقة أثناء تحويل الصور الشفافة. كلما ارتفعت الدقة، كلما كان سرعة التحويل أبطأ. القيمة الافتراضية هي 300.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dpi |  | قيمة الدقة |

### setUnicodeProcessingRules {#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-}
قواعد لحل المشكلات مع تخطيط Unicode. يمكن أن تكون null.
