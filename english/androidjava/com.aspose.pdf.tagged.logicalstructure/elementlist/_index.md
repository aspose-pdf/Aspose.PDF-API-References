---
title: ElementList
second_title: Aspose.PDF for Java API Reference
description: Represents an ordered collection of elements.
type: docs
weight: 13
url: /java/com.aspose.pdf.tagged.logicalstructure/elementlist/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public abstract class ElementList implements System.Collections.Generic.IGenericEnumerable<Element>
```

Represents an ordered collection of elements.
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Gets the number of elements in the ElementList. |
| [item(int index)](#item-int-) | Retrieves a element at the given index. |
| [get_Item(int index)](#get-Item-int-) |  |
| [iterator()](#iterator--) | Gets an enumerator that iterates through the collection of elements. |
| [addElement(Element element)](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement(Element element, boolean updatePdfDictionary)](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) |  |
| [removeElement(Element element)](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the number of elements in the ElementList.

**Returns:**
int - int value
### item(int index) {#item-int-}
```
public abstract Element item(int index)
```


Retrieves a element at the given index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index into the list of elements. |

**Returns:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) - The  /Aspose.Pdf.LogicalStructure.Element  with the specified index in the collection. If  index  is greater than or equal to the number of elements in the list, this returns null.
### get_Item(int index) {#get-Item-int-}
```
public Element get_Item(int index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element)
### iterator() {#iterator--}
```
public abstract System.Collections.Generic.IGenericEnumerator<Element> iterator()
```


Gets an enumerator that iterates through the collection of elements.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.tagged.logicalstructure.elements.Element> - An enumerator used to iterate through the collection of elements.
### addElement(Element element) {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public void addElement(Element element)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |

### addElement(Element element, boolean updatePdfDictionary) {#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-}
```
public abstract void addElement(Element element, boolean updatePdfDictionary)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |
| updatePdfDictionary | boolean |  |

### removeElement(Element element) {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public abstract void removeElement(Element element)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |

