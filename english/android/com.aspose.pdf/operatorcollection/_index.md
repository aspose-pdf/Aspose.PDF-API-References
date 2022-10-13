---
title: OperatorCollection
second_title: Aspose.PDF for Java API Reference
description: Class represents collection of operators
type: docs
weight: 187
url: /java/com.aspose.pdf/operatorcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseOperatorCollection](../../com.aspose.pdf/baseoperatorcollection)
```
public final class OperatorCollection extends BaseOperatorCollection
```

Class represents collection of operators
## Constructors

| Constructor | Description |
| --- | --- |
| [OperatorCollection(IPdfPrimitive contents)](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | Constructor of OperatorCollection. |
| [OperatorCollection(ITrailerable trailerable, IPdfPrimitive contents)](#OperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.engine.data.IPdfPrimitive-) | Constructor of OperatorCollection. |
## Methods

| Method | Description |
| --- | --- |
| [isCommandsParsed()](#isCommandsParsed--) | Gets commands parsed |
| [setData(IPdfPrimitive data)](#setData-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
| [updateData()](#updateData--) | Update object stream. |
| [size()](#size--) | Gets count of operators in the collection. |
| [isSynchronized()](#isSynchronized--) | Returns true if object is synchronized. |
| [isFastTextExtractionMode()](#isFastTextExtractionMode--) | Indicates wheather collection is limited to fast text extraction |
| [getSyncRoot()](#getSyncRoot--) | Gets synchronization object. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies operators into operators list. |
| [iterator()](#iterator--) | Returns enumerator for collection |
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts IOperatorSelector visitor object to process operators. |
| [add(Operator op)](#add-com.aspose.pdf.Operator-) | Adds new operator into collection. |
| [delete(int index)](#delete-int-) | Deletes operator from collection. |
| [deleteUnrestricted(int index)](#deleteUnrestricted-int-) | internal unrestricted version of Delete(index) |
| [insert(int index, Operator op)](#insert-int-com.aspose.pdf.Operator-) | Inserts operator into collection. |
| [replace(Iterable operators)](#replace-java.lang.Iterable-) | Replace operators in collection with other operators. |
| [replace(Operator[] operators)](#replace-com.aspose.pdf.Operator---) |  |
| [add(Operator[] ops)](#add-com.aspose.pdf.Operator---) | Add operators at the end of the contents operators. |
| [insert(int at, Operator[] ops)](#insert-int-com.aspose.pdf.Operator---) | Insert operators at the the given position. |
| [get_Item(int index)](#get-Item-int-) | Gets operator by its index. |
| [set_Item(int index, Operator value)](#set-Item-int-com.aspose.pdf.Operator-) |  |
| [getUnrestricted(int index)](#getUnrestricted-int-) | Internal unrestricted version of indexer |
| [delete(Operator[] ops)](#delete-com.aspose.pdf.Operator---) | Deletes operators from collection. |
| [delete(Iterable list)](#delete-java.lang.Iterable-) | Deletes operators from collection. |
| [insert(int at, Iterable ops)](#insert-int-java.lang.Iterable-) | Insert operators at the the given position. |
| [clear()](#clear--) | Removes all operators from list. |
| [toString()](#toString--) | Returns text representation of the operator. |
| [add(Iterable ops)](#add-java.lang.Iterable-) | Adds to collection all operators from other collection. |
| [isBracketed()](#isBracketed--) | Gets bracketed status of operator sequence i.e. is this operators are inside of q - Q blocks |
| [suppressUpdate()](#suppressUpdate--) | Suppresses update contents data The contents stream is not updated until ResumeUpdate is called |
| [resumeUpdate()](#resumeUpdate--) | Resumes document update. |
| [cancelUpdate()](#cancelUpdate--) | Cancels last update. |
| [toList()](#toList--) | Returns operator list. |
### OperatorCollection(IPdfPrimitive contents) {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public OperatorCollection(IPdfPrimitive contents)
```


Constructor of OperatorCollection. Constructs operators from primitive contains operators list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contents | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |

### OperatorCollection(ITrailerable trailerable, IPdfPrimitive contents) {#OperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public OperatorCollection(ITrailerable trailerable, IPdfPrimitive contents)
```


Constructor of OperatorCollection. Constructs operators from primitive contains operators list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| trailerable | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) |  |
| contents | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |

### isCommandsParsed() {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```


Gets commands parsed

**Returns:**
boolean - boolean value
### setData(IPdfPrimitive data) {#setData-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public void setData(IPdfPrimitive data)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |

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
int
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Returns true if object is synchronized.

**Returns:**
boolean
### isFastTextExtractionMode() {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```


Indicates wheather collection is limited to fast text extraction

**Returns:**
boolean - boolean value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets synchronization object.

**Returns:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array array, int index)
```


Copies operators into operators list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array with operators which must to be copied. This array must be Object[] or Operator[]. |
| index | int | Starting index from which operators will be copied |

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

> ```
> Example demonstrates how to add operators to the end of page.contents.
>  
>  Document doc = new Document("input.pdf");
>  doc.getPages().get(1).getContents().add(new Operator.q());
>  doc.getPages().get(1).getContents().add(new Operator.Q());
> ```

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

> ```
> Example demonstrates how to delete operator by its index.
>  
>  Document doc = new Document("input.pdf");
>  OperatorCollection oc = doc.getPages(1).getContents();
>  oc.delete(3);
> ```

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
| index | int |  |

### insert(int index, Operator op) {#insert-int-com.aspose.pdf.Operator-}
```
public void insert(int index, Operator op)
```


Inserts operator into collection.

--------------------

> ```
> Example demonstrates how to insert operator to the page contents.
>  
>  Document doc = new Document("input.pdf");
>  OperatorCollection oc = doc.getPages(1).getContents();
>  oc.insert(1, new Operator.q());
>  oc.add(new Operator.Q());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index where new operator must be added |
| op | [Operator](../../com.aspose.pdf/operator) | Operator which will be insterted |

### replace(Iterable operators) {#replace-java.lang.Iterable-}
```
public void replace(Iterable operators)
```


Replace operators in collection with other operators.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operators | java.lang.Iterable | Operators list which will replace operators currently contained in the collection. Eash operator from the list must have correct index in range [1..N] where N is count of operators in the collection |

### replace(Operator[] operators) {#replace-com.aspose.pdf.Operator---}
```
public void replace(Operator[] operators)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operators | [Operator\[\]](../../com.aspose.pdf/operator) |  |

### add(Operator[] ops) {#add-com.aspose.pdf.Operator---}
```
public void add(Operator[] ops)
```


Add operators at the end of the contents operators.

--------------------

> ```
> Example demonstrates how to add  operator to the end of page contents.
>  
>  Document doc = new Document("input.pdf");
>  OperatorCollection oc = doc.getPages().get(1).getContents();
>  oc.add(new Operator[] { new Operator.q(), new Operator.Q() } );
> ```

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

> ```
> Example demonstrates how to insert operator to the page contents.
>  
>  Document doc = new Document("input.pdf");
>  OperatorCollection oc = doc.getPages().get(1).getContents();
>  oc.insert(1, new Operator[] { new Operator.q(), new Operator.Q() } );
> ```

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

> ```
> Example demonstrates how to get operator of page contents by index.
>  
>  Document doc = new Document("input.pdf");
>  OperatorCollection oc = doc.getPages().get(1).getContents();
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| value | [Operator](../../com.aspose.pdf/operator) |  |

### getUnrestricted(int index) {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```


Internal unrestricted version of indexer

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[Operator](../../com.aspose.pdf/operator) - 
### delete(Operator[] ops) {#delete-com.aspose.pdf.Operator---}
```
public void delete(Operator[] ops)
```


Deletes operators from collection.

--------------------

> ```
> Example demonstrates how to remove operator from page contents.
>  
>  Document doc = new Document("input.pdf");
>  OperatorCollection oc = doc.getPages().get(1).getContents();
>  oc.delete(new Operator[] { oc[1] } );
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ops | [Operator\[\]](../../com.aspose.pdf/operator) | Array of operators to delete |

### delete(Iterable list) {#delete-java.lang.Iterable-}
```
public void delete(Iterable list)
```


Deletes operators from collection.

--------------------

> ```
> Example demonstrates how to remove operator from page contents.
>  
>  Document doc = new Document("input.pdf");
>  OperatorCollection oc = doc.getPages().get(1).getContents();
>  ArrayList opList = new ArrayList();
>  opList.add(oc[1]);
>  oc.delete(opList);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| list | java.lang.Iterable | The list of operators to delete |

### insert(int at, Iterable ops) {#insert-int-java.lang.Iterable-}
```
public void insert(int at, Iterable ops)
```


Insert operators at the the given position.

--------------------

> ```
> Example demonstrates how to insert operators to page contents.
>  
>  Document doc = new Document("input.pdf");
>  OperatorCollection oc = doc.getPages().get(1).getContents();
>  ArrayList opList = new ArrayList();
>  opList.add(new Operator.q());
>  opList.add(new Operator.Q());
>  oc.insert(1, opList);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| at | int | Index from which operators are being started to insert. |
| ops | java.lang.Iterable | Array of operators to be inserted. |

### clear() {#clear--}
```
public void clear()
```


Removes all operators from list.

--------------------

> ```
> Example demonstrates how to clear page contents.
>  
>  Document doc = new Document("input.pdf");
>  doc.getPages().get(1).clear();
> ```

### toString() {#toString--}
```
public String toString()
```


Returns text representation of the operator.

**Returns:**
java.lang.String - Text representation of operator.
### add(Iterable ops) {#add-java.lang.Iterable-}
```
public void add(Iterable ops)
```


Adds to collection all operators from other collection.

--------------------

> ```
> Example demonstrates how to add operator collection to the page contents.
>  
>  Document doc = new Document("input.pdf");
>  OperatorCollection oc = doc.getPages(1).getContents();
>  ArrayList opList = new ArrayList();
>  opList.add(new Operator.q());
>  opList.add(new Operator.Q());
>  oc.add(opList);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ops | java.lang.Iterable | collection whitch contains operators which will be added. |

### isBracketed() {#isBracketed--}
```
public boolean isBracketed()
```


Gets bracketed status of operator sequence i.e. is this operators are inside of q - Q blocks

**Returns:**
boolean
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
