---
title: "AnnotationCollection"
linktitle: "AnnotationCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثّل مجموعة التعليقات التوضيحية."
type: docs
weight: 80
url: /ar/java/com.aspose.pdf/annotationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AnnotationCollection

**All Implemented Interfaces:**
Iterable < Annotation >

```
public final class AnnotationCollection extends Object implements Iterable < Annotation >
```

فئة تمثّل مجموعة التعليقات التوضيحية.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [AnnotationCollection](#AnnotationCollection-com.aspose.pdf.Page-) | منشئ AnnotationCollection. ينشئ مجموعة تعليقات توضيحية للتعليقات على الصفحة المحددة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | يقبل الزائر لمعالجة التعليق التوضيحي. |
| [add](#add-com.aspose.pdf.Annotation-) | يضيف التعليق التوضيحي إلى المجموعة. |
| [add](#add-com.aspose.pdf.Annotation-boolean-) | يضيف التعليق التوضيحي إلى المجموعة. إذا تم تدوير الصفحة، فسيتم إعادة حساب مستطيل التعليق التوضيحي وفقًا لذلك. |
| [clear](#clear--) | يحذف جميع التعليقات التوضيحية من المجموعة. |
| [contains](#contains-com.aspose.pdf.Annotation-) | يتحقق مما إذا كان التعليق التوضيحي المحدد ينتمي إلى المجموعة. |
| [copyTo](#copyTo-com.aspose.pdf.Annotation:A-int-) | ينسخ مصفوفة التعليقات التوضيحية إلى المجموعة. |
| [delete](#delete--) | يحذف جميع التعليقات التوضيحية من المجموعة. |
| [delete](#delete-com.aspose.pdf.Annotation-) | يحذف جميع التعليقات التوضيحية من المجموعة. |
| [delete](#delete-int-) | يحذف التعليق التوضيحي من المجموعة حسب الفهرس. |
| [findByName](#findByName-java.lang.String-) | يرجع التعليق التوضيحي باسمه. |
| [get_Item](#get_Item-int-) | فهرس العنصر المراد الحصول عليه. |
| [getSyncRoot](#getSyncRoot--) | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى com.aspose.pdf.AnnotationCollection. |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| [isSynchronized](#isSynchronized--) | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى com.aspose.pdf.AnnotationCollection متزامنًا (آمن للخيوط). |
| [iterator](#iterator--) | يعيد عداد المجموعة. |
| [remove](#remove-com.aspose.pdf.Annotation-) | يحذف التعليق المحدد من المجموعة. |
| [size](#size--) | يحصل على عدد التعليقات في المجموعة. |

### AnnotationCollection {#AnnotationCollection-com.aspose.pdf.Page-}
منشئ AnnotationCollection. ينشئ مجموعة تعليقات توضيحية للتعليقات على الصفحة المحددة.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
يقبل الزائر لمعالجة التعليق التوضيحي.

### add {#add-com.aspose.pdf.Annotation-}
يضيف التعليق التوضيحي إلى المجموعة.

### add {#add-com.aspose.pdf.Annotation-boolean-}
يضيف التعليق التوضيحي إلى المجموعة. إذا تم تدوير الصفحة، فسيتم إعادة حساب مستطيل التعليق التوضيحي وفقًا لذلك.

### clear {#clear--}
```
public void clear()
```

يحذف جميع التعليقات التوضيحية من المجموعة.

### contains {#contains-com.aspose.pdf.Annotation-}
يتحقق مما إذا كان التعليق التوضيحي المحدد ينتمي إلى المجموعة.

### copyTo {#copyTo-com.aspose.pdf.Annotation:A-int-}
ينسخ مصفوفة التعليقات التوضيحية إلى المجموعة.

### delete {#delete--}
```
public void delete()
```

يحذف جميع التعليقات التوضيحية من المجموعة.

### delete {#delete-com.aspose.pdf.Annotation-}
يحذف جميع التعليقات التوضيحية من المجموعة.

### delete {#delete-int-}
```
public void delete(int index)
```

يحذف التعليق التوضيحي من المجموعة حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس التعليق الذي سيتم حذفه. |

### findByName {#findByName-java.lang.String-}
يرجع التعليق التوضيحي باسمه.

### get_Item {#get_Item-int-}
```
public Annotation get_Item(int index)
```

فهرس العنصر المراد الحصول عليه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | قيمة الفهرس تبدأ من الواحد. |

**Returns:**
كائن التعليق

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى com.aspose.pdf.AnnotationCollection.

**Returns:**
كائن للمزامنة

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط.

**Returns:**
قيمة منطقية

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

يحصل على قيمة تشير إلى ما إذا كان الوصول إلى com.aspose.pdf.AnnotationCollection متزامنًا (آمن للخيوط).

**Returns:**
قيمة منطقية

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Annotation > iterator()
```

يعيد عداد المجموعة.

**Returns:**
كائن عداد

### remove {#remove-com.aspose.pdf.Annotation-}
يحذف التعليق المحدد من المجموعة.

### size {#size--}
```
public int size()
```

يحصل على عدد التعليقات في المجموعة.

**Returns:**
قيمة int
