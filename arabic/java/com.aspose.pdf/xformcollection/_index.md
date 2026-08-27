---
title: "XFormCollection"
linktitle: "XFormCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "الفئة تمثل مجموعة XFormCollection."
type: docs
weight: 5600
url: /ar/java/com.aspose.pdf/xformcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFormCollection

**All Implemented Interfaces:**
Iterable < XForm >

```
public final class XFormCollection extends Object implements Iterable < XForm >
```

الفئة تمثل مجموعة XFormCollection.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.XForm-) | يضيف XForm جديدًا إلى المجموعة. |
| [clear](#clear--) | يمسح جميع العناصر من المجموعة. |
| [contains](#contains-com.aspose.pdf.XForm-) | يحدّد ما إذا كانت المجموعة تحتوي على قيمة محددة. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | ينسخ XFormCollection إلى المجموعة. |
| [delete](#delete--) | يحذف جميع XForms من المجموعة. |
| [delete](#delete-int-) | احذف XForm من المجموعة |
| [delete](#delete-java.lang.String-) | يحذف جميع XForms من المجموعة. |
| [freeMemory](#freeMemory--) | يمسح البيانات المخزنة مؤقتًا، ويحرّر الذاكرة، إلخ. |
| [get_Item](#get_Item-int-) | يعيد XForm حسب الفهرس. |
| [get_Item](#get_Item-java.lang.String-) | يعيد XForm حسب اسمه. يتم إلقاء استثناء إذا لم يُعثر على XForm بالاسم المحدد. |
| [getFormName](#getFormName-com.aspose.pdf.XForm-) | يعيد اسم النموذج في مجموعة النماذج هذه |
| [getSyncRoot](#getSyncRoot--) | كائن المزامنة. |
| [hasForm](#hasForm-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| [isSynchronized](#isSynchronized--) | يُعيد true إذا كان الكائن متزامنًا. |
| [iterator](#iterator--) | يعيد عداد المجموعة. |
| [remove](#remove-com.aspose.pdf.XForm-) | يحذف العنصر المحدد من المجموعة. |
| [size](#size--) | يحصل على عدد XForms في المجموعة. |

### add {#add-com.aspose.pdf.XForm-}
يضيف XForm جديدًا إلى المجموعة.

### clear {#clear--}
```
public void clear()
```

يمسح جميع العناصر من المجموعة.

### contains {#contains-com.aspose.pdf.XForm-}
يحدّد ما إذا كانت المجموعة تحتوي على قيمة محددة.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
ينسخ XFormCollection إلى المجموعة.

### delete {#delete--}
```
public void delete()
```

يحذف جميع XForms من المجموعة.

### delete {#delete-int-}
```
public void delete(int index)
```

احذف XForm من المجموعة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس XForm الذي يجب حذفه |

### delete {#delete-java.lang.String-}
يحذف جميع XForms من المجموعة.

### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

يمسح البيانات المخزنة مؤقتًا، ويحرّر الذاكرة، إلخ.

### get_Item {#get_Item-int-}
```
public XForm get_Item(int index)
```

يعيد XForm حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس XFormCollection. يبدأ ترقيم XForms من 1 |

**Returns:**
XForm المسترجع

### get_Item {#get_Item-java.lang.String-}
يعيد XForm حسب اسمه. يتم إلقاء استثناء إذا لم يُعثر على XForm بالاسم المحدد.

### getFormName {#getFormName-com.aspose.pdf.XForm-}
يعيد اسم النموذج في مجموعة النماذج هذه

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

كائن المزامنة.

**Returns:**
Object

### hasForm {#hasForm-java.lang.String-}


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

يُعيد true إذا كان الكائن متزامنًا.

**Returns:**
boolean

### iterator {#iterator--}
```
public Iterator < XForm > iterator()
```

يعيد عداد المجموعة.

**Returns:**
المُعدِّد للمجموعة

### remove {#remove-com.aspose.pdf.XForm-}
يحذف العنصر المحدد من المجموعة.

### size {#size--}
```
public int size()
```

يحصل على عدد XForms في المجموعة.

**Returns:**
قيمة int
