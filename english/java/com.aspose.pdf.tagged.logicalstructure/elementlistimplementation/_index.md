---
title: ElementListImplementation
linktitle: ElementListImplementation
second_title: Aspose.PDF for Java API Reference
description:
type: docs
weight: 50
url: /java/com.aspose.pdf.tagged.logicalstructure/elementlistimplementation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList com.aspose.pdf.tagged.logicalstructure.ElementListImplementation, com.aspose.pdf.tagged.logicalstructure.ElementList, com.aspose.pdf.tagged.logicalstructure.ElementListImplementation

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public class ElementListImplementation extends ElementList
```



## Constructors

| Constructor | Description |
| --- | --- |
| [ElementListImplementation](#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |

## Methods

| Method | Description |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Add element to list. |
| [getCount](#getCount--) | Gets the number of elements in the ElementList. |
| [item](#item-int-) | Retrieves a element at the given index. |
| [iterator](#iterator--) | Gets an enumerator that iterates through the collection of elements. |

### ElementListImplementation {#ElementListImplementation-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Add element to list.

### getCount {#getCount--}
```
public int getCount()
```

Gets the number of elements in the ElementList.

**Returns:**
int value

### item {#item-int-}
```
public Element item(int index)
```

Retrieves a element at the given index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  |  |

**Returns:**
The /Aspose.Pdf.LogicalStructure.Element with the specified index in the collection. If index is greater than or equal to the number of elements in the list, this returns null.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Gets an enumerator that iterates through the collection of elements.

**Returns:**
An enumerator used to iterate through the collection of elements.
