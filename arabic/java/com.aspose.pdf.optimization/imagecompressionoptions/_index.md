---
title: "ImageCompressionOptions"
linktitle: "ImageCompressionOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة تحتوي على مجموعة من الخيارات لضغط الصورة."
type: docs
weight: 10
url: /ar/java/com.aspose.pdf.optimization/imagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.ImageCompressionOptions

```
public class ImageCompressionOptions extends Object
```

الفئة تحتوي على مجموعة من الخيارات لضغط الصورة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ImageCompressionOptions](#ImageCompressionOptions--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEncoding](#getEncoding--) | الحصول على الترميز أو تعيينه المستخدم لتخزين الصور. |
| [getImageQuality](#getImageQuality--) | يحدد مستوى ضغط الصورة عندما يتم استخدام علم CompressImages. |
| [getMaxResolution](#getMaxResolution--) | يحدد أقصى دقة للصور. إذا كانت الصورة ذات دقة أعلى فسيتم تعديل حجمها. |
| [getResizeImages](#getResizeImages--) | إذا تم تعيين هذا العلم إلى true وكان CompressImages كذلك، سيتم تغيير حجم الصور إذا كانت دقة الصورة أكبر من المعامل MaxResolution المحدد. |
| [getVersion](#getVersion--) | إصدار خوارزمية الضغط. القيم الممكنة هي: 1. ضغط قياسي، 2. سريع (ضغط محسّن يكون أسرع من القياسي لكنه قد لا يكون مناسبًا لجميع الصور)، 3. مختلط (يُطبق الضغط القياسي على الصور التي لا يمكن ضغطها بالخوارزمية الأسرع، قد يعطي هذا أفضل ضغط لكنه أبطأ من الخوارزمية "سريع". الإصدار "سريع" غير قابل لتغيير حجم الصور (سيتم استخدام الطريقة القياسية). الافتراضي هو "قياسي".) |
| [isCompressImages](#isCompressImages--) | إذا تم تعيين هذا العلم إلى true، سيتم ضغط الصور في المستند. يتم تحديد مستوى الضغط باستخدام الخاصية ImageQuality. |
| [setCompressImages](#setCompressImages-boolean-) | إذا تم تعيين هذا العلم إلى true، سيتم ضغط الصور في المستند. يتم تحديد مستوى الضغط باستخدام الخاصية ImageQuality. |
| [setEncoding](#setEncoding-int-) | الحصول على الترميز أو تعيينه المستخدم لتخزين الصور. |
| [setImageQuality](#setImageQuality-int-) | يحدد مستوى ضغط الصورة عندما يتم استخدام علم CompressImages. |
| [setMaxResolution](#setMaxResolution-int-) | يحدد أقصى دقة للصور. إذا كانت الصورة ذات دقة أعلى فسيتم تعديل حجمها. |
| [setResizeImages](#setResizeImages-boolean-) | إذا تم تعيين هذا العلم إلى true وكان CompressImages كذلك، سيتم تغيير حجم الصور إذا كانت دقة الصورة أكبر من المعامل MaxResolution المحدد. |
| [setVersion](#setVersion-int-) | إصدار خوارزمية الضغط. القيم الممكنة هي: 1. ضغط قياسي، 2. سريع (ضغط محسّن يكون أسرع من القياسي لكنه قد لا يكون مناسبًا لجميع الصور)، 3. مختلط (يُطبق الضغط القياسي على الصور التي لا يمكن ضغطها بالخوارزمية الأسرع، قد يعطي هذا أفضل ضغط لكنه أبطأ من الخوارزمية "سريع". الإصدار "سريع" غير قابل لتغيير حجم الصور (سيتم استخدام الطريقة القياسية). الافتراضي هو "قياسي".) |

### ImageCompressionOptions {#ImageCompressionOptions--}
```
public ImageCompressionOptions()
```



### getEncoding {#getEncoding--}
```
public final int getEncoding()
```

الحصول على الترميز أو تعيينه المستخدم لتخزين الصور.

**Returns:**
عنصر ImageEncoding

### getImageQuality {#getImageQuality--}
```
public final int getImageQuality()
```

يحدد مستوى ضغط الصورة عندما يتم استخدام علم CompressImages.

**Returns:**
قيمة int

### getMaxResolution {#getMaxResolution--}
```
public final int getMaxResolution()
```

يحدد أقصى دقة للصور. إذا كانت الصورة ذات دقة أعلى فسيتم تعديل حجمها.

**Returns:**
قيمة int

### getResizeImages {#getResizeImages--}
```
public final boolean getResizeImages()
```

إذا تم تعيين هذا العلم إلى true وكان CompressImages كذلك، سيتم تغيير حجم الصور إذا كانت دقة الصورة أكبر من المعامل MaxResolution المحدد.

**Returns:**
قيمة منطقية

### getVersion {#getVersion--}
```
public final int getVersion()
```

إصدار خوارزمية الضغط. القيم الممكنة هي: 1. ضغط قياسي، 2. سريع (ضغط محسّن يكون أسرع من القياسي لكنه قد لا يكون مناسبًا لجميع الصور)، 3. مختلط (يُطبق الضغط القياسي على الصور التي لا يمكن ضغطها بالخوارزمية الأسرع، قد يعطي هذا أفضل ضغط لكنه أبطأ من الخوارزمية "سريع". الإصدار "سريع" غير قابل لتغيير حجم الصور (سيتم استخدام الطريقة القياسية). الافتراضي هو "قياسي".)

**Returns:**
قيمة int

### isCompressImages {#isCompressImages--}
```
public final boolean isCompressImages()
```

إذا تم تعيين هذا العلم إلى true، سيتم ضغط الصور في المستند. يتم تحديد مستوى الضغط باستخدام الخاصية ImageQuality.

**Returns:**
قيمة منطقية

### setCompressImages {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```

إذا تم تعيين هذا العلم إلى true، سيتم ضغط الصور في المستند. يتم تحديد مستوى الضغط باستخدام الخاصية ImageQuality.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setEncoding {#setEncoding-int-}
```
public final void setEncoding(int value)
```

الحصول على الترميز أو تعيينه المستخدم لتخزين الصور.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر ImageEncoding |

### setImageQuality {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```

يحدد مستوى ضغط الصورة عندما يتم استخدام علم CompressImages.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setMaxResolution {#setMaxResolution-int-}
```
public final void setMaxResolution(int value)
```

يحدد أقصى دقة للصور. إذا كانت الصورة ذات دقة أعلى فسيتم تعديل حجمها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setResizeImages {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```

إذا تم تعيين هذا العلم إلى true وكان CompressImages كذلك، سيتم تغيير حجم الصور إذا كانت دقة الصورة أكبر من المعامل MaxResolution المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setVersion {#setVersion-int-}
```
public final void setVersion(int value)
```

إصدار خوارزمية الضغط. القيم الممكنة هي: 1. ضغط قياسي، 2. سريع (ضغط محسّن يكون أسرع من القياسي لكنه قد لا يكون مناسبًا لجميع الصور)، 3. مختلط (يُطبق الضغط القياسي على الصور التي لا يمكن ضغطها بالخوارزمية الأسرع، قد يعطي هذا أفضل ضغط لكنه أبطأ من الخوارزمية "سريع". الإصدار "سريع" غير قابل لتغيير حجم الصور (سيتم استخدام الطريقة القياسية). الافتراضي هو "قياسي".)

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |
