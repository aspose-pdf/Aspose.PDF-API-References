---
title: CosPdfDictionary
linktitle: CosPdfDictionary
second_title: Aspose.PDF for Java API Reference
description: A class for accessing an object's dictionary.
type: docs
weight: 20
url: /java/com.aspose.pdf.dataeditor/cospdfdictionary/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.dataeditor.CosPdfPrimitive com.aspose.pdf.dataeditor.CosPdfDictionary, com.aspose.pdf.dataeditor.CosPdfPrimitive, com.aspose.pdf.dataeditor.CosPdfDictionary

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.Generic.IGenericDictionary< String, ICosPdfPrimitive >, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, com.aspose.ms.System.Collections.IEnumerable<com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>, ICosPdfPrimitive, Iterable <com.aspose.ms.System.Collections.Generic.KeyValuePair< String, ICosPdfPrimitive >>

```
public class CosPdfDictionary extends CosPdfPrimitive implements com.aspose.ms.System.Collections.Generic.IGenericDictionary< String , ICosPdfPrimitive >
```

A class for accessing an object's dictionary.

## Constructors

| Constructor | Description |
| --- | --- |
| [CosPdfDictionary](#CosPdfDictionary-com.aspose.pdf.Resources-) | Creates a dictionary from resources. @exception ArgumentNullException The resources are null. |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Set ICosPdfPrimitive to dictionary. |
| [add](#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Set {@link ICosPdfPrimitive} to dictionary. @exception ArgumentException Throw exception if key/value can't be edited or removed. |
| [addItem](#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Add item pair. |
| [addItem](#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Add item. |
| [clear](#clear--) | Removes all items from the {@link CosPdfDictionary}. |
| [contains](#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Determines whether the CosPdfDictionary contains a specific value. |
| [containsItem](#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Return true if contains item |
| [containsKey](#containsKey-java.lang.String-) | Determines whether the {@link CosPdfDictionary} contains an element with the specified key. |
| [copyTo](#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copies the elements of the CosPdfDictionary to an Array , starting at a particular Array index. |
| [copyToTArray](#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-) | Copy To Array |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Document-) | Creates an empty dictionary that will be attached to the document. |
| [createEmptyDictionary](#createEmptyDictionary-com.aspose.pdf.Page-) | Creates an empty dictionary that will be attached to the page. |
| [get_Item](#get_Item-java.lang.String-) | Gets or sets the element with the specified key. |
| [getAllKeys](#getAllKeys--) | Full collection of keys. Contains editable and not editable keys. |
| [getKeys](#getKeys--) | Collection of editable keys. |
| [getValues](#getValues--) | Gets an {@link ICollection} containing the values in the {@link CosPdfDictionary}. |
| [isReadOnly](#isReadOnly--) | Gets a value indicating whether the {@link CosPdfDictionary} is read-only. |
| [iterator](#iterator--) | Returns an enumerator that iterates through the collection. |
| [remove](#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Removes the first occurrence of a specific object from the CosPdfDictionary . |
| [remove](#remove-java.lang.String-) | Removes the element with the specified key from the {@link CosPdfDictionary}. |
| [removeItem](#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-) | Remove Item |
| [removeItemByKey](#removeItemByKey-java.lang.String-) | Remove item by key. |
| [set_Item](#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-) | Gets or sets the element with the specified key. @exception ArgumentNullException The key is null. @exception KeyNotFoundException The property is retrieved and key is not found. @exception ArgumentException Throw exception if key can't be edited/set. |
| [size](#size--) | Gets the number of elements contained in the {@link CosPdfDictionary}. |
| [toCosPdfDictionary](#toCosPdfDictionary--) | Tries cast this instance to {@link CosPdfDictionary}. |
| [tryGetValue](#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-) | For access to simple data type like string, name, bool, number. Returns null for other types. |
| [tryGetValue](#tryGetValue-java.lang.String-java.lang.Object:A-) | Try to get value |

### CosPdfDictionary {#CosPdfDictionary-com.aspose.pdf.Resources-}
Creates a dictionary from resources. @exception ArgumentNullException The resources are null.

### add {#add-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Set ICosPdfPrimitive to dictionary.

### add {#add-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Set {@link ICosPdfPrimitive} to dictionary. @exception ArgumentException Throw exception if key/value can't be edited or removed.

### addItem {#addItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Add item pair.

### addItem {#addItem-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Add item.

### clear {#clear--}
```
public final void clear()
```

Removes all items from the {@link CosPdfDictionary}.

### contains {#contains-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Determines whether the CosPdfDictionary contains a specific value.

### containsItem {#containsItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Return true if contains item

### containsKey {#containsKey-java.lang.String-}
Determines whether the {@link CosPdfDictionary} contains an element with the specified key.

### copyTo {#copyTo-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copies the elements of the CosPdfDictionary to an Array , starting at a particular Array index.

### copyToTArray {#copyToTArray-com.aspose.ms.System.Collections.Generic.KeyValuePair:A-int-}
Copy To Array

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Document-}
Creates an empty dictionary that will be attached to the document.

### createEmptyDictionary {#createEmptyDictionary-com.aspose.pdf.Page-}
Creates an empty dictionary that will be attached to the page.

### get_Item {#get_Item-java.lang.String-}
Gets or sets the element with the specified key.

### getAllKeys {#getAllKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getAllKeys()
```

Full collection of keys. Contains editable and not editable keys.

**Returns:**
List of String values

### getKeys {#getKeys--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< String > getKeys()
```

Collection of editable keys.

**Returns:**
List of String values

### getValues {#getValues--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericCollection< ICosPdfPrimitive > getValues()
```

Gets an {@link ICollection} containing the values in the {@link CosPdfDictionary}.

**Returns:**
List of ICosPdfPrimitive instances

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Gets a value indicating whether the {@link CosPdfDictionary} is read-only.

**Returns:**
true if the {@link CosPdfDictionary} is read-only; otherwise, false.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair< String , ICosPdfPrimitive >> iterator()
```

Returns an enumerator that iterates through the collection.

**Returns:**
An enumerator that can be used to iterate through the collection.

### remove {#remove-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Removes the first occurrence of a specific object from the CosPdfDictionary .

### remove {#remove-java.lang.String-}
Removes the element with the specified key from the {@link CosPdfDictionary}.

### removeItem {#removeItem-com.aspose.ms.System.Collections.Generic.KeyValuePair-}
Remove Item

### removeItemByKey {#removeItemByKey-java.lang.String-}
Remove item by key.

### set_Item {#set_Item-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive-}
Gets or sets the element with the specified key. @exception ArgumentNullException The key is null. @exception KeyNotFoundException The property is retrieved and key is not found. @exception ArgumentException Throw exception if key can't be edited/set.

### size {#size--}
```
public final int size()
```

Gets the number of elements contained in the {@link CosPdfDictionary}.

**Returns:**
int value

### toCosPdfDictionary {#toCosPdfDictionary--}
```
public CosPdfDictionary toCosPdfDictionary()
```

Tries cast this instance to {@link CosPdfDictionary}.

**Returns:**
null if instance is not {@link CosPdfDictionary} else {@link CosPdfDictionary}.

### tryGetValue {#tryGetValue-java.lang.String-com.aspose.pdf.dataeditor.ICosPdfPrimitive:A-}
For access to simple data type like string, name, bool, number. Returns null for other types.

### tryGetValue {#tryGetValue-java.lang.String-java.lang.Object:A-}
Try to get value
