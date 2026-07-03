---
title: TabStops
second_title: Aspose.PDF for Java API Reference
description: Represents a collection of {@code TabStop} objects.
type: docs
weight: 4850
url: /java/com.aspose.pdf/tabstops/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStops

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class TabStops extends Object implements com.aspose.ms.System.ICloneable
```

Represents a collection of {@code TabStop} objects.

## Constructors

| Constructor | Description |
| --- | --- |
| [TabStops](#TabStops--) | Initializes a new instance of the {@code TabStops} class. |

## Methods

| Method | Description |
| --- | --- |
| [add](#add--) | Initializes a new instance of the {@code TabStop} class and add it to the TabStops collection. |
| [add](#add-float-) | Initializes a new instance of the {@code TabStop} class with specified position and add it to the TabStops collection. |
| [add](#add-float-int-) | Initializes a new instance of the {@code TabStop} class with specified position and leader type and add it to the TabStops collection. |
| [add](#add-com.aspose.pdf.TabStop-) | Initializes a new instance of the {@code TabStop} class and add it to the TabStops collection. |
| [deepClone](#deepClone--) | Clones a new {@code TabStops} objects. |
| [get_Item](#get_Item-int-) | Gets a {@code TabStop} object from the collection according to TabStop index. |
| [getCount](#getCount--) | Returns tabStops Cound |
| [isReadOnly](#isReadOnly--) | Gets value indicating that this {@code TabStops} instance is already attached to {@code TextFragment} and became readonly. |
| [set_Item](#set_Item-int-com.aspose.pdf.TabStop-) | Sets a {@code TabStop} object from the collection according to TabStop index. |

### TabStops {#TabStops--}
```
public TabStops()
```

Initializes a new instance of the {@code TabStops} class.

### add {#add--}
```
public TabStop add()
```

Initializes a new instance of the {@code TabStop} class and add it to the TabStops collection.

**Returns:**
The new {@code TabStop} object.

### add {#add-float-}
```
public TabStop add(float position)
```

Initializes a new instance of the {@code TabStop} class with specified position and add it to the TabStops collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position |  | The position of the tab stop. |

**Returns:**
The new {@code TabStop} object.

### add {#add-float-int-}
```
public TabStop add(float position, int leaderType)
```

Initializes a new instance of the {@code TabStop} class with specified position and leader type and add it to the TabStops collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position |  | The position of the tab stop. |
| leaderType |  | The leader type of the tab stop. |

**Returns:**
The new {@code TabStop} object.

### add {#add-com.aspose.pdf.TabStop-}
Initializes a new instance of the {@code TabStop} class and add it to the TabStops collection.

**Returns:**
The new {@code TabStop} object.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clones a new {@code TabStops} objects.

**Returns:**
The new {@code TabStops} object.

### get_Item {#get_Item-int-}
```
public TabStop get_Item(int index)
```

Gets a {@code TabStop} object from the collection according to TabStop index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Zero-based index of element in {@code TabStops} collection. |

**Returns:**
{@code TabStop} object.

### getCount {#getCount--}
```
public int getCount()
```

Returns tabStops Cound

**Returns:**
int value

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gets value indicating that this {@code TabStops} instance is already attached to {@code TextFragment} and became readonly.

**Returns:**
boolean value

### set_Item {#set_Item-int-com.aspose.pdf.TabStop-}
Sets a {@code TabStop} object from the collection according to TabStop index.
