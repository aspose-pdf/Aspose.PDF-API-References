---
title: DictionaryEditor
linktitle: DictionaryEditor
second_title: Aspose.PDF for Java API Reference
description: A class for accessing an document's tree dictionary (document dictionary, page dictionary, resources dictionary).
type: docs
weight: 70
url: /java/com.aspose.pdf.dataeditor/dictionaryeditor/
---
**Inheritance:**
java.lang.Object, java.util.Dictionary <K,V> java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Dictionary <K,V>, java.util.Hashtable < String , ICosPdfPrimitive > com.aspose.pdf.dataeditor.DictionaryEditor, java.util.Hashtable < String , ICosPdfPrimitive >, com.aspose.pdf.dataeditor.DictionaryEditor

**All Implemented Interfaces:**
Serializable, Cloneable, Map < String, ICosPdfPrimitive >

```
public class DictionaryEditor extends Hashtable < String , ICosPdfPrimitive >
```

A class for accessing an document's tree dictionary (document dictionary, page dictionary, resources dictionary).

## Constructors

| Constructor | Description |
| --- | --- |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Document-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Page-) |  |
| [DictionaryEditor](#DictionaryEditor-com.aspose.pdf.Resources-) | @exception ArgumentNullException The resources are null. |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Set ICosPdfPrimitive to dictionary. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Set {@link ICosPdfPrimitive} to dictionary. |
| [clear](#clear--) | Removes all items from the {@link DictionaryEditor}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Determines whether the DictionaryEditor contains a specific value. |
| [containsKey](#containsKey-java.lang.String-) | Determines whether the {@link DictionaryEditor} contains an element with the specified key. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copies the elements of the DictionaryEditor to an Array , starting at a particular Array index. |
| [get_Item](#get_Item-java.lang.String-) | Gets or sets the element with the specified key. |
| [getAllKeys](#getAllKeys--) | Full collection of keys. Contains editable and not editable keys. |
| [getKeys](#getKeys--) | Collection of editable keys. |
| [getValues](#getValues--) | Gets an {@link ICollection} containing the values in the {@link DictionaryEditor}. |
| [isReadOnly](#isReadOnly--) | Gets a value indicating whether the {@link DictionaryEditor} is read-only. |
| [iterator](#iterator--) | Returns an enumerator that iterates through the collection. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Removes the first occurrence of a specific object from the DictionaryEditor . |
| [remove](#remove-java.lang.String-) | Removes the element with the specified key from the {@link DictionaryEditor}. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Gets or sets the element with the specified key. |
| [size](#size--) | Gets the number of elements contained in the {@link DictionaryEditor}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | For access to simple data type like string, name, bool, number. Returns null for other types. |

### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Document-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Page-}


### DictionaryEditor {#DictionaryEditor-com.aspose.pdf.Resources-}
@exception ArgumentNullException The resources are null.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Set ICosPdfPrimitive to dictionary.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Set {@link ICosPdfPrimitive} to dictionary.

### clear {#clear--}
```
public final void clear()
```

Removes all items from the {@link DictionaryEditor}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Determines whether the DictionaryEditor contains a specific value.

### containsKey {#containsKey-java.lang.String-}
Determines whether the {@link DictionaryEditor} contains an element with the specified key.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copies the elements of the DictionaryEditor to an Array , starting at a particular Array index.

### get_Item {#get_Item-java.lang.String-}
Gets or sets the element with the specified key.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Full collection of keys. Contains editable and not editable keys.

**Returns:**
Iterable of String instance

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Collection of editable keys.

**Returns:**
Iterable of String instance

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Gets an {@link ICollection} containing the values in the {@link DictionaryEditor}.

**Returns:**
Iterable of ICosPdfPrimitive instance

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Gets a value indicating whether the {@link DictionaryEditor} is read-only.

**Returns:**
true if the {@link DictionaryEditor} is read-only; otherwise, false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Returns an enumerator that iterates through the collection.

**Returns:**
An enumerator that can be used to iterate through the collection.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Removes the first occurrence of a specific object from the DictionaryEditor .

### remove {#remove-java.lang.String-}
Removes the element with the specified key from the {@link DictionaryEditor}.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Gets or sets the element with the specified key.

### size {#size--}
```
public final int size()
```

Gets the number of elements contained in the {@link DictionaryEditor}.

**Returns:**
int value

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
For access to simple data type like string, name, bool, number. Returns null for other types.
