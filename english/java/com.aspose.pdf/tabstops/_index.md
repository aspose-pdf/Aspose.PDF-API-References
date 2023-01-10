---
title: TabStops
second_title: Aspose.PDF for Java API Reference
description: Represents a collection of TabStop objects.
type: docs
weight: 352
url: /java/com.aspose.pdf/tabstops/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public class TabStops implements System.ICloneable
```

Represents a collection of  TabStop  objects.
## Constructors

| Constructor | Description |
| --- | --- |
| [TabStops()](#TabStops--) | Initializes a new instance of the  TabStops  class. |
## Methods

| Method | Description |
| --- | --- |
| [isReadOnly()](#isReadOnly--) | Gets value indicating that this  TabStops  instance is already attached to  TextFragment  and became readonly. |
| [add()](#add--) | Initializes a new instance of the  TabStop  class and add it to the TabStops collection. |
| [add(float position)](#add-float-) | Initializes a new instance of the  TabStop  class with specified position and add it to the TabStops collection. |
| [add(TabStop tabStop)](#add-com.aspose.pdf.TabStop-) | Add instance of the  TabStop  class to the TabStops collection. |
| [getCount()](#getCount--) | Returns tabStops Cound |
| [add(float position, int leaderType)](#add-float-int-) | Initializes a new instance of the  TabStop  class with specified position and leader type and add it to the TabStops collection. |
| [deepClone()](#deepClone--) | Clones a new  TabStops  objects. |
| [get_Item(int index)](#get-Item-int-) | Gets a  TabStop  object from the collection according to TabStop index. |
| [set_Item(int index, TabStop value)](#set-Item-int-com.aspose.pdf.TabStop-) | Sets a  TabStop  object from the collection according to TabStop index. |
### TabStops() {#TabStops--}
```
public TabStops()
```


Initializes a new instance of the  TabStops  class.

### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets value indicating that this  TabStops  instance is already attached to  TextFragment  and became readonly.

**Returns:**
boolean - boolean value
### add() {#add--}
```
public TabStop add()
```


Initializes a new instance of the  TabStop  class and add it to the TabStops collection.

**Returns:**
[TabStop](../../com.aspose.pdf/tabstop) - The new  TabStop  object.
### add(float position) {#add-float-}
```
public TabStop add(float position)
```


Initializes a new instance of the  TabStop  class with specified position and add it to the TabStops collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | The position of the tab stop. |

**Returns:**
[TabStop](../../com.aspose.pdf/tabstop) - The new  TabStop  object.
### add(TabStop tabStop) {#add-com.aspose.pdf.TabStop-}
```
public void add(TabStop tabStop)
```


Add instance of the  TabStop  class to the TabStops collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tabStop | [TabStop](../../com.aspose.pdf/tabstop) | The  TabStop  object. |

### getCount() {#getCount--}
```
public int getCount()
```


Returns tabStops Cound

**Returns:**
int - int value
### add(float position, int leaderType) {#add-float-int-}
```
public TabStop add(float position, int leaderType)
```


Initializes a new instance of the  TabStop  class with specified position and leader type and add it to the TabStops collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | The position of the tab stop. |
| leaderType | int | The leader type of the tab stop. |

**Returns:**
[TabStop](../../com.aspose.pdf/tabstop) - The new  TabStop  object.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clones a new  TabStops  objects.

**Returns:**
java.lang.Object - The new  TabStops  object.
### get_Item(int index) {#get-Item-int-}
```
public TabStop get_Item(int index)
```


Gets a  TabStop  object from the collection according to TabStop index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Zero-based index of element in  TabStops  collection. |

**Returns:**
[TabStop](../../com.aspose.pdf/tabstop) -  TabStop  object.
### set_Item(int index, TabStop value) {#set-Item-int-com.aspose.pdf.TabStop-}
```
public void set_Item(int index, TabStop value)
```


Sets a  TabStop  object from the collection according to TabStop index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Zero-based index of element in  TabStops  collection. |
| value | [TabStop](../../com.aspose.pdf/tabstop) |  TabStop  object. |

