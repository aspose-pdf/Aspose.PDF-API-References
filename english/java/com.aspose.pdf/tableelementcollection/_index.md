---
title: TableElementCollection
second_title: Aspose.PDF for Java API Reference
description: Represents a collection of elements absorbed from existing table
type: docs
weight: 355
url: /java/com.aspose.pdf/tableelementcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class TableElementCollection<T1> implements Iterable<T1>
```

Represents a collection of elements absorbed from existing table

 T : Instance of type implementing  ITableElement 
## Methods

| Method | Description |
| --- | --- |
| [addItem(ITableElement element)](#addItem-com.aspose.pdf.ITableElement-) | Adds the text fragment element at the specified index. |
| [clear()](#clear--) | Clears all items from the collection. |
| [containsItem(T1 item)](#containsItem-T1-) | Determines whether the collection contains a specific value. |
| [copyToTArray(T1[] array, int index)](#copyToTArray-T1---int-) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the text fragment element at the specified index. |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether collection is read-only |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [iterator()](#iterator--) | Returns an enumerator for the entire collection. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | Returns an enumerator for the entire collection. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeItem(T1 item)](#removeItem-T1-) | Deletes specified item from collection. |
| [size()](#size--) | Gets the number of table elements actually contained in the collection. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addItem(ITableElement element) {#addItem-com.aspose.pdf.ITableElement-}
```
public void addItem(ITableElement element)
```


Adds the text fragment element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [ITableElement](../../com.aspose.pdf/itableelement) | ITableElement instance |

### clear() {#clear--}
```
public void clear()
```


Clears all items from the collection.

### containsItem(T1 item) {#containsItem-T1-}
```
public boolean containsItem(T1 item)
```


Determines whether the collection contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | T1 | The object to locate in the collection |

**Returns:**
boolean - true if item is found in the collection; otherwise, false.
### copyToTArray(T1[] array, int index) {#copyToTArray-T1---int-}
```
public void copyToTArray(T1[] array, int index)
```


Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | T1[] | Array of objects which will be copied. |
| index | int | Starting index from which copying will be started. |

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
java.lang.Object - SyncRoot Object
### get_Item(int index) {#get-Item-int-}
```
public T1 get_Item(int index)
```


Gets the text fragment element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index within the collection. |

**Returns:**
T1 - table element object.
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
public System.Collections.IEnumerator<T1> iterator()
```


Returns an enumerator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator<T1> - Enumerator object.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator iterator_Rename_Namesake()
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




### removeItem(T1 item) {#removeItem-T1-}
```
public boolean removeItem(T1 item)
```


Deletes specified item from collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | T1 | The object to delete |

**Returns:**
boolean - true if item was deleted from collection; otherwise, false.
### size() {#size--}
```
public int size()
```


Gets the number of table elements actually contained in the collection.

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

