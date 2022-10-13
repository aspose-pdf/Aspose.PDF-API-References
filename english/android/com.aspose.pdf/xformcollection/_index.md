---
title: XFormCollection
second_title: Aspose.PDF for Java API Reference
description: Class represents collection of XFormCollection.
type: docs
weight: 324
url: /java/com.aspose.pdf/xformcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.ICollection
```
public final class XFormCollection implements System.Collections.ICollection
```

Class represents collection of XFormCollection.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Gets count of XForms in collection. |
| [isSynchronized()](#isSynchronized--) | Returns true if object is synchronized. |
| [getSyncRoot()](#getSyncRoot--) | Synchronization object. |
| [add(XForm xform)](#add-com.aspose.pdf.XForm-) | Adds new XForm into collection. |
| [delete(int index)](#delete-int-) | Delete XForm from collectin |
| [delete()](#delete--) | Deletes all XForms from collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies XFormCollection into collection. |
| [iterator()](#iterator--) | Retunrs collection enumerator. |
| [delete(String name)](#delete-java.lang.String-) | Deletes XForm from collection by form name. |
| [get_Item(int index)](#get-Item-int-) | Returns XForm by index. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returns XForm by its name. |
| [getFormName(XForm form)](#getFormName-com.aspose.pdf.XForm-) | Returns name of the form in this form collection |
| [hasForm(String formName)](#hasForm-java.lang.String-) |  |
### size() {#size--}
```
public int size()
```


Gets count of XForms in collection.

**Returns:**
int
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Returns true if object is synchronized.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Synchronization object.

**Returns:**
java.lang.Object
### add(XForm xform) {#add-com.aspose.pdf.XForm-}
```
public void add(XForm xform)
```


Adds new XForm into collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xform | [XForm](../../com.aspose.pdf/xform) | XForm to add into collection |

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Delete XForm from collectin

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of XForm which must be deleted |

### delete() {#delete--}
```
public void delete()
```


Deletes all XForms from collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array array, int index)
```


Copies XFormCollection into collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array of XForm to be copied |
| index | int | Index where XFormCollection will be copied |

### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```


Retunrs collection enumerator.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Enumerator for collection
### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


Deletes XForm from collection by form name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of XForm to be deleted. |

### get_Item(int index) {#get-Item-int-}
```
public XForm get_Item(int index)
```


Returns XForm by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of XFormCollection. XForms numbering is started from 1 |

**Returns:**
[XForm](../../com.aspose.pdf/xform) - Retreived XForm
### get_Item(String name) {#get-Item-java.lang.String-}
```
public XForm get_Item(String name)
```


Returns XForm by its name. Exception is thrown if XForm with specified name is not found.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of XForm |

**Returns:**
[XForm](../../com.aspose.pdf/xform) - 
### getFormName(XForm form) {#getFormName-com.aspose.pdf.XForm-}
```
public String getFormName(XForm form)
```


Returns name of the form in this form collection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| form | [XForm](../../com.aspose.pdf/xform) | Form which name is searhced |

**Returns:**
java.lang.String - Form name in the collection; Null if form is not contained in the colleciton
### hasForm(String formName) {#hasForm-java.lang.String-}
```
public boolean hasForm(String formName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formName | java.lang.String |  |

**Returns:**
boolean
