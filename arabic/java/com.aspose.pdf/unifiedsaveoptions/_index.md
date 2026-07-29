---
title: "UnifiedSaveOptions"
linktitle: "UnifiedSaveOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "هذه الفئة تمثل خيارات الحفظ التي تستخدم طريقة تحويل موحدة (مع نموذج مستند داخلي موحد)."
type: docs
weight: 5420
url: /ar/java/com.aspose.pdf/unifiedsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions

```
public class UnifiedSaveOptions extends SaveOptions
```

هذه الفئة تمثل خيارات الحفظ التي تستخدم طريقة تحويل موحدة (مع نموذج مستند داخلي موحد).

## الحقول

| حقل | الوصف |
| --- | --- |
| [IsMultiThreading](#IsMultiThreading) | معالجة الصفحات في عدة خيوط. |

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [UnifiedSaveOptions](#UnifiedSaveOptions--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getProgressEventsRetranslator](#getProgressEventsRetranslator--) | يمثل معالج أحداث التقدم الداخلي الذي يعمل أثناء التحويل ويترجم أحداث التحويل لمراحل التحويل الداخلية إلى أحداث تقدم إجمالية خارجية. كما أن الفئة تُبث الأحداث التي تسمح بتحرير الموارد التي لم تعد مطلوبة. تتعامل هذه الفئة الداخلية مع أحداث تقدم التحويل من PDF إلى APS ومن APS إلى [Other format] لحساب التقدم الإجمالي وإبلاغ شفرة العميل بذلك. تستخدم هذه الفئة نوعين من الأحداث: تحويل نموذج ApsToExternal وأحداث تحويل PDF إلى APS لتوليد أحداث التقدم الإجمالي. يحتوي التصدير على ثلاث مراحل: 1) PDF إلى APS 2) التعرف على APS 3) تصدير APS إلى تنسيق الهدف. يسمح المُنشئ بضبط عدد الصفحات التي يتم تحويلها وما هو الجزء التقريبي لهذه أو تلك المرحلة في التقدم الإجمالي. |
| [isExtractOcrSublayerOnly](#isExtractOcrSublayerOnly--) | يُفعّل هذا السمة وظيفة استخراج الصورة أو النص من مستندات PDF مع طبقة OCR الفرعية. القيمة: {@code true} سيتم استخراج النص في المستند الناتج؛ وإلا {@code false}. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | أحيانًا تحتوي ملفات PDF على صور خلفية (لصفحات أو خلايا جدول) مُنشأة من عدة صور خلفية متكررة موضوعة بجوار بعضها. في مثل هذه الحالة، قد تُنشئ عارضات تنسيقات الهدف (مثلاً MsWord لتنسيق DOCS) حدودًا مرئية بين أجزاء صور الخلفية، بسبب اختلاف تقنيات تنعيم حواف الصورة (مضاد التعرج) عن تلك المستخدمة في Acrobat Reader. إذا بدا أن المستند المُصدَّر يحتوي على مثل هذه الحدود المرئية بين أجزاء صور الخلفية المتشابهة، يرجى تجربة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب فيه. انتبه! عادةً ما يؤدي تحسين الجودة هذا إلى إبطاء التحويل بشكل كبير، لذا يرجى استخدام هذا الخيار فقط عندما يكون ضروريًا حقًا. |
| [setExtractOcrSublayerOnly](#setExtractOcrSublayerOnly-boolean-) | <p> هذه السمة تُفعِّل الوظيفة لاستخراج الصورة أو النص لمستندات PDF مع طبقة OCR الفرعية. </p>القيمة: {@code true} سيُستخرج النص في المستند الناتج؛ وإلا، {@code false}. <hr> القيمة الافتراضية == false |
| [setProgressEventsRetranslator](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | يمثل معالج أحداث التقدم الداخلي الذي يعمل أثناء التحويل ويترجم أحداث التحويل لمراحل التحويل الداخلية إلى أحداث تقدم إجمالية خارجية. كما أن الفئة تُبث الأحداث التي تسمح بتحرير الموارد التي لم تعد مطلوبة. تتعامل هذه الفئة الداخلية مع أحداث تقدم التحويل من PDF إلى APS ومن APS إلى [Other format] لحساب التقدم الإجمالي وإبلاغ شفرة العميل بذلك. تستخدم هذه الفئة نوعين من الأحداث: تحويل نموذج ApsToExternal وأحداث تحويل PDF إلى APS لتوليد أحداث التقدم الإجمالي. يحتوي التصدير على ثلاث مراحل: 1) PDF إلى APS 2) التعرف على APS 3) تصدير APS إلى تنسيق الهدف. يسمح المُنشئ بضبط عدد الصفحات التي يتم تحويلها وما هو الجزء التقريبي لهذه أو تلك المرحلة في التقدم الإجمالي. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | أحيانًا تحتوي ملفات PDF على صور خلفية (لصفحات أو خلايا جدول) مُنشأة من عدة صور خلفية متكررة موضوعة بجوار بعضها. في مثل هذه الحالة، قد تُنشئ عارضات تنسيقات الهدف (مثلاً MsWord لتنسيق DOCS) حدودًا مرئية بين أجزاء صور الخلفية، بسبب اختلاف تقنيات تنعيم حواف الصورة (مضاد التعرج) عن تلك المستخدمة في Acrobat Reader. إذا بدا أن المستند المُصدَّر يحتوي على مثل هذه الحدود المرئية بين أجزاء صور الخلفية المتشابهة، يرجى تجربة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب فيه. انتبه! عادةً ما يؤدي تحسين الجودة هذا إلى إبطاء التحويل بشكل كبير، لذا يرجى استخدام هذا الخيار فقط عندما يكون ضروريًا حقًا. |

### IsMultiThreading {#IsMultiThreading}
```
public boolean IsMultiThreading
```

معالجة الصفحات في عدة خيوط.

### UnifiedSaveOptions {#UnifiedSaveOptions--}
```
public UnifiedSaveOptions()
```



### getProgressEventsRetranslator {#getProgressEventsRetranslator--}
```
public com.aspose.pdf.ConversionProgressEventsTranslator getProgressEventsRetranslator()
```

يمثل معالج أحداث التقدم الداخلي الذي يعمل أثناء التحويل ويترجم أحداث التحويل لمراحل التحويل الداخلية إلى أحداث تقدم إجمالية خارجية. كما أن الفئة تُبث الأحداث التي تسمح بتحرير الموارد التي لم تعد مطلوبة. تتعامل هذه الفئة الداخلية مع أحداث تقدم التحويل من PDF إلى APS ومن APS إلى [Other format] لحساب التقدم الإجمالي وإبلاغ شفرة العميل بذلك. تستخدم هذه الفئة نوعين من الأحداث: تحويل نموذج ApsToExternal وأحداث تحويل PDF إلى APS لتوليد أحداث التقدم الإجمالي. يحتوي التصدير على ثلاث مراحل: 1) PDF إلى APS 2) التعرف على APS 3) تصدير APS إلى تنسيق الهدف. يسمح المُنشئ بضبط عدد الصفحات التي يتم تحويلها وما هو الجزء التقريبي لهذه أو تلك المرحلة في التقدم الإجمالي.

**Returns:**
مثيل ConversionProgressEventsTranslator

### isExtractOcrSublayerOnly {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```

يُفعّل هذا السمة وظيفة استخراج الصورة أو النص من مستندات PDF مع طبقة OCR الفرعية. القيمة: {@code true} سيتم استخراج النص في المستند الناتج؛ وإلا {@code false}.

**Returns:**
قيمة منطقية

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

أحيانًا تحتوي ملفات PDF على صور خلفية (لصفحات أو خلايا جدول) مُنشأة من عدة صور خلفية متكررة موضوعة بجوار بعضها. في مثل هذه الحالة، قد تُنشئ عارضات تنسيقات الهدف (مثلاً MsWord لتنسيق DOCS) حدودًا مرئية بين أجزاء صور الخلفية، بسبب اختلاف تقنيات تنعيم حواف الصورة (مضاد التعرج) عن تلك المستخدمة في Acrobat Reader. إذا بدا أن المستند المُصدَّر يحتوي على مثل هذه الحدود المرئية بين أجزاء صور الخلفية المتشابهة، يرجى تجربة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب فيه. انتبه! عادةً ما يؤدي تحسين الجودة هذا إلى إبطاء التحويل بشكل كبير، لذا يرجى استخدام هذا الخيار فقط عندما يكون ضروريًا حقًا.

**Returns:**
قيمة منطقية

### setExtractOcrSublayerOnly {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```

<p> هذه السمة تُفعِّل الوظيفة لاستخراج الصورة أو النص لمستندات PDF مع طبقة OCR الفرعية. </p>القيمة: {@code true} سيُستخرج النص في المستند الناتج؛ وإلا، {@code false}. <hr> القيمة الافتراضية == false

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setProgressEventsRetranslator {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
يمثل معالج أحداث التقدم الداخلي الذي يعمل أثناء التحويل ويترجم أحداث التحويل لمراحل التحويل الداخلية إلى أحداث تقدم إجمالية خارجية. كما أن الفئة تُبث الأحداث التي تسمح بتحرير الموارد التي لم تعد مطلوبة. تتعامل هذه الفئة الداخلية مع أحداث تقدم التحويل من PDF إلى APS ومن APS إلى [Other format] لحساب التقدم الإجمالي وإبلاغ شفرة العميل بذلك. تستخدم هذه الفئة نوعين من الأحداث: تحويل نموذج ApsToExternal وأحداث تحويل PDF إلى APS لتوليد أحداث التقدم الإجمالي. يحتوي التصدير على ثلاث مراحل: 1) PDF إلى APS 2) التعرف على APS 3) تصدير APS إلى تنسيق الهدف. يسمح المُنشئ بضبط عدد الصفحات التي يتم تحويلها وما هو الجزء التقريبي لهذه أو تلك المرحلة في التقدم الإجمالي.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

أحيانًا تحتوي ملفات PDF على صور خلفية (لصفحات أو خلايا جدول) مُنشأة من عدة صور خلفية متكررة موضوعة بجوار بعضها. في مثل هذه الحالة، قد تُنشئ عارضات تنسيقات الهدف (مثلاً MsWord لتنسيق DOCS) حدودًا مرئية بين أجزاء صور الخلفية، بسبب اختلاف تقنيات تنعيم حواف الصورة (مضاد التعرج) عن تلك المستخدمة في Acrobat Reader. إذا بدا أن المستند المُصدَّر يحتوي على مثل هذه الحدود المرئية بين أجزاء صور الخلفية المتشابهة، يرجى تجربة استخدام هذا الإعداد للتخلص من هذا التأثير غير المرغوب فيه. انتبه! عادةً ما يؤدي تحسين الجودة هذا إلى إبطاء التحويل بشكل كبير، لذا يرجى استخدام هذا الخيار فقط عندما يكون ضروريًا حقًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | قيمة منطقية |
