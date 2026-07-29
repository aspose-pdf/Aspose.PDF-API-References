---
title: "ActionCollection"
linktitle: "ActionCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "مجموعة من الإجراءات"
type: docs
weight: 40
url: /ar/java/com.aspose.pdf/actioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public final class ActionCollection extends Object implements Iterable < PdfAction >
```

مجموعة من الإجراءات

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | يضيف إجراءً جديدًا إلى المجموعة. |
| [clear](#clear--) | مسح المجموعة. |
| [contains](#contains-com.aspose.pdf.PdfAction-) | غير مدعوم بعد. يُعيد true إذا كان العنصر المعطى موجودًا في المجموعة. |
| [copyTo](#copyTo-com.aspose.pdf.PdfAction:A-int-) | ينسخ مصفوفة الإجراءات إلى المجموعة. |
| [delete](#delete--) | حذف جميع الإجراءات. |
| [delete](#delete-int-) | يزيل الإجراء من المجموعة حسب الفهرس. |
| [get_Item](#get_Item-int-) | يحصل على الإجراء حسب فهرسه. |
| [getSyncRoot](#getSyncRoot--) | يحصل على كائن المزامنة. |
| [isReadOnly](#isReadOnly--) | يُعيد true إذا كانت المجموعة للقراءة فقط. |
| [isSynchronized](#isSynchronized--) | يُعيد true إذا كان الكائن متزامنًا. |
| [iterator](#iterator--) | / * / * يعيد المُعدد للمجموعة. / * / * / * |
| [remove](#remove-com.aspose.pdf.PdfAction-) | * غير مدعوم بعد. يزيل العنصر من المجموعة. |
| [size](#size--) | عدد الإجراءات في المجموعة. |

### add {#add-com.aspose.pdf.PdfAction-}
يضيف إجراءً جديدًا إلى المجموعة.

### clear {#clear--}
```
public void clear()
```

مسح المجموعة.

### contains {#contains-com.aspose.pdf.PdfAction-}
غير مدعوم بعد. يُعيد true إذا كان العنصر المعطى موجودًا في المجموعة.

### copyTo {#copyTo-com.aspose.pdf.PdfAction:A-int-}
ينسخ مصفوفة الإجراءات إلى المجموعة.

### delete {#delete--}
```
public void delete()
```

حذف جميع الإجراءات.

### delete {#delete-int-}
```
public void delete(int index)
```

يزيل الإجراء من المجموعة حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الإجراء للإزالة. |

### get_Item {#get_Item-int-}
```
public PdfAction get_Item(int index)
```

يحصل على الإجراء حسب فهرسه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الإجراء. |

**Returns:**
الإجراء المسترجع.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

يحصل على كائن المزامنة.

**Returns:**
قيمة Object

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

يُعيد true إذا كانت المجموعة للقراءة فقط.

**Returns:**
قيمة منطقية

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

يُعيد true إذا كان الكائن متزامنًا.

**Returns:**
قيمة منطقية

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator()
```

/ * / * يعيد المُعدد للمجموعة. / * / * / *

**Returns:**
عداد المجموعة. /

### remove {#remove-com.aspose.pdf.PdfAction-}
* Not supported yet. Removes item from collection.

### size {#size--}
```
public int size()
```

عدد الإجراءات في المجموعة.

**Returns:**
قيمة int
