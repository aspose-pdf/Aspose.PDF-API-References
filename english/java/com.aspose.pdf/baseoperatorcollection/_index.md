---
title: BaseOperatorCollection
second_title: Aspose.PDF for Java API Reference
description: Represents base class for operator collection.
type: docs
weight: 32
url: /java/com.aspose.pdf/baseoperatorcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class BaseOperatorCollection implements Iterable<Operator>
```

Represents base class for operator collection.
## Constructors

| Constructor | Description |
| --- | --- |
| [BaseOperatorCollection()](#BaseOperatorCollection--) |  |
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets operator by its index. |
| [set_Item(int index, Operator value)](#set-Item-int-com.aspose.pdf.Operator-) | Sets operator by its index. |
| [iterator()](#iterator--) | Returns enumerator for collection |
| [toList()](#toList--) | Returns opetator list. |
| [size()](#size--) | Gets count of operators in the collection. |
| [isEmpty()](#isEmpty--) | Returns TRUE if the collection is empty. |
| [isReadOnly()](#isReadOnly--) | Returns true if collection is read only. |
| [isFastTextExtractionMode()](#isFastTextExtractionMode--) | Indicates whether collection is limited to fast text extraction |
| [suppressUpdate()](#suppressUpdate--) | Suppresses update contents data. |
| [resumeUpdate()](#resumeUpdate--) | Resumes document update. |
| [insert(int index, Operator op)](#insert-int-com.aspose.pdf.Operator-) | Inserts operator into collection. |
| [add(Operator op)](#add-com.aspose.pdf.Operator-) | Adds new operator into collection. |
| [remove(Operator item)](#remove-com.aspose.pdf.Operator-) | Removes operator from collection. |
| [contains(Operator item)](#contains-com.aspose.pdf.Operator-) | Check if the item is in collection. |
| [clear()](#clear--) | Clears collection. |
| [getUnrestricted(int index)](#getUnrestricted-int-) | For internal usage only |
| [updateData()](#updateData--) | internal |
| [deleteUnrestricted(int index)](#deleteUnrestricted-int-) | internal |
| [cancelUpdate()](#cancelUpdate--) | Cancels last update. |
### BaseOperatorCollection() {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```


### get_Item(int index) {#get-Item-int-}
```
public abstract Operator get_Item(int index)
```


Gets operator by its index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. Numbering is starts from 1. |

**Returns:**
[Operator](../../com.aspose.pdf/operator) - Operator from requested index
### set_Item(int index, Operator value) {#set-Item-int-com.aspose.pdf.Operator-}
```
public abstract void set_Item(int index, Operator value)
```


Sets operator by its index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. Numbering is starts from 1. |
| value | [Operator](../../com.aspose.pdf/operator) | Operator. |

### iterator() {#iterator--}
```
public abstract Iterator<Operator> iterator()
```


Returns enumerator for collection

**Returns:**
java.util.Iterator<com.aspose.pdf.Operator> - Collection enumerator
### toList() {#toList--}
```
public abstract System.Collections.Generic.List<Operator> toList()
```


Returns opetator list.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> - opetator list.
### size() {#size--}
```
public abstract int size()
```


Gets count of operators in the collection.

**Returns:**
int - integer value
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Returns TRUE if the collection is empty.

**Returns:**
boolean - boolean value
### isReadOnly() {#isReadOnly--}
```
public abstract boolean isReadOnly()
```


Returns true if collection is read only.

**Returns:**
boolean - boolean value
### isFastTextExtractionMode() {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```


Indicates whether collection is limited to fast text extraction

**Returns:**
boolean - boolean value
### suppressUpdate() {#suppressUpdate--}
```
public abstract void suppressUpdate()
```


Suppresses update contents data. The contents stream is not updated until ResumeUpdate is called.

### resumeUpdate() {#resumeUpdate--}
```
public abstract void resumeUpdate()
```


Resumes document update. Updates contents stream in case there are any pending changes.

### insert(int index, Operator op) {#insert-int-com.aspose.pdf.Operator-}
```
public abstract void insert(int index, Operator op)
```


Inserts operator into collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index where new operator must be added |
| op | [Operator](../../com.aspose.pdf/operator) | Operator which will be insterted |

### add(Operator op) {#add-com.aspose.pdf.Operator-}
```
public abstract void add(Operator op)
```


Adds new operator into collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Operator which must be added |

### remove(Operator item) {#remove-com.aspose.pdf.Operator-}
```
public abstract boolean remove(Operator item)
```


Removes operator from collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [Operator](../../com.aspose.pdf/operator) | Operator instance item to remove. |

**Returns:**
boolean - boolean value True - if item removed; otherwise, false.
### contains(Operator item) {#contains-com.aspose.pdf.Operator-}
```
public abstract boolean contains(Operator item)
```


Check if the item is in collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [Operator](../../com.aspose.pdf/operator) | Operator instance item to find. |

**Returns:**
boolean - boolean value True - if item find; otherwise, false.
### clear() {#clear--}
```
public abstract void clear()
```


Clears collection.

### getUnrestricted(int index) {#getUnrestricted-int-}
```
public abstract Operator getUnrestricted(int index)
```


For internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | int value |

**Returns:**
[Operator](../../com.aspose.pdf/operator) - Operator object
### updateData() {#updateData--}
```
public abstract void updateData()
```


internal

### deleteUnrestricted(int index) {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```


internal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | int value |

### cancelUpdate() {#cancelUpdate--}
```
public abstract void cancelUpdate()
```


Cancels last update. This method may be called when the change should not raise contents update.

