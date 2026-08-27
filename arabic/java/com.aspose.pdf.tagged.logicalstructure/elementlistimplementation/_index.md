---
title: "ElementListImplementation"
linktitle: "ElementListImplementation"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description:
type: docs
weight: 50
url: /ar/java/com.aspose.pdf.tagged.logicalstructure/elementlistimplementation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList com.aspose.pdf.tagged.logicalstructure.ElementListImplementation, com.aspose.pdf.tagged.logicalstructure.ElementList, com.aspose.pdf.tagged.logicalstructure.ElementListImplementation

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public class ElementListImplementation extends ElementList
```



## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ElementListImplementation](#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | أضف عنصرًا إلى القائمة. |
| [getCount](#getCount--) | يحصل على عدد العناصر في ElementList. |
| [item](#item-int-) | يسترجع عنصرًا عند الفهرس المحدد. |
| [iterator](#iterator--) | يحصل على عداد يتنقل عبر مجموعة العناصر. |

### ElementListImplementation {#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
أضف عنصرًا إلى القائمة.

### getCount {#getCount--}
```
public int getCount()
```

يحصل على عدد العناصر في ElementList.

**Returns:**
قيمة int

### item {#item-int-}
```
public Element item(int index)
```

يسترجع عنصرًا عند الفهرس المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| index |  |  |

**Returns:**
العنصر /Aspose.Pdf.LogicalStructure.Element بالمؤشر المحدد في المجموعة. إذا كان المؤشر أكبر من أو يساوي عدد العناصر في القائمة، فإن هذا يرجع null.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

يحصل على عداد يتنقل عبر مجموعة العناصر.

**Returns:**
عداد يُستخدم للتنقل عبر مجموعة العناصر.
