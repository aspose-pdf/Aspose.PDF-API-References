---
title: Metadata
second_title: Aspose.PDF for Java API Reference
description: Provides access to XMP metadata stream.
type: docs
weight: 3050
url: /java/com.aspose.pdf/metadata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Metadata

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XmpValue >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XmpValue >>

```
public final class Metadata extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpValue >
```

Provides access to XMP metadata stream.

## Methods

| Method | Description |
| --- | --- |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Adds pair with key and value into the dictionary. |
| [addItem](#addItem-java.lang.String-java.lang.Object-) | Adds value to metadata. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-) | Adds pdf extension to metadata. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XmpValue-) | Adds value to metadata. |
| [clear](#clear--) | Clears metadata. |
| [contains](#contains-java.lang.String-) | Checks does key is contained in metadata. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Checks does specified key-value pair is contained in the dictionary. |
| [containsKey](#containsKey-java.lang.String-) | Determines does this dictionary contasins specified key. |
| [copyTo](#copyTo-com.aspose.ms.System.Array-int-) | Copies elements of the collection into array. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copies elements of the collection into array. |
| [get_Item](#get_Item-java.lang.String-) | Gets data from metadata. |
| [getExtensionFields_Internal](#getExtensionFields_Internal--) | For Internal usage only. Gets the dictionary of extension fields. |
| [getExtensionFields](#getExtensionFields--) | <p> Gets the dictionary of extension fields. </p> |
| [getItem](#getItem-java.lang.String-) | Gets data from metadata. |
| [getKeys](#getKeys--) | Gets collection of metadata keys. |
| [getNamespaceUriByPrefix](#getNamespaceUriByPrefix-java.lang.String-) | Returns namespace URI by prefix. |
| [getPrefixByNamespaceUri](#getPrefixByNamespaceUri-java.lang.String-) | Returns prefix by namespace URI. |
| [getSyncRoot](#getSyncRoot--) | Gets collection synchronization object. |
| [getValues](#getValues--) | Gets values in the metadata. |
| [isFixedSize](#isFixedSize--) | Checks if colleciton has fixed size. |
| [isReadOnly](#isReadOnly--) | Checks if collection is read-only. |
| [isSynchronized](#isSynchronized--) | Checks if collection is synchronized. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) |  |
| [iterator](#iterator--) | Returns dictionary enumerator. |
| [iteratorIE](#iteratorIE--) | Gets enumerator of the collection. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-) | Registers namespace URI. |
| [registerNamespaceUri](#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-) | Registers namespace URI. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Removes key/value pair from the colleciton. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Removes entry from metadata. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XmpValue-) | Sets data from metadata. |
| [setItem](#setItem-java.lang.String-com.aspose.pdf.XmpValue-) | Sets data from metadata. |
| [size](#size--) | Gets count of elements in the collection. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Tries to find key in the dictionary and retreives value if found. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-) | Tries to find key in the dictionary and retreives value if found. |

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Adds pair with key and value into the dictionary.

### addItem {#addItem-java.lang.String-java.lang.Object-}
Adds value to metadata.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpPdfAExtensionObject-}
Adds pdf extension to metadata.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XmpValue-}
Adds value to metadata.

### clear {#clear--}
```
public void clear()
```

Clears metadata.

### contains {#contains-java.lang.String-}
Checks does key is contained in metadata.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Checks does specified key-value pair is contained in the dictionary.

### containsKey {#containsKey-java.lang.String-}
Determines does this dictionary contasins specified key.

### copyTo {#copyTo-com.aspose.ms.System.Array-int-}
Copies elements of the collection into array.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copies elements of the collection into array.

### get_Item {#get_Item-java.lang.String-}
Gets data from metadata.

### getExtensionFields_Internal {#getExtensionFields_Internal--}
```
public com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XmpPdfAExtensionSchema > getExtensionFields_Internal()
```

For Internal usage only. Gets the dictionary of extension fields.

**Returns:**
internal object

### getExtensionFields {#getExtensionFields--}
```
public Hashtable < String , XmpPdfAExtensionSchema > getExtensionFields()
```

<p> Gets the dictionary of extension fields. </p>

**Returns:**
{@code Hashtable<String, XmpPdfAExtensionSchema>} object

### getItem {#getItem-java.lang.String-}
Gets data from metadata.

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Gets collection of metadata keys.

**Returns:**
ICollection object

### getNamespaceUriByPrefix {#getNamespaceUriByPrefix-java.lang.String-}
Returns namespace URI by prefix.

### getPrefixByNamespaceUri {#getPrefixByNamespaceUri-java.lang.String-}
Returns prefix by namespace URI.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Gets collection synchronization object.

**Returns:**
Object for synchronization

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XmpValue > getValues()
```

Gets values in the metadata.

**Returns:**
ICollection object

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Checks if colleciton has fixed size.

**Returns:**
boolean value

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Checks if collection is read-only.

**Returns:**
boolean value

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Checks if collection is synchronized.

**Returns:**
boolean value

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```



### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iterator()
```

Returns dictionary enumerator.

**Returns:**
Enumerator.

### iteratorIE {#iteratorIE--}
```
public Iterator <com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >> iteratorIE()
```

Gets enumerator of the collection.

**Returns:**
IEnumerator object @see IEnumerator

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-}
Registers namespace URI.

### registerNamespaceUri {#registerNamespaceUri-java.lang.String-java.lang.String-java.lang.String-}
Registers namespace URI.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Removes key/value pair from the colleciton.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Removes entry from metadata.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XmpValue-}
Sets data from metadata.

### setItem {#setItem-java.lang.String-com.aspose.pdf.XmpValue-}
Sets data from metadata.

### size {#size--}
```
public int size()
```

Gets count of elements in the collection.

**Returns:**
int value

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Tries to find key in the dictionary and retreives value if found.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.XmpValue:A-}
Tries to find key in the dictionary and retreives value if found.
