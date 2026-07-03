---
title: ElementList
second_title: Aspose.PDF for Java API Reference
description: Represents an ordered collection of elements.
type: docs
weight: 40
url: /java/com.aspose.pdf.tagged.logicalstructure/elementlist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.ElementList

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >, com.aspose.ms.System.Collections.IEnumerable< Element >, Iterable < Element >

```
public abstract class ElementList extends Object implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< Element >
```

Represents an ordered collection of elements.

## Methods

| Method | Description |
| --- | --- |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) | Add element to list. |
| [get_Item](#get_Item-int-) |  |
| [getCount](#getCount--) | Gets the number of elements in the ElementList. |
| [insertElement](#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-) | Insert element to list. |
| [item](#item-int-) | Retrieves a element at the given index. |
| [iterator](#iterator--) | Gets an enumerator that iterates through the collection of elements. |
| [removeAt](#removeAt-int-) | Remove element from list. |
| [removeElement](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) | Remove element from list. |

### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}


### addElement {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
Add element to list.

### get_Item {#get_Item-int-}
```
public Element get_Item(int index)
```



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  |  |

### getCount {#getCount--}
```
public abstract int getCount()
```

Gets the number of elements in the ElementList.

**Returns:**
int value

### insertElement {#insertElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-int-}
Insert element to list.

### item {#item-int-}
```
public abstract Element item(int index)
```

Retrieves a element at the given index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | The index into the list of elements. |

**Returns:**
The {@code /Aspose.Pdf.LogicalStructure.Element} with the specified index in the collection. If {@code index} is greater than or equal to the number of elements in the list, this returns null.

### iterator {#iterator--}
```
public abstract com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Element > iterator()
```

Gets an enumerator that iterates through the collection of elements.

**Returns:**
An enumerator used to iterate through the collection of elements.

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

Remove element from list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index to remove. |

### removeElement {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
Remove element from list.
