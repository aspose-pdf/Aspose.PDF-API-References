---
title: Metadata
second_title: Aspose.PDF for Java API Reference
description: Provides access to XMP metadata stream.
type: docs
weight: 220
url: /java/com.aspose.pdf/metadata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary
```
public final class Metadata implements System.Collections.Generic.IGenericDictionary<String,XmpValue>
```

Provides access to XMP metadata stream.
## Methods

| Method | Description |
| --- | --- |
| [addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | Adds pair with key and value into the dictionary. |
| [addItem(String prefix, XmpPdfAExtensionObject value)](#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-) | Adds pdf extension to metadata. |
| [addItem(String key, XmpValue value)](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | Adds value to metadata. |
| [addItem(String key, Object value)](#addItem-java.lang.String-java.lang.Object-) | Adds value to metadata. |
| [clear()](#clear--) | Clears metadata. |
| [contains(String key)](#contains-java.lang.String-) | Checks does key is contained in metadata. |
| [containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | Checks does specified key-value pair is contained in the dictionary. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determines does this dictionary contasins specified key. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies elements of the collection into array. |
| [copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index)](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue----int-) | Copies elements of the collection into array. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExtensionFields()](#getExtensionFields--) | Gets the dictionary of extension fields. |
| [getExtensionFields_Internal()](#getExtensionFields-Internal--) | For Internal usage only. |
| [getKeys()](#getKeys--) | Gets collection of metadata keys. |
| [getNamespaceUriByPrefix(String prefix)](#getNamespaceUriByPrefix-java.lang.String-) | Returns namespace URI by prefix. |
| [getPrefixByNamespaceUri(String namespaceUri)](#getPrefixByNamespaceUri-java.lang.String-) | Returns prefix by namespace URI. |
| [getSyncRoot()](#getSyncRoot--) | Gets collection synchronization object. |
| [getValues()](#getValues--) | Gets values in the metadata. |
| [get_Item(String key)](#get-Item-java.lang.String-) | Gets data from metadata. |
| [hashCode()](#hashCode--) |  |
| [isFixedSize()](#isFixedSize--) | Checks if colleciton has fixed size. |
| [isReadOnly()](#isReadOnly--) | Checks if collection is read-only. |
| [isSynchronized()](#isSynchronized--) | Checks if collection is synchronized. |
| [iterator()](#iterator--) | Returns dictionary enumerator. |
| [iteratorIE()](#iteratorIE--) | Gets enumerator of the collection. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Registers namespace URI. |
| [registerNamespaceUri(String prefix, String namespaceUri, String schemaDescription)](#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-) | Registers namespace URI. |
| [removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--) | Removes key/value pair from the colleciton. |
| [removeItemByKey(String key)](#removeItemByKey-java.lang.String-) | Removes entry from metadata. |
| [set_Item(String key, XmpValue value)](#set-Item-java.lang.String-com.aspose.pdf.XmpValue-) | Sets data from metadata. |
| [size()](#size--) | Gets count of elements in the collection. |
| [toString()](#toString--) |  |
| [tryGetValue(String key, XmpValue[] value)](#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue---) | Tries to find key in the dictionary and retreives value if found. |
| [tryGetValue(String key, Object[] value)](#tryGetValue-java.lang.String-java.lang.Object---) | Tries to find key in the dictionary and retreives value if found. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public void addItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


Adds pair with key and value into the dictionary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | Item to be added. |

### addItem(String prefix, XmpPdfAExtensionObject value) {#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-}
```
public void addItem(String prefix, XmpPdfAExtensionObject value)
```


Adds pdf extension to metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | The prefix of extension. |
| value | [XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject) | Value which will be added. |

### addItem(String key, XmpValue value) {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
```
public void addItem(String key, XmpValue value)
```


Adds value to metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key to add. |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | Value which will be added. |

### addItem(String key, Object value) {#addItem-java.lang.String-java.lang.Object-}
```
public void addItem(String key, Object value)
```


Adds value to metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key to add. |
| value | java.lang.Object | Value which will be added. |

### clear() {#clear--}
```
public void clear()
```


Clears metadata.

### contains(String key) {#contains-java.lang.String-}
```
public boolean contains(String key)
```


Checks does key is contained in metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key of entry to find. |

**Returns:**
boolean - True if key is contained in the metadata.
### containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public boolean containsItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


Checks does specified key-value pair is contained in the dictionary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | Key-value pair. |

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
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array array, int index)
```


Copies elements of the collection into array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Destination array. |
| index | int | Starting index. |

### copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index) {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue----int-}
```
public void copyToTArray(System.Collections.Generic.KeyValuePair<String,XmpValue>[] array, int index)
```


Copies elements of the collection into array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>[] | Destination array. |
| index | int | Starting index. |

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
### getExtensionFields() {#getExtensionFields--}
```
public Hashtable<String,XmpPdfAExtensionSchema> getExtensionFields()
```


Gets the dictionary of extension fields.

**Returns:**
java.util.Hashtable<java.lang.String,com.aspose.pdf.XmpPdfAExtensionSchema> -  Hashtable  object
### getExtensionFields_Internal() {#getExtensionFields-Internal--}
```
public System.Collections.Generic.IGenericDictionary<String,XmpPdfAExtensionSchema> getExtensionFields_Internal()
```


For Internal usage only.

Gets the dictionary of extension fields.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.String,com.aspose.pdf.XmpPdfAExtensionSchema> - internal object
### getKeys() {#getKeys--}
```
public System.Collections.Generic.IGenericCollection<String> getKeys()
```


Gets collection of metadata keys.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<java.lang.String> - ICollection object
### getNamespaceUriByPrefix(String prefix) {#getNamespaceUriByPrefix-java.lang.String-}
```
public String getNamespaceUriByPrefix(String prefix)
```


Returns namespace URI by prefix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | The value of prefix. |

**Returns:**
java.lang.String - The value of namespace URI.
### getPrefixByNamespaceUri(String namespaceUri) {#getPrefixByNamespaceUri-java.lang.String-}
```
public String getPrefixByNamespaceUri(String namespaceUri)
```


Returns prefix by namespace URI.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| namespaceUri | java.lang.String | Namespace URI. |

**Returns:**
java.lang.String - The value of prefix.
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets collection synchronization object.

**Returns:**
java.lang.Object - Object for synchronization
### getValues() {#getValues--}
```
public System.Collections.Generic.IGenericCollection<XmpValue> getValues()
```


Gets values in the metadata.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.pdf.XmpValue> - ICollection object
### get_Item(String key) {#get-Item-java.lang.String-}
```
public XmpValue get_Item(String key)
```


Gets data from metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key name. |

**Returns:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - Metadata object.
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


Checks if colleciton has fixed size.

**Returns:**
boolean - boolean value
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Checks if collection is read-only.

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Checks if collection is synchronized.

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,XmpValue>> iterator()
```


Returns dictionary enumerator.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>> - Enumerator.
### iteratorIE() {#iteratorIE--}
```
public Iterator<System.Collections.Generic.KeyValuePair<String,XmpValue>> iteratorIE()
```


Gets enumerator of the collection.

**Returns:**
java.util.Iterator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>> - IEnumerator object
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.IEnumerator iterator_Rename_Namesake()
```




**Returns:**
com.aspose.ms.System.Collections.IEnumerator
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Registers namespace URI.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | The value of prefix. |
| namespaceUri | java.lang.String | The value of namespace URI. |

### registerNamespaceUri(String prefix, String namespaceUri, String schemaDescription) {#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri, String schemaDescription)
```


Registers namespace URI.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| prefix | java.lang.String | The value of prefix. |
| namespaceUri | java.lang.String | The value of namespace URI. |
| schemaDescription | java.lang.String | The value of schema description. |

### removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item) {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-java.lang.String-com.aspose.pdf.XmpValue--}
```
public boolean removeItem(System.Collections.Generic.KeyValuePair<String,XmpValue> item)
```


Removes key/value pair from the colleciton.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue> | Key/value pair to be removed. |

**Returns:**
boolean - true if pair was found and removed.
### removeItemByKey(String key) {#removeItemByKey-java.lang.String-}
```
public boolean removeItemByKey(String key)
```


Removes entry from metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The key of entry to remove. |

**Returns:**
boolean - True - if key removed; otherwise, false.
### set_Item(String key, XmpValue value) {#set-Item-java.lang.String-com.aspose.pdf.XmpValue-}
```
public void set_Item(String key, XmpValue value)
```


Sets data from metadata.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | key name |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | The value object |

### size() {#size--}
```
public int size()
```


Gets count of elements in the collection.

**Returns:**
int - int value
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryGetValue(String key, XmpValue[] value) {#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue---}
```
public boolean tryGetValue(String key, XmpValue[] value)
```


Tries to find key in the dictionary and retreives value if found.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key to search in the dictionary. |
| value | [XmpValue\[\]](../../com.aspose.pdf/xmpvalue) | Retreived value. |

**Returns:**
boolean - true if key was found.
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

