---
title: "OutlineCollection"
linktitle: "OutlineCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل تسلسل هيكل مخطط المستند."
type: docs
weight: 3260
url: /ar/java/com.aspose.pdf/outlinecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineCollection extends Outlines
```

يمثل تسلسل هيكل مخطط المستند.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | يضيف عنصر المخطط إلى المجموعة. |
| [clear](#clear--) | يمسح جميع العناصر من المجموعة. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | غير مدعوم بعد. يتحقق مما إذا كانت المجموعة تحتوي على العنصر المحدد. |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | ينسخ عناصر المخطط إلى System.Array، بدءًا من فهرس System.Array معين. |
| [delete](#delete--) | يحذف جميع عناصر المخطط من مخطط المستند. |
| [delete](#delete-java.lang.String-) | يحذف جميع عناصر المخطط من مخطط المستند. |
| [get_Item](#get_Item-int-) | يحصل على عنصر المخطط من المجموعة حسب الفهرس. |
| [getFirst](#getFirst--) | يحصل على عنصر مخطط يمثل العنصر الأعلى المستوى الأول في المخطط. |
| [getLast](#getLast--) | يحصل على عنصر مخطط يمثل العنصر الأعلى المستوى الأخير في المخطط. |
| [getSyncRoot](#getSyncRoot--) | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى هذه المجموعة. |
| [getVisibleCount](#getVisibleCount--) | العدد هو مجموع عدد عناصر المخطط الظاهرة المتفرعة في جميع المستويات. ملاحظة: يرجى عدم الخلط بين Count الذي هو عدد العناصر في المجموعة. |
| [hasNext](#hasNext--) |  |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| [isSynchronized](#isSynchronized--) | يحصل على قيمة تشير إلى ما إذا كان الوصول إلى هذه المجموعة متزامنًا (آمن للخيوط). |
| [iterator](#iterator--) | يرجع عدادًا يتنقل عبر المجموعة. |
| [next](#next--) |  |
| [remove](#remove-int-) | إزالة العنصر حسب الفهرس. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | غير مدعوم بعد. دائمًا يرمي استثناءً. |
| [size](#size--) | يحصل على العدد الإجمالي لعناصر المخطط (الإشارات المرجعية) في جميع مستويات مخطط المستند. |

### add {#add-com.aspose.pdf.OutlineItemCollection-}
يضيف عنصر المخطط إلى المجموعة.

### clear {#clear--}
```
public void clear()
```

يمسح جميع العناصر من المجموعة.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
غير مدعوم بعد. يتحقق مما إذا كانت المجموعة تحتوي على العنصر المحدد.

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
ينسخ عناصر المخطط إلى System.Array، بدءًا من فهرس System.Array معين.

### delete {#delete--}
```
public void delete()
```

يحذف جميع عناصر المخطط من مخطط المستند.

### delete {#delete-java.lang.String-}
يحذف جميع عناصر المخطط من مخطط المستند.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

يحصل على عنصر المخطط من المجموعة حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس العنصر المطلوب. |

**Returns:**
كائن OutlineItemCollection

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

يحصل على عنصر مخطط يمثل العنصر الأعلى المستوى الأول في المخطط.

**Returns:**
كائن OutlineItemCollection

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

يحصل على عنصر مخطط يمثل العنصر الأعلى المستوى الأخير في المخطط.

**Returns:**
كائن OutlineItemCollection

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى هذه المجموعة.

**Returns:**
كائن للمزامنة

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

العدد هو مجموع عدد عناصر المخطط الظاهرة المتفرعة في جميع المستويات. ملاحظة: يرجى عدم الخلط بين Count الذي هو عدد العناصر في المجموعة.

**Returns:**
قيمة int

### hasNext {#hasNext--}
```
public boolean hasNext()
```



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

يحصل على قيمة تشير إلى ما إذا كان الوصول إلى هذه المجموعة متزامنًا (آمن للخيوط).

**Returns:**
قيمة منطقية

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

يرجع عدادًا يتنقل عبر المجموعة.

**Returns:**
كائن System.Collections.IEnumerator يمكن استخدامه للتنقل عبر المجموعة.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

إزالة العنصر حسب الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | فهرس العنصر الذي سيتم إزالته. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
غير مدعوم بعد. دائمًا يرمي استثناءً.

### size {#size--}
```
public int size()
```

يحصل على العدد الإجمالي لعناصر المخطط (الإشارات المرجعية) في جميع مستويات مخطط المستند.

**Returns:**
قيمة int
