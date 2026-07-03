---
title: PDF3DCrossSectionArray
linktitle: PDF3DCrossSectionArray
second_title: Aspose.PDF for Java API Reference
description: Class PDF3DCrossSectionArray.
type: docs
weight: 3600
url: /java/com.aspose.pdf/pdf3dcrosssectionarray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DCrossSectionArray

```
public class PDF3DCrossSectionArray extends Object
```

Class PDF3DCrossSectionArray.

## Constructors

| Constructor | Description |
| --- | --- |
| [PDF3DCrossSectionArray](#PDF3DCrossSectionArray-com.aspose.pdf.IDocument-) | Initializes a new instance of the {@code PDF3DCrossSectionArray} class. |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.PDF3DCrossSection-) | Adds the specified cross section to views array . |
| [get_Item](#get_Item-int-) | Gets or sets the {@code PDF3DCrossSection} at the specified index. |
| [getCount](#getCount--) | Gets the cross section count. |
| [removeAll](#removeAll--) | Removes all cross section from array. |
| [removeAt](#removeAt-int-) | Removes cross section from array at specified index. |
| [set_Item](#set_Item-int-com.aspose.pdf.PDF3DCrossSection-) | Gets or sets the {@code PDF3DCrossSection} at the specified index. |

### PDF3DCrossSectionArray {#PDF3DCrossSectionArray-com.aspose.pdf.IDocument-}
Initializes a new instance of the {@code PDF3DCrossSectionArray} class.

### add {#add-com.aspose.pdf.PDF3DCrossSection-}
Adds the specified cross section to views array .

### get_Item {#get_Item-int-}
```
public PDF3DCrossSection get_Item(int index)
```

Gets or sets the {@code PDF3DCrossSection} at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | The index. |

**Returns:**
Cross section. @throws IndexOutOfRangeException Invalid index: index should be in the range [1..n] where n equals to the cross sections count.

### getCount {#getCount--}
```
public int getCount()
```

Gets the cross section count.

**Returns:**
int value: The cross section count.

### removeAll {#removeAll--}
```
public void removeAll()
```

Removes all cross section from array.

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

Removes cross section from array at specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | The index of removed cross section in array. @throws IndexOutOfRangeException Invalid index: index should be in the range [1..n] where n equals to the cross sections count. |

### set_Item {#set_Item-int-com.aspose.pdf.PDF3DCrossSection-}
Gets or sets the {@code PDF3DCrossSection} at the specified index.
