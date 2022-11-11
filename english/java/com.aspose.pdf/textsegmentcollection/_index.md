---
title: TextSegmentCollection
second_title: Aspose.PDF for Java API Reference
description: Represents a text segments collection
type: docs
weight: 387
url: /java/com.aspose.pdf/textsegmentcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class TextSegmentCollection implements Iterable<TextSegment>
```

Represents a text segments collection
## Methods

| Method | Description |
| --- | --- |
| [add(TextSegment segment)](#add-com.aspose.pdf.TextSegment-) | Adds the text segment element at the specified index. |
| [clear()](#clear--) | Clears all items from the collection. |
| [contains(TextSegment item)](#contains-com.aspose.pdf.TextSegment-) | Determines whether the collection contains a specific value. |
| [copyTo(TextSegment[] array, int index)](#copyTo-com.aspose.pdf.TextSegment---int-) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array |
| [delete(int index)](#delete-int-) | Deletes the text segment element at the specified index. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the text segment element at the specified index. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether collection is read-only |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [iterator()](#iterator--) | Returns an enumerator for the entire collection. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(TextSegment item)](#remove-com.aspose.pdf.TextSegment-) | Deletes specified item from collection. |
| [size()](#size--) | Gets the number of  TextSegment  object elements actually contained in the collection. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(TextSegment segment) {#add-com.aspose.pdf.TextSegment-}
```
public void add(TextSegment segment)
```


Adds the text segment element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| segment | [TextSegment](../../com.aspose.pdf/textsegment) | Text segment object |

### clear() {#clear--}
```
public void clear()
```


Clears all items from the collection.

### contains(TextSegment item) {#contains-com.aspose.pdf.TextSegment-}
```
public boolean contains(TextSegment item)
```


Determines whether the collection contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [TextSegment](../../com.aspose.pdf/textsegment) | The object to locate in the collection |

**Returns:**
boolean - true if item is found in the collection; otherwise, false.
### copyTo(TextSegment[] array, int index) {#copyTo-com.aspose.pdf.TextSegment---int-}
```
public void copyTo(TextSegment[] array, int index)
```


Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [TextSegment\[\]](../../com.aspose.pdf/textsegment) | Array of objects which will be copied. |
| index | int | Starting index from which copying will be started. |

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Deletes the text segment element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | int value |

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
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to the collection.

**Returns:**
java.lang.Object - Object element
### get_Item(int index) {#get-Item-int-}
```
public TextSegment get_Item(int index)
```


Gets the text segment element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index within the collection. |

**Returns:**
[TextSegment](../../com.aspose.pdf/textsegment) - TextSegment object.
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


Gets a value indicating whether collection is read-only

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets a value indicating whether access to the collection is synchronized (thread safe).

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public Iterator<TextSegment> iterator()
```


Returns an enumerator for the entire collection.

**Returns:**
java.util.Iterator<com.aspose.pdf.TextSegment> - Enumerator object.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(TextSegment item) {#remove-com.aspose.pdf.TextSegment-}
```
public boolean remove(TextSegment item)
```


Deletes specified item from collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [TextSegment](../../com.aspose.pdf/textsegment) | The object to delete |

**Returns:**
boolean - true if item was deleted from collection; otherwise, false.
### size() {#size--}
```
public int size()
```


Gets the number of  TextSegment  object elements actually contained in the collection.

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

