---
title: DestinationCollection
linktitle: DestinationCollection
second_title: Aspose.PDF for Java API Reference
description: Class represents the collection of all destinations (a name tree mapping name strings to destinations (see 12.3.2.3, \"Named Destinations\") and (see 7.7.4, \"Name Dictionary\")) in.
type: docs
weight: 960
url: /java/com.aspose.pdf/destinationcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DestinationCollection

**All Implemented Interfaces:**
Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, Object >>

```
public final class DestinationCollection extends Object implements Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >>
```

Class represents the collection of all destinations (a name tree mapping name strings to destinations (see 12.3.2.3, "Named Destinations") and (see 7.7.4, "Name Dictionary")) in the pdf document.

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Adds the specified item. |
| [clear](#clear--) | Collection is read-only. Always throws NotSupportedException exception. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Determines whether this instance contains the object. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copies the elements of the collection to an Array, starting at a particular Array index. |
| [get_Item](#get_Item-int-) | Gets the destination object by index. |
| [getExplicitDestination](#getExplicitDestination-java.lang.String-boolean-) | Returns the explicit destination by the name. |
| [getPageNumber](#getPageNumber-java.lang.String-boolean-) | Returns the page number of destination by the name. |
| [indexOf](#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Returns the index of destination in collection. |
| [isReadOnly](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [iterator](#iterator--) | Returns the enumerator. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Removes the specified item. |
| [size](#size--) | Gets the number of elements contained in the collection. |

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Adds the specified item.

### clear {#clear--}
```
public void clear()
```

Collection is read-only. Always throws NotSupportedException exception.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Determines whether this instance contains the object.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copies the elements of the collection to an Array, starting at a particular Array index.

### get_Item {#get_Item-int-}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object > get_Item(int index)
```

Gets the destination object by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | The index of destination to get. |

**Returns:**
Destination.

### getExplicitDestination {#getExplicitDestination-java.lang.String-boolean-}
Returns the explicit destination by the name.

### getPageNumber {#getPageNumber-java.lang.String-boolean-}
Returns the page number of destination by the name.

### indexOf {#indexOf-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Returns the index of destination in collection.

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gets a value indicating whether the collection is read-only.

**Returns:**
boolean value

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , Object >> iterator()
```

Returns the enumerator.

**Returns:**
The enumerator.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Removes the specified item.

### size {#size--}
```
public int size()
```

Gets the number of elements contained in the collection.

**Returns:**
int value
