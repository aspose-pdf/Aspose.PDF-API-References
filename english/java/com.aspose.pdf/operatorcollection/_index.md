---
title: OperatorCollection
second_title: Aspose.PDF for Java API Reference
description: Class represents collection of operators
type: docs
weight: 231
url: /java/com.aspose.pdf/operatorcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseOperatorCollection](../../com.aspose.pdf/baseoperatorcollection)
```
public class OperatorCollection extends BaseOperatorCollection
```

Class represents collection of operators
## Constructors

| Constructor | Description |
| --- | --- |
| [OperatorCollection(IPdfPrimitive contents)](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | For internal usage only! |
## Methods

| Method | Description |
| --- | --- |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [isCommandsParsed()](#isCommandsParsed--) | Gets commands parsed |
| [updateNormalizedData()](#updateNormalizedData--) | Update object stream with fixing absent GSave/GRestore operators. |
| [updateData()](#updateData--) | Update object stream. |
| [size()](#size--) | Gets count of operators in the collection. |
| [precalculateOperatorsCount()](#precalculateOperatorsCount--) | Get amount of operators that describe content for the page without initialisation of them. |
| [isFastTextExtractionMode()](#isFastTextExtractionMode--) | Indicates wheather collection is limited to fast text extraction |
| [iterator()](#iterator--) | Returns enumerator for collection |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts IOperatorSelector visitor object to process operators. |
| [add(Operator op)](#add-com.aspose.pdf.Operator-) | Adds new operator into collection. |
| [delete(int index)](#delete-int-) | Deletes operator from collection. |
| [deleteUnrestricted(int index)](#deleteUnrestricted-int-) | internal unrestricted version of Delete(index) |
| [insert(int index, Operator op)](#insert-int-com.aspose.pdf.Operator-) | Inserts operator into collection. |
| [replace(Iterable<Operator> operators)](#replace-java.lang.Iterable-com.aspose.pdf.Operator--) | Replace operators in collection with other operators. |
| [replace(Operator[] operators)](#replace-com.aspose.pdf.Operator---) | Replace operators in collection with other operators. |
| [add(Operator[] ops)](#add-com.aspose.pdf.Operator---) | Add operators at the end of the contents operators. |
| [insert(int at, Operator[] ops)](#insert-int-com.aspose.pdf.Operator---) | Insert operators at the the given position. |
| [get_Item(int index)](#get-Item-int-) | Gets operator by its index. |
| [set_Item(int index, Operator value)](#set-Item-int-com.aspose.pdf.Operator-) | Sets operator by its index. |
| [getUnrestricted(int index)](#getUnrestricted-int-) | Internal unrestricted version of indexer |
| [delete(Operator[] ops)](#delete-com.aspose.pdf.Operator---) | Deletes operators from collection. |
| [delete(Iterable<Operator> list)](#delete-java.lang.Iterable-com.aspose.pdf.Operator--) | Deletes operators from collection. |
| [insert(int at, Iterable<Operator> ops)](#insert-int-java.lang.Iterable-com.aspose.pdf.Operator--) | Insert operators at the the given position. |
| [clear()](#clear--) | Removes all operators from list. |
| [toString()](#toString--) | Returns text representation of the operator. |
| [add(Iterable<Operator> ops)](#add-java.lang.Iterable-com.aspose.pdf.Operator--) | Adds to collection all operators from other collection. |
| [isBracketed()](#isBracketed--) | Gets bracketed status of operator sequence i.e. is this operators are inside of q - Q blocks |
| [suppressUpdate()](#suppressUpdate--) | Suppresses update contents data The contents stream is not updated until ResumeUpdate is called |
| [resumeUpdate()](#resumeUpdate--) | Resumes document update. |
| [cancelUpdate()](#cancelUpdate--) | Cancels last update. |
| [toList()](#toList--) | Returns operator list. |
| [remove(Operator op)](#remove-com.aspose.pdf.Operator-) | Remove operator from the collection. |
| [contains(Operator op)](#contains-com.aspose.pdf.Operator-) | Returns true if the collection contains given operator. |
### OperatorCollection(IPdfPrimitive contents) {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public OperatorCollection(IPdfPrimitive contents)
```


For internal usage only!

Constructor of OperatorCollection. Constructs operators from primitive contains operators list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contents | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | IPdfPrimitive object |

### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether the collection is read-only.

**Returns:**
boolean - boolean value
### isCommandsParsed() {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```


Gets commands parsed

**Returns:**
boolean - boolean value
### updateNormalizedData() {#updateNormalizedData--}
```
public void updateNormalizedData()
```


Update object stream with fixing absent GSave/GRestore operators.

### updateData() {#updateData--}
```
public void updateData()
```


Update object stream.

### size() {#size--}
```
public int size()
```


Gets count of operators in the collection.

**Returns:**
int - int value
### precalculateOperatorsCount() {#precalculateOperatorsCount--}
```
public int precalculateOperatorsCount()
```


Get amount of operators that describe content for the page without initialisation of them.

**Returns:**
int - int value
### isFastTextExtractionMode() {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```


Indicates wheather collection is limited to fast text extraction

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<Operator> iterator()
```


Returns enumerator for collection

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.Operator> - Collection enumerator
### accept(IOperatorSelector visitor) {#accept-com.aspose.pdf.IOperatorSelector-}
```
public void accept(IOperatorSelector visitor)
```


Accepts IOperatorSelector visitor object to process operators.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visitor | [IOperatorSelector](../../com.aspose.pdf/ioperatorselector) | Visitor object |

### add(Operator op) {#add-com.aspose.pdf.Operator-}
```
public void add(Operator op)
```


Adds new operator into collection.

--------------------

Example demonstrates how to add operators to the end of page.contents.

Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q());

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Operator which must be added |

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Deletes operator from collection.

--------------------

Example demonstrates how to delete operator by its index.

Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3);

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of operator which must be deleted. Operators numbering starts from 1. |

### deleteUnrestricted(int index) {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```


internal unrestricted version of Delete(index)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | int value |

### insert(int index, Operator op) {#insert-int-com.aspose.pdf.Operator-}
```
public void insert(int index, Operator op)
```


Inserts operator into collection.

--------------------

Example demonstrates how to insert operator to the page contents.

Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q());

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index where new operator must be added |
| op | [Operator](../../com.aspose.pdf/operator) | Operator which will be inserted |

### replace(Iterable<Operator> operators) {#replace-java.lang.Iterable-com.aspose.pdf.Operator--}
```
public void replace(Iterable<Operator> operators)
```


Replace operators in collection with other operators.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operators | java.lang.Iterable<com.aspose.pdf.Operator> | Operators list which will replace operators currently contained in the collection. Each operator from the list must have correct index in range [1..N] where N is count of operators in the collection |

### replace(Operator[] operators) {#replace-com.aspose.pdf.Operator---}
```
public void replace(Operator[] operators)
```


Replace operators in collection with other operators.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operators | [Operator\[\]](../../com.aspose.pdf/operator) | Operator[] array which will replace operators currently contained in the collection. Each operator from the list must have correct index in range [1..N] where N is count of operators in the collection |

### add(Operator[] ops) {#add-com.aspose.pdf.Operator---}
```
public void add(Operator[] ops)
```


Add operators at the end of the contents operators.

--------------------

Example demonstrates how to add operator to the end of page contents.

Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] \{ new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() \} );

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ops | [Operator\[\]](../../com.aspose.pdf/operator) | Array of operators to be added. Each operator can have any index (by default -1) because they come to the end of the contents operators i.e. indices are assigned automatically. |

### insert(int at, Operator[] ops) {#insert-int-com.aspose.pdf.Operator---}
```
public void insert(int at, Operator[] ops)
```


Insert operators at the the given position.

--------------------

Example demonstrates how to insert operator to the page contents.

Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] \{ new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() \} );

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| at | int | Index from which operators are being started to insert. |
| ops | [Operator\[\]](../../com.aspose.pdf/operator) | Array of operators to be inserted. Each operator can have any index (by default -1) because their indices adjusted automatically starting from  at . |

### get_Item(int index) {#get-Item-int-}
```
public Operator get_Item(int index)
```


Gets operator by its index.

--------------------

Example demonstrates how to get operator of page contents by index.

```
Document doc = new Document("input.pdf");
 OperatorCollection oc = doc.getPages().get(1).getContents();
 Operator first = oc.get_Item(1);
```

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | int value |
| value | [Operator](../../com.aspose.pdf/operator) | Operator object |

### getUnrestricted(int index) {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```


Internal unrestricted version of indexer

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | int value |

**Returns:**
[Operator](../../com.aspose.pdf/operator) - Operator object
### delete(Operator[] ops) {#delete-com.aspose.pdf.Operator---}
```
public void delete(Operator[] ops)
```


Deletes operators from collection.

--------------------

Example demonstrates how to remove operator from page contents.

Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] \{ oc[1] \} );

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ops | [Operator\[\]](../../com.aspose.pdf/operator) | Array of operators to delete |

### delete(Iterable<Operator> list) {#delete-java.lang.Iterable-com.aspose.pdf.Operator--}
```
public void delete(Iterable<Operator> list)
```


Deletes operators from collection.

--------------------

Example demonstrates how to remove operator from page contents.

Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); ArrayList<Operator> opList = new ArrayList<Operator>(); opList.add(oc[1]); oc.delete(opList);

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| list | java.lang.Iterable<com.aspose.pdf.Operator> | The list of operators to delete |

### insert(int at, Iterable<Operator> ops) {#insert-int-java.lang.Iterable-com.aspose.pdf.Operator--}
```
public void insert(int at, Iterable<Operator> ops)
```


Insert operators at the the given position.

--------------------

Example demonstrates how to insert operators to page contents.

Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); ArrayList<Operator> opList = new List<Operator>(); opList.add(new com.aspose.pdf.operators.q()); opList.add(new com.aspose.pdf.operators.Q()); oc.insert(1, opList);

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| at | int | Index from which operators are being started to insert. |
| ops | java.lang.Iterable<com.aspose.pdf.Operator> | Array of operators to be inserted. |

### clear() {#clear--}
```
public void clear()
```


Removes all operators from list.

--------------------

Example demonstrates how to clear page contents.

Document doc = new Document("input.pdf"); doc.getPages().get(1).clear();

### toString() {#toString--}
```
public String toString()
```


Returns text representation of the operator.

**Returns:**
java.lang.String - Text representation of operator.
### add(Iterable<Operator> ops) {#add-java.lang.Iterable-com.aspose.pdf.Operator--}
```
public void add(Iterable<Operator> ops)
```


Adds to collection all operators from other collection.

--------------------

```
Example demonstrates how to add operator collection to the page contents.

 Document doc = new Document("input.pdf");
 OperatorCollection oc = doc.getPages(1).getContents();
 ArrayList opList = new ArrayList();
 opList.add(new com.aspose.pdf.operators.q());
 opList.add(new com.aspose.pdf.operators.Q());
 oc.add(opList);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ops | java.lang.Iterable<com.aspose.pdf.Operator> | collection which contains operators which will be added. |

### isBracketed() {#isBracketed--}
```
public boolean isBracketed()
```


Gets bracketed status of operator sequence i.e. is this operators are inside of q - Q blocks

**Returns:**
boolean - boolean value
### suppressUpdate() {#suppressUpdate--}
```
public void suppressUpdate()
```


Suppresses update contents data The contents stream is not updated until ResumeUpdate is called

### resumeUpdate() {#resumeUpdate--}
```
public void resumeUpdate()
```


Resumes document update. Updates contents stream in case there are any pending changes.

### cancelUpdate() {#cancelUpdate--}
```
public void cancelUpdate()
```


Cancels last update. This method may be called when the change should not raise contents update.

### toList() {#toList--}
```
public System.Collections.Generic.List<Operator> toList()
```


Returns operator list.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> - operator list.
### remove(Operator op) {#remove-com.aspose.pdf.Operator-}
```
public boolean remove(Operator op)
```


Remove operator from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Operator to be removed. |

**Returns:**
boolean - True if operator was found and removed. False if operator did not belong to the collection.
### contains(Operator op) {#contains-com.aspose.pdf.Operator-}
```
public boolean contains(Operator op)
```


Returns true if the collection contains given operator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | Operator instance |

**Returns:**
boolean - boolean value True - if operator found; otherwise, false.
