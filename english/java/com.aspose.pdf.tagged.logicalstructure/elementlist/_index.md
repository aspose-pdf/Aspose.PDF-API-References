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
| [addElement(Element element)](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [addElement(Element element, boolean updatePdfDictionary)](#addElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-boolean-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Gets the number of elements in the ElementList. |
| [get_Item(int index)](#get-Item-int-) |  |
| [hashCode()](#hashCode--) |  |
| [item(int index)](#item-int-) | Retrieves a element at the given index. |
| [iterator()](#iterator--) | Gets an enumerator that iterates through the collection of elements. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeElement(Element element)](#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gets the number of elements in the ElementList.

**Returns:**
int - int value
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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
### iterator() {#iterator--}
```
public abstract System.Collections.Generic.IGenericEnumerator<Element> iterator()
```


Gets an enumerator that iterates through the collection of elements.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.tagged.logicalstructure.elements.Element> - An enumerator used to iterate through the collection of elements.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeElement(Element element) {#removeElement-com.aspose.pdf.tagged.logicalstructure.elements.Element-}
```
public abstract void removeElement(Element element)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [Element](../../com.aspose.pdf.tagged.logicalstructure.elements/element) |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

