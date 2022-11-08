---
title: Outlines
second_title: Aspose.PDF for Java API Reference
description: Class describes collection of outlines.
type: docs
weight: 241
url: /java/com.aspose.pdf/outlines/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class Outlines implements Iterable<OutlineItemCollection>
```

Class describes collection of outlines.
## Constructors

| Constructor | Description |
| --- | --- |
| [Outlines()](#Outlines--) |  |
## Methods

| Method | Description |
| --- | --- |
| [add(OutlineItemCollection item)](#add-com.aspose.pdf.OutlineItemCollection-) | Adds outline item to collection. |
| [clear()](#clear--) | Clears all items from the collection. |
| [contains(OutlineItemCollection item)](#contains-com.aspose.pdf.OutlineItemCollection-) | Always throws NotImplementedException. |
| [copyTo(OutlineItemCollection[] array, int arrayIndex)](#copyTo-com.aspose.pdf.OutlineItemCollection---int-) | Copies the outline entries to an System.Array, starting at a particular System.Array index. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getVisibleCount()](#getVisibleCount--) | Gets the total number of outline items at all levels in the document outline hierarchy. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(OutlineItemCollection item)](#remove-com.aspose.pdf.OutlineItemCollection-) | Remove outline collection item. |
| [size()](#size--) | Gets count. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Outlines() {#Outlines--}
```
public Outlines()
```


### add(OutlineItemCollection item) {#add-com.aspose.pdf.OutlineItemCollection-}
```
public abstract void add(OutlineItemCollection item)
```


Adds outline item to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | The outline item to be added. |

### clear() {#clear--}
```
public abstract void clear()
```


Clears all items from the collection.

### contains(OutlineItemCollection item) {#contains-com.aspose.pdf.OutlineItemCollection-}
```
public abstract boolean contains(OutlineItemCollection item)
```


Always throws NotImplementedException.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | The object to locate in the collection |

**Returns:**
boolean - boolean value True - if item found; otherwise, false.
### copyTo(OutlineItemCollection[] array, int arrayIndex) {#copyTo-com.aspose.pdf.OutlineItemCollection---int-}
```
public abstract void copyTo(OutlineItemCollection[] array, int arrayIndex)
```


Copies the outline entries to an System.Array, starting at a particular System.Array index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [OutlineItemCollection\[\]](../../com.aspose.pdf/outlineitemcollection) | The one-dimensional System.Array that is the destination. Must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

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
### getVisibleCount() {#getVisibleCount--}
```
public abstract int getVisibleCount()
```


Gets the total number of outline items at all levels in the document outline hierarchy.

**Returns:**
int - int value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public abstract boolean isReadOnly()
```


Gets a value indicating whether the collection is read-only.

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public abstract Iterator<OutlineItemCollection> iterator()
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
public abstract boolean remove(OutlineItemCollection item)
```


Remove outline collection item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [OutlineItemCollection](../../com.aspose.pdf/outlineitemcollection) | Item to delete. |

**Returns:**
boolean - boolean value True - if item removed; otherwise, false.
### size() {#size--}
```
public abstract int size()
```


Gets count.

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

