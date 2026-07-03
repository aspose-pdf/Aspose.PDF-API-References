---
title: BaseOperatorCollection
second_title: Aspose.PDF for Java API Reference
description: Represents base class for operator collection.
type: docs
weight: 270
url: /java/com.aspose.pdf/baseoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public abstract class BaseOperatorCollection extends Object implements Iterable < Operator >
```

Represents base class for operator collection.

## Constructors

| Constructor | Description |
| --- | --- |
| [BaseOperatorCollection](#BaseOperatorCollection--) |  |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Adds new operator into collection. |
| [cancelUpdate](#cancelUpdate--) | Cancels last update. This method may be called when the change should not raise contents update. |
| [clear](#clear--) | Clears collection. |
| [contains](#contains-com.aspose.pdf.Operator-) | Check if the item is in collection. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | internal |
| [get_Item](#get_Item-int-) | Gets operator by its index. |
| [getUnrestricted](#getUnrestricted-int-) | For internal usage only |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Inserts operator into collection. |
| [isEmpty](#isEmpty--) | Returns TRUE if the collection is empty. |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indicates whether collection is limited to fast text extraction |
| [isReadOnly](#isReadOnly--) | Returns true if collection is read only. |
| [iterator](#iterator--) | Returns enumerator for collection |
| [remove](#remove-com.aspose.pdf.Operator-) | Removes operator from collection. |
| [resumeUpdate](#resumeUpdate--) | Resumes document update. Updates contents stream in case there are any pending changes. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Sets operator by its index. |
| [size](#size--) | Gets count of operators in the collection. |
| [suppressUpdate](#suppressUpdate--) | Suppresses update contents data. The contents stream is not updated until ResumeUpdate is called. |
| [toList](#toList--) | Returns opetator list. |
| [updateData](#updateData--) | internal |

### BaseOperatorCollection {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```



### add {#add-com.aspose.pdf.Operator-}
Adds new operator into collection.

### cancelUpdate {#cancelUpdate--}
```
public abstract void cancelUpdate()
```

Cancels last update. This method may be called when the change should not raise contents update.

### clear {#clear--}
```
public abstract void clear()
```

Clears collection.

### contains {#contains-com.aspose.pdf.Operator-}
Check if the item is in collection.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```

internal

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | int value |

### get_Item {#get_Item-int-}
```
public abstract Operator get_Item(int index)
```

Gets operator by its index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of operator. Numbering is starts from 1. |

**Returns:**
Operator from requested index

### getUnrestricted {#getUnrestricted-int-}
```
public abstract Operator getUnrestricted(int index)
```

For internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | int value |

**Returns:**
Operator object

### insert {#insert-int-com.aspose.pdf.Operator-}
Inserts operator into collection.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Returns TRUE if the collection is empty.

**Returns:**
boolean value

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```

Indicates whether collection is limited to fast text extraction

**Returns:**
boolean value

### isReadOnly {#isReadOnly--}
```
public abstract boolean isReadOnly()
```

Returns true if collection is read only.

**Returns:**
boolean value

### iterator {#iterator--}
```
public abstract Iterator < Operator > iterator()
```

Returns enumerator for collection

**Returns:**
Collection enumerator

### remove {#remove-com.aspose.pdf.Operator-}
Removes operator from collection.

### resumeUpdate {#resumeUpdate--}
```
public abstract void resumeUpdate()
```

Resumes document update. Updates contents stream in case there are any pending changes.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Sets operator by its index.

### size {#size--}
```
public abstract int size()
```

Gets count of operators in the collection.

**Returns:**
integer value

### suppressUpdate {#suppressUpdate--}
```
public abstract void suppressUpdate()
```

Suppresses update contents data. The contents stream is not updated until ResumeUpdate is called.

### toList {#toList--}
```
public abstract com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Returns opetator list.

**Returns:**
opetator list.

### updateData {#updateData--}
```
public abstract void updateData()
```

internal
