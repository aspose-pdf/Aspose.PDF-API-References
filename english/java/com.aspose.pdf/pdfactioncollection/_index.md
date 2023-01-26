---
title: PdfActionCollection
second_title: Aspose.PDF for Java API Reference
description: Class describes list of actions.
type: docs
weight: 279
url: /java/com.aspose.pdf/pdfactioncollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class PdfActionCollection implements Iterable<PdfAction>
```

Class describes list of actions.
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Gets count of actions. |
| [get_Item(int index)](#get-Item-int-) | Gets action by its index. |
| [delete(int index)](#delete-int-) | Remove action by index. |
| [add(PdfAction action)](#add-com.aspose.pdf.PdfAction-) | Add action to action list. |
| [iterator()](#iterator--) | Gets enumerator. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | Internal method |
### getCount() {#getCount--}
```
public int getCount()
```


Gets count of actions.

**Returns:**
int - int value
### get_Item(int index) {#get-Item-int-}
```
public PdfAction get_Item(int index)
```


Gets action by its index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Action index value. |

**Returns:**
[PdfAction](../../com.aspose.pdf/pdfaction) - PdfAction index if found; otherwise, throws
### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Remove action by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of action to remove. |

### add(PdfAction action) {#add-com.aspose.pdf.PdfAction-}
```
public void add(PdfAction action)
```


Add action to action list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| action | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction instance Action to be added. |

### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<PdfAction> iterator()
```


Gets enumerator.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.PdfAction> - PDfAction enumerator.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator<PdfAction> iterator_Rename_Namesake()
```


Internal method

**Returns:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.PdfAction> - internal object.
