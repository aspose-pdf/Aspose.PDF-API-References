---
title: EmbeddedFileCollection
linktitle: EmbeddedFileCollection
second_title: Aspose.PDF for Java API Reference
description: Class representing embedded files collection.
type: docs
weight: 1200
url: /java/com.aspose.pdf/embeddedfilecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.EmbeddedFileCollection

**All Implemented Interfaces:**
Iterable < FileSpecification >

```
public class EmbeddedFileCollection extends Object implements Iterable < FileSpecification >
```

Class representing embedded files collection.

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.FileSpecification-) | Adds embedded file specification into collection. |
| [add](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | Adds file to embedded files with the specified key. |
| [clear](#clear--) | Remove all embedded files from document. |
| [contains](#contains-com.aspose.pdf.FileSpecification-) | Determines if collection contains specified FileSpecification. Not supported. |
| [copyTo](#copyTo-com.aspose.pdf.FileSpecification:A-int-) | Copies array of FileSpecification object into colleciton. |
| [delete](#delete--) | Remove all embedded files from document. |
| [delete](#delete-java.lang.String-) | Remove all embedded files from document. |
| [deleteByKey](#deleteByKey-java.lang.String-) | Deletes file from the collection by its key in the collection. |
| [findByName](#findByName-java.lang.String-) | Returns embedded file by its name. |
| [get_Item](#get_Item-int-) | Gets embedded file by its index. |
| [get_Item](#get_Item-java.lang.String-) | Gets embedded file by its name. |
| [getKeys](#getKeys--) | Returns list of file attachment keys. |
| [getSyncRoot](#getSyncRoot--) | Gets an object that can be used to synchronize access to this collection. |
| [isEmbeddedFilesExist](#isEmbeddedFilesExist--) | Check is Embedded Files structure exists. Return TRUE if structure exists, and FALSE if not. If document have never contained embedded files - this structure was not created and absent. |
| [isReadOnly](#isReadOnly--) | Determines if collection is read only. Always returns false. |
| [isSynchronized](#isSynchronized--) | Gets a value indicating whether access to this collection is synchronized (thread safe). |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Returns colleciton enumerator. |
| [iterator](#iterator--) | Returns colleciton enumerator. |
| [remove](#remove-com.aspose.pdf.FileSpecification-) | Removes specified FileSpecification from collection. Not supported. |
| [size](#size--) | Gets number of embedded files in collection. |

### add {#add-com.aspose.pdf.FileSpecification-}
Adds embedded file specification into collection.

### add {#add-java.lang.String-com.aspose.pdf.FileSpecification-}
Adds file to embedded files with the specified key.

### clear {#clear--}
```
public void clear()
```

Remove all embedded files from document.

### contains {#contains-com.aspose.pdf.FileSpecification-}
Determines if collection contains specified FileSpecification. Not supported.

### copyTo {#copyTo-com.aspose.pdf.FileSpecification:A-int-}
Copies array of FileSpecification object into colleciton.

### delete {#delete--}
```
public void delete()
```

Remove all embedded files from document.

### delete {#delete-java.lang.String-}
Remove all embedded files from document.

### deleteByKey {#deleteByKey-java.lang.String-}
Deletes file from the collection by its key in the collection.

### findByName {#findByName-java.lang.String-}
Returns embedded file by its name.

### get_Item {#get_Item-int-}
```
public FileSpecification get_Item(int index)
```

Gets embedded file by its index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of embedded file. Numbering is started from 1. |

**Returns:**
Retreived embedded file specification

### get_Item {#get_Item-java.lang.String-}
Gets embedded file by its name.

### getKeys {#getKeys--}
```
public final List < String > getKeys()
```

Returns list of file attachment keys.

**Returns:**
List of String values

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Gets an object that can be used to synchronize access to this collection.

**Returns:**
Object for synchronization

### isEmbeddedFilesExist {#isEmbeddedFilesExist--}
```
public boolean isEmbeddedFilesExist()
```

Check is Embedded Files structure exists. Return TRUE if structure exists, and FALSE if not. If document have never contained embedded files - this structure was not created and absent.

**Returns:**
boolean value

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Determines if collection is read only. Always returns false.

**Returns:**
boolean value

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Gets a value indicating whether access to this collection is synchronized (thread safe).

**Returns:**
boolean value

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< FileSpecification > iterator_Rename_Namesake()
```

Returns colleciton enumerator.

**Returns:**
Enumerator of colleciton.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.IEnumerator< FileSpecification > iterator()
```

Returns colleciton enumerator.

**Returns:**
Enumerator of colleciton.

### remove {#remove-com.aspose.pdf.FileSpecification-}
Removes specified FileSpecification from collection. Not supported.

### size {#size--}
```
public int size()
```

Gets number of embedded files in collection.

**Returns:**
int value
