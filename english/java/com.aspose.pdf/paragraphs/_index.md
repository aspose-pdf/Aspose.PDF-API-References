---
title: Paragraphs
second_title: Aspose.PDF for Java API Reference
description: This class represents paragraph collection.
type: docs
weight: 270
url: /java/com.aspose.pdf/paragraphs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable, com.aspose.ms.System.ICloneable
```
public class Paragraphs implements Iterable<BaseParagraph>, System.ICloneable
```

This class represents paragraph collection.
## Constructors

| Constructor | Description |
| --- | --- |
| [Paragraphs()](#Paragraphs--) |  |
## Methods

| Method | Description |
| --- | --- |
| [add(BaseParagraph paragraph)](#add-com.aspose.pdf.BaseParagraph-) | Add paragraph to collection. |
| [getRange(int index, int count)](#getRange-int-int-) | Remove paragraphs range. |
| [removeRange(int index, int count)](#removeRange-int-int-) | Remove paragraphs range. |
| [remove(BaseParagraph paragraph)](#remove-com.aspose.pdf.BaseParagraph-) | Remove paragraph from collection. |
| [insert(int index, BaseParagraph paragraph)](#insert-int-com.aspose.pdf.BaseParagraph-) | Insert paragraph to collection. |
| [getCount()](#getCount--) | Get paragraphs count. |
| [clear()](#clear--) | Clear paragraphs. |
| [insertRange(int index, System.Collections.Generic.List<BaseParagraph> collection)](#insertRange-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.BaseParagraph--) | Inserts the elements of a collection into the list at the specified index. |
| [get_Item(int index)](#get-Item-int-) | Gets paragraph from collection. |
| [set_Item(int index, BaseParagraph value)](#set-Item-int-com.aspose.pdf.BaseParagraph-) | Sets paragraph to collection. |
| [iterator()](#iterator--) |  |
| [deepClone()](#deepClone--) | Clones a new  Clone  object. |
### Paragraphs() {#Paragraphs--}
```
public Paragraphs()
```


### add(BaseParagraph paragraph) {#add-com.aspose.pdf.BaseParagraph-}
```
public void add(BaseParagraph paragraph)
```


Add paragraph to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [BaseParagraph](../../com.aspose.pdf/baseparagraph) | The paragraph. |

### getRange(int index, int count) {#getRange-int-int-}
```
public Paragraphs getRange(int index, int count)
```


Remove paragraphs range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The first paragraph index. |
| count | int | The paragraphs count. |

**Returns:**
[Paragraphs](../../com.aspose.pdf/paragraphs) - The paragraphs collection
### removeRange(int index, int count) {#removeRange-int-int-}
```
public void removeRange(int index, int count)
```


Remove paragraphs range.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The first paragraph index. |
| count | int | The paragraphs count. |

### remove(BaseParagraph paragraph) {#remove-com.aspose.pdf.BaseParagraph-}
```
public void remove(BaseParagraph paragraph)
```


Remove paragraph from collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [BaseParagraph](../../com.aspose.pdf/baseparagraph) | BaseParagraph object |

### insert(int index, BaseParagraph paragraph) {#insert-int-com.aspose.pdf.BaseParagraph-}
```
public void insert(int index, BaseParagraph paragraph)
```


Insert paragraph to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index for paragraph. |
| paragraph | [BaseParagraph](../../com.aspose.pdf/baseparagraph) | The paragraph. |

### getCount() {#getCount--}
```
public int getCount()
```


Get paragraphs count.

**Returns:**
int - int value
### clear() {#clear--}
```
public void clear()
```


Clear paragraphs.

### insertRange(int index, System.Collections.Generic.List<BaseParagraph> collection) {#insertRange-int-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.BaseParagraph--}
```
public void insertRange(int index, System.Collections.Generic.List<BaseParagraph> collection)
```


Inserts the elements of a collection into the list at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | int value (Index) |
| collection | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.BaseParagraph> | list of BaseParagraph objects (Collection) |

### get_Item(int index) {#get-Item-int-}
```
public BaseParagraph get_Item(int index)
```


Gets paragraph from collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The paragraph index. |

**Returns:**
[BaseParagraph](../../com.aspose.pdf/baseparagraph) - BaseParagraph object
### set_Item(int index, BaseParagraph value) {#set-Item-int-com.aspose.pdf.BaseParagraph-}
```
public void set_Item(int index, BaseParagraph value)
```


Sets paragraph to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The paragraph index. |
| value | [BaseParagraph](../../com.aspose.pdf/baseparagraph) | BaseParagraph object |

### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```




**Returns:**
com.aspose.ms.System.Collections.IEnumerator
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones a new  Clone  object.

**Returns:**
java.lang.Object - The new  Clone  object.
