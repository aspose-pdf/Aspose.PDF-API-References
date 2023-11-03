---
title: TextFragmentCollection
second_title: Aspose.PDF for Java API Reference
description: Represents a text fragments collection
type: docs
weight: 375
url: /java/com.aspose.pdf/textfragmentcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class TextFragmentCollection implements Iterable<TextFragment>
```

Represents a text fragments collection
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Gets the number of  TextFragment  object elements actually contained in the collection. |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether collection is read-only |
| [add(TextFragment fragment)](#add-com.aspose.pdf.TextFragment-) | Adds the text fragment element at the specified index. |
| [iterator()](#iterator--) | Returns an enumerator for the entire collection. |
| [copyTo(TextFragment[] array, int index)](#copyTo-com.aspose.pdf.TextFragment---int-) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array |
| [clear()](#clear--) | Clears all items from the collection. |
| [contains(TextFragment item)](#contains-com.aspose.pdf.TextFragment-) | Determines whether the collection contains a specific value. |
| [remove(TextFragment item)](#remove-com.aspose.pdf.TextFragment-) | Deletes specified item from collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the text fragment element at the specified index. |
### size() {#size--}
```
public int size()
```


Gets the number of  TextFragment  object elements actually contained in the collection.

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
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether collection is read-only

**Returns:**
boolean - boolean value
### add(TextFragment fragment) {#add-com.aspose.pdf.TextFragment-}
```
public void add(TextFragment fragment)
```


Adds the text fragment element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fragment | [TextFragment](../../com.aspose.pdf/textfragment) | TextFragment object element to add. |

### iterator() {#iterator--}
```
public Iterator<TextFragment> iterator()
```


Returns an enumerator for the entire collection.

**Returns:**
java.util.Iterator<com.aspose.pdf.TextFragment> - Enumerator object.
### copyTo(TextFragment[] array, int index) {#copyTo-com.aspose.pdf.TextFragment---int-}
```
public void copyTo(TextFragment[] array, int index)
```


Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [TextFragment\[\]](../../com.aspose.pdf/textfragment) | Array of objects which will be copied. |
| index | int | Starting index from which copying will be started. |

### clear() {#clear--}
```
public void clear()
```


Clears all items from the collection.

### contains(TextFragment item) {#contains-com.aspose.pdf.TextFragment-}
```
public boolean contains(TextFragment item)
```


Determines whether the collection contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [TextFragment](../../com.aspose.pdf/textfragment) | The object to locate in the collection |

**Returns:**
boolean - true if item is found in the collection; otherwise, false.
### remove(TextFragment item) {#remove-com.aspose.pdf.TextFragment-}
```
public boolean remove(TextFragment item)
```


Deletes specified item from collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [TextFragment](../../com.aspose.pdf/textfragment) | The object to delete |

**Returns:**
boolean - true if item was deleted from collection; otherwise, false.
### get_Item(int index) {#get-Item-int-}
```
public TextFragment get_Item(int index)
```


Gets the text fragment element at the specified index.

Index should be in the range [1..n] where n equals to the text fragments count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index within the collection. |

**Returns:**
[TextFragment](../../com.aspose.pdf/textfragment) - TextFragment object.
