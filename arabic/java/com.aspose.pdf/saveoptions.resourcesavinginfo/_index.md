---
title: "SaveOptions.ResourceSavingInfo"
linktitle: "SaveOptions.ResourceSavingInfo"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تمثل هذه الفئة مجموعة من البيانات المتعلقة بحفظ ملف المورد الخارجي التي تحدث أثناء تحويل PDF إلى تنسيق آخر (مثلاً HTML)."
type: docs
weight: 4440
url: /ar/java/com.aspose.pdf/saveoptions.resourcesavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.ResourceSavingInfo

```
public static class SaveOptions.ResourceSavingInfo extends Object
```

تمثل هذه الفئة مجموعة من البيانات المتعلقة بحفظ ملف المورد الخارجي التي تحدث أثناء تحويل PDF إلى تنسيق آخر (مثلاً HTML).

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getContentStream](#getContentStream--) | تم التعيين بواسطة المحول. يمثل المحتوى الثنائي للملف المحفوظ. |
| [getResourceType](#getResourceType--) | تم التعيين بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى كود الطريقة المخصصة يمكن استخدامه في الكود المخصص لتحديد كيفية المعالجة أو أين يتم حفظ الملف. |
| [getSupposedFileName](#getSupposedFileName--) | تم التعيين بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى كود الطريقة المخصصة يمكن استخدامه في الكود المخصص لتحديد كيفية المعالجة أو أين يتم حفظ الملف. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | يجب ضبط هذه العلامة إلى "true" في الكود المخصص إذا لسبب ما يجب معالجة الملف المقترح ليس بالكود المخصص بل بكود المحول نفسه بالطريقة القياسية للمحول. لذلك، تعني ضبط الإعداد إلى true أن الكود المخصص لم يعالج الملف المشار إليه ويجب على المحول التعامل معه بنفسه (في كلا الحالتين - للحفظ في مكان ما ولتسمية الملف في الإشارة إليه). |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | يجب ضبط هذه العلامة إلى "true" في الكود المخصص إذا لسبب ما يجب معالجة الملف المقترح ليس بالكود المخصص بل بكود المحول نفسه بالطريقة القياسية للمحول. لذلك، تعني ضبط الإعداد إلى true أن الكود المخصص لم يعالج الملف المشار إليه ويجب على المحول التعامل معه بنفسه (في كلا الحالتين - للحفظ في مكان ما ولتسمية الملف في الإشارة إليه). |

### getContentStream {#getContentStream--}
```
public byte[] getContentStream()
```

تم التعيين بواسطة المحول. يمثل المحتوى الثنائي للملف المحفوظ.

**Returns:**
مصفوفة من البايتات

### getResourceType {#getResourceType--}
```
public SaveOptions.NodeLevelResourceType getResourceType()
```

تم التعيين بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى كود الطريقة المخصصة يمكن استخدامه في الكود المخصص لتحديد كيفية المعالجة أو أين يتم حفظ الملف.

**Returns:**
عنصر NodeLevelResourceType @see NodeLevelResourceType

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

تم التعيين بواسطة المحول. اسم الملف المفترض الذي ينتقل من المحول إلى كود الطريقة المخصصة يمكن استخدامه في الكود المخصص لتحديد كيفية المعالجة أو أين يتم حفظ الملف.

**Returns:**
قيمة سلسلة

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

يجب ضبط هذه العلامة إلى "true" في الكود المخصص إذا لسبب ما يجب معالجة الملف المقترح ليس بالكود المخصص بل بكود المحول نفسه بالطريقة القياسية للمحول. لذلك، تعني ضبط الإعداد إلى true أن الكود المخصص لم يعالج الملف المشار إليه ويجب على المحول التعامل معه بنفسه (في كلا الحالتين - للحفظ في مكان ما ولتسمية الملف في الإشارة إليه).

**Returns:**
قيمة منطقية

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

يجب ضبط هذه العلامة إلى "true" في الكود المخصص إذا لسبب ما يجب معالجة الملف المقترح ليس بالكود المخصص بل بكود المحول نفسه بالطريقة القياسية للمحول. لذلك، تعني ضبط الإعداد إلى true أن الكود المخصص لم يعالج الملف المشار إليه ويجب على المحول التعامل معه بنفسه (في كلا الحالتين - للحفظ في مكان ما ولتسمية الملف في الإشارة إليه).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| customProcessingCancelled |  | قيمة منطقية |
