---
title: ActionCollection
second_title: Aspose.PDF for Java API Reference
description: Collection of actions
type: docs
weight: 14
url: /java/com.aspose.pdf/actioncollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class ActionCollection implements Iterable<PdfAction>
```

Collection of actions
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Count of actions on the collection. |
| [isSynchronized()](#isSynchronized--) | Returns true if object is synchronized. |
| [getSyncRoot()](#getSyncRoot--) | Gets synchronization object. |
| [isReadOnly()](#isReadOnly--) | Returns true if collection is readonly. |
| [add(PdfAction action)](#add-com.aspose.pdf.PdfAction-) | Adds new action into colleciton. |
| [delete(int index)](#delete-int-) | Removes action from collection by index. |
| [delete()](#delete--) | Delete all actions. |
| [copyTo(PdfAction[] array, int index)](#copyTo-com.aspose.pdf.PdfAction---int-) | Copies actions array into collection. |
| [iterator()](#iterator--) | Returns enumerator for collection. |
| [clear()](#clear--) | Clear collection. |
| [contains(PdfAction item)](#contains-com.aspose.pdf.PdfAction-) | Not supported yet. |
| [remove(PdfAction item)](#remove-com.aspose.pdf.PdfAction-) | \* Not supported yet. |
| [get_Item(int index)](#get-Item-int-) | Gets action by its index. |
### size() {#size--}
```
public int size()
```


Count of actions on the collection.

**Returns:**
int - int value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Returns true if object is synchronized.

**Returns:**
boolean - boolean value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets synchronization object.

**Returns:**
java.lang.Object - Object value
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Returns true if collection is readonly.

**Returns:**
boolean - boolean value
### add(PdfAction action) {#add-com.aspose.pdf.PdfAction-}
```
public void add(PdfAction action)
```


Adds new action into colleciton.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| action | [PdfAction](../../com.aspose.pdf/pdfaction) | Action which should be added. |

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Removes action from collection by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of action to remove. |

### delete() {#delete--}
```
public void delete()
```


Delete all actions.

### copyTo(PdfAction[] array, int index) {#copyTo-com.aspose.pdf.PdfAction---int-}
```
public void copyTo(PdfAction[] array, int index)
```


Copies actions array into collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [PdfAction\[\]](../../com.aspose.pdf/pdfaction) | Array of actions which must be copied into collection. |
| index | int | Index starting from which array will be copied. |

### iterator() {#iterator--}
```
public System.Collections.IEnumerator<PdfAction> iterator()
```


Returns enumerator for collection.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.PdfAction> - Collection enumerator.
### clear() {#clear--}
```
public void clear()
```


Clear collection.

### contains(PdfAction item) {#contains-com.aspose.pdf.PdfAction-}
```
public boolean contains(PdfAction item)
```


Not supported yet.

Returns true if give item presents in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction instance Not implemented. |

**Returns:**
boolean - boolean value Item to find.
### remove(PdfAction item) {#remove-com.aspose.pdf.PdfAction-}
```
public boolean remove(PdfAction item)
```


\* Not supported yet.

Removes item from collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [PdfAction](../../com.aspose.pdf/pdfaction) | Item to delete. |

**Returns:**
boolean - boolean value Not implemented.
### get_Item(int index) {#get-Item-int-}
```
public PdfAction get_Item(int index)
```


Gets action by its index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of action. |

**Returns:**
[PdfAction](../../com.aspose.pdf/pdfaction) - Retreived action.
