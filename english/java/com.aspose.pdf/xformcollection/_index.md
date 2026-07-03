---
title: XFormCollection
second_title: Aspose.PDF for Java API Reference
description: Class represents collection of XFormCollection.
type: docs
weight: 5600
url: /java/com.aspose.pdf/xformcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFormCollection

**All Implemented Interfaces:**
Iterable < XForm >

```
public final class XFormCollection extends Object implements Iterable < XForm >
```

Class represents collection of XFormCollection.

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.XForm-) | Adds new XForm into collection. |
| [clear](#clear--) | Clears all items from the collection. |
| [contains](#contains-com.aspose.pdf.XForm-) | Determines whether the collection contains a specific value. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | Copies XFormCollection into collection. |
| [delete](#delete--) | Deletes all XForms from collection. |
| [delete](#delete-int-) | Delete XForm from collectin |
| [delete](#delete-java.lang.String-) | Deletes all XForms from collection. |
| [freeMemory](#freeMemory--) | Clears cached data, frees memory etc. |
| [get_Item](#get_Item-int-) | Returns XForm by index. |
| [get_Item](#get_Item-java.lang.String-) | Returns XForm by its name. Exception is thrown if XForm with specified name is not found. |
| [getFormName](#getFormName-com.aspose.pdf.XForm-) | Returns name of the form in this form collection |
| [getSyncRoot](#getSyncRoot--) | Synchronization object. |
| [hasForm](#hasForm-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [isSynchronized](#isSynchronized--) | Returns true if object is synchronized. |
| [iterator](#iterator--) | Returns collection enumerator. |
| [remove](#remove-com.aspose.pdf.XForm-) | Deletes specified item from collection. |
| [size](#size--) | Gets count of XForms in collection. |

### add {#add-com.aspose.pdf.XForm-}
Adds new XForm into collection.

### clear {#clear--}
```
public void clear()
```

Clears all items from the collection.

### contains {#contains-com.aspose.pdf.XForm-}
Determines whether the collection contains a specific value.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
Copies XFormCollection into collection.

### delete {#delete--}
```
public void delete()
```

Deletes all XForms from collection.

### delete {#delete-int-}
```
public void delete(int index)
```

Delete XForm from collectin

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of XForm which must be deleted |

### delete {#delete-java.lang.String-}
Deletes all XForms from collection.

### freeMemory {#freeMemory--}
```
public final void freeMemory()
```

Clears cached data, frees memory etc.

### get_Item {#get_Item-int-}
```
public XForm get_Item(int index)
```

Returns XForm by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of XFormCollection. XForms numbering is started from 1 |

**Returns:**
Retrieved XForm

### get_Item {#get_Item-java.lang.String-}
Returns XForm by its name. Exception is thrown if XForm with specified name is not found.

### getFormName {#getFormName-com.aspose.pdf.XForm-}
Returns name of the form in this form collection

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Synchronization object.

**Returns:**
Object

### hasForm {#hasForm-java.lang.String-}


### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gets a value indicating whether the collection is read-only.

**Returns:**
boolean value

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Returns true if object is synchronized.

**Returns:**
boolean

### iterator {#iterator--}
```
public Iterator < XForm > iterator()
```

Returns collection enumerator.

**Returns:**
Enumerator for collection

### remove {#remove-com.aspose.pdf.XForm-}
Deletes specified item from collection.

### size {#size--}
```
public int size()
```

Gets count of XForms in collection.

**Returns:**
int value
