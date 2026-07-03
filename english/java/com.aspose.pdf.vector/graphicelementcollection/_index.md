---
title: GraphicElementCollection
second_title: Aspose.PDF for Java API Reference
description: Represents {@link GraphicElement} collection.
type: docs
weight: 20
url: /java/com.aspose.pdf.vector/graphicelementcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElementCollection

**All Implemented Interfaces:**
Iterable < GraphicElement >

```
public final class GraphicElementCollection extends Object implements Iterable < GraphicElement >
```

Represents {@link GraphicElement} collection.

## Constructors

| Constructor | Description |
| --- | --- |
| [GraphicElementCollection](#GraphicElementCollection--) | Initializes the new collection. |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.vector.GraphicElement-) | Adds a new {@link GraphicElement} to the collection. All items in the collection must have the same {@code GraphicElement.Parent}({@link GraphicElement#getParent}). |
| [clear](#clear--) | Clears the collection. |
| [contains](#contains-com.aspose.pdf.vector.GraphicElement-) | Determines whether an element is in the collection. |
| [copyTo](#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array. |
| [get_Item](#get_Item-int-) | Gets the {@link GraphicElement} element at the specified index. |
| [isReadOnly](#isReadOnly--) | Gets a value indicating whether collection is read only. Always returns false. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Returns an enumerator for the entire collection. |
| [iterator](#iterator--) | Returns an enumerator for the entire collection. |
| [remove](#remove-com.aspose.pdf.vector.GraphicElement-) | Deletes the {@link GraphicElement} element. |
| [size](#size--) | Gets the number of {@link GraphicElement} object elements actually contained in the collection. |
| [toList](#toList--) | Returns the inner collection for unrestricted enumeration. |
| [toString](#toString--) | Gets a string representation of this collection. |

### GraphicElementCollection {#GraphicElementCollection--}
```
public GraphicElementCollection()
```

Initializes the new collection.

### add {#add-com.aspose.pdf.vector.GraphicElement-}
Adds a new {@link GraphicElement} to the collection. All items in the collection must have the same {@code GraphicElement.Parent}({@link GraphicElement#getParent}).

### clear {#clear--}
```
public final void clear()
```

Clears the collection.

### contains {#contains-com.aspose.pdf.vector.GraphicElement-}
Determines whether an element is in the collection.

### copyTo {#copyTo-com.aspose.pdf.vector.GraphicElement:A-int-}
Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array.

### get_Item {#get_Item-int-}
```
public final GraphicElement get_Item(int index)
```

Gets the {@link GraphicElement} element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index within the collection. |

**Returns:**
{@link GraphicElement}.

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Gets a value indicating whether collection is read only. Always returns false.

**Returns:**
boolean value

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public final com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Returns an enumerator for the entire collection.

**Returns:**
Enumerator object.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< GraphicElement > iterator()
```

Returns an enumerator for the entire collection.

**Returns:**
Enumerator object.

### remove {#remove-com.aspose.pdf.vector.GraphicElement-}
Deletes the {@link GraphicElement} element.

### size {#size--}
```
public final int size()
```

Gets the number of {@link GraphicElement} object elements actually contained in the collection.

**Returns:**
int value

### toList {#toList--}
```
public final com.aspose.ms.System.Collections.Generic.List< GraphicElement > toList()
```

Returns the inner collection for unrestricted enumeration.

**Returns:**
Inner list

### toString {#toString--}
```
public String toString()
```

Gets a string representation of this collection.

**Returns:**
The string.
