---
title: "OptimizationOptions"
linktitle: "OptimizationOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة التي تصف خوارزمية تحسين المستند. يمكن استخدام نسخة من هذه الفئة كمعامل لطريقة OptimizeResources()."
type: docs
weight: 40
url: /ar/java/com.aspose.pdf.optimization/optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions

```
public class OptimizationOptions extends Object
```

الفئة التي تصف خوارزمية تحسين المستند. يمكن استخدام نسخة من هذه الفئة كمعامل لطريقة OptimizeResources().

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [all](#all--) | ينشئ استراتيجية تحسين مع تفعيل جميع الخيارات. يرجى ملاحظة أن يتم تفعيل الخيارات التي لا تغير أي وظيفة في المستند فقط. على سبيل المثال، ضغط الصور وإلغاء تضمين الخطوط لن يتم تفعيله (ويمكن تضمينه يدويًا). |
| [getCompressAllContentStreams](#getCompressAllContentStreams--) | إذا تم الضبط إلى {@link}، فسيتم ضغط جميع تدفقات محتوى الصفحات غير المضغوطة باستخدام مرشح FlateDecode أثناء {@code Document#OptimizeResources()}. القيمة الافتراضية هي {@link} للحفاظ على التوافق مع الإصدارات السابقة. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | مجموعة من الخيارات التي تصف ما إذا كانت الصور في المستند ستُضغط ومعلمات الضغط. |
| [getImageEncoding](#getImageEncoding--) | ترميز الصورة الذي سيُستخدم. |
| [getImageQuality](#getImageQuality--) | يحدد مستوى ضغط الصورة عندما يتم استخدام علم CompressIamges. |
| [getMaxResoultion](#getMaxResoultion--) | يحدد أقصى دقة للصور. إذا كانت الصورة ذات دقة أعلى فسيتم تصغيرها. |
| [isAllowReusePageContent](#isAllowReusePageContent--) | إذا كان صحيحًا، سيتم إعادة استخدام محتويات الصفحات عندما يتم تحسين المستند للصفحات المتساوية. |
| [isCompressImages](#isCompressImages--) | إذا تم تعيين هذه العلامة إلى true سيتم ضغط الصور في المستند. مستوى الضغط محدد بخصيصة ImageQuality. |
| [isCompressObjects](#isCompressObjects--) | إذا تم تعيين هذه العلامة إلى {@code }، سيتم تعبئة كائنات Pdf في تدفقات Objest وضغطها لتقليل حجم ملف pdf. |
| [isLinkDuplicateStreams](#isLinkDuplicateStreams--) | إذا تم تعيين هذه العلامة إلى true، سيتم تحليل تدفقات Resource. إذا تم العثور على تدفقات مكررة (أي إذا كان محتوى التدفق متساوٍ)، فسيتم تخزين تلك التدفقات ككائن واحد. هذا يسمح بتقليل حجم المستند في بعض الحالات (على سبيل المثال، عندما تم دمج نفس المستند عدة مرات). |
| [isRemovePrivateInfo](#isRemovePrivateInfo--) | إزالة المعلومات الخاصة (معلومات جزء الصفحة). |
| [isRemoveUnusedObjects](#isRemoveUnusedObjects--) | إذا تم تعيين هذه العلامة إلى true، سيتم فحص جميع كائنات المستند وإزالة الكائنات غير المستخدمة (أي الكائنات التي لا تحتوي على أي إشارة) من المستند. |
| [isRemoveUnusedStreams](#isRemoveUnusedStreams--) | إذا تم تعيين هذه العلامة إلى true، يتم فحص كل مورد بناءً على استخدامه. إذا لم يُستخدم المورد أبداً، يتم إزالة المورد. قد يؤدي ذلك إلى تقليل حجم المستند، على سبيل المثال عندما تم استخراج الصفحات من المستند. |
| [isResizeImages](#isResizeImages--) | إذا تم تعيين هذه العلامة إلى true وكان CompressImages مضبوطًا على true، سيتم تغيير حجم الصور إذا كانت دقة الصورة أكبر من المعامل MaxResolution المحدد. |
| [isSubsetFonts](#isSubsetFonts--) | سيتم تحويل الخطوط إلى مجموعات جزئية إذا تم تعيينها إلى true. |
| [isUnembedFonts](#isUnembedFonts--) | اجعل الخطوط غير مضمنة إذا تم تعيينها إلى true. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | إذا كان صحيحًا، سيتم إعادة استخدام محتويات الصفحات عندما يتم تحسين المستند للصفحات المتساوية. |
| [setCompressAllContentStreams](#setCompressAllContentStreams-boolean-) | إذا تم الضبط إلى {@link}، فسيتم ضغط جميع تدفقات محتوى الصفحات غير المضغوطة باستخدام مرشح FlateDecode أثناء {@code Document#OptimizeResources()}. القيمة الافتراضية هي {@link} للحفاظ على التوافق مع الإصدارات السابقة. |
| [setCompressImages](#setCompressImages-boolean-) | إذا تم تعيين هذه العلامة إلى true سيتم ضغط الصور في المستند. مستوى الضغط محدد بخصيصة ImageQuality. |
| [setCompressObjects](#setCompressObjects-boolean-) | إذا تم تعيين هذه العلامة إلى {@code }، سيتم تعبئة كائنات Pdf في تدفقات Objest وضغطها لتقليل حجم ملف pdf. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | مجموعة من الخيارات التي تصف ما إذا كانت الصور في المستند ستُضغط ومعلمات الضغط. |
| [setImageEncoding](#setImageEncoding-int-) | ترميز الصورة الذي سيُستخدم. |
| [setImageQuality](#setImageQuality-int-) | يحدد مستوى ضغط الصورة عندما يتم استخدام علم CompressIamges. |
| [setLinkDuplicateStreams](#setLinkDuplicateStreams-boolean-) | إذا تم تعيين هذه العلامة إلى true، سيتم تحليل تدفقات Resource. إذا تم العثور على تدفقات مكررة (أي إذا كان محتوى التدفق متساوٍ)، فسيتم تخزين تلك التدفقات ككائن واحد. هذا يسمح بتقليل حجم المستند في بعض الحالات (على سبيل المثال، عندما تم دمج نفس المستند عدة مرات). |
| [setMaxResoultion](#setMaxResoultion-int-) | يحدد أقصى دقة للصور. إذا كانت الصورة ذات دقة أعلى فسيتم تصغيرها. |
| [setRemovePrivateInfo](#setRemovePrivateInfo-boolean-) | إزالة المعلومات الخاصة (معلومات جزء الصفحة). |
| [setRemoveUnusedObjects](#setRemoveUnusedObjects-boolean-) | إذا تم تعيين هذه العلامة إلى true، سيتم فحص جميع كائنات المستند وإزالة الكائنات غير المستخدمة (أي الكائنات التي لا تحتوي على أي إشارة) من المستند. |
| [setRemoveUnusedStreams](#setRemoveUnusedStreams-boolean-) | إذا تم تعيين هذه العلامة إلى true، يتم فحص كل مورد بناءً على استخدامه. إذا لم يُستخدم المورد أبداً، يتم إزالة المورد. قد يؤدي ذلك إلى تقليل حجم المستند، على سبيل المثال عندما تم استخراج الصفحات من المستند. |
| [setResizeImages](#setResizeImages-boolean-) | إذا تم تعيين هذه العلامة إلى true وكان CompressImages مضبوطًا على true، سيتم تغيير حجم الصور إذا كانت دقة الصورة أكبر من المعامل MaxResolution المحدد. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | سيتم تحويل الخطوط إلى مجموعات جزئية إذا تم تعيينها إلى true. |
| [setUnembedFonts](#setUnembedFonts-boolean-) | اجعل الخطوط غير مضمنة إذا تم تعيينها إلى true. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```



### all {#all--}
```
public static OptimizationOptions all()
```

ينشئ استراتيجية تحسين مع تفعيل جميع الخيارات. يرجى ملاحظة أن يتم تفعيل الخيارات التي لا تغير أي وظيفة في المستند فقط. على سبيل المثال، ضغط الصور وإلغاء تضمين الخطوط لن يتم تفعيله (ويمكن تضمينه يدويًا).

**Returns:**
كائن OptimizationOptions.

### getCompressAllContentStreams {#getCompressAllContentStreams--}
```
public final boolean getCompressAllContentStreams()
```

إذا تم الضبط إلى {@link}، فسيتم ضغط جميع تدفقات محتوى الصفحات غير المضغوطة باستخدام مرشح FlateDecode أثناء {@code Document#OptimizeResources()}. القيمة الافتراضية هي {@link} للحفاظ على التوافق مع الإصدارات السابقة.

**Returns:**
قيمة منطقية

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

مجموعة من الخيارات التي تصف ما إذا كانت الصور في المستند ستُضغط ومعلمات الضغط.

**Returns:**
مثيل ImageCompressionOptions

### getImageEncoding {#getImageEncoding--}
```
public final int getImageEncoding()
```

ترميز الصورة الذي سيُستخدم.

**Returns:**
عنصر ImageEncoding

### getImageQuality {#getImageQuality--}
```
@Deprecated public final int getImageQuality()
```

يحدد مستوى ضغط الصورة عندما يتم استخدام علم CompressIamges.

**Returns:**
قيمة int @deprecated يرجى استخدام ImageCompressionOptions.ImageQuality بدلاً من ذلك.

### getMaxResoultion {#getMaxResoultion--}
```
public final int getMaxResoultion()
```

يحدد أقصى دقة للصور. إذا كانت الصورة ذات دقة أعلى فسيتم تصغيرها.

**Returns:**
قيمة int

### isAllowReusePageContent {#isAllowReusePageContent--}
```
public final boolean isAllowReusePageContent()
```

إذا كان صحيحًا، سيتم إعادة استخدام محتويات الصفحات عندما يتم تحسين المستند للصفحات المتساوية.

**Returns:**
قيمة منطقية

### isCompressImages {#isCompressImages--}
```
@Deprecated public final boolean isCompressImages()
```

إذا تم تعيين هذه العلامة إلى true سيتم ضغط الصور في المستند. مستوى الضغط محدد بخصيصة ImageQuality.

**Returns:**
قيمة boolean @deprecated يرجى استخدام ImageCompressionOptions.CompressImages بدلاً من ذلك.

### isCompressObjects {#isCompressObjects--}
```
public final boolean isCompressObjects()
```

إذا تم تعيين هذه العلامة إلى {@code }، سيتم تعبئة كائنات Pdf في تدفقات Objest وضغطها لتقليل حجم ملف pdf.

**Returns:**
قيمة منطقية

### isLinkDuplicateStreams {#isLinkDuplicateStreams--}
```
public final boolean isLinkDuplicateStreams()
```

إذا تم تعيين هذه العلامة إلى true، سيتم تحليل تدفقات Resource. إذا تم العثور على تدفقات مكررة (أي إذا كان محتوى التدفق متساوٍ)، فسيتم تخزين تلك التدفقات ككائن واحد. هذا يسمح بتقليل حجم المستند في بعض الحالات (على سبيل المثال، عندما تم دمج نفس المستند عدة مرات).

**Returns:**
قيمة منطقية

### isRemovePrivateInfo {#isRemovePrivateInfo--}
```
public final boolean isRemovePrivateInfo()
```

إزالة المعلومات الخاصة (معلومات جزء الصفحة).

**Returns:**
قيمة منطقية

### isRemoveUnusedObjects {#isRemoveUnusedObjects--}
```
public final boolean isRemoveUnusedObjects()
```

إذا تم تعيين هذه العلامة إلى true، سيتم فحص جميع كائنات المستند وإزالة الكائنات غير المستخدمة (أي الكائنات التي لا تحتوي على أي إشارة) من المستند.

**Returns:**
قيمة منطقية

### isRemoveUnusedStreams {#isRemoveUnusedStreams--}
```
public final boolean isRemoveUnusedStreams()
```

إذا تم تعيين هذه العلامة إلى true، يتم فحص كل مورد بناءً على استخدامه. إذا لم يُستخدم المورد أبداً، يتم إزالة المورد. قد يؤدي ذلك إلى تقليل حجم المستند، على سبيل المثال عندما تم استخراج الصفحات من المستند.

**Returns:**
قيمة منطقية

### isResizeImages {#isResizeImages--}
```
@Deprecated public final boolean isResizeImages()
```

إذا تم تعيين هذه العلامة إلى true وكان CompressImages مضبوطًا على true، سيتم تغيير حجم الصور إذا كانت دقة الصورة أكبر من المعامل MaxResolution المحدد.

**Returns:**
قيمة boolean @deprecated يرجى استخدام ImageCompressionOptions.ResizeImages بدلاً من ذلك.

### isSubsetFonts {#isSubsetFonts--}
```
public final boolean isSubsetFonts()
```

سيتم تحويل الخطوط إلى مجموعات جزئية إذا تم تعيينها إلى true.

**Returns:**
قيمة منطقية

### isUnembedFonts {#isUnembedFonts--}
```
public final boolean isUnembedFonts()
```

اجعل الخطوط غير مضمنة إذا تم تعيينها إلى true.

**Returns:**
قيمة منطقية

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```

إذا كان صحيحًا، سيتم إعادة استخدام محتويات الصفحات عندما يتم تحسين المستند للصفحات المتساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setCompressAllContentStreams {#setCompressAllContentStreams-boolean-}
```
public final void setCompressAllContentStreams(boolean value)
```

إذا تم الضبط إلى {@link}، فسيتم ضغط جميع تدفقات محتوى الصفحات غير المضغوطة باستخدام مرشح FlateDecode أثناء {@code Document#OptimizeResources()}. القيمة الافتراضية هي {@link} للحفاظ على التوافق مع الإصدارات السابقة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setCompressImages {#setCompressImages-boolean-}
```
@Deprecated public final void setCompressImages(boolean value)
```

إذا تم تعيين هذه العلامة إلى true سيتم ضغط الصور في المستند. مستوى الضغط محدد بخصيصة ImageQuality.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة boolean @deprecated يرجى استخدام ImageCompressionOptions.CompressImages بدلاً من ذلك. |

### setCompressObjects {#setCompressObjects-boolean-}
```
public final void setCompressObjects(boolean value)
```

إذا تم تعيين هذه العلامة إلى {@code }، سيتم تعبئة كائنات Pdf في تدفقات Objest وضغطها لتقليل حجم ملف pdf.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
مجموعة من الخيارات التي تصف ما إذا كانت الصور في المستند ستُضغط ومعلمات الضغط.

### setImageEncoding {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```

ترميز الصورة الذي سيُستخدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر ImageEncoding |

### setImageQuality {#setImageQuality-int-}
```
@Deprecated public final void setImageQuality(int value)
```

يحدد مستوى ضغط الصورة عندما يتم استخدام علم CompressIamges.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int @deprecated يرجى استخدام ImageCompressionOptions.ImageQuality بدلاً من ذلك. |

### setLinkDuplicateStreams {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```

إذا تم تعيين هذه العلامة إلى true، سيتم تحليل تدفقات Resource. إذا تم العثور على تدفقات مكررة (أي إذا كان محتوى التدفق متساوٍ)، فسيتم تخزين تلك التدفقات ككائن واحد. هذا يسمح بتقليل حجم المستند في بعض الحالات (على سبيل المثال، عندما تم دمج نفس المستند عدة مرات).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMaxResoultion {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```

يحدد أقصى دقة للصور. إذا كانت الصورة ذات دقة أعلى فسيتم تصغيرها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setRemovePrivateInfo {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```

إزالة المعلومات الخاصة (معلومات جزء الصفحة).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRemoveUnusedObjects {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```

إذا تم تعيين هذه العلامة إلى true، سيتم فحص جميع كائنات المستند وإزالة الكائنات غير المستخدمة (أي الكائنات التي لا تحتوي على أي إشارة) من المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRemoveUnusedStreams {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```

إذا تم تعيين هذه العلامة إلى true، يتم فحص كل مورد بناءً على استخدامه. إذا لم يُستخدم المورد أبداً، يتم إزالة المورد. قد يؤدي ذلك إلى تقليل حجم المستند، على سبيل المثال عندما تم استخراج الصفحات من المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setResizeImages {#setResizeImages-boolean-}
```
@Deprecated public final void setResizeImages(boolean value)
```

إذا تم تعيين هذه العلامة إلى true وكان CompressImages مضبوطًا على true، سيتم تغيير حجم الصور إذا كانت دقة الصورة أكبر من المعامل MaxResolution المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة boolean @deprecated يرجى استخدام ImageCompressionOptions.ResizeImages بدلاً من ذلك. |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

سيتم تحويل الخطوط إلى مجموعات جزئية إذا تم تعيينها إلى true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setUnembedFonts {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```

اجعل الخطوط غير مضمنة إذا تم تعيينها إلى true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
