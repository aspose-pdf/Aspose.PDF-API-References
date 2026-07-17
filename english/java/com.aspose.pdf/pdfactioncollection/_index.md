---
title: PdfActionCollection
linktitle: PdfActionCollection
second_title: Aspose.PDF for Java API Reference
description: Class describes list of actions.
type: docs
weight: 3680
url: /java/com.aspose.pdf/pdfactioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public class PdfActionCollection extends Object implements Iterable < PdfAction >
```

Class describes list of actions.

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | Add action to action list. |
| [delete](#delete-int-) | Remove action by index. |
| [get_Item](#get_Item-int-) | Gets action by its index. |
| [getCount](#getCount--) | Gets count of actions. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Internal method |
| [iterator](#iterator--) | Gets enumerator. |

### add {#add-com.aspose.pdf.PdfAction-}
Add action to action list.

### delete {#delete-int-}
```
public void delete(int index)
```

Remove action by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of action to remove. |

### get_Item {#get_Item-int-}
```
public PdfAction get_Item(int index)
```

Gets action by its index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Action index value. |

**Returns:**
PdfAction index if found; otherwise, throws @throws IndexOutOfRangeException IndexOutOfRangeException

### getCount {#getCount--}
```
public int getCount()
```

Gets count of actions.

**Returns:**
int value

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator_Rename_Namesake()
```

Internal method

**Returns:**
internal object.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< PdfAction > iterator()
```

Gets enumerator.

**Returns:**
PDfAction enumerator.
