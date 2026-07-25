---
title: "OptionCollection"
linktitle: "OptionCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل مجموعة خيارات حقل الاختيار."
type: docs
weight: 3250
url: /ar/java/com.aspose.pdf/optioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.OptionCollection

**All Implemented Interfaces:**
Iterable < Option >

```
public final class OptionCollection extends Object implements Iterable < Option >
```

فئة تمثل مجموعة خيارات حقل الاختيار.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.Option-) | يضيف عنصرًا إلى المجموعة، يرمي . لم يتم التنفيذ بعد. |
| [clear](#clear--) | يزيل جميع العناصر من المجموعة. |
| [contains](#contains-com.aspose.pdf.Option-) | يتحقق مما إذا كان العنصر موجودًا في المجموعة، يرمي . لم يتم التنفيذ بعد. |
| [deleteOption](#deleteOption-java.lang.String-) | يحذف الخيار حسب اسمه. |
| [get_Item](#get_Item-int-) | يحصل على الخيار حسب الفهرس. |
| [get_Item](#get_Item-java.lang.String-) | يحصل على الخيار باسمه. |
| [get](#get-int-) | يحصل على الخيار حسب الفهرس. |
| [get](#get-java.lang.String-) | يحصل على الخيار من المجموعة باستخدام اسم الخيار. |
| [getSyncRoot](#getSyncRoot--) | كائن المزامنة للمجموعة. |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| [isSynchronized](#isSynchronized--) | يرجع true إذا كان الكائن متزامنًا. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | يرجع عدادًا للخيارات في المجموعة. |
| [iterator](#iterator--) | يرجع عدادًا للخيارات في المجموعة. |
| [remove](#remove-com.aspose.pdf.Option-) | يزيل العنصر من المجموعة، يرمي . لم يتم تنفيذها بعد. |
| [size](#size--) | يحصل على عدد الخيارات. |

### add {#add-com.aspose.pdf.Option-}
يضيف عنصرًا إلى المجموعة، يرمي . لم يتم التنفيذ بعد.

### clear {#clear--}
```
public void clear()
```

يزيل جميع العناصر من المجموعة.

### contains {#contains-com.aspose.pdf.Option-}
يتحقق مما إذا كان العنصر موجودًا في المجموعة، يرمي . لم يتم التنفيذ بعد.

### deleteOption {#deleteOption-java.lang.String-}
يحذف الخيار حسب اسمه.

### get_Item {#get_Item-int-}
```
public Option get_Item(int index)
```

يحصل على الخيار حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الخيار. |

**Returns:**
الخيار في الفهرس المحدد.

### get_Item {#get_Item-java.lang.String-}
يحصل على الخيار باسمه.

### get {#get-int-}
```
public Option get(int index)
```

يحصل على الخيار حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس الخيار. يجب أن يكون الفهرس في النطاق [1..n] حيث n هو عدد الخيارات. |

**Returns:**
الخيار المسترجع.

### get {#get-java.lang.String-}
يحصل على الخيار من المجموعة باستخدام اسم الخيار.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

كائن المزامنة للمجموعة.

**Returns:**
عنصر Object

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

يرجع true إذا كان الكائن متزامنًا.

**Returns:**
قيمة منطقية

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

يرجع عدادًا للخيارات في المجموعة.

**Returns:**
عداد الخيارات.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< Option > iterator()
```

يرجع عدادًا للخيارات في المجموعة.

**Returns:**
عداد الخيارات.

### remove {#remove-com.aspose.pdf.Option-}
يزيل العنصر من المجموعة، يرمي . لم يتم تنفيذها بعد.

### size {#size--}
```
public int size()
```

يحصل على عدد الخيارات.

**Returns:**
قيمة int
