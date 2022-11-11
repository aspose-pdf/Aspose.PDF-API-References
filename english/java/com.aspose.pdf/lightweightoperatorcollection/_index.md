---
title: LightweightOperatorCollection
second_title: Aspose.PDF for Java API Reference
description: Lightweight operator collection.
type: docs
weight: 194
url: /java/com.aspose.pdf/lightweightoperatorcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseOperatorCollection](../../com.aspose.pdf/baseoperatorcollection)
```
public class LightweightOperatorCollection extends BaseOperatorCollection
```

Lightweight operator collection. Intended to be used in scenarios when underlying contents stream is not attached, where just operator collection is required as a result.
## Constructors

| Constructor | Description |
| --- | --- |
| [LightweightOperatorCollection()](#LightweightOperatorCollection--) | Initialize object |
| [LightweightOperatorCollection(ITrailerable trailerable, System.Collections.Generic.List<Operator> operators)](#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--) | For internal usage only! |
| [LightweightOperatorCollection(OperatorCollection operatorCollection)](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | Initialize object |
## Methods

| Method | Description |
| --- | --- |
| [add(Operator op)](#add-com.aspose.pdf.Operator-) | Add operator |
| [addRange(LightweightOperatorCollection oc)](#addRange-com.aspose.pdf.LightweightOperatorCollection-) | Add LightweightOperatorCollection |
| [cancelUpdate()](#cancelUpdate--) | Cancels last update. |
| [clear()](#clear--) |  |
| [contains(Operator item)](#contains-com.aspose.pdf.Operator-) |  |
| [deleteUnrestricted(int index)](#deleteUnrestricted-int-) | internal delete Unrestrictedelement |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getUnrestricted(int index)](#getUnrestricted-int-) | For internal usage getUnrestricted operator |
| [get_Item(int index)](#get-Item-int-) | Gets operator by its index. |
| [hashCode()](#hashCode--) |  |
| [insert(int index, Operator op)](#insert-int-com.aspose.pdf.Operator-) | Insert operator |
| [isEmpty()](#isEmpty--) | Returns TRUE if the collection is empty. |
| [isFastTextExtractionMode()](#isFastTextExtractionMode--) | Indicates whether collection is limited to fast text extraction |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [iterator()](#iterator--) | Return iterator |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Operator item)](#remove-com.aspose.pdf.Operator-) |  |
| [resumeUpdate()](#resumeUpdate--) | Resumes document update. |
| [set_Item(int index, Operator value)](#set-Item-int-com.aspose.pdf.Operator-) | Sets operator by its index. |
| [size()](#size--) | Operators count |
| [suppressUpdate()](#suppressUpdate--) | Suppresses update contents data. |
| [toList()](#toList--) | Returns operators list. |
| [toString()](#toString--) |  |
| [updateData()](#updateData--) | internal |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LightweightOperatorCollection() {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```


Initialize object

### LightweightOperatorCollection(ITrailerable trailerable, System.Collections.Generic.List<Operator> operators) {#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.Operator--}
```
public LightweightOperatorCollection(ITrailerable trailerable, System.Collections.Generic.List<Operator> operators)
```


For internal usage only!

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) | Internal object |
| operators | com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> | Internal object |

### LightweightOperatorCollection(OperatorCollection operatorCollection) {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
```
public LightweightOperatorCollection(OperatorCollection operatorCollection)
```


Initialize object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorCollection | [OperatorCollection](../../com.aspose.pdf/operatorcollection) | OperatorCollection object |

### add(Operator op) {#add-com.aspose.pdf.Operator-}
```
public void add(Operator op)
```


Add operator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Operator object |

### addRange(LightweightOperatorCollection oc) {#addRange-com.aspose.pdf.LightweightOperatorCollection-}
```
public void addRange(LightweightOperatorCollection oc)
```


Add LightweightOperatorCollection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oc | [LightweightOperatorCollection](../../com.aspose.pdf/lightweightoperatorcollection) | LightweightOperatorCollection instance |

### cancelUpdate() {#cancelUpdate--}
```
public void cancelUpdate()
```


Cancels last update. This method may be called when the change should not raise contents update.

### clear() {#clear--}
```
public void clear()
```


Clears collection.

### contains(Operator item) {#contains-com.aspose.pdf.Operator-}
```
public boolean contains(Operator item)
```


Check if the item is in collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [Operator](../../com.aspose.pdf/operator) | Operator instance |

**Returns:**
boolean - boolean value
### deleteUnrestricted(int index) {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```


internal delete Unrestrictedelement

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
public Operator getUnrestricted(int index)
```


For internal usage getUnrestricted operator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | int value |

**Returns:**
[Operator](../../com.aspose.pdf/operator) - Operator object
### get_Item(int index) {#get-Item-int-}
```
public Operator get_Item(int index)
```


Gets operator by its index.

--------------------

```
Example demonstrates how to get operator of page contents by index.


 Document doc = new Document("input.pdf");
 OperatorCollection oc = doc.getPages().get_Item(1).getContents();
 Operator first = oc.get_Item(1);
```

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
public void insert(int index, Operator op)
```


Insert operator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | int value |
| op | [Operator](../../com.aspose.pdf/operator) | Operator object |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Returns TRUE if the collection is empty.

**Returns:**
boolean - boolean value
### isFastTextExtractionMode() {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```


Indicates whether collection is limited to fast text extraction

**Returns:**
boolean - boolean value
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether the collection is read-only.

**Returns:**
boolean
### iterator() {#iterator--}
```
public Iterator<Operator> iterator()
```


Return iterator

**Returns:**
java.util.Iterator<com.aspose.pdf.Operator> -  IGenericEnumerator  object
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
public boolean remove(Operator item)
```


Removes operator from collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [Operator](../../com.aspose.pdf/operator) | Operator instance |

**Returns:**
boolean - boolean value
### resumeUpdate() {#resumeUpdate--}
```
public void resumeUpdate()
```


Resumes document update. Updates contents stream in case there are any pending changes.

### set_Item(int index, Operator value) {#set-Item-int-com.aspose.pdf.Operator-}
```
public void set_Item(int index, Operator value)
```


Sets operator by its index.

--------------------

```
Example demonstrates how to get operator of page contents by index.


 Document doc = new Document("input.pdf");
 OperatorCollection oc = doc.getPages().get_Item(1).getContents();
 Operator first = oc.get_Item(1);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator. Numbering is starts from 1. |
| value | [Operator](../../com.aspose.pdf/operator) | Operator from requested index |

### size() {#size--}
```
public int size()
```


Operators count

**Returns:**
int - int value
### suppressUpdate() {#suppressUpdate--}
```
public void suppressUpdate()
```


Suppresses update contents data. The contents stream is not updated until ResumeUpdate is called.

### toList() {#toList--}
```
public System.Collections.Generic.List<Operator> toList()
```


Returns operators list.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> - operators list.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateData() {#updateData--}
```
public void updateData()
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

