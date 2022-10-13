---
title: LightweightOperatorCollection
second_title: Aspose.PDF for Java API Reference
description: Lightweight operator collection.
type: docs
weight: 161
url: /java/com.aspose.pdf/lightweightoperatorcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseOperatorCollection](../../com.aspose.pdf/baseoperatorcollection)

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public class LightweightOperatorCollection extends BaseOperatorCollection implements System.Collections.Generic.IGenericEnumerable<Operator>
```

Lightweight operator collection. Intended to be used in scenarios when underlying contents stream is not attached, where just operator collection is required as a result.
## Constructors

| Constructor | Description |
| --- | --- |
| [LightweightOperatorCollection()](#LightweightOperatorCollection--) | Initialize object |
| [LightweightOperatorCollection(OperatorCollection operatorCollection)](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | Initialize object |
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets operator by its index. |
| [set_Item(int index, Operator value)](#set-Item-int-com.aspose.pdf.Operator-) | Sets operator by its index. |
| [iterator()](#iterator--) | Return iterator |
| [size()](#size--) | Operators count |
| [getSyncRoot()](#getSyncRoot--) | Return SyncRoot Object |
| [isSynchronized()](#isSynchronized--) | Return true if isSynchronized |
| [isFastTextExtractionMode()](#isFastTextExtractionMode--) | Indicates wheather collection is limited to fast text extraction |
| [suppressUpdate()](#suppressUpdate--) | Suppresses update contents data. |
| [resumeUpdate()](#resumeUpdate--) | Resumes document update. |
| [insert(int index, Operator op)](#insert-int-com.aspose.pdf.Operator-) | Insert operator |
| [add(Operator op)](#add-com.aspose.pdf.Operator-) | Add operator |
| [getUnrestricted(int index)](#getUnrestricted-int-) | For internal usage getUnrestricted operator |
| [updateData()](#updateData--) | internal |
| [deleteUnrestricted(int index)](#deleteUnrestricted-int-) | internal delete Unrestrictedelement |
| [cancelUpdate()](#cancelUpdate--) | Cancels last update. |
| [toList()](#toList--) | Returns operators list. |
### LightweightOperatorCollection() {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```


Initialize object

### LightweightOperatorCollection(OperatorCollection operatorCollection) {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
```
public LightweightOperatorCollection(OperatorCollection operatorCollection)
```


Initialize object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorCollection | [OperatorCollection](../../com.aspose.pdf/operatorcollection) | OperatorCollection object |

### get_Item(int index) {#get-Item-int-}
```
public Operator get_Item(int index)
```


Gets operator by its index.

--------------------

> ```
> Example demonstrates how to get operator of page contents by index.
> 
>  
>  Document doc = new Document("input.pdf");
>  OperatorCollection oc = doc.getPages().get_Item(1).getContents();
>  Operator first = oc.get_Item(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. Numbering is starts from 1. |

**Returns:**
[Operator](../../com.aspose.pdf/operator) - Operator from requested index
### set_Item(int index, Operator value) {#set-Item-int-com.aspose.pdf.Operator-}
```
public void set_Item(int index, Operator value)
```


Sets operator by its index.

--------------------

> ```
> Example demonstrates how to get operator of page contents by index.
> 
>  
>  Document doc = new Document("input.pdf");
>  OperatorCollection oc = doc.getPages().get_Item(1).getContents();
>  Operator first = oc.get_Item(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. Numbering is starts from 1. |
| value | [Operator](../../com.aspose.pdf/operator) | Operator from requested index |

### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<Operator> iterator()
```


Return iterator

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.Operator> - IGenericEnumerator object
### size() {#size--}
```
public int size()
```


Operators count

**Returns:**
int - int value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Return SyncRoot Object

**Returns:**
java.lang.Object - Return SyncRoot Object
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Return true if isSynchronized

**Returns:**
boolean - boolean value
### isFastTextExtractionMode() {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```


Indicates wheather collection is limited to fast text extraction

**Returns:**
boolean - boolean value
### suppressUpdate() {#suppressUpdate--}
```
public void suppressUpdate()
```


Suppresses update contents data. The contents stream is not updated until ResumeUpdate is called.

### resumeUpdate() {#resumeUpdate--}
```
public void resumeUpdate()
```


Resumes document update. Updates contents stream in case there are any pending changes.

### insert(int index, Operator op) {#insert-int-com.aspose.pdf.Operator-}
```
public void insert(int index, Operator op)
```


Insert operator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | int value |
| op | [Operator](../../com.aspose.pdf/operator) | Operator object |

### add(Operator op) {#add-com.aspose.pdf.Operator-}
```
public void add(Operator op)
```


Add operator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Operator object |

### getUnrestricted(int index) {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```


For internal usage getUnrestricted operator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | int value |

**Returns:**
[Operator](../../com.aspose.pdf/operator) - Operator object
### updateData() {#updateData--}
```
public void updateData()
```


internal

### deleteUnrestricted(int index) {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```


internal delete Unrestrictedelement

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | int value |

### cancelUpdate() {#cancelUpdate--}
```
public void cancelUpdate()
```


Cancels last update. This method may be called when the change should not raise contents update.

### toList() {#toList--}
```
public System.Collections.Generic.List<Operator> toList()
```


Returns operators list.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> - operators list.
