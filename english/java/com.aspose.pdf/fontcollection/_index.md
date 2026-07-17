---
title: FontCollection
linktitle: FontCollection
second_title: Aspose.PDF for Java API Reference
description: <p> Represents font collection. </p> <hr> <pre> The example demonstrates how to make all font declared on page as embedded. // Open document Document doc = new.
type: docs
weight: 1670
url: /java/com.aspose.pdf/fontcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontCollection

**All Implemented Interfaces:**
Iterable < Font >

```
public final class FontCollection extends Object implements Iterable < Font >
```

<p> Represents font collection. </p> <hr> <pre> The example demonstrates how to make all font declared on page as embedded. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // ensure all fonts declared on page resources are embedded // note that if fonts are declared on form resources they are not accessible from page resources for(com.aspose.pdf.Font font : doc.getPages().get_Item(1).getResources().getFonts()) { if(!font.isEmbedded()) font.isEmbedded(true); } doc.save("D:\\Tests\\input.pdf"); </pre> <hr> <p> Font collections represented by {@code FontCollection} class are used in several scenarios. For example, in resources with {@code Resources.Fonts} property. </p>

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.Font-) | Adds Font into collection. |
| [add](#add-com.aspose.pdf.Font-java.lang.String:A-) | Adds new font to font resources and returns automatically assigned name of font resource. |
| [add](#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-) | Add new font to font collection. |
| [add](#add-java.lang.String-java.lang.String-) | Adds to font resources new font entry with specified base font name. |
| [clear_Rename_Namesake](#clear_Rename_Namesake--) | / * / * Adds Font into collection. / * / * |
| [contains](#contains-com.aspose.pdf.Font-) | Determines whether the collection contains a specific value. |
| [contains](#contains-java.lang.String-) | Checks if font exists in font collection. |
| [copyTo](#copyTo-com.aspose.pdf.Font:A-int-) | Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array |
| [delete](#delete-java.lang.String-) | Deletes Font with resource name specified |
| [get_Item](#get_Item-int-) | Gets the font element at the specified index. |
| [get_Item](#get_Item-java.lang.String-) | Gets font from the collection by font name. Exception is thrown if font was not found. |
| [getFontsDictionary](#getFontsDictionary--) | Get IPdfDictionary object |
| [getHash](#getHash--) |  |
| [getSyncRoot](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [isReadOnly](#isReadOnly--) | Gets a value indicating whether collection is read-only |
| [isSynchronized](#isSynchronized--) | Gets a value indicating whether access to the collection is synchronized (thread safe). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Returns an enumerator for the entire collection. |
| [iterator](#iterator--) | Returns an enumerator for the entire collection. |
| [remove](#remove-com.aspose.pdf.Font-) | Deletes specified item from collection. |
| [size](#size--) | Gets the number of {@code Font} object elements actually contained in the collection. |

### add {#add-com.aspose.pdf.Font-}
Adds Font into collection.

### add {#add-com.aspose.pdf.Font-java.lang.String:A-}
Adds new font to font resources and returns automatically assigned name of font resource.

### add {#add-java.lang.String-com.aspose.pdf.engine.data.IPdfObject-}
Add new font to font collection.

### add {#add-java.lang.String-java.lang.String-}
Adds to font resources new font entry with specified base font name.

### clear_Rename_Namesake {#clear_Rename_Namesake--}
```
public void clear_Rename_Namesake()
```

/ * / * Adds Font into collection. / * / *

### contains {#contains-com.aspose.pdf.Font-}
Determines whether the collection contains a specific value.

### contains {#contains-java.lang.String-}
Checks if font exists in font collection.

### copyTo {#copyTo-com.aspose.pdf.Font:A-int-}
Copies the entire collection to a compatible one-dimensional Array, starting at the specified index of the target array

### delete {#delete-java.lang.String-}
Deletes Font with resource name specified

### get_Item {#get_Item-int-}
```
public Font get_Item(int index)
```

Gets the font element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index within the collection. |

**Returns:**
Font object.

### get_Item {#get_Item-java.lang.String-}
Gets font from the collection by font name. Exception is thrown if font was not found.

### getFontsDictionary {#getFontsDictionary--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getFontsDictionary()
```

Get IPdfDictionary object

**Returns:**
IPdfDictionary object

### getHash {#getHash--}
```
public com.aspose.pdf.engine.collections.HashDictionary< String , Font > getHash()
```



### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Gets an object that can be used to synchronize access to the collection.

**Returns:**
Object for synchronization

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gets a value indicating whether collection is read-only

**Returns:**
boolean value

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Gets a value indicating whether access to the collection is synchronized (thread safe).

**Returns:**
boolean value

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator iterator_Rename_Namesake()
```

Returns an enumerator for the entire collection.

**Returns:**
Enumerator object.

### iterator {#iterator--}
```
public Iterator < Font > iterator()
```

Returns an enumerator for the entire collection.

**Returns:**
Enumerator object.

### remove {#remove-com.aspose.pdf.Font-}
Deletes specified item from collection.

### size {#size--}
```
public int size()
```

Gets the number of {@code Font} object elements actually contained in the collection.

**Returns:**
int value
