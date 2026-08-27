---
title: "SvgExtractionOptions"
linktitle: "SvgExtractionOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة خيارات لاستخراج الرسومات المتجهة من صفحة مستند PDF."
type: docs
weight: 30
url: /ar/java/com.aspose.pdf.vector.extraction/svgextractionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SvgExtractionOptions

```
public class SvgExtractionOptions extends Object
```

يمثل فئة خيارات لاستخراج الرسومات المتجهة من صفحة مستند PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SvgExtractionOptions](#SvgExtractionOptions--) | ينشئ مثيل فئة SvgExtractionOptions. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAutoGrouping](#getAutoGrouping--) | يحصل ويضبط الخيار لتجميع المسارات الفرعية تلقائيًا في صور. هذا الخيار يستثني خيار {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) |
| [getExtractEverySubPathToSvg](#getExtractEverySubPathToSvg--) | يحصل ويضبط الخيار لاستخراج كل مسار فرعي من مستند PDF إلى صور SVG منفصلة. |
| [getExtractionAreaBound](#getExtractionAreaBound--) | يحصل ويضبط المستطيل الحدودي الذي يحدد منطقة الاستخراج لاستخراج SVG. |
| [getGroupStrength](#getGroupStrength--) | يحصل ويضبط خيار قوة تجميع المسارات الفرعية في صور. يتيح لك تكوين درجة تجميع المسارات الفرعية. تتراوح القيمة من 0 إلى 1. القيمة 0 تعني تمكين خيار {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) . القيمة 1 ستنشئ صورة واحدة لجميع المسارات المتجهية في الصفحة. يكون لهذا الخيار تأثير عندما يكون {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) خاطئًا. القيمة الافتراضية هي {@code 0.8}. |
| [getMinStrokeWidth](#getMinStrokeWidth--) | يحصل أو يضبط الحد الأدنى لعرض الخط الذي سيُستخدم في SVG الناتج. إذا كان PDF يستخدم عرض خط أرق، فسيتم استبداله بهذا العرض. القيمة الافتراضية هي 0.5. تُعبّر القيمة بوحدات مساحة المستخدم المحوّلة لصفحة PDF المحوّلة. بشكل افتراضي، وحدة مساحة المستخدم واحدة تساوي 1/72 بوصة (0.35 مم)، لكن يمكن أن يتجاوزها مستند PDF. يمكن للتحويلات أن تؤثر على الحد الأدنى الفعلي للعرض في SVG المُولَّد. |
| [getStrictExtractionAreaBoundCheck](#getStrictExtractionAreaBoundCheck--) | يحصل ويضبط خيارًا لتحديد ما إذا كان يتم فحص ما إذا كانت المسارات الفرعية داخل المستطيل المحدد في {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). إذا تم تعيينه إلى false، فستُستخرج المسارات الفرعية التي ليست مشمولة بالكامل في {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). القيمة الافتراضية هي {@code True}. |
| [getUnpackPageContentXForm](#getUnpackPageContentXForm--) | يحصل ويضبط علامة تحدد ما إذا كان يجب فك ضغط XFrom الموجود على الصفحات أم لا. يمكن أن تنتهي عناصر XFrom في ملفات SVG مختلفة. يتم فك ضغط XForms التي يتم عرضها بواسطة عبارات Do من محتوى الصفحة فقط. لا يتم فك ضغط XForms المتداخلة. |
| [getUnpackXFormPredicate](#getUnpackXFormPredicate--) | يحصل ويضبط خيارًا لفك ضغط XForm فقط المتطابق مع الشرط المحدد. |
| [setAutoGrouping](#setAutoGrouping-boolean-) | يحصل ويضبط الخيار لتجميع المسارات الفرعية تلقائيًا في صور. هذا الخيار يستثني خيار {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)}) |
| [setExtractEverySubPathToSvg](#setExtractEverySubPathToSvg-boolean-) | يحصل ويضبط الخيار لاستخراج كل مسار فرعي من مستند PDF إلى صور SVG منفصلة. |
| [setExtractionAreaBound](#setExtractionAreaBound-com.aspose.pdf.Rectangle-) | يحصل ويضبط المستطيل الحدودي الذي يحدد منطقة الاستخراج لاستخراج SVG. |
| [setGroupStrength](#setGroupStrength-double-) | يحصل ويضبط خيار قوة تجميع المسارات الفرعية في صور. يتيح لك تكوين درجة تجميع المسارات الفرعية. تتراوح القيمة من 0 إلى 1. القيمة 0 تعني تمكين خيار {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) . القيمة 1 ستنشئ صورة واحدة لجميع المسارات المتجهية في الصفحة. يكون لهذا الخيار تأثير عندما يكون {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) خاطئًا. القيمة الافتراضية هي {@code 0.8}. |
| [setMinStrokeWidth](#setMinStrokeWidth-double-) | يحصل أو يضبط الحد الأدنى لعرض الخط الذي سيُستخدم في SVG الناتج. إذا كان PDF يستخدم عرض خط أرق، فسيتم استبداله بهذا العرض. القيمة الافتراضية هي 0.5. تُعبّر القيمة بوحدات مساحة المستخدم المحوّلة لصفحة PDF المحوّلة. بشكل افتراضي، وحدة مساحة المستخدم واحدة تساوي 1/72 بوصة (0.35 مم)، لكن يمكن أن يتجاوزها مستند PDF. يمكن للتحويلات أن تؤثر على الحد الأدنى الفعلي للعرض في SVG المُولَّد. |
| [setStrictExtractionAreaBoundCheck](#setStrictExtractionAreaBoundCheck-boolean-) | يحصل ويضبط خيارًا لتحديد ما إذا كان يتم فحص ما إذا كانت المسارات الفرعية داخل المستطيل المحدد في {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). إذا تم تعيينه إلى false، فستُستخرج المسارات الفرعية التي ليست مشمولة بالكامل في {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). القيمة الافتراضية هي {@code True}. |
| [setUnpackPageContentXForm](#setUnpackPageContentXForm-boolean-) | يحصل ويضبط علامة تحدد ما إذا كان يجب فك ضغط XFrom الموجود على الصفحات أم لا. يمكن أن تنتهي عناصر XFrom في ملفات SVG مختلفة. يتم فك ضغط XForms التي يتم عرضها بواسطة عبارات Do من محتوى الصفحة فقط. لا يتم فك ضغط XForms المتداخلة. |
| [setUnpackXFormPredicate](#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-) | يحصل ويضبط خيارًا لفك ضغط XForm فقط المتطابق مع الشرط المحدد. |

### SvgExtractionOptions {#SvgExtractionOptions--}
```
public SvgExtractionOptions()
```

ينشئ مثيل فئة SvgExtractionOptions.

### getAutoGrouping {#getAutoGrouping--}
```
public final boolean getAutoGrouping()
```

يحصل ويضبط الخيار لتجميع المسارات الفرعية تلقائيًا في صور. هذا الخيار يستثني خيار {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)})

**Returns:**
قيمة منطقية

### getExtractEverySubPathToSvg {#getExtractEverySubPathToSvg--}
```
public final boolean getExtractEverySubPathToSvg()
```

يحصل ويضبط الخيار لاستخراج كل مسار فرعي من مستند PDF إلى صور SVG منفصلة.

**Returns:**
قيمة منطقية

### getExtractionAreaBound {#getExtractionAreaBound--}
```
public final Rectangle getExtractionAreaBound()
```

يحصل ويضبط المستطيل الحدودي الذي يحدد منطقة الاستخراج لاستخراج SVG.

**Returns:**
مثيل Rectangle

### getGroupStrength {#getGroupStrength--}
```
public final double getGroupStrength()
```

يحصل ويضبط خيار قوة تجميع المسارات الفرعية في صور. يتيح لك تكوين درجة تجميع المسارات الفرعية. تتراوح القيمة من 0 إلى 1. القيمة 0 تعني تمكين خيار {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) . القيمة 1 ستنشئ صورة واحدة لجميع المسارات المتجهية في الصفحة. يكون لهذا الخيار تأثير عندما يكون {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) خاطئًا. القيمة الافتراضية هي {@code 0.8}.

**Returns:**
قيمة double

### getMinStrokeWidth {#getMinStrokeWidth--}
```
public final double getMinStrokeWidth()
```

يحصل أو يضبط الحد الأدنى لعرض الخط الذي سيُستخدم في SVG الناتج. إذا كان PDF يستخدم عرض خط أرق، فسيتم استبداله بهذا العرض. القيمة الافتراضية هي 0.5. تُعبّر القيمة بوحدات مساحة المستخدم المحوّلة لصفحة PDF المحوّلة. بشكل افتراضي، وحدة مساحة المستخدم واحدة تساوي 1/72 بوصة (0.35 مم)، لكن يمكن أن يتجاوزها مستند PDF. يمكن للتحويلات أن تؤثر على الحد الأدنى الفعلي للعرض في SVG المُولَّد.

**Returns:**
قيمة double

### getStrictExtractionAreaBoundCheck {#getStrictExtractionAreaBoundCheck--}
```
public final boolean getStrictExtractionAreaBoundCheck()
```

يحصل ويضبط خيارًا لتحديد ما إذا كان يتم فحص ما إذا كانت المسارات الفرعية داخل المستطيل المحدد في {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). إذا تم تعيينه إلى false، فستُستخرج المسارات الفرعية التي ليست مشمولة بالكامل في {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). القيمة الافتراضية هي {@code True}.

**Returns:**
قيمة منطقية

### getUnpackPageContentXForm {#getUnpackPageContentXForm--}
```
public final boolean getUnpackPageContentXForm()
```

يحصل ويضبط علامة تحدد ما إذا كان يجب فك ضغط XFrom الموجود على الصفحات أم لا. يمكن أن تنتهي عناصر XFrom في ملفات SVG مختلفة. يتم فك ضغط XForms التي يتم عرضها بواسطة عبارات Do من محتوى الصفحة فقط. لا يتم فك ضغط XForms المتداخلة.

**Returns:**
قيمة منطقية

### getUnpackXFormPredicate {#getUnpackXFormPredicate--}
```
public final com.aspose.ms.System.Predicate< XFormPlacement > getUnpackXFormPredicate()
```

يحصل ويضبط خيارًا لفك ضغط XForm فقط المتطابق مع الشرط المحدد.

**Returns:**
مثيل Predicate داخلي من مثيل XFormPlacement

### setAutoGrouping {#setAutoGrouping-boolean-}
```
public final void setAutoGrouping(boolean value)
```

يحصل ويضبط الخيار لتجميع المسارات الفرعية تلقائيًا في صور. هذا الخيار يستثني خيار {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.GroupStrengthGroupStrength}({@link #getGroupStrength}/{@link #setGroupStrength(double)})

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setExtractEverySubPathToSvg {#setExtractEverySubPathToSvg-boolean-}
```
public final void setExtractEverySubPathToSvg(boolean value)
```

يحصل ويضبط الخيار لاستخراج كل مسار فرعي من مستند PDF إلى صور SVG منفصلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setExtractionAreaBound {#setExtractionAreaBound-com.aspose.pdf.Rectangle-}
يحصل ويضبط المستطيل الحدودي الذي يحدد منطقة الاستخراج لاستخراج SVG.

### setGroupStrength {#setGroupStrength-double-}
```
public final void setGroupStrength(double value)
```

يحصل ويضبط خيار قوة تجميع المسارات الفرعية في صور. يتيح لك تكوين درجة تجميع المسارات الفرعية. تتراوح القيمة من 0 إلى 1. القيمة 0 تعني تمكين خيار {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractEverySubPathToSvgExtractEverySubPathToSvg}({@link #getExtractEverySubPathToSvg}/{@link #setExtractEverySubPathToSvg(boolean)}) . القيمة 1 ستنشئ صورة واحدة لجميع المسارات المتجهية في الصفحة. يكون لهذا الخيار تأثير عندما يكون {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.AutoGroupingAutoGrouping}({@link #getAutoGrouping}/{@link #setAutoGrouping(boolean)}) خاطئًا. القيمة الافتراضية هي {@code 0.8}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setMinStrokeWidth {#setMinStrokeWidth-double-}
```
public final void setMinStrokeWidth(double value)
```

يحصل أو يضبط الحد الأدنى لعرض الخط الذي سيُستخدم في SVG الناتج. إذا كان PDF يستخدم عرض خط أرق، فسيتم استبداله بهذا العرض. القيمة الافتراضية هي 0.5. تُعبّر القيمة بوحدات مساحة المستخدم المحوّلة لصفحة PDF المحوّلة. بشكل افتراضي، وحدة مساحة المستخدم واحدة تساوي 1/72 بوصة (0.35 مم)، لكن يمكن أن يتجاوزها مستند PDF. يمكن للتحويلات أن تؤثر على الحد الأدنى الفعلي للعرض في SVG المُولَّد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة double |

### setStrictExtractionAreaBoundCheck {#setStrictExtractionAreaBoundCheck-boolean-}
```
public final void setStrictExtractionAreaBoundCheck(boolean value)
```

يحصل ويضبط خيارًا لتحديد ما إذا كان يتم فحص ما إذا كانت المسارات الفرعية داخل المستطيل المحدد في {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). إذا تم تعيينه إلى false، فستُستخرج المسارات الفرعية التي ليست مشمولة بالكامل في {@code Aspose.Pdf.Vector.Extraction.SvgExtractionOptions.ExtractionAreaBoundExtractionAreaBound}({@link #getExtractionAreaBound}/{@link #setExtractionAreaBound(Rectangle)}). القيمة الافتراضية هي {@code True}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setUnpackPageContentXForm {#setUnpackPageContentXForm-boolean-}
```
public final void setUnpackPageContentXForm(boolean value)
```

يحصل ويضبط علامة تحدد ما إذا كان يجب فك ضغط XFrom الموجود على الصفحات أم لا. يمكن أن تنتهي عناصر XFrom في ملفات SVG مختلفة. يتم فك ضغط XForms التي يتم عرضها بواسطة عبارات Do من محتوى الصفحة فقط. لا يتم فك ضغط XForms المتداخلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setUnpackXFormPredicate {#setUnpackXFormPredicate-com.aspose.ms.System.Predicate-}
يحصل ويضبط خيارًا لفك ضغط XForm فقط المتطابق مع الشرط المحدد.
