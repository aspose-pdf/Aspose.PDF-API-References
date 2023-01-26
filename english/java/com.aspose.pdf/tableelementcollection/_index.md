---
title: TableElementCollection
second_title: Aspose.PDF for Java API Reference
description: Represents a collection of elements absorbed from existing table
type: docs
weight: 359
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
| [size()](#size--) | Gets the number of table elements actually contained in the collection. |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether collection is read-only |
| [addItem(ITableElement element)](#addItem-com.aspose.pdf.ITableElement-) | Adds the text fragment element at the specified index. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | Returns an enumerator for the entire collection. |
| [iterator()](#iterator--) | Returns an enumerator for the entire collection. |
| [copyToTArray(T1[] array, int index)](#copyToTArray-T1---int-) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array |
| [clear()](#clear--) | Clears all items from the collection. |
| [containsItem(T1 item)](#containsItem-T1-) | Determines whether the collection contains a specific value. |
| [removeItem(T1 item)](#removeItem-T1-) | Deletes specified item from collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the text fragment element at the specified index. |
### size() {#size--}
```
public int size()
```


Gets the number of table elements actually contained in the collection.

**Returns:**
int - int value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to the collection.

**Returns:**
java.lang.Object - SyncRoot Object
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets a value indicating whether access to the collection is synchronized (thread safe).

**Returns:**
boolean - boolean value
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether collection is read-only

**Returns:**
boolean - boolean value
### addItem(ITableElement element) {#addItem-com.aspose.pdf.ITableElement-}
```
public void addItem(ITableElement element)
```


Adds the text fragment element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [ITableElement](../../com.aspose.pdf/itableelement) | ITableElement instance |

### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator iterator_Rename_Namesake()
```


Returns an enumerator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Enumerator object.
### iterator() {#iterator--}
```
public System.Collections.IEnumerator<T1> iterator()
```


Returns an enumerator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator<T1> - Enumerator object.
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
