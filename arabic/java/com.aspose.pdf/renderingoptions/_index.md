---
title: "RenderingOptions"
linktitle: "RenderingOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خيارات العرض."
type: docs
weight: 4150
url: /ar/java/com.aspose.pdf/renderingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.RenderingOptions

```
public final class RenderingOptions extends Object
```

يمثل خيارات العرض.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RenderingOptions](#RenderingOptions--) | يُنشئ مثيلًا جديدًا لكائن {@code RenderingOptions}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAnalyzeFonts](#getAnalyzeFonts--) | يستبدل الخطوط حسب الحاجة لضمان إمكانية عرض جميع الأحرف في النص. يتبع خوارزمية استبدال الخطوط الخطوات التالية: 1. إذا قام المستخدم بتعيين خاصية DefaultFontName صراحةً، تحقق مما إذا كان الخط المحدد يمكنه عرض الأحرف المطلوبة. 2. إذا لم يتم تعيين خط من قبل المستخدم، ابحث عبر الخطوط المضافة عبر {@code FontRepository.Sources}. 3. حلل النص لتحديد أبجديته أو خطه واقترح أسماء الخطوط وفقًا لذلك. حاول العثور على هذه الخطوط واستخدامها من النظام. 4. كخيار احتياطي، ابحث في النظام عن أي خط قادر على عرض الأحرف المطلوبة. |
| [getBarcodeOptimization](#getBarcodeOptimization--) | يحصل على وضع تحسين الباركود. |
| [getConvertFontsToUnicodeTTF](#getConvertFontsToUnicodeTTF--) | يشير إلى أن جميع الخطوط سيتم تحويلها إلى إصدارات TTF يونيكود. هذا مفيد لأسباب التوافق ولتحسين استخدام الخطوط، لأن كل خط TTF جديد سيحتوي ليس على جميع الرموز من الخط الأصلي، بل فقط الرموز المستخدمة في النص. |
| [getDefaultFontName](#getDefaultFontName--) | يحصل/يضبط الاسم الافتراضي للخط المستخدم كبديل للخطوط المفقودة. |
| [getHeightExtraUnits](#getHeightExtraUnits--) | يحصل أو يضبط قيمة تُستخدم لزيادة أو تقليل عرض المستطيل لمُعامل AppendRectangle. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | يحصل أو يضبط الإشارة إلى أنه سيتم تجاهل الأخطاء المتعلقة بغياب الخط. true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false افتراضيًا |
| [getInterpolationHighQuality](#getInterpolationHighQuality--) | يحصل أو يضبط وضع الجودة العالية للتقريب. |
| [getMaxFontsCacheSize](#getMaxFontsCacheSize--) | الحد الأقصى لعدد الخطوط في ذاكرة التخزين المؤقت للخطوط. القيمة الافتراضية هي 10. |
| [getMaxSymbolsCacheSize](#getMaxSymbolsCacheSize--) | الحد الأقصى لعدد الرموز في ذاكرة التخزين المؤقت للرموز. القيمة الافتراضية هي 100. |
| [getOptimizeDimensions](#getOptimizeDimensions--) | يحصل أو يضبط وضع تحسين الأبعاد. |
| [getScaleImagesToFitPageWidth](#getScaleImagesToFitPageWidth--) | يحصل أو يعيّن قيمة تُستخدم لتكبير جميع الصور على الصفحة لتناسب عرض الصفحة. |
| [getSystemFontsNativeRendering](#getSystemFontsNativeRendering--) | يحصل على وضع يتم فيه عرض خطوط النظام أصليًا |
| [getUseFontHinting](#getUseFontHinting--) | استخدام هذه العلامة يُفعّل آلية تحسين الخطوط. تحسين الخطوط هو استخدام تعليمات رياضية لضبط عرض الخط الخارجي. في بعض الحالات قد يحل تشغيل هذه العلامة مشاكل وضوح النص. في الوقت الحالي قد يؤثر استخدام هذه العلامة فقط على خطوط TTF إذا تم استخدام هذه الخطوط في المستند الأصلي. |
| [getUseNewImagingEngine](#getUseNewImagingEngine--) | يحصل على علامة تحدد ما إذا كان محرك التصوير الجديد يُستخدم أم لا. |
| [getWidthExtraUnits](#getWidthExtraUnits--) | يحصل أو يضبط قيمة تُستخدم لزيادة أو تقليل عرض المستطيل لمُعامل AppendRectangle. |
| [isTryToSkipDocumentErrors](#isTryToSkipDocumentErrors--) | يحصل على قيمة تُستخدم لتجاوز الأخطاء أثناء معالجة ملف PDF |
| [setAnalyzeFonts](#setAnalyzeFonts-boolean-) | يستبدل الخطوط حسب الحاجة لضمان إمكانية عرض جميع الأحرف في النص. يتبع خوارزمية استبدال الخطوط الخطوات التالية: 1. إذا قام المستخدم بتعيين خاصية DefaultFontName صراحةً، تحقق مما إذا كان الخط المحدد يمكنه عرض الأحرف المطلوبة. 2. إذا لم يتم تعيين خط من قبل المستخدم، ابحث عبر الخطوط المضافة عبر {@code FontRepository.Sources}. 3. حلل النص لتحديد أبجديته أو خطه واقترح أسماء الخطوط وفقًا لذلك. حاول العثور على هذه الخطوط واستخدامها من النظام. 4. كخيار احتياطي، ابحث في النظام عن أي خط قادر على عرض الأحرف المطلوبة. |
| [setBarcodeOptimization](#setBarcodeOptimization-boolean-) | يضبط وضع تحسين الباركود. |
| [setConvertFontsToUnicodeTTF](#setConvertFontsToUnicodeTTF-boolean-) | يشير إلى أن جميع الخطوط سيتم تحويلها إلى إصدارات TTF يونيكود. هذا مفيد لأسباب التوافق ولتحسين استخدام الخطوط، لأن كل خط TTF جديد سيحتوي ليس على جميع الرموز من الخط الأصلي، بل فقط الرموز المستخدمة في النص. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | يحصل/يضبط الاسم الافتراضي للخط المستخدم كبديل للخطوط المفقودة. |
| [setHeightExtraUnits](#setHeightExtraUnits-float-) | يحصل أو يضبط قيمة تُستخدم لزيادة أو تقليل عرض المستطيل لمُعامل AppendRectangle. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | يحصل أو يضبط الإشارة إلى أنه سيتم تجاهل الأخطاء المتعلقة بغياب الخط. true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false افتراضيًا |
| [setInterpolationHighQuality](#setInterpolationHighQuality-boolean-) | يحصل أو يضبط وضع الجودة العالية للتقريب. |
| [setMaxFontsCacheSize](#setMaxFontsCacheSize-int-) | الحد الأقصى لعدد الخطوط في ذاكرة التخزين المؤقت للخطوط. القيمة الافتراضية هي 10. |
| [setMaxSymbolsCacheSize](#setMaxSymbolsCacheSize-int-) | الحد الأقصى لعدد الرموز في ذاكرة التخزين المؤقت للرموز. القيمة الافتراضية هي 100. |
| [setOptimizeDimensions](#setOptimizeDimensions-boolean-) | يحصل أو يضبط وضع تحسين الأبعاد. |
| [setScaleImagesToFitPageWidth](#setScaleImagesToFitPageWidth-boolean-) | يحصل أو يعيّن قيمة تُستخدم لتكبير جميع الصور على الصفحة لتناسب عرض الصفحة. |
| [setSystemFontsNativeRendering](#setSystemFontsNativeRendering-boolean-) | يضبط وضع يتم فيه عرض خطوط النظام أصليًا |
| [setTryToSkipDocumentErrors](#setTryToSkipDocumentErrors-boolean-) | يضبط قيمة تُستخدم لتجاوز الأخطاء أثناء معالجة ملف PDF |
| [setUseFontHinting](#setUseFontHinting-boolean-) | استخدام هذه العلامة يُفعّل آلية تحسين الخطوط. تحسين الخطوط هو استخدام تعليمات رياضية لضبط عرض الخط الخارجي. في بعض الحالات قد يحل تشغيل هذه العلامة مشاكل وضوح النص. في الوقت الحالي قد يؤثر استخدام هذه العلامة فقط على خطوط TTF إذا تم استخدام هذه الخطوط في المستند الأصلي. |
| [setUseNewImagingEngine](#setUseNewImagingEngine-boolean-) | يضبط علامة تحدد ما إذا كان محرك التصوير الجديد يُستخدم أم لا. |
| [setWidthExtraUnits](#setWidthExtraUnits-float-) | يحصل أو يضبط قيمة تُستخدم لزيادة أو تقليل عرض المستطيل لمُعامل AppendRectangle. |

### RenderingOptions {#RenderingOptions--}
```
public RenderingOptions()
```

يُنشئ مثيلًا جديدًا لكائن {@code RenderingOptions}.

### getAnalyzeFonts {#getAnalyzeFonts--}
```
public final boolean getAnalyzeFonts()
```

يستبدل الخطوط حسب الحاجة لضمان إمكانية عرض جميع الأحرف في النص. يتبع خوارزمية استبدال الخطوط الخطوات التالية: 1. إذا قام المستخدم بتعيين خاصية DefaultFontName صراحةً، تحقق مما إذا كان الخط المحدد يمكنه عرض الأحرف المطلوبة. 2. إذا لم يتم تعيين خط من قبل المستخدم، ابحث عبر الخطوط المضافة عبر {@code FontRepository.Sources}. 3. حلل النص لتحديد أبجديته أو خطه واقترح أسماء الخطوط وفقًا لذلك. حاول العثور على هذه الخطوط واستخدامها من النظام. 4. كخيار احتياطي، ابحث في النظام عن أي خط قادر على عرض الأحرف المطلوبة.

**Returns:**
قيمة منطقية

### getBarcodeOptimization {#getBarcodeOptimization--}
```
public boolean getBarcodeOptimization()
```

يحصل على وضع تحسين الباركود.

**Returns:**
قيمة منطقية

### getConvertFontsToUnicodeTTF {#getConvertFontsToUnicodeTTF--}
```
public boolean getConvertFontsToUnicodeTTF()
```

يشير إلى أن جميع الخطوط سيتم تحويلها إلى إصدارات TTF يونيكود. هذا مفيد لأسباب التوافق ولتحسين استخدام الخطوط، لأن كل خط TTF جديد سيحتوي ليس على جميع الرموز من الخط الأصلي، بل فقط الرموز المستخدمة في النص.

**Returns:**
قيمة منطقية

### getDefaultFontName {#getDefaultFontName--}
```
public final String getDefaultFontName()
```

يحصل/يضبط الاسم الافتراضي للخط المستخدم كبديل للخطوط المفقودة.

**Returns:**
قيمة سلسلة

### getHeightExtraUnits {#getHeightExtraUnits--}
```
public final float getHeightExtraUnits()
```

يحصل أو يضبط قيمة تُستخدم لزيادة أو تقليل عرض المستطيل لمُعامل AppendRectangle.

**Returns:**
قيمة عائمة

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

يحصل أو يضبط الإشارة إلى أنه سيتم تجاهل الأخطاء المتعلقة بغياب الخط. true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false افتراضيًا

**Returns:**
قيمة منطقية

### getInterpolationHighQuality {#getInterpolationHighQuality--}
```
public boolean getInterpolationHighQuality()
```

يحصل أو يضبط وضع الجودة العالية للتقريب.

**Returns:**
قيمة منطقية

### getMaxFontsCacheSize {#getMaxFontsCacheSize--}
```
public int getMaxFontsCacheSize()
```

الحد الأقصى لعدد الخطوط في ذاكرة التخزين المؤقت للخطوط. القيمة الافتراضية هي 10.

**Returns:**
قيمة int

### getMaxSymbolsCacheSize {#getMaxSymbolsCacheSize--}
```
public int getMaxSymbolsCacheSize()
```

الحد الأقصى لعدد الرموز في ذاكرة التخزين المؤقت للرموز. القيمة الافتراضية هي 100.

**Returns:**
قيمة int

### getOptimizeDimensions {#getOptimizeDimensions--}
```
public final boolean getOptimizeDimensions()
```

يحصل أو يضبط وضع تحسين الأبعاد.

**Returns:**
قيمة منطقية

### getScaleImagesToFitPageWidth {#getScaleImagesToFitPageWidth--}
```
@Deprecated public final boolean getScaleImagesToFitPageWidth()
```

يحصل أو يعيّن قيمة تُستخدم لتكبير جميع الصور على الصفحة لتناسب عرض الصفحة.

**Returns:**
قيمة منطقية @deprecated ScaleImagesToFitPageWidth تم إهمالها.

### getSystemFontsNativeRendering {#getSystemFontsNativeRendering--}
```
public boolean getSystemFontsNativeRendering()
```

يحصل على وضع يتم فيه عرض خطوط النظام أصليًا

**Returns:**
قيمة منطقية

### getUseFontHinting {#getUseFontHinting--}
```
public boolean getUseFontHinting()
```

استخدام هذه العلامة يُفعّل آلية تحسين الخطوط. تحسين الخطوط هو استخدام تعليمات رياضية لضبط عرض الخط الخارجي. في بعض الحالات قد يحل تشغيل هذه العلامة مشاكل وضوح النص. في الوقت الحالي قد يؤثر استخدام هذه العلامة فقط على خطوط TTF إذا تم استخدام هذه الخطوط في المستند الأصلي.

**Returns:**
قيمة منطقية

### getUseNewImagingEngine {#getUseNewImagingEngine--}
```
@Deprecated public boolean getUseNewImagingEngine()
```

يحصل على علامة تحدد ما إذا كان محرك التصوير الجديد يُستخدم أم لا.

**Returns:**
قيمة منطقية @deprecated UseNewImagingEngine تم إهمالها

### getWidthExtraUnits {#getWidthExtraUnits--}
```
public float getWidthExtraUnits()
```

يحصل أو يضبط قيمة تُستخدم لزيادة أو تقليل عرض المستطيل لمُعامل AppendRectangle.

**Returns:**
قيمة عائمة

### isTryToSkipDocumentErrors {#isTryToSkipDocumentErrors--}
```
public boolean isTryToSkipDocumentErrors()
```

يحصل على قيمة تُستخدم لتجاوز الأخطاء أثناء معالجة ملف PDF

**Returns:**
قيمة منطقية

### setAnalyzeFonts {#setAnalyzeFonts-boolean-}
```
public final void setAnalyzeFonts(boolean value)
```

يستبدل الخطوط حسب الحاجة لضمان إمكانية عرض جميع الأحرف في النص. يتبع خوارزمية استبدال الخطوط الخطوات التالية: 1. إذا قام المستخدم بتعيين خاصية DefaultFontName صراحةً، تحقق مما إذا كان الخط المحدد يمكنه عرض الأحرف المطلوبة. 2. إذا لم يتم تعيين خط من قبل المستخدم، ابحث عبر الخطوط المضافة عبر {@code FontRepository.Sources}. 3. حلل النص لتحديد أبجديته أو خطه واقترح أسماء الخطوط وفقًا لذلك. حاول العثور على هذه الخطوط واستخدامها من النظام. 4. كخيار احتياطي، ابحث في النظام عن أي خط قادر على عرض الأحرف المطلوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setBarcodeOptimization {#setBarcodeOptimization-boolean-}
```
public void setBarcodeOptimization(boolean value)
```

يضبط وضع تحسين الباركود.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setConvertFontsToUnicodeTTF {#setConvertFontsToUnicodeTTF-boolean-}
```
public void setConvertFontsToUnicodeTTF(boolean value)
```

يشير إلى أن جميع الخطوط سيتم تحويلها إلى إصدارات TTF يونيكود. هذا مفيد لأسباب التوافق ولتحسين استخدام الخطوط، لأن كل خط TTF جديد سيحتوي ليس على جميع الرموز من الخط الأصلي، بل فقط الرموز المستخدمة في النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
يحصل/يضبط الاسم الافتراضي للخط المستخدم كبديل للخطوط المفقودة.

### setHeightExtraUnits {#setHeightExtraUnits-float-}
```
public final void setHeightExtraUnits(float value)
```

يحصل أو يضبط قيمة تُستخدم لزيادة أو تقليل عرض المستطيل لمُعامل AppendRectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

يحصل أو يضبط الإشارة إلى أنه سيتم تجاهل الأخطاء المتعلقة بغياب الخط. true - يعني أن أخطاء غياب الخط سيتم تجاهلها. سيتم تخطي مقاطع النص التي تشير إلى موارد غير صحيحة أثناء المعالجة. false افتراضيًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setInterpolationHighQuality {#setInterpolationHighQuality-boolean-}
```
public void setInterpolationHighQuality(boolean value)
```

يحصل أو يضبط وضع الجودة العالية للتقريب.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMaxFontsCacheSize {#setMaxFontsCacheSize-int-}
```
public void setMaxFontsCacheSize(int value)
```

الحد الأقصى لعدد الخطوط في ذاكرة التخزين المؤقت للخطوط. القيمة الافتراضية هي 10.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setMaxSymbolsCacheSize {#setMaxSymbolsCacheSize-int-}
```
public void setMaxSymbolsCacheSize(int value)
```

الحد الأقصى لعدد الرموز في ذاكرة التخزين المؤقت للرموز. القيمة الافتراضية هي 100.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setOptimizeDimensions {#setOptimizeDimensions-boolean-}
```
public final void setOptimizeDimensions(boolean value)
```

يحصل أو يضبط وضع تحسين الأبعاد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setScaleImagesToFitPageWidth {#setScaleImagesToFitPageWidth-boolean-}
```
@Deprecated public final void setScaleImagesToFitPageWidth(boolean value)
```

يحصل أو يعيّن قيمة تُستخدم لتكبير جميع الصور على الصفحة لتناسب عرض الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية @deprecated ScaleImagesToFitPageWidth تم إهمالها. |

### setSystemFontsNativeRendering {#setSystemFontsNativeRendering-boolean-}
```
public void setSystemFontsNativeRendering(boolean value)
```

يضبط وضع يتم فيه عرض خطوط النظام أصليًا

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setTryToSkipDocumentErrors {#setTryToSkipDocumentErrors-boolean-}
```
public void setTryToSkipDocumentErrors(boolean value)
```

يضبط قيمة تُستخدم لتجاوز الأخطاء أثناء معالجة ملف PDF

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setUseFontHinting {#setUseFontHinting-boolean-}
```
public void setUseFontHinting(boolean value)
```

استخدام هذه العلامة يُفعّل آلية تحسين الخطوط. تحسين الخطوط هو استخدام تعليمات رياضية لضبط عرض الخط الخارجي. في بعض الحالات قد يحل تشغيل هذه العلامة مشاكل وضوح النص. في الوقت الحالي قد يؤثر استخدام هذه العلامة فقط على خطوط TTF إذا تم استخدام هذه الخطوط في المستند الأصلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setUseNewImagingEngine {#setUseNewImagingEngine-boolean-}
```
@Deprecated public void setUseNewImagingEngine(boolean value)
```

يضبط علامة تحدد ما إذا كان محرك التصوير الجديد يُستخدم أم لا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية @deprecated UseNewImagingEngine تم إهمالها |

### setWidthExtraUnits {#setWidthExtraUnits-float-}
```
public void setWidthExtraUnits(float value)
```

يحصل أو يضبط قيمة تُستخدم لزيادة أو تقليل عرض المستطيل لمُعامل AppendRectangle.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |
