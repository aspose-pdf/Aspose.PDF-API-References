---
title: XFormCollection
second_title: Aspose.PDF for Java API Reference
description: Class represents collection of XFormCollection.
type: docs
weight: 408
url: /java/com.aspose.pdf/xformcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class XFormCollection implements Iterable<XForm>
```

Class represents collection of XFormCollection.
## Methods

| Method | Description |
| --- | --- |
| [add(XForm xform)](#add-com.aspose.pdf.XForm-) | Adds new XForm into collection. |
| [clear()](#clear--) | Clears all items from the collection. |
| [contains(XForm item)](#contains-com.aspose.pdf.XForm-) | Determines whether the collection contains a specific value. |
| [copyTo(XForm[] array, int index)](#copyTo-com.aspose.pdf.XForm---int-) | Copies XFormCollection into collection. |
| [delete()](#delete--) | Deletes all XForms from collection. |
| [delete(int index)](#delete-int-) | Delete XForm from collectin |
| [delete(String name)](#delete-java.lang.String-) | Deletes XForm from collection by form name. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFormName(XForm form)](#getFormName-com.aspose.pdf.XForm-) | Returns name of the form in this form collection |
| [getSyncRoot()](#getSyncRoot--) | Synchronization object. |
| [get_Item(int index)](#get-Item-int-) | Returns XForm by index. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returns XForm by its name. |
| [hasForm(String formName)](#hasForm-java.lang.String-) |  |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [isSynchronized()](#isSynchronized--) | Returns true if object is synchronized. |
| [iterator()](#iterator--) | Returns collection enumerator. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(XForm item)](#remove-com.aspose.pdf.XForm-) | Deletes specified item from collection. |
| [size()](#size--) | Gets count of XForms in collection. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(XForm xform) {#add-com.aspose.pdf.XForm-}
```
public void add(XForm xform)
```


Adds new XForm into collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xform | [XForm](../../com.aspose.pdf/xform) | XForm to add into collection |

### clear() {#clear--}
```
public void clear()
```


Clears all items from the collection.

### contains(XForm item) {#contains-com.aspose.pdf.XForm-}
```
public boolean contains(XForm item)
```


Determines whether the collection contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [XForm](../../com.aspose.pdf/xform) | The object to locate in the collection |

**Returns:**
boolean - true if item is found in the collection; otherwise, false.
### copyTo(XForm[] array, int index) {#copyTo-com.aspose.pdf.XForm---int-}
```
public void copyTo(XForm[] array, int index)
```


Copies XFormCollection into collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [XForm\[\]](../../com.aspose.pdf/xform) | Array of XForm to be copied |
| index | int | Index where XFormCollection will be copied |

### delete() {#delete--}
```
public void delete()
```


Deletes all XForms from collection.

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Delete XForm from collectin

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of XForm which must be deleted |

### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


Deletes XForm from collection by form name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of XForm to be deleted. |

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
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Synchronization object.

**Returns:**
java.lang.Object - Object
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
[XForm](../../com.aspose.pdf/xform) - XForm object
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether the collection is read-only.

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Returns true if object is synchronized.

**Returns:**
boolean - boolean
### iterator() {#iterator--}
```
public Iterator<XForm> iterator()
```


Returns collection enumerator.

**Returns:**
java.util.Iterator<com.aspose.pdf.XForm> - Enumerator for collection
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(XForm item) {#remove-com.aspose.pdf.XForm-}
```
public boolean remove(XForm item)
```


Deletes specified item from collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [XForm](../../com.aspose.pdf/xform) | The object to delete |

**Returns:**
boolean - true if item was deleted from collection; otherwise, false.
### size() {#size--}
```
public int size()
```


Gets count of XForms in collection.

**Returns:**
int - int value
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

