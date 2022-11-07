---
title: OutlineCollection
second_title: Aspose.PDF for Java API Reference
description: Represents document outline hierarchy.
type: docs
weight: 191
url: /java/com.aspose.pdf/outlinecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class OutlineCollection implements Iterable<OutlineItemCollection>
```

Represents document outline hierarchy.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Gets the total number of outline items (bookmarks) at all levels of the document outline. |
| [getFirst()](#getFirst--) | Gets an outline item representing the first top-level item in the outline. |
| [getLast()](#getLast--) | Gets an outline item representing the last top-level item in the outline. |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to this collection is synchronized (thread safe). |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to this collection. |
| [add(OutlineItemCollection outline)](#add-com.aspose.pdf.OutlineItemCollection-) | Adds outline item to collection. |
| [delete()](#delete--) | Deletes all outline items from the document outline. |
| [delete(String name)](#delete-java.lang.String-) | Deletes the outline item with specified title from the document outline. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets outline item from collection by index. |
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

### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - An System.Collections.IEnumerator object that can be used to iterate through the collection.
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
