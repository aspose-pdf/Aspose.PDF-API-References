---
title: AppearanceDictionary
second_title: Aspose.PDF for Java API Reference
description: Annotation appearance dictionary specifying how the annotation shall be presented visually on the page.
type: docs
weight: 24
url: /java/com.aspose.pdf/appearancedictionary/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary
```
public final class AppearanceDictionary implements System.Collections.Generic.IGenericDictionary<String,XForm>
```

Annotation appearance dictionary specifying how the annotation shall be presented visually on the page.
## Methods

| Method | Description |
| --- | --- |
| [add(Object key, Object value)](#add-java.lang.Object-java.lang.Object-) | Adds an element with the provided key and value. |
| [addItem(System.Collections.Generic.KeyValuePair<String,XForm> item)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--) | Adds pair with key and value into the dictionary. |
| [addItem(String key, XForm value)](#addItem-java.lang.String-com.aspose.pdf.XForm-) | Add X form for specifed key. |
| [clear()](#clear--) | Removes all elements from the dictionary. |
| [containsItem(System.Collections.Generic.KeyValuePair<String,XForm> item)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--) | Checks does specified key-value pair is contained in the dictionary. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determines does this dictionary contasins specified key. |
| [copyTo(XForm[] array, int index)](#copyTo-com.aspose.pdf.XForm---int-) | Copies the elements of the dictionary to an Array, starting at a particular Array index. |
| [copyToTArray(System.Collections.Generic.KeyValuePair<String,XForm>[] array, int arrayIndex)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm----int-) | Copies the elements of the ICollection to an Array, starting at a particular Array index. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDict()](#getDict--) | Gets pdf dictionary |
| [getKeys()](#getKeys--) | Gets keys of the dictionary. |
| [getKeys_()](#getKeys---) | Gets keys of the dictionary. |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the dictionary. |
| [getValues()](#getValues--) | Gets the list of the dictionary values. |
| [getValues_()](#getValues---) | Gets the list of the dictionary values. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Represents convenient form for getting appearance streams. |
| [hashCode()](#hashCode--) |  |
| [isFixedSize()](#isFixedSize--) | Gets a value indicating whether dictionary has a fixed size. |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether dictionary is read-only. |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to the dictionary is synchronized (thread safe). |
| [iterator()](#iterator--) | Returns an IDictionaryEnumerator object for the dictionary. |
| [iterator__Rename_Namesake()](#iterator--Rename-Namesake--) | Enumerator for the collection. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeItem(System.Collections.Generic.KeyValuePair<String,XForm> item)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--) | Removes key/value pair from the collection. |
| [removeItemByKey(String key)](#removeItemByKey-java.lang.String-) | Removes key from the dictionary. |
| [set_Item(String key, XForm value)](#set-Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [size()](#size--) | Gets the number of elements contained in the dictionary. |
| [toString()](#toString--) |  |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | Tries to find key in the dictionary and retreives value if found. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(Object key, Object value) {#add-java.lang.Object-java.lang.Object-}
```
public void add(Object key, Object value)
```


Adds an element with the provided key and value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.Object | Element key. |
| value | java.lang.Object | Element value. |

### addItem(System.Collections.Generic.KeyValuePair<String,XForm> item) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--}
```
public void addItem(System.Collections.Generic.KeyValuePair<String,XForm> item)
```


Adds pair with key and value into the dictionary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm> | Item to be added. |

### addItem(String key, XForm value) {#addItem-java.lang.String-com.aspose.pdf.XForm-}
```
public void addItem(String key, XForm value)
```


Add X form for specifed key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Element key. |
| value | [XForm](../../com.aspose.pdf/xform) | XForm object value. |

### clear() {#clear--}
```
public void clear()
```


Removes all elements from the dictionary.

### containsItem(System.Collections.Generic.KeyValuePair<String,XForm> item) {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--}
```
public boolean containsItem(System.Collections.Generic.KeyValuePair<String,XForm> item)
```


Checks does specified key-value pair is contained in the dictionary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm> | Key-value pair. |

**Returns:**
boolean - true if this pauir was found.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public boolean containsKey(String key)
```


Determines does this dictionary contasins specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key to search in the dictionary. |

**Returns:**
boolean - true if key is found.
### copyTo(XForm[] array, int index) {#copyTo-com.aspose.pdf.XForm---int-}
```
public void copyTo(XForm[] array, int index)
```


Copies the elements of the dictionary to an Array, starting at a particular Array index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [XForm\[\]](../../com.aspose.pdf/xform) | Array where items must be copied. |
| index | int | Index where items must be copied. |

### copyToTArray(System.Collections.Generic.KeyValuePair<String,XForm>[] array, int arrayIndex) {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm----int-}
```
public void copyToTArray(System.Collections.Generic.KeyValuePair<String,XForm>[] array, int arrayIndex)
```


Copies the elements of the ICollection to an Array, starting at a particular Array index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm>[] | The one-dimensional Array that is the destination of the elements copied from ICollection. The Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

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
### getDict() {#getDict--}
```
public IPdfDictionary getDict()
```


Gets pdf dictionary

**Returns:**
[IPdfDictionary](../../com.aspose.pdf.engine.data/ipdfdictionary) - IPdfDictionary object
### getKeys() {#getKeys--}
```
public System.Collections.Generic.IGenericCollection<String> getKeys()
```


Gets keys of the dictionary. If appearance dictionary has subditionaries, then  Keys  contains (N|R|D).state values, where N - normal appearance, R - rollover appearance, D - down appearance and state - the name of the state (e.g. On, Off for checkboxes).

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<java.lang.String> - List of String values
### getKeys_() {#getKeys---}
```
public List<String> getKeys_()
```


Gets keys of the dictionary. If appearance dictionary has subditionaries, then  Keys  contains (N|R|D).state values, where N - normal appearance, R - rollover appearance, D - down appearance and state - the name of the state (e.g. On, Off for checkboxes).

**Returns:**
java.util.List<java.lang.String> - List of String values
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to the dictionary.

**Returns:**
java.lang.Object - Object for synchronization
### getValues() {#getValues--}
```
public System.Collections.Generic.IGenericCollection<XForm> getValues()
```


Gets the list of the dictionary values. Result collection contains the list of XForm objects.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.pdf.XForm> - List of XForm values
### getValues_() {#getValues---}
```
public List<XForm> getValues_()
```


Gets the list of the dictionary values. Result collection contains the list of XForm objects.

**Returns:**
java.util.List<com.aspose.pdf.XForm> - List of XForm values
### get_Item(String key) {#get-Item-java.lang.String-}
```
public XForm get_Item(String key)
```


Represents convenient form for getting appearance streams.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Represents path to appearance stream. If appearance dictionary has subdictionaries, then path must contain 2 parts ( Keys ), else path has only one part. |

**Returns:**
[XForm](../../com.aspose.pdf/xform) - XForm object (appearance stream) which corresponds to the given key.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFixedSize() {#isFixedSize--}
```
public boolean isFixedSize()
```


Gets a value indicating whether dictionary has a fixed size.

**Returns:**
boolean - boolean value
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether dictionary is read-only.

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets a value indicating whether access to the dictionary is synchronized (thread safe).

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,XForm>> iterator()
```


Returns an IDictionaryEnumerator object for the dictionary.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm>> - Enumerator of the dictionary.
### iterator__Rename_Namesake() {#iterator--Rename-Namesake--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,XForm>> iterator__Rename_Namesake()
```


Enumerator for the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm>> - enumerator of the collection items.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeItem(System.Collections.Generic.KeyValuePair<String,XForm> item) {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--}
```
public boolean removeItem(System.Collections.Generic.KeyValuePair<String,XForm> item)
```


Removes key/value pair from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm> | Key/value pair to be removed. |

**Returns:**
boolean - true if pair was found and removed.
### removeItemByKey(String key) {#removeItemByKey-java.lang.String-}
```
public boolean removeItemByKey(String key)
```


Removes key from the dictionary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key to be removed from the dictionary. |

**Returns:**
boolean - true if key was successfully removed.
### set_Item(String key, XForm value) {#set-Item-java.lang.String-com.aspose.pdf.XForm-}
```
public void set_Item(String key, XForm value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String |  |
| value | [XForm](../../com.aspose.pdf/xform) |  |

### size() {#size--}
```
public int size()
```


Gets the number of elements contained in the dictionary.

**Returns:**
int - int value
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryGetValue(String key, Object[] value) {#tryGetValue-java.lang.String-java.lang.Object---}
```
public boolean tryGetValue(String key, Object[] value)
```


Tries to find key in the dictionary and retreives value if found.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key to search in the dictionary. |
| value | java.lang.Object[] | Retreived value. |

**Returns:**
boolean - true if key was found.
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

