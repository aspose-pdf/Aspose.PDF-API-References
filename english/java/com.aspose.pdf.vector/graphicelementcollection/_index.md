---
title: GraphicElementCollection
second_title: Aspose.PDF for Java API Reference
description: Represents  collection.
type: docs
weight: 11
url: /java/com.aspose.pdf.vector/graphicelementcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class GraphicElementCollection implements Iterable<GraphicElement>
```

Represents [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement) collection.
## Constructors

| Constructor | Description |
| --- | --- |
| [GraphicElementCollection()](#GraphicElementCollection--) | Initializes the new collection. |
## Methods

| Method | Description |
| --- | --- |
| [iterator()](#iterator--) | Returns an enumerator for the entire collection. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | Returns an enumerator for the entire collection. |
| [add(GraphicElement item)](#add-com.aspose.pdf.vector.GraphicElement-) | Adds a new [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement) to the collection. |
| [clear()](#clear--) | Clears the collection. |
| [contains(GraphicElement item)](#contains-com.aspose.pdf.vector.GraphicElement-) | Determines whether an element is in the collection. |
| [copyTo(GraphicElement[] array, int arrayIndex)](#copyTo-com.aspose.pdf.vector.GraphicElement---int-) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array. |
| [remove(GraphicElement item)](#remove-com.aspose.pdf.vector.GraphicElement-) | Deletes the [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement) element. |
| [size()](#size--) | Gets the number of [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement) object elements actually contained in the collection. |
| [toList()](#toList--) | Returns the inner collection for unrestricted enumeration. |
| [toString()](#toString--) | Gets a string representation of this collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement) element at the specified index. |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether collection is read only. |
### GraphicElementCollection() {#GraphicElementCollection--}
```
public GraphicElementCollection()
```


Initializes the new collection.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<GraphicElement> iterator()
```


Returns an enumerator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.vector.GraphicElement> - Enumerator object.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public final System.Collections.IEnumerator iterator_Rename_Namesake()
```


Returns an enumerator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Enumerator object.
### add(GraphicElement item) {#add-com.aspose.pdf.vector.GraphicElement-}
```
public final void add(GraphicElement item)
```


Adds a new [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement) to the collection. All items in the collection must have the same  GraphicElement.Parent ([GraphicElement\#getParent](../../com.aspose.pdf.engine.pagemodel/graphicelement\#getParent)).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [GraphicElement](../../com.aspose.pdf.vector/graphicelement) | IGraphicElement. |

### clear() {#clear--}
```
public final void clear()
```


Clears the collection.

### contains(GraphicElement item) {#contains-com.aspose.pdf.vector.GraphicElement-}
```
public final boolean contains(GraphicElement item)
```


Determines whether an element is in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [GraphicElement](../../com.aspose.pdf.vector/graphicelement) | [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement) to search. |

**Returns:**
boolean - True - if element found; otherwise, false.
### copyTo(GraphicElement[] array, int arrayIndex) {#copyTo-com.aspose.pdf.vector.GraphicElement---int-}
```
public final void copyTo(GraphicElement[] array, int arrayIndex)
```


Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [GraphicElement\[\]](../../com.aspose.pdf.vector/graphicelement) | Array of objects which will be copied. |
| arrayIndex | int | Starting index from which copying will be started. |

### remove(GraphicElement item) {#remove-com.aspose.pdf.vector.GraphicElement-}
```
public final boolean remove(GraphicElement item)
```


Deletes the [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement) element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [GraphicElement](../../com.aspose.pdf.vector/graphicelement) | [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement) object that will be deleted. |

**Returns:**
boolean - True - if element found; otherwise, false.
### size() {#size--}
```
public final int size()
```


Gets the number of [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement) object elements actually contained in the collection.

**Returns:**
int - int value
### toList() {#toList--}
```
public final System.Collections.Generic.List<GraphicElement> toList()
```


Returns the inner collection for unrestricted enumeration.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.vector.GraphicElement> - Inner list
### toString() {#toString--}
```
public String toString()
```


Gets a string representation of this collection.

**Returns:**
java.lang.String - The string.
### get_Item(int index) {#get-Item-int-}
```
public final GraphicElement get_Item(int index)
```


Gets the [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement) element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index within the collection. |

**Returns:**
[GraphicElement](../../com.aspose.pdf.vector/graphicelement) - [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement).
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Gets a value indicating whether collection is read only. Always returns false.

**Returns:**
boolean - boolean value
