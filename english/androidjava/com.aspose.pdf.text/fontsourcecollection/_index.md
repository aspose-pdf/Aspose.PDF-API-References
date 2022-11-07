---
title: FontSourceCollection
second_title: Aspose.PDF for Java API Reference
description: Represents font sources collection.
type: docs
weight: 13
url: /java/com.aspose.pdf.text/fontsourcecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class FontSourceCollection implements Iterable
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
| [size()](#size--) | Gets the number of  object elements actually contained in the collection. |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [iterator()](#iterator--) | Returns an enumerator for the entire collection. |
| [add(FontSource fontSource)](#add-com.aspose.pdf.FontSource-) | Adds new font source object to the collection. |
| [clear()](#clear--) | Clears the font source collection. |
| [delete(FontSource fontSource)](#delete-com.aspose.pdf.FontSource-) | Deletes the font source element. |
| [getItem(int index)](#getItem-int-) | Gets the font element at the specified index. |
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

### size() {#size--}
```
public int size()
```


Gets the number of  object elements actually contained in the collection.

**Returns:**
int - int value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to the collection.

**Returns:**
java.lang.Object - Object element
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

### delete(FontSource fontSource) {#delete-com.aspose.pdf.FontSource-}
```
public void delete(FontSource fontSource)
```


Deletes the font source element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontSource | [FontSource](../../com.aspose.pdf/fontsource) | FontSource object that will be deleted. |

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
[FontSource](../../com.aspose.pdf/fontsource) - Fout source object.
