---
title: FontSourceCollection
second_title: Aspose.PDF for Java API Reference
description: Represents font sources collection.
type: docs
weight: 12
url: /java/com.aspose.pdf.text/fontsourcecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FontSourceCollection implements Iterable<FontSource>
```

Represents font sources collection.
## Constructors

| Constructor | Description |
| --- | --- |
| [FontSourceCollection()](#FontSourceCollection--) | Initializes collection object |
## Fields

| Field | Description |
| --- | --- |
| [CollectionChanged](#CollectionChanged) | CollectionChanged event |
## Methods

| Method | Description |
| --- | --- |
| [add(FontSource fontSource)](#add-com.aspose.pdf.FontSource-) | Adds new font source object to the collection. |
| [clear()](#clear--) | Clears the font source collection. |
| [contains(FontSource item)](#contains-com.aspose.pdf.FontSource-) | Determines whether an element is in the collection. |
| [copyTo(FontSource[] array, int index)](#copyTo-com.aspose.pdf.FontSource---int-) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array |
| [delete(FontSource fontSource)](#delete-com.aspose.pdf.FontSource-) | Deletes the font source element. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getItem(int index)](#getItem-int-) | Gets the font element at the specified index. |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [hashCode()](#hashCode--) |  |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [iterator()](#iterator--) | Returns an enumerator for the entire collection. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(FontSource item)](#remove-com.aspose.pdf.FontSource-) | Deletes the font source element. |
| [size()](#size--) | Gets the number of Font object elements actually contained in the collection. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FontSourceCollection() {#FontSourceCollection--}
```
public FontSourceCollection()
```


Initializes collection object

### CollectionChanged {#CollectionChanged}
```
public final PdfEvent<System.EventHandler> CollectionChanged
```


CollectionChanged event

### add(FontSource fontSource) {#add-com.aspose.pdf.FontSource-}
```
public void add(FontSource fontSource)
```


Adds new font source object to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontSource | [FontSource](../../com.aspose.pdf/fontsource) | Font source. |

### clear() {#clear--}
```
public void clear()
```


Clears the font source collection.

### contains(FontSource item) {#contains-com.aspose.pdf.FontSource-}
```
public boolean contains(FontSource item)
```


Determines whether an element is in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [FontSource](../../com.aspose.pdf/fontsource) | FontSource object to search. |

**Returns:**
boolean - True - if element found; otherwise, false.
### copyTo(FontSource[] array, int index) {#copyTo-com.aspose.pdf.FontSource---int-}
```
public void copyTo(FontSource[] array, int index)
```


Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [FontSource\[\]](../../com.aspose.pdf/fontsource) | Array of objects which will be copied. |
| index | int | Starting index from which copying will be started. |

### delete(FontSource fontSource) {#delete-com.aspose.pdf.FontSource-}
```
public void delete(FontSource fontSource)
```


Deletes the font source element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontSource | [FontSource](../../com.aspose.pdf/fontsource) | FontSource object that will be deleted. |

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
### getItem(int index) {#getItem-int-}
```
public FontSource getItem(int index)
```


Gets the font element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index within the collection. |

**Returns:**
[FontSource](../../com.aspose.pdf/fontsource) - Font source object.
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to the collection.

**Returns:**
java.lang.Object - Object element
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets a value indicating whether access to the collection is synchronized (thread safe).

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```


Returns an enumerator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Enumerator object.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(FontSource item) {#remove-com.aspose.pdf.FontSource-}
```
public boolean remove(FontSource item)
```


Deletes the font source element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [FontSource](../../com.aspose.pdf/fontsource) | FontSource object that will be deleted. |

**Returns:**
boolean - True - if element found; otherwise, false.
### size() {#size--}
```
public int size()
```


Gets the number of Font object elements actually contained in the collection.

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

