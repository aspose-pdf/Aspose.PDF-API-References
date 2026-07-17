---
title: TextFragmentCollection
linktitle: TextFragmentCollection
second_title: Aspose.PDF for Java API Reference
description: Represents a text fragments collection
type: docs
weight: 5130
url: /java/com.aspose.pdf/textfragmentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextFragmentCollection

**All Implemented Interfaces:**
Iterable < TextFragment >

```
public final class TextFragmentCollection extends Object implements Iterable < TextFragment >
```

Represents a text fragments collection

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.TextFragment-) | Adds the text fragment element at the specified index. |
| [clear](#clear--) | Clears all items from the collection. |
| [contains](#contains-com.aspose.pdf.TextFragment-) | Determines whether the collection contains a specific value. |
| [copyTo](#copyTo-com.aspose.pdf.TextFragment:A-int-) | / * / * Returns an enumerator for the entire collection. / * / * |
| [get_Item](#get_Item-int-) | Gets the text fragment element at the specified index. Index should be in the range [1..n] where n equals to the text fragments count. |
| [getSyncRoot](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [isReadOnly](#isReadOnly--) | Gets a value indicating whether collection is read-only |
| [isSynchronized](#isSynchronized--) | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [iterator](#iterator--) | Returns an enumerator for the entire collection. |
| [remove](#remove-com.aspose.pdf.TextFragment-) | Deletes specified item from collection. |
| [size](#size--) | Gets the number of {@code TextFragment} object elements actually contained in the collection. |

### add {#add-com.aspose.pdf.TextFragment-}
Adds the text fragment element at the specified index.

### clear {#clear--}
```
public void clear()
```

Clears all items from the collection.

### contains {#contains-com.aspose.pdf.TextFragment-}
Determines whether the collection contains a specific value.

### copyTo {#copyTo-com.aspose.pdf.TextFragment:A-int-}
/ * / * Returns an enumerator for the entire collection. / * / *

### get_Item {#get_Item-int-}
```
public TextFragment get_Item(int index)
```

Gets the text fragment element at the specified index. Index should be in the range [1..n] where n equals to the text fragments count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index within the collection. |

**Returns:**
TextFragment object.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Gets an object that can be used to synchronize access to the collection.

**Returns:**
Object element

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gets a value indicating whether collection is read-only

**Returns:**
boolean value

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Gets a value indicating whether access to the collection is synchronized (thread safe).

**Returns:**
boolean value

### iterator {#iterator--}
```
public Iterator < TextFragment > iterator()
```

Returns an enumerator for the entire collection.

**Returns:**
Enumerator object.

### remove {#remove-com.aspose.pdf.TextFragment-}
Deletes specified item from collection.

### size {#size--}
```
public int size()
```

Gets the number of {@code TextFragment} object elements actually contained in the collection.

**Returns:**
int value
