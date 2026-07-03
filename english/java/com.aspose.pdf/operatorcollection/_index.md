---
title: OperatorCollection
linktitle: OperatorCollection
second_title: Aspose.PDF for Java API Reference
description: Class represents collection of operators
type: docs
weight: 3190
url: /java/com.aspose.pdf/operatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.OperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.OperatorCollection

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Iterable < Operator >

```
public class OperatorCollection extends BaseOperatorCollection implements com.aspose.ms.System.IDisposable
```

Class represents collection of operators

## Constructors

| Constructor | Description |
| --- | --- |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | For internal usage only! |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-) | For internal usage only! |

## Methods

| Method | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts IOperatorSelector visitor object to process operators. |
| [add](#add-java.lang.Iterable-) | Adds to collection all operators from other collection. |
| [add](#add-com.aspose.pdf.Operator-) | <p> Adds new operator into collection. </p> <hr> <p> Example demonstrates how to add operators to the end of page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p> |
| [add](#add-com.aspose.pdf.Operator:A-) | <p> Add operators at the end of the contents operators. </p> <hr> <p> Example demonstrates how to add operator to the end of page contents. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [cancelUpdate](#cancelUpdate--) | Cancels last update. This method may be called when the change should not raise contents update. |
| [clear](#clear--) | <p> Removes all operators from list. </p> <hr> <p> Example demonstrates how to clear page contents. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p> |
| [close](#close--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [contains](#contains-com.aspose.pdf.Operator-) | Returns true if the collection contains given operator. |
| [delete](#delete-int-) | <p> Deletes operator from collection. </p> <hr> <p> Example demonstrates how to delete operator by its index. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p> |
| [delete](#delete-java.lang.Iterable-) | Deletes operators from collection. |
| [delete](#delete-com.aspose.pdf.Operator:A-) | <p> Deletes operators from collection. </p> <hr> <p> Example demonstrates how to remove operator from page contents. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p> |
| [deleteUnrestricted](#deleteUnrestricted-int-) | internal unrestricted version of Delete(index) |
| [dispose](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [get_Item](#get_Item-int-) | <p> Gets operator by its index. </p> <hr> Example demonstrates how to get operator of page contents by index. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | Internal unrestricted version of indexer |
| [insert](#insert-int-java.lang.Iterable-) | Insert operators at the the given position. |
| [insert](#insert-int-com.aspose.pdf.Operator-) | <p> Inserts operator into collection. </p> <hr> <p> Example demonstrates how to insert operator to the page contents. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p> |
| [insert](#insert-int-com.aspose.pdf.Operator:A-) | <p> Insert operators at the the given position. </p> <hr> <p> Example demonstrates how to insert operator to the page contents. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [isBracketed](#isBracketed--) | Gets bracketed status of operator sequence i.e. is this operators are inside of q - Q blocks |
| [isCommandsParsed](#isCommandsParsed--) | Gets commands parsed |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indicates wheather collection is limited to fast text extraction |
| [isReadOnly](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [iterator](#iterator--) | Returns enumerator for collection |
| [precalculateOperatorsCount](#precalculateOperatorsCount--) | Get amount of operators that describe content for the page without initialisation of them. |
| [remove](#remove-com.aspose.pdf.Operator-) | Remove operator from the collection. |
| [replace](#replace-java.lang.Iterable-) | Replace operators in collection with other operators. |
| [replace](#replace-com.aspose.pdf.Operator:A-) | Replace operators in collection with other operators. |
| [resumeUpdate](#resumeUpdate--) | Resumes document update. Updates contents stream in case there are any pending changes. |
| [resumeUpdate](#resumeUpdate-boolean-) | Resumes document update. Updates contents stream in case there are any pending changes. Marks all operators as "changed" if invalidate parameter is true. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Sets operator by its index. |
| [size](#size--) | Gets count of operators in the collection. |
| [suppressUpdate](#suppressUpdate--) | Suppresses update contents data The contents stream is not updated until ResumeUpdate is called |
| [toList](#toList--) | Returns operator list. |
| [toString](#toString--) | Returns text representation of the operator. |
| [updateData](#updateData--) | Update object stream. |
| [updateNormalizedData](#updateNormalizedData--) | Update object stream with fixing absent GSave/GRestore operators. |

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
For internal usage only!

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-}
For internal usage only!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepts IOperatorSelector visitor object to process operators.

### add {#add-java.lang.Iterable-}
Adds to collection all operators from other collection.

### add {#add-com.aspose.pdf.Operator-}
<p> Adds new operator into collection. </p> <hr> <p> Example demonstrates how to add operators to the end of page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p>

### add {#add-com.aspose.pdf.Operator:A-}
<p> Add operators at the end of the contents operators. </p> <hr> <p> Example demonstrates how to add operator to the end of page contents. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Cancels last update. This method may be called when the change should not raise contents update.

### clear {#clear--}
```
public void clear()
```

<p> Removes all operators from list. </p> <hr> <p> Example demonstrates how to clear page contents. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p>

### close {#close--}
```
public final void close()
```

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### contains {#contains-com.aspose.pdf.Operator-}
Returns true if the collection contains given operator.

### delete {#delete-int-}
```
public void delete(int index)
```

<p> Deletes operator from collection. </p> <hr> <p> Example demonstrates how to delete operator by its index. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of operator which must be deleted. Operators numbering starts from 1. |

### delete {#delete-java.lang.Iterable-}
Deletes operators from collection.

### delete {#delete-com.aspose.pdf.Operator:A-}
<p> Deletes operators from collection. </p> <hr> <p> Example demonstrates how to remove operator from page contents. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p>

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

internal unrestricted version of Delete(index)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | int value |

### dispose {#dispose--}
```
public final void dispose()
```

Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Gets operator by its index. </p> <hr> Example demonstrates how to get operator of page contents by index. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre>

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

Internal unrestricted version of indexer

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | int value |

**Returns:**
Operator object

### insert {#insert-int-java.lang.Iterable-}
Insert operators at the the given position.

### insert {#insert-int-com.aspose.pdf.Operator-}
<p> Inserts operator into collection. </p> <hr> <p> Example demonstrates how to insert operator to the page contents. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p>

### insert {#insert-int-com.aspose.pdf.Operator:A-}
<p> Insert operators at the the given position. </p> <hr> <p> Example demonstrates how to insert operator to the page contents. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### isBracketed {#isBracketed--}
```
public boolean isBracketed()
```

Gets bracketed status of operator sequence i.e. is this operators are inside of q - Q blocks

**Returns:**
boolean value

### isCommandsParsed {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```

Gets commands parsed

**Returns:**
boolean value

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

Indicates wheather collection is limited to fast text extraction

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
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Operator > iterator()
```

Returns enumerator for collection

**Returns:**
Collection enumerator

### precalculateOperatorsCount {#precalculateOperatorsCount--}
```
public int precalculateOperatorsCount()
```

Get amount of operators that describe content for the page without initialisation of them.

**Returns:**
int value

### remove {#remove-com.aspose.pdf.Operator-}
Remove operator from the collection.

### replace {#replace-java.lang.Iterable-}
Replace operators in collection with other operators.

### replace {#replace-com.aspose.pdf.Operator:A-}
Replace operators in collection with other operators.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Resumes document update. Updates contents stream in case there are any pending changes.

### resumeUpdate {#resumeUpdate-boolean-}
```
public final void resumeUpdate(boolean updateAll)
```

Resumes document update. Updates contents stream in case there are any pending changes. Marks all operators as "changed" if invalidate parameter is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| updateAll |  | If true, all operators in the collection marked as updated. |

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Sets operator by its index.

### size {#size--}
```
public int size()
```

Gets count of operators in the collection.

**Returns:**
int value

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Suppresses update contents data The contents stream is not updated until ResumeUpdate is called

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Returns operator list.

**Returns:**
operator list.

### toString {#toString--}
```
public String toString()
```

Returns text representation of the operator.

**Returns:**
Text representation of operator.

### updateData {#updateData--}
```
public void updateData()
```

Update object stream.

### updateNormalizedData {#updateNormalizedData--}
```
public void updateNormalizedData()
```

Update object stream with fixing absent GSave/GRestore operators.
