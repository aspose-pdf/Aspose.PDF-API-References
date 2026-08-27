---
title: "AutoTaggingSettings"
linktitle: "AutoTaggingSettings"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يوفر إعدادات لوظيفة الوسم التلقائي في مستندات PDF. تسمح الفئة {@link AutoTaggingSettings} بتكوين الخيارات للوسم التلقائي لمحتوى PDF. ذلك."
type: docs
weight: 230
url: /ar/java/com.aspose.pdf/autotaggingsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AutoTaggingSettings

```
public final class AutoTaggingSettings extends Object
```

توفر إعدادات لوظيفة الوسم التلقائي في مستندات PDF. تسمح فئة {@link AutoTaggingSettings} بتكوين الخيارات للوسم التلقائي لمحتوى PDF. تشمل الخصائص لتمكين أو تعطيل الوسم التلقائي، وتحديد استراتيجية للتعرف على العناوين، وتعريف مستويات العناوين بناءً على أحجام الخط.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [AutoTaggingSettings](#AutoTaggingSettings--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDefault](#getDefault--) | يحصل على الإعدادات الافتراضية لوظيفة الوسم التلقائي في مستندات PDF. تمكّن الإعدادات الافتراضية الوسم التلقائي وتستخدم الاستراتيجية التلقائية للتعرف على العناوين. يمكن استخدام هذه الإعدادات كإعداد أساسي لتحويل صيغ PDF أو عمليات أخرى تتطلب الوسم التلقائي لمحتوى PDF. |
| [getEnableAutoTagging](#getEnableAutoTagging--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت وظيفة الوسم التلقائي مفعلة. عندما تكون مفعلة، تقوم وظيفة الوسم التلقائي تلقائيًا بإنشاء محتوى موسوم لمستند PDF، مما يمكن أن يحسن إمكانية الوصول والبنية. |
| [getHeadingLevels](#getHeadingLevels--) | يحصل أو يضبط مستويات العناوين المستخدمة لتحديد بنية العناوين في مستند PDF. تسمح الخاصية {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) بتكوين ربط أحجام الخط بمستويات العناوين. يُستخدم ذلك أثناء عملية الوسم التلقائي لتحديد وتعيين مستويات العناوين المناسبة بناءً على حجم الخط لعناصر النص في المستند. |
| [getHeadingRecognitionStrategy](#getHeadingRecognitionStrategy--) | يحصل على أو يضبط الاستراتيجية المستخدمة للتعرف على العناوين في المستند أثناء الوسم التلقائي. الخاصية {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) تحدد كيفية تحديد العناوين في المستند. تشمل الاستراتيجيات المتاحة التعرف على العناوين بناءً على المخططات، التحليل الاستدلالي، أو الاكتشاف التلقائي. ضبط هذه الخاصية إلى {@link HeadingRecognitionStrategy#None} يعطل التعرف على العناوين. |
| [setEnableAutoTagging](#setEnableAutoTagging-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت وظيفة الوسم التلقائي مفعلة. عندما تكون مفعلة، تقوم وظيفة الوسم التلقائي تلقائيًا بإنشاء محتوى موسوم لمستند PDF، مما يمكن أن يحسن إمكانية الوصول والبنية. |
| [setHeadingLevels](#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-) | يحصل أو يضبط مستويات العناوين المستخدمة لتحديد بنية العناوين في مستند PDF. تسمح الخاصية {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) بتكوين ربط أحجام الخط بمستويات العناوين. يُستخدم ذلك أثناء عملية الوسم التلقائي لتحديد وتعيين مستويات العناوين المناسبة بناءً على حجم الخط لعناصر النص في المستند. |
| [setHeadingRecognitionStrategy](#setHeadingRecognitionStrategy-int-) | يحصل على أو يضبط الاستراتيجية المستخدمة للتعرف على العناوين في المستند أثناء الوسم التلقائي. الخاصية {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) تحدد كيفية تحديد العناوين في المستند. تشمل الاستراتيجيات المتاحة التعرف على العناوين بناءً على المخططات، التحليل الاستدلالي، أو الاكتشاف التلقائي. ضبط هذه الخاصية إلى {@link HeadingRecognitionStrategy#None} يعطل التعرف على العناوين. |

### AutoTaggingSettings {#AutoTaggingSettings--}
```
public AutoTaggingSettings()
```



### getDefault {#getDefault--}
```
public static AutoTaggingSettings getDefault()
```

يحصل على الإعدادات الافتراضية لوظيفة الوسم التلقائي في مستندات PDF. تمكّن الإعدادات الافتراضية الوسم التلقائي وتستخدم الاستراتيجية التلقائية للتعرف على العناوين. يمكن استخدام هذه الإعدادات كإعداد أساسي لتحويل صيغ PDF أو عمليات أخرى تتطلب الوسم التلقائي لمحتوى PDF.

**Returns:**
مثيل AutoTaggingSettings

### getEnableAutoTagging {#getEnableAutoTagging--}
```
public final boolean getEnableAutoTagging()
```

يحصل أو يضبط قيمة تشير إلى ما إذا كانت وظيفة الوسم التلقائي مفعلة. عندما تكون مفعلة، تقوم وظيفة الوسم التلقائي تلقائيًا بإنشاء محتوى موسوم لمستند PDF، مما يمكن أن يحسن إمكانية الوصول والبنية.

**Returns:**
قيمة منطقية

### getHeadingLevels {#getHeadingLevels--}
```
public final HeadingLevels getHeadingLevels()
```

يحصل أو يضبط مستويات العناوين المستخدمة لتحديد بنية العناوين في مستند PDF. تسمح الخاصية {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) بتكوين ربط أحجام الخط بمستويات العناوين. يُستخدم ذلك أثناء عملية الوسم التلقائي لتحديد وتعيين مستويات العناوين المناسبة بناءً على حجم الخط لعناصر النص في المستند.

**Returns:**
مثيل HeadingLevels

### getHeadingRecognitionStrategy {#getHeadingRecognitionStrategy--}
```
public final int getHeadingRecognitionStrategy()
```

يحصل على أو يضبط الاستراتيجية المستخدمة للتعرف على العناوين في المستند أثناء الوسم التلقائي. الخاصية {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) تحدد كيفية تحديد العناوين في المستند. تشمل الاستراتيجيات المتاحة التعرف على العناوين بناءً على المخططات، التحليل الاستدلالي، أو الاكتشاف التلقائي. ضبط هذه الخاصية إلى {@link HeadingRecognitionStrategy#None} يعطل التعرف على العناوين.

**Returns:**
عنصر HeadingRecognitionStrategy

### setEnableAutoTagging {#setEnableAutoTagging-boolean-}
```
public final void setEnableAutoTagging(boolean value)
```

يحصل أو يضبط قيمة تشير إلى ما إذا كانت وظيفة الوسم التلقائي مفعلة. عندما تكون مفعلة، تقوم وظيفة الوسم التلقائي تلقائيًا بإنشاء محتوى موسوم لمستند PDF، مما يمكن أن يحسن إمكانية الوصول والبنية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setHeadingLevels {#setHeadingLevels-com.aspose.pdf.markdownoptions.HeadingLevels-}
يحصل أو يضبط مستويات العناوين المستخدمة لتحديد بنية العناوين في مستند PDF. تسمح الخاصية {@code HeadingLevels}({@link #getHeadingLevels}/{@link #setHeadingLevels(HeadingLevels)}) بتكوين ربط أحجام الخط بمستويات العناوين. يُستخدم ذلك أثناء عملية الوسم التلقائي لتحديد وتعيين مستويات العناوين المناسبة بناءً على حجم الخط لعناصر النص في المستند.

### setHeadingRecognitionStrategy {#setHeadingRecognitionStrategy-int-}
```
public final void setHeadingRecognitionStrategy(int value)
```

يحصل على أو يضبط الاستراتيجية المستخدمة للتعرف على العناوين في المستند أثناء الوسم التلقائي. الخاصية {@code HeadingRecognitionStrategy}({@link #getHeadingRecognitionStrategy}/{@link #setHeadingRecognitionStrategy(int)}) تحدد كيفية تحديد العناوين في المستند. تشمل الاستراتيجيات المتاحة التعرف على العناوين بناءً على المخططات، التحليل الاستدلالي، أو الاكتشاف التلقائي. ضبط هذه الخاصية إلى {@link HeadingRecognitionStrategy#None} يعطل التعرف على العناوين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر HeadingRecognitionStrategy |
