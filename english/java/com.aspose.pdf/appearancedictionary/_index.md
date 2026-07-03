---
title: AppearanceDictionary
second_title: Aspose.PDF for Java API Reference
description: Annotation appearance dictionary specifying how the annotation shall be presented visually on the page.
type: docs
weight: 150
url: /java/com.aspose.pdf/appearancedictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AppearanceDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, XForm >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, XForm >>

```
public final class AppearanceDictionary extends Object implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , XForm >
```

Annotation appearance dictionary specifying how the annotation shall be presented visually on the page.

## Methods

| Method | Description |
| --- | --- |
| [add](#add-java.lang.Object-java.lang.Object-) | Adds an element with the provided key and value. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Adds pair with key and value into the dictionary. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.XForm-) | Add X form for specifed key. |
| [clear](#clear--) | Removes all elements from the dictionary. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Checks does specified key-value pair is contained in the dictionary. |
| [containsKey](#containsKey-java.lang.String-) | Determines does this dictionary contasins specified key. |
| [copyTo](#copyTo-com.aspose.pdf.XForm:A-int-) | / * / * Returns an IDictionaryEnumerator object for the dictionary. / * / * / * |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copies the elements of the ICollection to an Array, starting at a particular Array index. |
| [get_Item](#get_Item-java.lang.String-) | Represents convenient form for getting appearance streams. |
| [getDict](#getDict--) | Gets pdf dictionary |
| [getKeys_](#getKeys_--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\|R\|D).state values, where N - normal appearance, R - rollover appearance, D - down appearance and state - the name of the state (e.g. On, Off for checkboxes). |
| [getKeys](#getKeys--) | Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N\|R\|D).state values, where N - normal appearance, R - rollover appearance, D - down appearance and state - the name of the state (e.g. On, Off for checkboxes). |
| [getSyncRoot](#getSyncRoot--) | Gets an object that can be used to synchronize access to the dictionary. |
| [getValues_](#getValues_--) | Gets the list of the dictionary values. Result collection contains the list of XForm objects. |
| [getValues](#getValues--) | Gets the list of the dictionary values. Result collection contains the list of XForm objects. |
| [isFixedSize](#isFixedSize--) | Gets a value indicating whether dictionary has a fixed size. |
| [isReadOnly](#isReadOnly--) | Gets a value indicating whether dictionary is read-only. |
| [isSynchronized](#isSynchronized--) | Gets a value indicating whether access to the dictionary is synchronized (thread safe). |
| [iterator__Rename_Namesake](#iterator__Rename_Namesake--) | Enumerator for the collection. |
| [iterator](#iterator--) | Returns an IDictionaryEnumerator object for the dictionary. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Removes key/value pair from the collection. |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Removes key from the dictionary. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.XForm-) |  |
| [size](#size--) | Gets the number of elements contained in the dictionary. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Tries to find key in the dictionary and retreives value if found. |

### add {#add-java.lang.Object-java.lang.Object-}
Adds an element with the provided key and value.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Adds pair with key and value into the dictionary.

### addItem {#addItem-java.lang.String-com.aspose.pdf.XForm-}
Add X form for specifed key.

### clear {#clear--}
```
public void clear()
```

Removes all elements from the dictionary.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Checks does specified key-value pair is contained in the dictionary.

### containsKey {#containsKey-java.lang.String-}
Determines does this dictionary contasins specified key.

### copyTo {#copyTo-com.aspose.pdf.XForm:A-int-}
/ * / * Returns an IDictionaryEnumerator object for the dictionary. / * / * / *

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copies the elements of the ICollection to an Array, starting at a particular Array index.

### get_Item {#get_Item-java.lang.String-}
Represents convenient form for getting appearance streams.

### getDict {#getDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getDict()
```

Gets pdf dictionary

**Returns:**
IPdfDictionary object

### getKeys_ {#getKeys_--}
```
public List < String > getKeys_()
```

Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N|R|D).state values, where N - normal appearance, R - rollover appearance, D - down appearance and state - the name of the state (e.g. On, Off for checkboxes).

**Returns:**
List of String values

### getKeys {#getKeys--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Gets keys of the dictionary. If appearance dictionary has subditionaries, then {@code Keys} contains (N|R|D).state values, where N - normal appearance, R - rollover appearance, D - down appearance and state - the name of the state (e.g. On, Off for checkboxes).

**Returns:**
List of String values

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Gets an object that can be used to synchronize access to the dictionary.

**Returns:**
Object for synchronization

### getValues_ {#getValues_--}
```
public List < XForm > getValues_()
```

Gets the list of the dictionary values. Result collection contains the list of XForm objects.

**Returns:**
List of XForm values

### getValues {#getValues--}
```
public com.aspose.ms.System.Collections.Generic.IGenericCollection< XForm > getValues()
```

Gets the list of the dictionary values. Result collection contains the list of XForm objects.

**Returns:**
List of XForm values

### isFixedSize {#isFixedSize--}
```
public boolean isFixedSize()
```

Gets a value indicating whether dictionary has a fixed size.

**Returns:**
boolean value

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gets a value indicating whether dictionary is read-only.

**Returns:**
boolean value

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Gets a value indicating whether access to the dictionary is synchronized (thread safe).

**Returns:**
boolean value

### iterator__Rename_Namesake {#iterator__Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator__Rename_Namesake()
```

Enumerator for the collection.

**Returns:**
enumerator of the collection items.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XForm >> iterator()
```

Returns an IDictionaryEnumerator object for the dictionary.

**Returns:**
Enumerator of the dictionary.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Removes key/value pair from the collection.

### removeItemByKey {#removeItemByKey-java.lang.String-}
Removes key from the dictionary.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.XForm-}


### size {#size--}
```
public int size()
```

Gets the number of elements contained in the dictionary.

**Returns:**
int value

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Tries to find key in the dictionary and retreives value if found.
