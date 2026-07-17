---
title: OutlineCollection
linktitle: OutlineCollection
second_title: Aspose.PDF for Java API Reference
description: Represents document outline hierarchy.
type: docs
weight: 3260
url: /java/com.aspose.pdf/outlinecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineCollection extends Outlines
```

Represents document outline hierarchy.

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Adds outline item to collection. |
| [clear](#clear--) | Clears all items from the collection. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Not supported yet. Checks does collection contains given item. |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Copies the outline items to an System.Array, starting at a particular System.Array index. |
| [delete](#delete--) | Deletes all outline items from the document outline. |
| [delete](#delete-java.lang.String-) | Deletes all outline items from the document outline. |
| [get_Item](#get_Item-int-) | Gets outline item from collection by index. |
| [getFirst](#getFirst--) | Gets an outline item representing the first top-level item in the outline. |
| [getLast](#getLast--) | Gets an outline item representing the last top-level item in the outline. |
| [getSyncRoot](#getSyncRoot--) | Gets an object that can be used to synchronize access to this collection. |
| [getVisibleCount](#getVisibleCount--) | Count is the sum of the number of visible descendent outline items at all levels. Note: please don't confuse with Count which is number if items in collection. |
| [hasNext](#hasNext--) |  |
| [isReadOnly](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [isSynchronized](#isSynchronized--) | Gets a value indicating whether access to this collection is synchronized (thread safe). |
| [iterator](#iterator--) | Returns an enumerator that iterates through the collection. |
| [next](#next--) |  |
| [remove](#remove-int-) | Remove item by index. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Not supported yet. Always throws exception |
| [size](#size--) | Gets the total number of outline items (bookmarks) at all levels of the document outline. |

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Adds outline item to collection.

### clear {#clear--}
```
public void clear()
```

Clears all items from the collection.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Not supported yet. Checks does collection contains given item.

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Copies the outline items to an System.Array, starting at a particular System.Array index.

### delete {#delete--}
```
public void delete()
```

Deletes all outline items from the document outline.

### delete {#delete-java.lang.String-}
Deletes all outline items from the document outline.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Gets outline item from collection by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of requested item. |

**Returns:**
OutlineItemCollection object

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Gets an outline item representing the first top-level item in the outline.

**Returns:**
OutlineItemCollection object

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Gets an outline item representing the last top-level item in the outline.

**Returns:**
OutlineItemCollection object

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Gets an object that can be used to synchronize access to this collection.

**Returns:**
Object for synchronization

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Count is the sum of the number of visible descendent outline items at all levels. Note: please don't confuse with Count which is number if items in collection.

**Returns:**
int value

### hasNext {#hasNext--}
```
public boolean hasNext()
```



### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gets a value indicating whether the collection is read-only.

**Returns:**
boolean value

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Gets a value indicating whether access to this collection is synchronized (thread safe).

**Returns:**
boolean value

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

Returns an enumerator that iterates through the collection.

**Returns:**
An System.Collections.IEnumerator object that can be used to iterate through the collection.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

Remove item by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of the item to be removed. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Not supported yet. Always throws exception

### size {#size--}
```
public int size()
```

Gets the total number of outline items (bookmarks) at all levels of the document outline.

**Returns:**
int value
