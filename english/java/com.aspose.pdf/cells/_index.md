---
title: Cells
second_title: Aspose.PDF for Java API Reference
description: Represents a cells collection of row.
type: docs
weight: 50
url: /java/com.aspose.pdf/cells/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class Cells implements Iterable<Cell>
```

Represents a cells collection of row.
## Constructors

| Constructor | Description |
| --- | --- |
| [Cells()](#Cells--) |  |
## Methods

| Method | Description |
| --- | --- |
| [add()](#add--) | Add cell to collection. |
| [add(String text, TextState ts)](#add-java.lang.String-com.aspose.pdf.TextState-) | Add cell to collection. |
| [add(String text)](#add-java.lang.String-) | Add cell to collection. |
| [add(Cell cell)](#add-com.aspose.pdf.Cell-) | Add cell to collection. |
| [removeRange(int index, int count)](#removeRange-int-int-) | Remove cell set from collection. |
| [remove(Object obj)](#remove-java.lang.Object-) | Remove cell set from collection. |
| [remove(Cell cell)](#remove-com.aspose.pdf.Cell-) | Remove cell set from collection. |
| [insert(int index, Cell cell)](#insert-int-com.aspose.pdf.Cell-) | Insert cell to collection. |
| [iterator()](#iterator--) | Gets collection's enumerator. |
| [getCount()](#getCount--) | The items count. |
| [get_Item(int index)](#get-Item-int-) | Gets cell. |
| [set_Item(int index, Cell value)](#set-Item-int-com.aspose.pdf.Cell-) | Sets cells. |
### Cells() {#Cells--}
```
public Cells()
```


### add() {#add--}
```
public Cell add()
```


Add cell to collection.

**Returns:**
[Cell](../../com.aspose.pdf/cell) - The new cell
### add(String text, TextState ts) {#add-java.lang.String-com.aspose.pdf.TextState-}
```
public Cell add(String text, TextState ts)
```


Add cell to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text for cell. |
| ts | [TextState](../../com.aspose.pdf/textstate) | The text state. |

**Returns:**
[Cell](../../com.aspose.pdf/cell) - The new cell
### add(String text) {#add-java.lang.String-}
```
public Cell add(String text)
```


Add cell to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text for cell. |

**Returns:**
[Cell](../../com.aspose.pdf/cell) - The new cell
### add(Cell cell) {#add-com.aspose.pdf.Cell-}
```
public void add(Cell cell)
```


Add cell to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell | [Cell](../../com.aspose.pdf/cell) | The cell to collection. |

### removeRange(int index, int count) {#removeRange-int-int-}
```
public void removeRange(int index, int count)
```


Remove cell set from collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The collection index. |
| count | int | The rows count. |

### remove(Object obj) {#remove-java.lang.Object-}
```
public void remove(Object obj)
```


Remove cell set from collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object. |

### remove(Cell cell) {#remove-com.aspose.pdf.Cell-}
```
public void remove(Cell cell)
```


Remove cell set from collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell | [Cell](../../com.aspose.pdf/cell) | The cell object. |

### insert(int index, Cell cell) {#insert-int-com.aspose.pdf.Cell-}
```
public void insert(int index, Cell cell)
```


Insert cell to collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The selected index. |
| cell | [Cell](../../com.aspose.pdf/cell) | The selected cell. |

### iterator() {#iterator--}
```
public Iterator<Cell> iterator()
```


Gets collection's enumerator.

**Returns:**
java.util.Iterator<com.aspose.pdf.Cell> - Iterator of Cell instances
### getCount() {#getCount--}
```
public int getCount()
```


The items count.

**Returns:**
int - int value
### get_Item(int index) {#get-Item-int-}
```
public Cell get_Item(int index)
```


Gets cell.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The cell index. |

**Returns:**
[Cell](../../com.aspose.pdf/cell) - Cell object
### set_Item(int index, Cell value) {#set-Item-int-com.aspose.pdf.Cell-}
```
public void set_Item(int index, Cell value)
```


Sets cells.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The cell index. |
| value | [Cell](../../com.aspose.pdf/cell) | The cells value |

