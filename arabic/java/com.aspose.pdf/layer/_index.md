---
title: "Layer"
linktitle: "Layer"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل طبقة داخل صفحة PDF."
type: docs
weight: 2640
url: /ar/java/com.aspose.pdf/layer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Layer

```
public class Layer extends Object
```

يمثل طبقة داخل صفحة PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Layer](#Layer-java.lang.String-java.lang.String-) | يُهيئ مثلاً جديداً من الفئة {@code Layer}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [delete](#delete--) | يحذف الطبقة الحالية من مستند PDF. |
| [flatten](#flatten-boolean-) | يقوم بتسطيح الطبقة المحددة. |
| [getContents](#getContents--) | <p> يحصل على محتوى الطبقة. </p> |
| [getDefaultState](#getDefaultState--) | يحصل على الحالة الافتراضية للطبقة PDF. |
| [getId](#getId--) | يحصل على معرّف الطبقة. |
| [getLocked](#getLocked--) | يحصل على قيمة تشير إلى ما إذا كانت الطبقة مقفلة. |
| [getName](#getName--) | يحصل على اسم الطبقة. |
| [lock](#lock--) | يقفل الطبقة. |
| [save](#save-java.io.OutputStream-) | يحفظ الطبقة الحالية إلى مستند PDF. |
| [save](#save-java.lang.String-) | يحفظ الطبقة الحالية إلى مستند PDF. |
| [setDefaultState](#setDefaultState-com.aspose.pdf.DefaultState-) | يضبط الحالة الافتراضية للطبقة PDF. |
| [unlock](#unlock--) | يفك قفل الطبقة. |

### Layer {#Layer-java.lang.String-java.lang.String-}
يُهيئ مثلاً جديداً من الفئة {@code Layer}.

### delete {#delete--}
```
public final void delete()
```

يحذف الطبقة الحالية من مستند PDF.

### flatten {#flatten-boolean-}
```
public final void flatten(boolean cleanupContentStream)
```

يقوم بتسطيح الطبقة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| cleanupContentStream |  | يحدد ما إذا كان يجب إزالة علامات مجموعة المحتوى الاختيارية من تدفق المحتوى. ضبط معلمة {@code cleanupContentStream} إلى false يسرّع عملية التسطيح. |

### getContents {#getContents--}
```
public List < Operator > getContents()
```

<p> يحصل على محتوى الطبقة. </p>

**Returns:**
{@code List<Operator>} كائن

### getDefaultState {#getDefaultState--}
```
public final DefaultState getDefaultState()
```

يحصل على الحالة الافتراضية للطبقة PDF.

**Returns:**
الحالة الافتراضية للطبقة PDF.

### getId {#getId--}
```
public String getId()
```

يحصل على معرّف الطبقة.

**Returns:**
قيمة سلسلة

### getLocked {#getLocked--}
```
public final boolean getLocked()
```

يحصل على قيمة تشير إلى ما إذا كانت الطبقة مقفلة.

**Returns:**
قيمة منطقية

### getName {#getName--}
```
public String getName()
```

يحصل على اسم الطبقة.

**Returns:**
قيمة سلسلة

### lock {#lock--}
```
public final void lock()
```

يقفل الطبقة.

### save {#save-java.io.OutputStream-}
يحفظ الطبقة الحالية إلى مستند PDF.

### save {#save-java.lang.String-}
يحفظ الطبقة الحالية إلى مستند PDF.

### setDefaultState {#setDefaultState-com.aspose.pdf.DefaultState-}
يضبط الحالة الافتراضية للطبقة PDF.

### unlock {#unlock--}
```
public final void unlock()
```

يفك قفل الطبقة.
