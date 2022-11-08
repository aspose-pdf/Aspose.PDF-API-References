---
title: BaseOperatorCollection
second_title: Aspose.PDF for Java API Reference
description: Represents base class for operator collection.
type: docs
weight: 33
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
| [add(Operator op)](#add-com.aspose.pdf.Operator-) | Adds new operator into collection. |
| [cancelUpdate()](#cancelUpdate--) | Cancels last update. |
| [clear()](#clear--) | Clears collection. |
| [contains(Operator item)](#contains-com.aspose.pdf.Operator-) | Check if the item is in collection. |
| [deleteUnrestricted(int index)](#deleteUnrestricted-int-) | internal |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getUnrestricted(int index)](#getUnrestricted-int-) | For internal usage only |
| [get_Item(int index)](#get-Item-int-) | Gets operator by its index. |
| [hashCode()](#hashCode--) |  |
| [insert(int index, Operator op)](#insert-int-com.aspose.pdf.Operator-) | Inserts operator into collection. |
| [isEmpty()](#isEmpty--) | Returns TRUE if the collection is empty. |
| [isFastTextExtractionMode()](#isFastTextExtractionMode--) | Indicates whether collection is limited to fast text extraction |
| [isReadOnly()](#isReadOnly--) | Returns true if collection is read only. |
| [iterator()](#iterator--) | Returns enumerator for collection |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Operator item)](#remove-com.aspose.pdf.Operator-) | Removes operator from collection. |
| [resumeUpdate()](#resumeUpdate--) | Resumes document update. |
| [set_Item(int index, Operator value)](#set-Item-int-com.aspose.pdf.Operator-) | Sets operator by its index. |
| [size()](#size--) | Gets count of operators in the collection. |
| [suppressUpdate()](#suppressUpdate--) | Suppresses update contents data. |
| [toList()](#toList--) | Returns opetator list. |
| [toString()](#toString--) |  |
| [updateData()](#updateData--) | internal |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseOperatorCollection() {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```


### add(Operator op) {#add-com.aspose.pdf.Operator-}
```
public abstract void add(Operator op)
```


Adds new operator into collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Operator which must be added |

### cancelUpdate() {#cancelUpdate--}
```
public abstract void cancelUpdate()
```


Cancels last update. This method may be called when the change should not raise contents update.

### clear() {#clear--}
```
public abstract void clear()
```


Clears collection.

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
### deleteUnrestricted(int index) {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```


internal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | int value |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Returns TRUE if the collection is empty.

**Returns:**
boolean - boolean value
### isFastTextExtractionMode() {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```


Indicates whether collection is limited to fast text extraction

**Returns:**
boolean - boolean value
### isReadOnly() {#isReadOnly--}
```
public abstract boolean isReadOnly()
```


Returns true if collection is read only.

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public abstract Iterator<Operator> iterator()
```


Returns enumerator for collection

**Returns:**
java.util.Iterator<com.aspose.pdf.Operator> - Collection enumerator
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
### resumeUpdate() {#resumeUpdate--}
```
public abstract void resumeUpdate()
```


Resumes document update. Updates contents stream in case there are any pending changes.

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

### size() {#size--}
```
public abstract int size()
```


Gets count of operators in the collection.

**Returns:**
int - integer value
### suppressUpdate() {#suppressUpdate--}
```
public abstract void suppressUpdate()
```


Suppresses update contents data. The contents stream is not updated until ResumeUpdate is called.

### toList() {#toList--}
```
public abstract System.Collections.Generic.List<Operator> toList()
```


Returns opetator list.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> - opetator list.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateData() {#updateData--}
```
public abstract void updateData()
```


internal

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

