---
title: FontSourceCollection
linktitle: FontSourceCollection
second_title: Aspose.PDF for Java API Reference
description: Represents font sources collection.
type: docs
weight: 40
url: /java/com.aspose.pdf.text/fontsourcecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSourceCollection

**All Implemented Interfaces:**
Iterable < FontSource >

```
public final class FontSourceCollection extends Object implements Iterable < FontSource >
```

Represents font sources collection.

## Fields

| Field | Description |
| --- | --- |
| [CollectionChanged](#CollectionChanged) | CollectionChanged event |

## Constructors

| Constructor | Description |
| --- | --- |
| [FontSourceCollection](#FontSourceCollection--) | Initializes collection object |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.FontSource-) | Adds new font source object to the collection. |
| [clear](#clear--) | Clears the font source collection. |
| [contains](#contains-com.aspose.pdf.FontSource-) | Determines whether an element is in the collection. |
| [copyTo](#copyTo-com.aspose.pdf.FontSource:A-int-) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array |
| [delete](#delete-com.aspose.pdf.FontSource-) | Deletes the font source element. |
| [getItem](#getItem-int-) | Gets the font element at the specified index. |
| [getSyncRoot](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [isSynchronized](#isSynchronized--) | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [iterator](#iterator--) | Returns an enumerator for the entire collection. |
| [remove](#remove-com.aspose.pdf.FontSource-) | Deletes the font source element. |
| [size](#size--) | Gets the number of Font object elements actually contained in the collection. |

### CollectionChanged {#CollectionChanged}
```
public final PdfEvent <com.aspose.ms.System.EventHandler> CollectionChanged
```

CollectionChanged event

### FontSourceCollection {#FontSourceCollection--}
```
public FontSourceCollection()
```

Initializes collection object

### add {#add-com.aspose.pdf.FontSource-}
Adds new font source object to the collection.

### clear {#clear--}
```
public void clear()
```

Clears the font source collection.

### contains {#contains-com.aspose.pdf.FontSource-}
Determines whether an element is in the collection.

### copyTo {#copyTo-com.aspose.pdf.FontSource:A-int-}
Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array

### delete {#delete-com.aspose.pdf.FontSource-}
Deletes the font source element.

### getItem {#getItem-int-}
```
public FontSource getItem(int index)
```

Gets the font element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index within the collection. |

**Returns:**
Font source object.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Gets an object that can be used to synchronize access to the collection.

**Returns:**
Object element

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Gets a value indicating whether access to the collection is synchronized (thread safe).

**Returns:**
boolean value

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator()
```

Returns an enumerator for the entire collection.

**Returns:**
Enumerator object.

### remove {#remove-com.aspose.pdf.FontSource-}
Deletes the font source element.

### size {#size--}
```
public int size()
```

Gets the number of Font object elements actually contained in the collection.

**Returns:**
int value
