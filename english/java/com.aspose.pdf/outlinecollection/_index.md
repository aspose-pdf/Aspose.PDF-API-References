---
title: OutlineCollection
second_title: Aspose.PDF for Java API Reference
description: Represents document outline hierarchy.
type: docs
weight: 240
url: /java/com.aspose.pdf/outlinecollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Outlines](../../com.aspose.pdf/outlines)
```
public final class OutlineCollection extends Outlines
```

Represents document outline hierarchy.
## Methods

| Method | Description |
| --- | --- |
| [hasNext()](#hasNext--) |  |
| [next()](#next--) |  |
| [getVisibleCount()](#getVisibleCount--) | Count is the sum of the number of visible descendent outline items at all levels. |
| [size()](#size--) | Gets the total number of outline items (bookmarks) at all levels of the document outline. |
| [getFirst()](#getFirst--) | Gets an outline item representing the first top-level item in the outline. |
| [getLast()](#getLast--) | Gets an outline item representing the last top-level item in the outline. |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to this collection is synchronized (thread safe). |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to this collection. |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [add(OutlineItemCollection outline)](#add-com.aspose.pdf.OutlineItemCollection-) | Adds outline item to collection. |
| [delete()](#delete--) | Deletes all outline items from the document outline. |
| [delete(String name)](#delete-java.lang.String-) | Deletes the outline item with specified title from the document outline. |
| [copyTo(OutlineItemCollection[] array, int index)](#copyTo-com.aspose.pdf.OutlineItemCollection---int-) | Copies the outline items to an System.Array, starting at a particular System.Array index. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [clear()](#clear--) | Clears all items from the collection. |
| [contains(OutlineItemCollection item)](#contains-com.aspose.pdf.OutlineItemCollection-) | Not supported yet. |
| [remove(OutlineItemCollection item)](#remove-com.aspose.pdf.OutlineItemCollection-) | Not supported yet. |
| [remove(int index)](#remove-int-) | Remove item by index. |
| [get_Item(int index)](#get-Item-int-) | Gets outline item from collection by index. |
### hasNext() {#hasNext--}
```
public boolean hasNext()
```




**Returns:**
boolean
### next() {#next--}
```
public OutlineItemCollection next()
```




**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection)
### getVisibleCount() {#getVisibleCount--}
```
public int getVisibleCount()
```


Count is the sum of the number of visible descendent outline items at all levels. Note: please don't confuse with Count which is number if items in collection.

**Returns:**
int
### size() {#size--}
```
public int size()
```


Gets the total number of outline items (bookmarks) at all levels of the document outline.

**Returns:**
int - int value
### getFirst() {#getFirst--}
```
public OutlineItemCollection getFirst()
```


Gets an outline item representing the first top-level item in the outline.

**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - OutlineItemCollection object
### getLast() {#getLast--}
```
public OutlineItemCollection getLast()
```


Gets an outline item representing the last top-level item in the outline.

**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - OutlineItemCollection object
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets a value indicating whether access to this collection is synchronized (thread safe).

**Returns:**
boolean - boolean value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to this collection.

**Returns:**
java.lang.Object - Object for synchronization
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether the collection is read-only.

**Returns:**
boolean - boolean value
### add(OutlineItemCollection outline) {#add-com.aspose.pdf.OutlineItemCollection-}
```
public void add(OutlineItemCollection outline)
```


Adds outline item to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outline | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | The outline item to be added. |

### delete() {#delete--}
```
public void delete()
```


Deletes all outline items from the document outline.

### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


Deletes the outline item with specified title from the document outline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The title of outline item to be deleted |

### copyTo(OutlineItemCollection[] array, int index) {#copyTo-com.aspose.pdf.OutlineItemCollection---int-}
```
public void copyTo(OutlineItemCollection[] array, int index)
```


Copies the outline items to an System.Array, starting at a particular System.Array index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [OutlineItemCollection\[\]](../../com.aspose.pdf/outlineitemcollection) | The one-dimensional System.Array that is the destination. Must have zero-based indexing. |
| index | int | The zero-based index in array at which copying begins. |

### iterator() {#iterator--}
```
public Iterator<OutlineItemCollection> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
java.util.Iterator<com.aspose.pdf.OutlineItemCollection> - An System.Collections.IEnumerator object that can be used to iterate through the collection.
### clear() {#clear--}
```
public void clear()
```


Clears all items from the collection.

### contains(OutlineItemCollection item) {#contains-com.aspose.pdf.OutlineItemCollection-}
```
public boolean contains(OutlineItemCollection item)
```


Not supported yet.

Checks does collection contains given item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | The object to locate in the collection |

**Returns:**
boolean - boolean value True - if item found; otherwise, false.
### remove(OutlineItemCollection item) {#remove-com.aspose.pdf.OutlineItemCollection-}
```
public boolean remove(OutlineItemCollection item)
```


Not supported yet.

Always throws exception

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | The object to locate in the collection |

**Returns:**
boolean - boolean value True - if item removed; otherwise, false.
### remove(int index) {#remove-int-}
```
public final void remove(int index)
```


Remove item by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the item to be removed. |

### get_Item(int index) {#get-Item-int-}
```
public OutlineItemCollection get_Item(int index)
```


Gets outline item from collection by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of requested item. |

**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) - OutlineItemCollection object
