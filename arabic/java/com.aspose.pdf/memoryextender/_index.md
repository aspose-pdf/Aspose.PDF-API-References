---
title: "MemoryExtender"
linktitle: "MemoryExtender"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة MemoryExtender. باستخدام ملفات كبيرة على نظام بذاكرة كومة محدودة، يمكن تمكينه لاستخدام مساحة القرص كذاكرة تبديل مؤقتة."
type: docs
weight: 3020
url: /ar/java/com.aspose.pdf/memoryextender/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.MemoryExtender

```
public class MemoryExtender extends Object
```

يمثل فئة MemoryExtender. باستخدام ملفات كبيرة على نظام بذاكرة كومة محدودة، يمكن تمكينه لاستخدام مساحة القرص كذاكرة تبديل مؤقتة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [MemoryExtender](#MemoryExtender--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getCallBackPageImage](#getCallBackPageImage--) | احصل على محلل الذاكرة المؤقتة المخصص. |
| [getElementRenderingTimeout](#getElementRenderingTimeout--) | الحد الأقصى للوقت لتصوير عنصر واحد يستخدم في تحويل الصفحة إلى صورة. القيمة الافتراضية 10000 مللي ثانية. يُستخدم فقط عندما تكون isSkipHeavyContentEnabled() == true. |
| [isEnabledMultiPageImageCache](#isEnabledMultiPageImageCache--) | احصل على حالة الحقل EnabledMultiPageImageCache. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault--) | مفعل لاستخدام OptimizedMemoryStream كذاكرة تخزين افتراضية. مطلوب للعمل مع مستندات كبيرة يزيد حجمها عن 2 جيجابايت. القيمة الافتراضية هي FALSE. |
| [isOptimizedMemoryStreamByDefault](#isOptimizedMemoryStreamByDefault-boolean-) | مفعل لاستخدام OptimizedMemoryStream كذاكرة تخزين افتراضية. مطلوب للعمل مع مستندات كبيرة يزيد حجمها عن 2 جيجابايت. القيمة الافتراضية هي FALSE. |
| [isSkipHeavyContentEnabled](#isSkipHeavyContentEnabled--) | مفعل لتخطي الكائنات ذات الاستهلاك العالي للذاكرة أثناء التصوير عند نقص ذاكرة الـ heap. القيمة الافتراضية هي FALSE. |
| [isSwapEnabled](#isSwapEnabled--) | مفعل لاستخدام مساحة القرص كذاكرة تبادل مؤقتة. القيمة الافتراضية هي FALSE. |
| [isTryToCreateFolderIfAbsent](#isTryToCreateFolderIfAbsent--) | يحصل على قيمة تشير إلى ما إذا كان يجب إنشاء المجلدات المفقودة تلقائيًا. <p>إذا تم تعيينها إلى {@code true}، فإن طرق Aspose التي تحفظ حسب المسار ستحاول إنشاء بنية المجلد الهدف إذا لم تكن موجودة بالفعل. <p>القيمة الافتراضية هي {@code false}. |
| [setCallBackPageImage](#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-) | طبق محلل الذاكرة المؤقتة المخصص الجديد. |
| [setElementRenderingTimeout](#setElementRenderingTimeout-int-) | الحد الأقصى للوقت لتصوير عنصر واحد يستخدم في تحويل الصفحة إلى صورة. القيمة الافتراضية 10000 مللي ثانية. يُستخدم فقط عندما تكون isSkipHeavyContentEnabled() == true. |
| [setEnableMultiPageCache](#setEnableMultiPageCache-boolean-) | عيّن الحالة الجديدة للحقل EnabledMultiPageImageCache. |
| [setSkipHeavyContentEnabled](#setSkipHeavyContentEnabled-boolean-) | عيّن العلامة لتمكين تخطي الكائنات ذات الاستهلاك العالي للذاكرة أثناء التصوير عند نقص ذاكرة الـ heap. |
| [setSwapEnabled](#setSwapEnabled-boolean-) | تعيين العلامة لتحديد ما إذا كان تمكين مساحة القرص للاستخدام كذاكرة تبادل مؤقتة. |
| [setTryToCreateFolderIfAbsent](#setTryToCreateFolderIfAbsent-boolean-) | يضبط قيمة تشير إلى ما إذا كان يجب إنشاء المجلدات المفقودة تلقائيًا. <p>إذا تم تعيينها إلى {@code true}، فإن طرق Aspose التي تحفظ عبر المسار ستحاول إنشاء بنية المجلد الهدف إذا لم تكن موجودة بالفعل. <p>القيمة الافتراضية هي {@code false}. |

### MemoryExtender {#MemoryExtender--}
```
public MemoryExtender()
```



### getCallBackPageImage {#getCallBackPageImage--}
```
public static MemoryExtender.CallBackPageImage getCallBackPageImage()
```

احصل على محلل الذاكرة المؤقتة المخصص.

**Returns:**
كائن CallBackPageImage

### getElementRenderingTimeout {#getElementRenderingTimeout--}
```
public static int getElementRenderingTimeout()
```

الحد الأقصى للوقت لتصوير عنصر واحد يستخدم في تحويل الصفحة إلى صورة. القيمة الافتراضية 10000 مللي ثانية. يُستخدم فقط عندما تكون isSkipHeavyContentEnabled() == true.

**Returns:**
قيمة int عدد المللي ثانية

### isEnabledMultiPageImageCache {#isEnabledMultiPageImageCache--}
```
public static boolean isEnabledMultiPageImageCache()
```

احصل على حالة الحقل EnabledMultiPageImageCache.

**Returns:**
قيمة منطقية

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault--}
```
public static boolean isOptimizedMemoryStreamByDefault()
```

مفعل لاستخدام OptimizedMemoryStream كذاكرة تخزين افتراضية. مطلوب للعمل مع مستندات كبيرة يزيد حجمها عن 2 جيجابايت. القيمة الافتراضية هي FALSE.

**Returns:**
قيمة منطقية

### isOptimizedMemoryStreamByDefault {#isOptimizedMemoryStreamByDefault-boolean-}
```
public static void isOptimizedMemoryStreamByDefault(boolean value)
```

مفعل لاستخدام OptimizedMemoryStream كذاكرة تخزين افتراضية. مطلوب للعمل مع مستندات كبيرة يزيد حجمها عن 2 جيجابايت. القيمة الافتراضية هي FALSE.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### isSkipHeavyContentEnabled {#isSkipHeavyContentEnabled--}
```
public static boolean isSkipHeavyContentEnabled()
```

مفعل لتخطي الكائنات ذات الاستهلاك العالي للذاكرة أثناء التصوير عند نقص ذاكرة الـ heap. القيمة الافتراضية هي FALSE.

**Returns:**
قيمة منطقية

### isSwapEnabled {#isSwapEnabled--}
```
public static boolean isSwapEnabled()
```

مفعل لاستخدام مساحة القرص كذاكرة تبادل مؤقتة. القيمة الافتراضية هي FALSE.

**Returns:**
قيمة منطقية

### isTryToCreateFolderIfAbsent {#isTryToCreateFolderIfAbsent--}
```
public static boolean isTryToCreateFolderIfAbsent()
```

يحصل على قيمة تشير إلى ما إذا كان يجب إنشاء المجلدات المفقودة تلقائيًا. <p>إذا تم تعيينها إلى {@code true}، فإن طرق Aspose التي تحفظ حسب المسار ستحاول إنشاء بنية المجلد الهدف إذا لم تكن موجودة بالفعل. <p>القيمة الافتراضية هي {@code false}.

**Returns:**
قيمة منطقية

### setCallBackPageImage {#setCallBackPageImage-com.aspose.pdf.MemoryExtender.CallBackPageImage-}
طبق محلل الذاكرة المؤقتة المخصص الجديد.

### setElementRenderingTimeout {#setElementRenderingTimeout-int-}
```
public static void setElementRenderingTimeout(int value)
```

الحد الأقصى للوقت لتصوير عنصر واحد يستخدم في تحويل الصفحة إلى صورة. القيمة الافتراضية 10000 مللي ثانية. يُستخدم فقط عندما تكون isSkipHeavyContentEnabled() == true.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int عدد المللي ثانية |

### setEnableMultiPageCache {#setEnableMultiPageCache-boolean-}
```
public static void setEnableMultiPageCache(boolean enableMultiPageImageCache_)
```

عيّن الحالة الجديدة للحقل EnabledMultiPageImageCache.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| enableMultiPageImageCache_ |  | قيمة منطقية |

### setSkipHeavyContentEnabled {#setSkipHeavyContentEnabled-boolean-}
```
public static void setSkipHeavyContentEnabled(boolean value)
```

عيّن العلامة لتمكين تخطي الكائنات ذات الاستهلاك العالي للذاكرة أثناء التصوير عند نقص ذاكرة الـ heap.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setSwapEnabled {#setSwapEnabled-boolean-}
```
public static void setSwapEnabled(boolean value)
```

تعيين العلامة لتحديد ما إذا كان تمكين مساحة القرص للاستخدام كذاكرة تبادل مؤقتة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setTryToCreateFolderIfAbsent {#setTryToCreateFolderIfAbsent-boolean-}
```
public static void setTryToCreateFolderIfAbsent(boolean value)
```

يضبط قيمة تشير إلى ما إذا كان يجب إنشاء المجلدات المفقودة تلقائيًا. <p>إذا تم تعيينها إلى {@code true}، فإن طرق Aspose التي تحفظ عبر المسار ستحاول إنشاء بنية المجلد الهدف إذا لم تكن موجودة بالفعل. <p>القيمة الافتراضية هي {@code false}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
