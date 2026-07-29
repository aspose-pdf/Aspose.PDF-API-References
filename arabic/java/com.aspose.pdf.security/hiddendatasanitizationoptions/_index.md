---
title: "HiddenDataSanitizationOptions"
linktitle: "HiddenDataSanitizationOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خيارات التكوين لتطهير البيانات المخفية داخل المستند."
type: docs
weight: 10
url: /ar/java/com.aspose.pdf.security/hiddendatasanitizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizationOptions

```
public final class HiddenDataSanitizationOptions extends Object
```

يمثل خيارات التكوين لتطهير البيانات المخفية داخل المستند.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [HiddenDataSanitizationOptions](#HiddenDataSanitizationOptions--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [all](#all--) | ينشئ مثيلاً جديدًا من الفئة {@link HiddenDataSanitizationOptions} مع ضبط جميع الخيارات للتنقية. يتضمن ذلك تمكين إزالة التعليقات التوضيحية، JavaScript، البيانات الوصفية، المرفقات، فهرس البحث، المعلومات الخاصة، تسطيح النماذج والطبقات، مع تعطيل خيار تحويل الصفحات إلى صور. يمكن تعديل التكوينات الاختيارية مثل {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) أو {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) يدويًا بعد الحصول على المثيل، لأنها غير مفعلة افتراضيًا. |
| [getConvertPagesToImages](#getConvertPagesToImages--) | يحصل على خيار تحويل الصفحات إلى صور. إذا تم تمكين هذا الخيار، سيتجاهل خيار ImageCompressionOptions. يجب تمكين الخيار يدويًا عند استخدام طريقة {@code #All()} إذا كان مطلوبًا. سيحدث تحويل الصفحات إلى صور بعد مسح البيانات المخفية الرئيسية، التي يتم التحكم فيها بواسطة خيارات أخرى. |
| [getFlattenForms](#getFlattenForms--) | يحصل على قيمة تشير إلى ما إذا كان يجب تسطيح النماذج في المستند أثناء عملية التنقية. تسطيح النماذج يحول حقول النماذج التفاعلية إلى محتوى ثابت، مما يجعلها غير قابلة للتحرير أو الملء. |
| [getFlattenLayers](#getFlattenLayers--) | يحصل على خيار تسطيح الطبقات في مستند PDF. عند تمكينه، يتم دمج جميع الطبقات في المستند في طبقة واحدة، مما يزيل هيكلها المنفصل. هذا الخيار مفيد لتنقية المستندات عن طريق تبسيط محتواها وضمان عدم وجود بيانات مخفية داخل الطبقات. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | يحصل على خيار تحويل صور المستند. يجب تمكين الخيار يدويًا عند استخدام طريقة {@code #All()} إذا كان مطلوبًا. |
| [getImageDpi](#getImageDpi--) | يحصل على خيار حل صور الصفحات أثناء التحويل. |
| [getRemoveAnnotations](#getRemoveAnnotations--) | يحصل على قيمة تشير إلى ما إذا كان يجب إزالة التعليقات التوضيحية من المستند. عند تمكينه، سيتم إزالة جميع التعليقات التوضيحية الموجودة في المستند أثناء عملية التنقية. سيتم تطبيق تعليقات التمويه. |
| [getRemoveAttachments](#getRemoveAttachments--) | يحصل على خيار إزالة جميع الملفات المرفقة من المستند. عند تمكينه، يضمن حذف أي مرفقات داخل PDF أثناء عملية التنقية. |
| [getRemoveJavaScriptsAndActions](#getRemoveJavaScriptsAndActions--) | يحصل على قيمة تشير إلى ما إذا كان يجب إزالة JavaScript والإجراءات المرتبطة منه من المستند. هذا الخيار مفيد لإزالة الثغرات الأمنية المحتملة التي تُدخلها النصوص المضمنة. |
| [getRemoveMetadata](#getRemoveMetadata--) | يحصل على خيار إزالة البيانات الوصفية من المستند. إذا تم تعيينه إلى true، سيتم إزالة البيانات الوصفية مثل خصائص المستند ومعلومات البيانات الوصفية المضمنة الإضافية أثناء التنقية. |
| [getRemoveSearchIndexAndPrivateInfo](#getRemoveSearchIndexAndPrivateInfo--) | يحصل على قيمة تشير إلى ما إذا كان يجب إزالة فهرس البحث والمعلومات الخاصة من المستند. يتيح إزالة فهارس البحث المضمنة والبيانات الخاصة لتعزيز أمان المستند وخصوصيته. |
| [setConvertPagesToImages](#setConvertPagesToImages-boolean-) | يضبط خيار تحويل الصفحات إلى صور. إذا تم تمكين هذا الخيار، سيتجاهل خيار ImageCompressionOptions. يجب تمكين الخيار يدويًا عند استخدام طريقة {@code #All()} إذا كان مطلوبًا. سيحدث تحويل الصفحات إلى صور بعد مسح البيانات المخفية الرئيسية، التي يتم التحكم فيها بواسطة خيارات أخرى. |
| [setFlattenForms](#setFlattenForms-boolean-) | يضبط قيمة تشير إلى ما إذا كان يجب تسطيح النماذج في المستند أثناء عملية التنقية. تسطيح النماذج يحول حقول النماذج التفاعلية إلى محتوى ثابت، مما يجعلها غير قابلة للتحرير أو الملء. |
| [setFlattenLayers](#setFlattenLayers-boolean-) | يضبط خيار تسطيح الطبقات في مستند PDF. عند تمكينه، يتم دمج جميع الطبقات في المستند في طبقة واحدة، مما يزيل هيكلها المنفصل. هذا الخيار مفيد لتنقية المستندات عن طريق تبسيط محتواها وضمان عدم وجود بيانات مخفية داخل الطبقات. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | يضبط خيار تحويل صور المستند. يجب تمكين الخيار يدويًا عند استخدام طريقة {@code #All()} إذا كان مطلوبًا. |
| [setImageDpi](#setImageDpi-int-) | يضبط خيار حل صور الصفحات أثناء التحويل. |
| [setRemoveAnnotations](#setRemoveAnnotations-boolean-) | يضبط قيمة تشير إلى ما إذا كان يجب إزالة التعليقات التوضيحية من المستند. عند تمكينه، سيتم إزالة جميع التعليقات التوضيحية الموجودة في المستند أثناء عملية التنقية. سيتم تطبيق تعليقات التمويه. |
| [setRemoveAttachments](#setRemoveAttachments-boolean-) | يضبط الخيار لإزالة جميع الملفات المرفقة من المستند. عند التمكين، يضمن حذف أي مرفقات داخل ملف PDF أثناء عملية التطهير. |
| [setRemoveJavaScriptsAndActions](#setRemoveJavaScriptsAndActions-boolean-) | يضبط قيمة تشير إلى ما إذا كان يجب إزالة JavaScript والإجراءات المرتبطة منه من المستند. هذا الخيار مفيد لإزالة الثغرات الأمنية المحتملة التي قد تُدخلها السكريبتات المضمنة. |
| [setRemoveMetadata](#setRemoveMetadata-boolean-) | يضبط خيارًا لإزالة البيانات الوصفية من المستند. إذا تم تعيينه إلى true، ستُزال البيانات الوصفية مثل خصائص المستند ومعلومات البيانات الوصفية المضمنة الإضافية أثناء عملية التطهير. |
| [setRemoveSearchIndexAndPrivateInfo](#setRemoveSearchIndexAndPrivateInfo-boolean-) | يضبط قيمة تشير إلى ما إذا كان يجب إزالة فهرس البحث والمعلومات الخاصة من المستند. يتيح إزالة فهارس البحث المضمنة والبيانات الخاصة لتعزيز أمان المستند وخصوصيته. |

### HiddenDataSanitizationOptions {#HiddenDataSanitizationOptions--}
```
public HiddenDataSanitizationOptions()
```



### all {#all--}
```
public static HiddenDataSanitizationOptions all()
```

ينشئ مثيلاً جديدًا من الفئة {@link HiddenDataSanitizationOptions} مع ضبط جميع الخيارات للتنقية. يتضمن ذلك تمكين إزالة التعليقات التوضيحية، JavaScript، البيانات الوصفية، المرفقات، فهرس البحث، المعلومات الخاصة، تسطيح النماذج والطبقات، مع تعطيل خيار تحويل الصفحات إلى صور. يمكن تعديل التكوينات الاختيارية مثل {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) أو {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) يدويًا بعد الحصول على المثيل، لأنها غير مفعلة افتراضيًا.

**Returns:**
كائن {@link HiddenDataSanitizationOptions} مع جميع خيارات التطهير مُكوَّن مسبقًا.

### getConvertPagesToImages {#getConvertPagesToImages--}
```
public final boolean getConvertPagesToImages()
```

يحصل على خيار تحويل الصفحات إلى صور. إذا تم تمكين هذا الخيار، سيتجاهل خيار ImageCompressionOptions. يجب تمكين الخيار يدويًا عند استخدام طريقة {@code #All()} إذا كان مطلوبًا. سيحدث تحويل الصفحات إلى صور بعد مسح البيانات المخفية الرئيسية، التي يتم التحكم فيها بواسطة خيارات أخرى.

**Returns:**
الخيار لتحويل الصفحات إلى صور.

### getFlattenForms {#getFlattenForms--}
```
public final boolean getFlattenForms()
```

يحصل على قيمة تشير إلى ما إذا كان يجب تسطيح النماذج في المستند أثناء عملية التنقية. تسطيح النماذج يحول حقول النماذج التفاعلية إلى محتوى ثابت، مما يجعلها غير قابلة للتحرير أو الملء.

**Returns:**
قيمة تشير إلى ما إذا كان يجب تسطيح النماذج في المستند أثناء عملية التطهير.

### getFlattenLayers {#getFlattenLayers--}
```
public final boolean getFlattenLayers()
```

يحصل على خيار تسطيح الطبقات في مستند PDF. عند تمكينه، يتم دمج جميع الطبقات في المستند في طبقة واحدة، مما يزيل هيكلها المنفصل. هذا الخيار مفيد لتنقية المستندات عن طريق تبسيط محتواها وضمان عدم وجود بيانات مخفية داخل الطبقات.

**Returns:**
الخيار لتسطيح الطبقات في مستند PDF.

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

يحصل على خيار تحويل صور المستند. يجب تمكين الخيار يدويًا عند استخدام طريقة {@code #All()} إذا كان مطلوبًا.

**Returns:**
خيار تحويل صور المستند.

### getImageDpi {#getImageDpi--}
```
public final int getImageDpi()
```

يحصل على خيار حل صور الصفحات أثناء التحويل.

**Returns:**
الخيار لحل صور الصفحات أثناء التحويل.

### getRemoveAnnotations {#getRemoveAnnotations--}
```
public final boolean getRemoveAnnotations()
```

يحصل على قيمة تشير إلى ما إذا كان يجب إزالة التعليقات التوضيحية من المستند. عند تمكينه، سيتم إزالة جميع التعليقات التوضيحية الموجودة في المستند أثناء عملية التنقية. سيتم تطبيق تعليقات التمويه.

**Returns:**
قيمة تشير إلى ما إذا كان يجب إزالة التعليقات التوضيحية من المستند.

### getRemoveAttachments {#getRemoveAttachments--}
```
public final boolean getRemoveAttachments()
```

يحصل على خيار إزالة جميع الملفات المرفقة من المستند. عند تمكينه، يضمن حذف أي مرفقات داخل PDF أثناء عملية التنقية.

**Returns:**
الخيار لإزالة جميع الملفات المرفقة من المستند.

### getRemoveJavaScriptsAndActions {#getRemoveJavaScriptsAndActions--}
```
public final boolean getRemoveJavaScriptsAndActions()
```

يحصل على قيمة تشير إلى ما إذا كان يجب إزالة JavaScript والإجراءات المرتبطة منه من المستند. هذا الخيار مفيد لإزالة الثغرات الأمنية المحتملة التي تُدخلها النصوص المضمنة.

**Returns:**
قيمة تشير إلى ما إذا كان يجب إزالة JavaScript والإجراءات المرتبطة منه من المستند.

### getRemoveMetadata {#getRemoveMetadata--}
```
public final boolean getRemoveMetadata()
```

يحصل على خيار إزالة البيانات الوصفية من المستند. إذا تم تعيينه إلى true، سيتم إزالة البيانات الوصفية مثل خصائص المستند ومعلومات البيانات الوصفية المضمنة الإضافية أثناء التنقية.

**Returns:**
خيار لإزالة البيانات الوصفية من المستند.

### getRemoveSearchIndexAndPrivateInfo {#getRemoveSearchIndexAndPrivateInfo--}
```
public final boolean getRemoveSearchIndexAndPrivateInfo()
```

يحصل على قيمة تشير إلى ما إذا كان يجب إزالة فهرس البحث والمعلومات الخاصة من المستند. يتيح إزالة فهارس البحث المضمنة والبيانات الخاصة لتعزيز أمان المستند وخصوصيته.

**Returns:**
قيمة تشير إلى ما إذا كان يجب إزالة فهرس البحث والمعلومات الخاصة من المستند.

### setConvertPagesToImages {#setConvertPagesToImages-boolean-}
```
public final void setConvertPagesToImages(boolean value)
```

يضبط خيار تحويل الصفحات إلى صور. إذا تم تمكين هذا الخيار، سيتجاهل خيار ImageCompressionOptions. يجب تمكين الخيار يدويًا عند استخدام طريقة {@code #All()} إذا كان مطلوبًا. سيحدث تحويل الصفحات إلى صور بعد مسح البيانات المخفية الرئيسية، التي يتم التحكم فيها بواسطة خيارات أخرى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | الخيار لتحويل الصفحات إلى صور. |

### setFlattenForms {#setFlattenForms-boolean-}
```
public final void setFlattenForms(boolean value)
```

يضبط قيمة تشير إلى ما إذا كان يجب تسطيح النماذج في المستند أثناء عملية التنقية. تسطيح النماذج يحول حقول النماذج التفاعلية إلى محتوى ثابت، مما يجعلها غير قابلة للتحرير أو الملء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة تشير إلى ما إذا كان يجب تسطيح النماذج في المستند أثناء عملية التطهير. |

### setFlattenLayers {#setFlattenLayers-boolean-}
```
public final void setFlattenLayers(boolean value)
```

يضبط خيار تسطيح الطبقات في مستند PDF. عند تمكينه، يتم دمج جميع الطبقات في المستند في طبقة واحدة، مما يزيل هيكلها المنفصل. هذا الخيار مفيد لتنقية المستندات عن طريق تبسيط محتواها وضمان عدم وجود بيانات مخفية داخل الطبقات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | الخيار لتسطيح الطبقات في مستند PDF. |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
يضبط خيار تحويل صور المستند. يجب تمكين الخيار يدويًا عند استخدام طريقة {@code #All()} إذا كان مطلوبًا.

### setImageDpi {#setImageDpi-int-}
```
public final void setImageDpi(int value)
```

يضبط خيار حل صور الصفحات أثناء التحويل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | الخيار لحل صور الصفحات أثناء التحويل. |

### setRemoveAnnotations {#setRemoveAnnotations-boolean-}
```
public final void setRemoveAnnotations(boolean value)
```

يضبط قيمة تشير إلى ما إذا كان يجب إزالة التعليقات التوضيحية من المستند. عند تمكينه، سيتم إزالة جميع التعليقات التوضيحية الموجودة في المستند أثناء عملية التنقية. سيتم تطبيق تعليقات التمويه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة تشير إلى ما إذا كان يجب إزالة التعليقات التوضيحية من المستند. |

### setRemoveAttachments {#setRemoveAttachments-boolean-}
```
public final void setRemoveAttachments(boolean value)
```

يضبط الخيار لإزالة جميع الملفات المرفقة من المستند. عند التمكين، يضمن حذف أي مرفقات داخل ملف PDF أثناء عملية التطهير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | الخيار لإزالة جميع الملفات المرفقة من المستند. |

### setRemoveJavaScriptsAndActions {#setRemoveJavaScriptsAndActions-boolean-}
```
public final void setRemoveJavaScriptsAndActions(boolean value)
```

يضبط قيمة تشير إلى ما إذا كان يجب إزالة JavaScript والإجراءات المرتبطة منه من المستند. هذا الخيار مفيد لإزالة الثغرات الأمنية المحتملة التي قد تُدخلها السكريبتات المضمنة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة تشير إلى ما إذا كان يجب إزالة JavaScript والإجراءات المرتبطة منه من المستند. |

### setRemoveMetadata {#setRemoveMetadata-boolean-}
```
public final void setRemoveMetadata(boolean value)
```

يضبط خيارًا لإزالة البيانات الوصفية من المستند. إذا تم تعيينه إلى true، ستُزال البيانات الوصفية مثل خصائص المستند ومعلومات البيانات الوصفية المضمنة الإضافية أثناء عملية التطهير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | خيار لإزالة البيانات الوصفية من المستند. |

### setRemoveSearchIndexAndPrivateInfo {#setRemoveSearchIndexAndPrivateInfo-boolean-}
```
public final void setRemoveSearchIndexAndPrivateInfo(boolean value)
```

يضبط قيمة تشير إلى ما إذا كان يجب إزالة فهرس البحث والمعلومات الخاصة من المستند. يتيح إزالة فهارس البحث المضمنة والبيانات الخاصة لتعزيز أمان المستند وخصوصيته.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة تشير إلى ما إذا كان يجب إزالة فهرس البحث والمعلومات الخاصة من المستند. |
