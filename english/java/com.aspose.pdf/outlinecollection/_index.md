---
title: OutlineCollection
second_title: Aspose.PDF for Java API Reference
description: Represents document outline hierarchy.
type: docs
weight: 239
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
| [add(OutlineItemCollection outline)](#add-com.aspose.pdf.OutlineItemCollection-) | Adds outline item to collection. |
| [clear()](#clear--) | Clears all items from the collection. |
| [contains(OutlineItemCollection item)](#contains-com.aspose.pdf.OutlineItemCollection-) | Not supported yet. |
| [copyTo(OutlineItemCollection[] array, int index)](#copyTo-com.aspose.pdf.OutlineItemCollection---int-) | Copies the outline items to an System.Array, starting at a particular System.Array index. |
| [delete()](#delete--) | Deletes all outline items from the document outline. |
| [delete(String name)](#delete-java.lang.String-) | Deletes the outline item with specified title from the document outline. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFirst()](#getFirst--) | Gets an outline item representing the first top-level item in the outline. |
| [getLast()](#getLast--) | Gets an outline item representing the last top-level item in the outline. |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to this collection. |
| [getVisibleCount()](#getVisibleCount--) | Count is the sum of the number of visible descendent outline items at all levels. |
| [get_Item(int index)](#get-Item-int-) | Gets outline item from collection by index. |
| [hasNext()](#hasNext--) |  |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to this collection is synchronized (thread safe). |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) |  |
| [next()](#next--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(OutlineItemCollection item)](#remove-com.aspose.pdf.OutlineItemCollection-) | Not supported yet. |
| [remove(int index)](#remove-int-) | Remove item by index. |
| [size()](#size--) | Gets the total number of outline items (bookmarks) at all levels of the document outline. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(OutlineItemCollection outline) {#add-com.aspose.pdf.OutlineItemCollection-}
```
public void add(OutlineItemCollection outline)
```


Adds outline item to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outline | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | The outline item to be added. |

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
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to this collection.

**Returns:**
java.lang.Object - Object for synchronization
### getVisibleCount() {#getVisibleCount--}
```
public int getVisibleCount()
```


Count is the sum of the number of visible descendent outline items at all levels. Note: please don't confuse with Count which is number if items in collection.

**Returns:**
int
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
### hasNext() {#hasNext--}
```
public boolean hasNext()
```




**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether the collection is read-only.

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets a value indicating whether access to this collection is synchronized (thread safe).

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public Iterator<OutlineItemCollection> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
java.util.Iterator<com.aspose.pdf.OutlineItemCollection> - An System.Collections.IEnumerator object that can be used to iterate through the collection.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public final System.Collections.IEnumerator iterator_Rename_Namesake()
```




**Returns:**
com.aspose.ms.System.Collections.IEnumerator
### next() {#next--}
```
public OutlineItemCollection next()
```




**Returns:**
[OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

### size() {#size--}
```
public int size()
```


Gets the total number of outline items (bookmarks) at all levels of the document outline.

**Returns:**
int - int value
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

