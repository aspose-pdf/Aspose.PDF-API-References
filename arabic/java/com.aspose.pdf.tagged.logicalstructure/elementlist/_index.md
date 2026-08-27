---
title: "ElementList"
linktitle: "ElementList"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل مجموعة مرتبة من العناصر."
type: docs
weight: 40
url: /ar/java/com.aspose.pdf.tagged.logicalstructure/elementlist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public abstract class ElementList extends Object implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >
```

يمثل مجموعة مرتبة من العناصر.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | أضف عنصرًا إلى القائمة. |
| [get_Item](#get_Item-int-) |  |
| [getCount](#getCount--) | يحصل على عدد العناصر في ElementList. |
| [insertElement](#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | إدراج عنصر إلى القائمة. |
| [item](#item-int-) | يسترجع عنصرًا عند الفهرس المحدد. |
| [iterator](#iterator--) | يحصل على عداد يتنقل عبر مجموعة العناصر. |
| [removeAt](#removeAt-int-) | إزالة عنصر من القائمة. |
| [removeElement](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | إزالة عنصر من القائمة. |

### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
أضف عنصرًا إلى القائمة.

### get_Item {#get_Item-int-}
```
public Element get_Item(int index)
```



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  |  |

### getCount {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد العناصر في ElementList.

**Returns:**
قيمة int

### insertElement {#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
إدراج عنصر إلى القائمة.

### item {#item-int-}
```
public abstract Element item(int index)
```

يسترجع عنصرًا عند الفهرس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | الفهرس في قائمة العناصر. |

**Returns:**
الـ {@code /Aspose.Pdf.LogicalStructure.Element} ذات الفهرس المحدد في المجموعة. إذا كان {@code index} أكبر من أو يساوي عدد العناصر في القائمة، فإن هذا يُعيد null.

### iterator {#iterator--}
```
public abstract com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

يحصل على عداد يتنقل عبر مجموعة العناصر.

**Returns:**
عداد يُستخدم للتنقل عبر مجموعة العناصر.

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

إزالة عنصر من القائمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  | الفهرس للإزالة. |

### removeElement {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
إزالة عنصر من القائمة.
