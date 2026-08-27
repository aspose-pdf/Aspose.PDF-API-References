---
title: "GraphicElementCollection"
linktitle: "GraphicElementCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل مجموعة {@link GraphicElement}."
type: docs
weight: 20
url: /ar/java/com.aspose.pdf.vector/graphicelementcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElementCollection

**All Implemented Interfaces:**
قابل للتكرار < GraphicElement >

```
public final class GraphicElementCollection extends Object implements Iterable < GraphicElement >
```

يمثل مجموعة {@link GraphicElement}.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [GraphicElementCollection](#GraphicElementCollection--) | يُهيئ المجموعة الجديدة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.vector.GraphicElement-) | يضيف {@link GraphicElement} جديدًا إلى المجموعة. يجب أن تكون جميع العناصر في المجموعة لها نفس {@code GraphicElement.Parent}({@link GraphicElement#getParent}). |
| [clear](#clear--) | يمسح المجموعة. |
| [contains](#contains-com.aspose.pdf.vector.GraphicElement-) | يحدد ما إذا كان العنصر موجودًا في المجموعة. |
| [copyTo](#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-) | ينسخ المجموعة بالكامل إلى مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد في مصفوفة الهدف. |
| [get_Item](#get_Item-int-) | يحصل على العنصر {@link GraphicElement} عند الفهرس المحدد. |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تُشير إلى ما إذا كانت المجموعة للقراءة فقط. دائمًا تُعيد false. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | يعيد عدّادًا للمجموعة بالكامل. |
| [iterator](#iterator--) | يعيد عدّادًا للمجموعة بالكامل. |
| [remove](#remove-com.aspose.pdf.vector.GraphicElement-) | يحذف العنصر {@link GraphicElement}. |
| [size](#size--) | يحصل على عدد عناصر كائن {@link GraphicElement} الموجودة فعليًا في المجموعة. |
| [toList](#toList--) | يعيد المجموعة الداخلية للتعداد غير المقيد. |
| [toString](#toString--) | يحصل على تمثيل نصي لهذه المجموعة. |

### GraphicElementCollection {#GraphicElementCollection--}
```
public GraphicElementCollection()
```

يُهيئ المجموعة الجديدة.

### add {#add-com.aspose.pdf.vector.GraphicElement-}
يضيف {@link GraphicElement} جديدًا إلى المجموعة. يجب أن تكون جميع العناصر في المجموعة لها نفس {@code GraphicElement.Parent}({@link GraphicElement#getParent}).

### clear {#clear--}
```
public final void clear()
```

يمسح المجموعة.

### contains {#contains-com.aspose.pdf.vector.GraphicElement-}
يحدد ما إذا كان العنصر موجودًا في المجموعة.

### copyTo {#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-}
ينسخ المجموعة بالكامل إلى مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد في مصفوفة الهدف.

### get_Item {#get_Item-int-}
```
public final GraphicElement get_Item(int index)
```

يحصل على العنصر {@link GraphicElement} عند الفهرس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | الفهرس داخل المجموعة. |

**Returns:**
{@link GraphicElement}.

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

يحصل على قيمة تُشير إلى ما إذا كانت المجموعة للقراءة فقط. دائمًا تُعيد false.

**Returns:**
قيمة منطقية

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public final com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

يعيد عدّادًا للمجموعة بالكامل.

**Returns:**
كائن عدّاد.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< GraphicElement > iterator()
```

يعيد عدّادًا للمجموعة بالكامل.

**Returns:**
كائن عدّاد.

### remove {#remove-com.aspose.pdf.vector.GraphicElement-}
يحذف العنصر {@link GraphicElement}.

### size {#size--}
```
public final int size()
```

يحصل على عدد عناصر كائن {@link GraphicElement} الموجودة فعليًا في المجموعة.

**Returns:**
قيمة int

### toList {#toList--}
```
public final com.aspose.ms.System.Collections.Generic.List< GraphicElement > toList()
```

يعيد المجموعة الداخلية للتعداد غير المقيد.

**Returns:**
القائمة الداخلية

### toString {#toString--}
```
public String toString()
```

يحصل على تمثيل نصي لهذه المجموعة.

**Returns:**
السلسلة.
