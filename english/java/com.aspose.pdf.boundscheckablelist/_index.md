---
title: >
linktitle: >
second_title: Aspose.PDF for Java API Reference
description: Represents BoundsCheckableList - wrapper around System.Collections.Generic.List.
type: docs
weight: 10
url: /java/com.aspose.pdf.boundscheckablelist//
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.boundscheckablelist.BoundsCheckableList<T>

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<T>, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<T>, com.aspose.ms.System.Collections.Generic.IGenericList<T>, com.aspose.ms.System.Collections.IEnumerable<T>, Iterable <T>

```
public class BoundsCheckableList<T extends IBoundsCheckableItem > extends Object implements com.aspose.ms.System.Collections.Generic.IGenericList<T>
```

Represents BoundsCheckableList - wrapper around System.Collections.Generic.List.

## Constructors

| Constructor | Description |
| --- | --- |
| [BoundsCheckableList](#BoundsCheckableList--) | Initializes a new instance of the BoundsCheckableList class. |
| [BoundsCheckableList](#BoundsCheckableList-int-double-double-) | Initializes a new instance of the BoundsCheckableList class. |

## Methods

| Method | Description |
| --- | --- |
| [addItem](#addItem-T-) | Adds an object to the end of the System.Collections.Generic.List depending on "boundsCheckMode" parameter. |
| [clear](#clear--) | Removes all elements from the System.Collections.Generic.List. |
| [containsItem](#containsItem-T-) | Determines whether an element is in the System.Collections.Generic.List. |
| [copyToTArray](#copyToTArray-T:A-int-) | Copies the entire System.Collections.Generic.List to a compatible one-dimensional array, starting at the specified index of the target array. |
| [get_Item](#get_Item-int-) | Gets or sets paragraph from or to collection. |
| [indexOfItem](#indexOfItem-T-) | Searches for the specified object and returns the zero-based index of the first occurrence within the entire System.Collections.Generic.List. |
| [insertItem](#insertItem-int-T-) | Inserts an element into the System.Collections.Generic.List at the specified index. |
| [isReadOnly](#isReadOnly--) | Gets the value indicating if collection is readonly. |
| [iterator](#iterator--) | Returns an enumerator that iterates through the System.Collections.Generic.List. |
| [removeAt](#removeAt-int-) | Removes the element at the specified index of the System.Collections.Generic.List. |
| [removeItem](#removeItem-T-) | Removes the first occurrence of a specific object from the System.Collections.Generic.List. |
| [set_Item](#set_Item-int-T-) | Gets or sets paragraph from or to collection. |
| [size](#size--) | Gets the number of elements contained in the System.Collections.Generic.List. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-) | Updates boundsCheckMode parameter for initialized collection. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-double-double-) | Updates boundsCheckMode parameter for initialized collection. |

### BoundsCheckableList {#BoundsCheckableList--}
```
public BoundsCheckableList()
```

Initializes a new instance of the BoundsCheckableList class.

### BoundsCheckableList {#BoundsCheckableList-int-double-double-}
```
public BoundsCheckableList(int boundsCheckMode, double containerWidth, double containerHeight)
```

Initializes a new instance of the BoundsCheckableList class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| boundsCheckMode |  | The bounds cCheck mode. |
| containerWidth |  | The container width. |
| containerHeight |  | The container height. |

### addItem {#addItem-T-}
```
public final void addItem( T item)
```

Adds an object to the end of the System.Collections.Generic.List depending on "boundsCheckMode" parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item |  | The object to be added to the end of the System.Collections.Generic.List. The value can be "null" for reference types. |

### clear {#clear--}
```
public final void clear()
```

Removes all elements from the System.Collections.Generic.List.

### containsItem {#containsItem-T-}
```
public final boolean containsItem( T item)
```

Determines whether an element is in the System.Collections.Generic.List.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item |  | The object to locate in the System.Collections.Generic.List. The value can be null for reference types. |

**Returns:**
true if itemitem is found in the System.Collections.Generic.List; otherwise, false.

### copyToTArray {#copyToTArray-T:A-int-}
```
public final void copyToTArray( T [] array, int arrayIndex)
```

Copies the entire System.Collections.Generic.List to a compatible one-dimensional array, starting at the specified index of the target array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array |  | The one-dimensional System.Array that is the destination of the elements copied from System.Collections.Generic.List. The System.Array must have zero-based indexing. |
| arrayIndex |  | The zero-based index in array at which copying begins. |

### get_Item {#get_Item-int-}
```
public final T get_Item(int index)
```

Gets or sets paragraph from or to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | The paragraph index. |

**Returns:**
the element at the specified index.

### indexOfItem {#indexOfItem-T-}
```
public final int indexOfItem( T item)
```

Searches for the specified object and returns the zero-based index of the first occurrence within the entire System.Collections.Generic.List.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item |  | The object to locate in the System.Collections.Generic.List. The value can be null for reference types. |

**Returns:**
The zero-based index of the first occurrence of itemitem within the entire System.Collections.Generic.List, if found; otherwise, –1.

### insertItem {#insertItem-int-T-}
```
public final void insertItem(int index, T item)
```

Inserts an element into the System.Collections.Generic.List at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | The zero-based index at which item should be inserted. |
| item |  | The object to insert. The value can be null for reference types. |

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Gets the value indicating if collection is readonly.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< T > iterator()
```

Returns an enumerator that iterates through the System.Collections.Generic.List.

**Returns:**
A Enumerator for the System.Collections.Generic.List.

### removeAt {#removeAt-int-}
```
public final void removeAt(int index)
```

Removes the element at the specified index of the System.Collections.Generic.List.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | The zero-based index of the element to remove. |

### removeItem {#removeItem-T-}
```
public final boolean removeItem( T item)
```

Removes the first occurrence of a specific object from the System.Collections.Generic.List.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item |  | The object to remove from the System.Collections.Generic.List. The value can be null for reference types. |

**Returns:**
true if itemitem is successfully removed; otherwise, false. This method also returns false if itemitem was not found in the System.Collections.Generic.List.

### set_Item {#set_Item-int-T-}
```
public final void set_Item(int index, T value)
```

Gets or sets paragraph from or to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | The paragraph index. |

### size {#size--}
```
public final int size()
```

Gets the number of elements contained in the System.Collections.Generic.List.

**Returns:**
The number of elements contained in the System.Collections.Generic.List.

### updateBoundsCheckMode {#updateBoundsCheckMode-int-}
```
public final void updateBoundsCheckMode(int boundsCheckMode)
```

Updates boundsCheckMode parameter for initialized collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| boundsCheckMode |  | The bounds check mode. |

### updateBoundsCheckMode {#updateBoundsCheckMode-int-double-double-}
```
public final void updateBoundsCheckMode(int boundsCheckMode, double containerWidth, double containerHeight)
```

Updates boundsCheckMode parameter for initialized collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| boundsCheckMode |  | The bounds check mode. |
| containerWidth |  | The container width. |
| containerHeight |  | The container height. |
