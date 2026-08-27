---
title: "OutlineItemCollection"
linktitle: "OutlineItemCollection"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل مدخل المخطط في تسلسل هيكل المخطط لوثيقة PDF."
type: docs
weight: 3270
url: /ar/java/com.aspose.pdf/outlineitemcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineItemCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineItemCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineItemCollection extends Outlines
```

يمثل مدخل المخطط في تسلسل هيكل المخطط لوثيقة PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-) | يُنشئ مثلاً جديداً لهذه الفئة باستخدام كائن إدخال المخطط الداخلي للمحرك. |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.OutlineCollection-) | يُنشئ مثلاً لعنصر المخطط باستخدام كائن التسلسل الهرمي الجذر. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | يضيف عنصر المخطط إلى المجموعة. |
| [clear](#clear--) | يمسح جميع العناصر من المجموعة. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | غير مدعوم بعد. دائماً يرمي NotImplementedException |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | ينسخ إدخالات المخطط إلى System.Array، بدءاً من فهرس System.Array معين. |
| [delete](#delete--) | يحذف عنصر المخطط هذا من تسلسل هرمي مخطط المستند. |
| [delete](#delete-java.lang.String-) | يحذف عنصر المخطط هذا من تسلسل هرمي مخطط المستند. |
| [get_Item](#get_Item-int-) | يحصل على عنصر المخطط من المجموعة باستخدام الفهرس. |
| [getAction](#getAction--) | يحصل على الإجراء لهذا عنصر المخطط. |
| [getBold](#getBold--) | يحصل على علامة الخط العريض لنص عنوان هذا عنصر المخطط |
| [getColor](#getColor--) | يحصل على اللون لنص عنوان هذا عنصر المخطط. |
| [getDestination](#getDestination--) | يحصل على الوجهة لهذا عنصر المخطط. |
| [getEngineDict](#getEngineDict--) | داخلي فقط |
| [getEngineObj](#getEngineObj--) | داخلي فقط |
| [getFirst](#getFirst--) | يحصل على عنصر المخطط الذي يمثل أول عنصر من المستوى الأعلى في تسلسل هرمي المخطط. |
| [getItalic](#getItalic--) | يحصل على علامة المائل لنص عنوان هذا عنصر المخطط |
| [getLast](#getLast--) | يحصل على عنصر المخطط الذي يمثل آخر عنصر من المستوى الأعلى في تسلسل هرمي المخطط. |
| [getLevel](#getLevel--) | يحصل على مستوى التسلسل الهرمي لعنصر المخطط. |
| [getNext](#getNext--) | يحصل على عنصر المخطط الذي يمثل العنصر التالي نسبياً لهذا العنصر في تسلسل هرمي المخطط. |
| [getOpen](#getOpen--) | احصل على حالة الفتح (true/false) لعنصر المخطط. |
| [getParent](#getParent--) | يحصل على كائن الأصل لهذا عنصر المخطط في تسلسل هرمي المخطط. |
| [getPrev](#getPrev--) | يحصل على عنصر المخطط الذي يمثل العنصر السابق نسبياً لهذا العنصر في تسلسل هرمي المخطط. |
| [getSyncRoot](#getSyncRoot--) | يحصل على الكائن الذي يمكن استخدامه لمزامنة الوصول إلى هذه المجموعة. |
| [getTitle](#getTitle--) | يحصل على العنوان لهذا عنصر المخطط. |
| [getVisibleCount](#getVisibleCount--) | يحصل على العدد الإجمالي لعناصر المخطط في جميع المستويات في تسلسل هرمي مخطط المستند. |
| [hasNext](#hasNext--) | تحقق مما إذا كان عنصر المخطط يمثل العنصر التالي بالنسبة لهذا العنصر في تسلسل هيكل المخطط. |
| [insert](#insert-int-com.aspose.pdf.OutlineItemCollection-) | يدخل عنصر المخطط في المجموعة في المكان المحدد. |
| [isReadOnly](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كانت المجموعة للقراءة فقط. |
| [isSynchronized](#isSynchronized--) | يحصل على القيمة التي تشير إلى ما إذا كان الوصول إلى هذه المجموعة متزامنًا (آمن للخيوط). |
| [iterator](#iterator--) | يرجع عدادًا يتنقل عبر المجموعة. |
| [next](#next--) |  |
| [remove](#remove-int-) | إزالة العنصر حسب الفهرس. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | غير مدعوم بعد. دائماً يرمي NotImplementedException |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | يضبط الإجراء لهذا العنصر في المخطط. |
| [setBold](#setBold-boolean-) | يضبط علامة الغامق لنص العنوان لهذا العنصر في المخطط |
| [setColor](#setColor-java.awt.Color-) | يضبط اللون لنص العنوان لهذا العنصر في المخطط. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | يضبط الوجهة لهذا العنصر في المخطط. |
| [setItalic](#setItalic-boolean-) | يضبط علامة المائل لنص العنوان لهذا العنصر في المخطط |
| [setOpen](#setOpen-boolean-) | يضبط حالة الفتح (صحيح/خطأ) للعنصر في المخطط. |
| [setTitle](#setTitle-java.lang.String-) | يضبط العنوان لهذا العنصر في المخطط. |
| [size](#size--) | عدد عناصر المجموعة. يرجى عدم الخلط مع VisibleCount: يحصل VisibleCount على عدد عناصر المخطط المرئية على جميع المستويات. |

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-}
يُنشئ مثلاً جديداً لهذه الفئة باستخدام كائن إدخال المخطط الداخلي للمحرك.

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.OutlineCollection-}
يُنشئ مثلاً لعنصر المخطط باستخدام كائن التسلسل الهرمي الجذر.

### add {#add-com.aspose.pdf.OutlineItemCollection-}
يضيف عنصر المخطط إلى المجموعة.

### clear {#clear--}
```
public void clear()
```

يمسح جميع العناصر من المجموعة.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
غير مدعوم بعد. دائماً يرمي NotImplementedException

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
ينسخ إدخالات المخطط إلى System.Array، بدءاً من فهرس System.Array معين.

### delete {#delete--}
```
public void delete()
```

يحذف عنصر المخطط هذا من تسلسل هرمي مخطط المستند.

### delete {#delete-java.lang.String-}
يحذف عنصر المخطط هذا من تسلسل هرمي مخطط المستند.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

يحصل على عنصر المخطط من المجموعة باستخدام الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | الفهرس داخل المجموعة. |

**Returns:**
كائن OutlineItemCollection.

### getAction {#getAction--}
```
public PdfAction getAction()
```

يحصل على الإجراء لهذا عنصر المخطط.

**Returns:**
قيمة PdfAction

### getBold {#getBold--}
```
public boolean getBold()
```

يحصل على علامة الخط العريض لنص عنوان هذا عنصر المخطط

**Returns:**
قيمة منطقية

### getColor {#getColor--}
```
public Color getColor()
```

يحصل على اللون لنص عنوان هذا عنصر المخطط.

**Returns:**
قيمة اللون

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

يحصل على الوجهة لهذا عنصر المخطط.

**Returns:**
قيمة IAppointment

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

داخلي فقط

**Returns:**
كائن IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

داخلي فقط

**Returns:**
كائن IPdfObject

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

يحصل على عنصر المخطط الذي يمثل أول عنصر من المستوى الأعلى في تسلسل هرمي المخطط.

**Returns:**
قيمة OutlineItemCollection

### getItalic {#getItalic--}
```
public boolean getItalic()
```

يحصل على علامة المائل لنص عنوان هذا عنصر المخطط

**Returns:**
قيمة منطقية

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

يحصل على عنصر المخطط الذي يمثل آخر عنصر من المستوى الأعلى في تسلسل هرمي المخطط.

**Returns:**
قيمة OutlineItemCollection

### getLevel {#getLevel--}
```
public int getLevel()
```

يحصل على مستوى التسلسل الهرمي لعنصر المخطط.

**Returns:**
قيمة int

### getNext {#getNext--}
```
public OutlineItemCollection getNext()
```

يحصل على عنصر المخطط الذي يمثل العنصر التالي نسبياً لهذا العنصر في تسلسل هرمي المخطط.

**Returns:**
قيمة OutlineItemCollection

### getOpen {#getOpen--}
```
public boolean getOpen()
```

احصل على حالة الفتح (true/false) لعنصر المخطط.

**Returns:**
قيمة منطقية

### getParent {#getParent--}
```
public Outlines getParent()
```

يحصل على كائن الأصل لهذا عنصر المخطط في تسلسل هرمي المخطط.

**Returns:**
قيمة Object

### getPrev {#getPrev--}
```
public OutlineItemCollection getPrev()
```

يحصل على عنصر المخطط الذي يمثل العنصر السابق نسبياً لهذا العنصر في تسلسل هرمي المخطط.

**Returns:**
قيمة OutlineItemCollection

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

يحصل على الكائن الذي يمكن استخدامه لمزامنة الوصول إلى هذه المجموعة.

**Returns:**
قيمة Object

### getTitle {#getTitle--}
```
public String getTitle()
```

يحصل على العنوان لهذا عنصر المخطط.

**Returns:**
قيمة سلسلة

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

يحصل على العدد الإجمالي لعناصر المخطط في جميع المستويات في تسلسل هرمي مخطط المستند.

**Returns:**
قيمة int

### hasNext {#hasNext--}
```
public final boolean hasNext()
```

تحقق مما إذا كان عنصر المخطط يمثل العنصر التالي بالنسبة لهذا العنصر في تسلسل هيكل المخطط.

**Returns:**
قيمة منطقية

### insert {#insert-int-com.aspose.pdf.OutlineItemCollection-}
يدخل عنصر المخطط في المجموعة في المكان المحدد.

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

يحصل على القيمة التي تشير إلى ما إذا كان الوصول إلى هذه المجموعة متزامنًا (آمن للخيوط).

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
| index |  | فهرس العنصر الذي سيتم حذفه. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
غير مدعوم بعد. دائماً يرمي NotImplementedException

### setAction {#setAction-com.aspose.pdf.PdfAction-}
يضبط الإجراء لهذا العنصر في المخطط.

### setBold {#setBold-boolean-}
```
public void setBold(boolean value)
```

يضبط علامة الغامق لنص العنوان لهذا العنصر في المخطط

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setColor {#setColor-java.awt.Color-}
يضبط اللون لنص العنوان لهذا العنصر في المخطط.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
يضبط الوجهة لهذا العنصر في المخطط.

### setItalic {#setItalic-boolean-}
```
public void setItalic(boolean value)
```

يضبط علامة المائل لنص العنوان لهذا العنصر في المخطط

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

يضبط حالة الفتح (صحيح/خطأ) للعنصر في المخطط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setTitle {#setTitle-java.lang.String-}
يضبط العنوان لهذا العنصر في المخطط.

### size {#size--}
```
public int size()
```

عدد عناصر المجموعة. يرجى عدم الخلط مع VisibleCount: يحصل VisibleCount على عدد عناصر المخطط المرئية على جميع المستويات.

**Returns:**
قيمة int
