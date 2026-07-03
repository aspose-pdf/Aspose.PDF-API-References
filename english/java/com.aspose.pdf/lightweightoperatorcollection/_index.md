---
title: LightweightOperatorCollection
second_title: Aspose.PDF for Java API Reference
description: Lightweight operator collection. Intended to be used in scenarios when underlying contents stream is not attached, where just operator collection is required as a result.
type: docs
weight: 2700
url: /java/com.aspose.pdf/lightweightoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.LightweightOperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.LightweightOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public class LightweightOperatorCollection extends BaseOperatorCollection
```

Lightweight operator collection. Intended to be used in scenarios when underlying contents stream is not attached, where just operator collection is required as a result.

## Constructors

| Constructor | Description |
| --- | --- |
| [LightweightOperatorCollection](#LightweightOperatorCollection--) | Initialize object |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-) | Initialize object |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | Initialize object |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Add operator |
| [addRange](#addRange-com.aspose.pdf.LightweightOperatorCollection-) | Add LightweightOperatorCollection |
| [cancelUpdate](#cancelUpdate--) | Cancels last update. This method may be called when the change should not raise contents update. |
| [clear](#clear--) | Clears collection. |
| [contains](#contains-com.aspose.pdf.Operator-) | Check if the item is in collection. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | internal delete Unrestrictedelement |
| [get_Item](#get_Item-int-) | <p> Gets operator by its index. </p> <hr> <pre> Example demonstrates how to get operator of page contents by index. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | For internal usage getUnrestricted operator |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Insert operator |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indicates whether collection is limited to fast text extraction |
| [isReadOnly](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [iterator](#iterator--) | Return iterator |
| [remove](#remove-com.aspose.pdf.Operator-) | Removes operator from collection. |
| [resumeUpdate](#resumeUpdate--) | Resumes document update. Updates contents stream in case there are any pending changes. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Sets operator by its index. <hr> <pre> Example demonstrates how to get operator of page contents by index. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [size](#size--) | Operators count |
| [suppressUpdate](#suppressUpdate--) | Suppresses update contents data. The contents stream is not updated until ResumeUpdate is called. |
| [toList](#toList--) | Returns operators list. |
| [updateData](#updateData--) | internal |

### LightweightOperatorCollection {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```

Initialize object

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-}
Initialize object

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
Initialize object

### add {#add-com.aspose.pdf.Operator-}
Add operator

### addRange {#addRange-com.aspose.pdf.LightweightOperatorCollection-}
Add LightweightOperatorCollection

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Cancels last update. This method may be called when the change should not raise contents update.

### clear {#clear--}
```
public void clear()
```

Clears collection.

### contains {#contains-com.aspose.pdf.Operator-}
Check if the item is in collection.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

internal delete Unrestrictedelement

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | int value |

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Gets operator by its index. </p> <hr> <pre> Example demonstrates how to get operator of page contents by index. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of operator. Numbering is starts from 1. |

**Returns:**
Operator from requested index

### getUnrestricted {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```

For internal usage getUnrestricted operator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | int value |

**Returns:**
Operator object

### insert {#insert-int-com.aspose.pdf.Operator-}
Insert operator

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

Indicates whether collection is limited to fast text extraction

**Returns:**
boolean value

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gets a value indicating whether the collection is read-only.

**Returns:**
boolean value

### iterator {#iterator--}
```
public Iterator < Operator > iterator()
```

Return iterator

**Returns:**
{@code IGenericEnumerator<Operator>} object

### remove {#remove-com.aspose.pdf.Operator-}
Removes operator from collection.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Resumes document update. Updates contents stream in case there are any pending changes.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Sets operator by its index. <hr> <pre> Example demonstrates how to get operator of page contents by index. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

### size {#size--}
```
public int size()
```

Operators count

**Returns:**
int value

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Suppresses update contents data. The contents stream is not updated until ResumeUpdate is called.

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Returns operators list.

**Returns:**
operators list.

### updateData {#updateData--}
```
public void updateData()
```

internal
