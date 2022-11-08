---
title: OperatorCollection
second_title: Aspose.PDF for Java API Reference
description: Class represents collection of operators
type: docs
weight: 233
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
| [accept(IOperatorSelector visitor)](#accept-com.aspose.pdf.IOperatorSelector-) | Accepts IOperatorSelector visitor object to process operators. |
| [add(Operator op)](#add-com.aspose.pdf.Operator-) | Adds new operator into collection. |
| [add(Operator[] ops)](#add-com.aspose.pdf.Operator---) | Add operators at the end of the contents operators. |
| [add(Iterable<Operator> ops)](#add-java.lang.Iterable-com.aspose.pdf.Operator--) | Adds to collection all operators from other collection. |
| [cancelUpdate()](#cancelUpdate--) | Cancels last update. |
| [clear()](#clear--) | Removes all operators from list. |
| [contains(Operator op)](#contains-com.aspose.pdf.Operator-) | Returns true if the collection contains given operator. |
| [delete(Operator[] ops)](#delete-com.aspose.pdf.Operator---) | Deletes operators from collection. |
| [delete(int index)](#delete-int-) | Deletes operator from collection. |
| [delete(Iterable<Operator> list)](#delete-java.lang.Iterable-com.aspose.pdf.Operator--) | Deletes operators from collection. |
| [deleteUnrestricted(int index)](#deleteUnrestricted-int-) | internal unrestricted version of Delete(index) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getUnrestricted(int index)](#getUnrestricted-int-) | Internal unrestricted version of indexer |
| [get_Item(int index)](#get-Item-int-) | Gets operator by its index. |
| [hashCode()](#hashCode--) |  |
| [insert(int index, Operator op)](#insert-int-com.aspose.pdf.Operator-) | Inserts operator into collection. |
| [insert(int at, Operator[] ops)](#insert-int-com.aspose.pdf.Operator---) | Insert operators at the the given position. |
| [insert(int at, Iterable<Operator> ops)](#insert-int-java.lang.Iterable-com.aspose.pdf.Operator--) | Insert operators at the the given position. |
| [isBracketed()](#isBracketed--) | Gets bracketed status of operator sequence i.e. is this operators are inside of q - Q blocks |
| [isCommandsParsed()](#isCommandsParsed--) | Gets commands parsed |
| [isEmpty()](#isEmpty--) | Returns TRUE if the collection is empty. |
| [isFastTextExtractionMode()](#isFastTextExtractionMode--) | Indicates wheather collection is limited to fast text extraction |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [iterator()](#iterator--) | Returns enumerator for collection |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(Operator op)](#remove-com.aspose.pdf.Operator-) | Remove operator from the collection. |
| [replace(Operator[] operators)](#replace-com.aspose.pdf.Operator---) | Replace operators in collection with other operators. |
| [replace(Iterable<Operator> operators)](#replace-java.lang.Iterable-com.aspose.pdf.Operator--) | Replace operators in collection with other operators. |
| [resumeUpdate()](#resumeUpdate--) | Resumes document update. |
| [set_Item(int index, Operator value)](#set-Item-int-com.aspose.pdf.Operator-) | Sets operator by its index. |
| [size()](#size--) | Gets count of operators in the collection. |
| [suppressUpdate()](#suppressUpdate--) | Suppresses update contents data The contents stream is not updated until ResumeUpdate is called |
| [toList()](#toList--) | Returns operator list. |
| [toString()](#toString--) | Returns text representation of the operator. |
| [updateData()](#updateData--) | Update object stream. |
| [updateNormalizedData()](#updateNormalizedData--) | Update object stream with fixing absent GSave/GRestore operators. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### cancelUpdate() {#cancelUpdate--}
```
public void cancelUpdate()
```


Cancels last update. This method may be called when the change should not raise contents update.

### clear() {#clear--}
```
public void clear()
```


Removes all operators from list.

--------------------

Example demonstrates how to clear page contents.

Document doc = new Document("input.pdf"); doc.getPages().get(1).clear();

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

### deleteUnrestricted(int index) {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```


internal unrestricted version of Delete(index)

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


Internal unrestricted version of indexer

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


Inserts operator into collection.

--------------------

Example demonstrates how to insert operator to the page contents.

Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q());

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index where new operator must be added |
| op | [Operator](../../com.aspose.pdf/operator) | Operator which will be inserted |

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

### isBracketed() {#isBracketed--}
```
public boolean isBracketed()
```


Gets bracketed status of operator sequence i.e. is this operators are inside of q - Q blocks

**Returns:**
boolean - boolean value
### isCommandsParsed() {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```


Gets commands parsed

**Returns:**
boolean - boolean value
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


Indicates wheather collection is limited to fast text extraction

**Returns:**
boolean - boolean value
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether the collection is read-only.

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<Operator> iterator()
```


Returns enumerator for collection

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.Operator> - Collection enumerator
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
### replace(Operator[] operators) {#replace-com.aspose.pdf.Operator---}
```
public void replace(Operator[] operators)
```


Replace operators in collection with other operators.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operators | [Operator\[\]](../../com.aspose.pdf/operator) | Operator[] array which will replace operators currently contained in the collection. Each operator from the list must have correct index in range [1..N] where N is count of operators in the collection |

### replace(Iterable<Operator> operators) {#replace-java.lang.Iterable-com.aspose.pdf.Operator--}
```
public void replace(Iterable<Operator> operators)
```


Replace operators in collection with other operators.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operators | java.lang.Iterable<com.aspose.pdf.Operator> | Operators list which will replace operators currently contained in the collection. Each operator from the list must have correct index in range [1..N] where N is count of operators in the collection |

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | int value |
| value | [Operator](../../com.aspose.pdf/operator) | Operator object |

### size() {#size--}
```
public int size()
```


Gets count of operators in the collection.

**Returns:**
int - int value
### suppressUpdate() {#suppressUpdate--}
```
public void suppressUpdate()
```


Suppresses update contents data The contents stream is not updated until ResumeUpdate is called

### toList() {#toList--}
```
public System.Collections.Generic.List<Operator> toList()
```


Returns operator list.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator> - operator list.
### toString() {#toString--}
```
public String toString()
```


Returns text representation of the operator.

**Returns:**
java.lang.String - Text representation of operator.
### updateData() {#updateData--}
```
public void updateData()
```


Update object stream.

### updateNormalizedData() {#updateNormalizedData--}
```
public void updateNormalizedData()
```


Update object stream with fixing absent GSave/GRestore operators.

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

