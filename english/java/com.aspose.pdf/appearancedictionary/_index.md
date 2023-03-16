---
title: AppearanceDictionary
second_title: Aspose.PDF for Java API Reference
description: Annotation appearance dictionary specifying how the annotation shall be presented visually on the page.
type: docs
weight: 22
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
| [getDict()](#getDict--) | Gets pdf dictionary |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether dictionary is read-only. |
| [isFixedSize()](#isFixedSize--) | Gets a value indicating whether dictionary has a fixed size. |
| [getKeys()](#getKeys--) | Gets keys of the dictionary. |
| [getKeys_()](#getKeys---) | Gets keys of the dictionary. |
| [getValues()](#getValues--) | Gets the list of the dictionary values. |
| [getValues_()](#getValues---) | Gets the list of the dictionary values. |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to the dictionary is synchronized (thread safe). |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the dictionary. |
| [size()](#size--) | Gets the number of elements contained in the dictionary. |
| [clear()](#clear--) | Removes all elements from the dictionary. |
| [add(Object key, Object value)](#add-java.lang.Object-java.lang.Object-) | Adds an element with the provided key and value. |
| [iterator()](#iterator--) | Returns an IDictionaryEnumerator object for the dictionary. |
| [copyTo(XForm[] array, int index)](#copyTo-com.aspose.pdf.XForm---int-) | Copies the elements of the dictionary to an Array, starting at a particular Array index. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Represents convenient form for getting appearance streams. |
| [set_Item(String key, XForm value)](#set-Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [addItem(String key, XForm value)](#addItem-java.lang.String-com.aspose.pdf.XForm-) | Add X form for specifed key. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determines does this dictionary contasins specified key. |
| [removeItemByKey(String key)](#removeItemByKey-java.lang.String-) | Removes key from the dictionary. |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | Tries to find key in the dictionary and retreives value if found. |
| [addItem(System.Collections.Generic.KeyValuePair<String,XForm> item)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--) | Adds pair with key and value into the dictionary. |
| [containsItem(System.Collections.Generic.KeyValuePair<String,XForm> item)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--) | Checks does specified key-value pair is contained in the dictionary. |
| [copyToTArray(System.Collections.Generic.KeyValuePair<String,XForm>[] array, int arrayIndex)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm----int-) | Copies the elements of the ICollection to an Array, starting at a particular Array index. |
| [removeItem(System.Collections.Generic.KeyValuePair<String,XForm> item)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--) | Removes key/value pair from the collection. |
| [iterator__Rename_Namesake()](#iterator--Rename-Namesake--) | Enumerator for the collection. |
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether dictionary is read-only.

**Returns:**
boolean - boolean value
### isFixedSize() {#isFixedSize--}
```
public boolean isFixedSize()
```


Gets a value indicating whether dictionary has a fixed size.

**Returns:**
boolean - boolean value
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
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets a value indicating whether access to the dictionary is synchronized (thread safe).

**Returns:**
boolean - boolean value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to the dictionary.

**Returns:**
java.lang.Object - Object for synchronization
### size() {#size--}
```
public int size()
```


Gets the number of elements contained in the dictionary.

**Returns:**
int - int value
### clear() {#clear--}
```
public void clear()
```


Removes all elements from the dictionary.

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

### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,XForm>> iterator()
```


Returns an IDictionaryEnumerator object for the dictionary.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm>> - Enumerator of the dictionary.
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
### set_Item(String key, XForm value) {#set-Item-java.lang.String-com.aspose.pdf.XForm-}
```
public void set_Item(String key, XForm value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String |  |
| value | [XForm](../../com.aspose.pdf/xform) |  |

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
### addItem(System.Collections.Generic.KeyValuePair<String,XForm> item) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XForm--}
```
public void addItem(System.Collections.Generic.KeyValuePair<String,XForm> item)
```


Adds pair with key and value into the dictionary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm> | Item to be added. |

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
### iterator__Rename_Namesake() {#iterator--Rename-Namesake--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,XForm>> iterator__Rename_Namesake()
```


Enumerator for the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XForm>> - enumerator of the collection items.
