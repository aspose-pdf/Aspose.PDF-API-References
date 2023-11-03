---
title: EmbeddedFileCollection
second_title: Aspose.PDF for Java API Reference
description: Class representing embedded files collection.
type: docs
weight: 96
url: /java/com.aspose.pdf/embeddedfilecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class EmbeddedFileCollection implements Iterable<FileSpecification>
```

Class representing embedded files collection.
## Methods

| Method | Description |
| --- | --- |
| [isSynchronized()](#isSynchronized--) | Gets a value indicating whether access to this collection is synchronized (thread safe). |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to this collection. |
| [size()](#size--) | Gets number of embedded files in collection. |
| [isReadOnly()](#isReadOnly--) | Determines if collection is read only. |
| [copyTo(FileSpecification[] array, int index)](#copyTo-com.aspose.pdf.FileSpecification---int-) | Copies array of FileSpecification object into colleciton. |
| [iterator()](#iterator--) | Returns colleciton enumerator. |
| [iterator_Rename_Namesake()](#iterator-Rename-Namesake--) | Returns colleciton enumerator. |
| [isEmbeddedFilesExist()](#isEmbeddedFilesExist--) | Check is Embedded Files structure exists. |
| [add(FileSpecification file)](#add-com.aspose.pdf.FileSpecification-) | Adds embedded file specification into collection. |
| [add(String key, FileSpecification file)](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | Adds file to embedded files with the specified key. |
| [deleteByKey(String key)](#deleteByKey-java.lang.String-) | Deletes file from the collection by its key in the collection. |
| [getKeys()](#getKeys--) | Returns list of file attachment keys. |
| [findByName(String name)](#findByName-java.lang.String-) | Returns embedded file by its name. |
| [delete(String name)](#delete-java.lang.String-) | Delete embedded file by name. |
| [delete()](#delete--) | Remove all embedded files from document. |
| [remove(FileSpecification item)](#remove-com.aspose.pdf.FileSpecification-) | Removes specified FileSpecification from collection. |
| [contains(FileSpecification item)](#contains-com.aspose.pdf.FileSpecification-) | Determines if collection contains specified FileSpecification. |
| [clear()](#clear--) | Remove all embedded files from document. |
| [get_Item(int index)](#get-Item-int-) | Gets embedded file by its index. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets embedded file by its name. |
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Gets a value indicating whether access to this collection is synchronized (thread safe).

**Returns:**
boolean - boolean value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Gets an object that can be used to synchronize access to this collection.

**Returns:**
java.lang.Object - Object for synchronization
### size() {#size--}
```
public int size()
```


Gets number of embedded files in collection.

**Returns:**
int - int value
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Determines if collection is read only. Always returns false.

**Returns:**
boolean - boolean value
### copyTo(FileSpecification[] array, int index) {#copyTo-com.aspose.pdf.FileSpecification---int-}
```
public void copyTo(FileSpecification[] array, int index)
```


Copies array of FileSpecification object into colleciton.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [FileSpecification\[\]](../../com.aspose.pdf/filespecification) | Array of objects which will be copied. |
| index | int | Starting index from which copying will be started. |

### iterator() {#iterator--}
```
public System.Collections.IEnumerator<FileSpecification> iterator()
```


Returns colleciton enumerator.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator<com.aspose.pdf.FileSpecification> - Enumerator of colleciton.
### iterator_Rename_Namesake() {#iterator-Rename-Namesake--}
```
public System.Collections.Generic.IGenericEnumerator<FileSpecification> iterator_Rename_Namesake()
```


Returns colleciton enumerator.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.pdf.FileSpecification> - Enumerator of colleciton.
### isEmbeddedFilesExist() {#isEmbeddedFilesExist--}
```
public boolean isEmbeddedFilesExist()
```


Check is Embedded Files structure exists. Return TRUE if structure exists, and FALSE if not. If document have never contained embedded files - this structure was not created and absent.

**Returns:**
boolean - boolean value
### add(FileSpecification file) {#add-com.aspose.pdf.FileSpecification-}
```
public void add(FileSpecification file)
```


Adds embedded file specification into collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | [FileSpecification](../../com.aspose.pdf/filespecification) | FileSpecification which should be added into colleciton. |

### add(String key, FileSpecification file) {#add-java.lang.String-com.aspose.pdf.FileSpecification-}
```
public void add(String key, FileSpecification file)
```


Adds file to embedded files with the specified key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key in the embedded files. |
| file | [FileSpecification](../../com.aspose.pdf/filespecification) | File specification. |

### deleteByKey(String key) {#deleteByKey-java.lang.String-}
```
public void deleteByKey(String key)
```


Deletes file from the collection by its key in the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | String object Key name. |

### getKeys() {#getKeys--}
```
public final List<String> getKeys()
```


Returns list of file attachment keys.

**Returns:**
java.util.List<java.lang.String> - List of String values
### findByName(String name) {#findByName-java.lang.String-}
```
public final FileSpecification findByName(String name)
```


Returns embedded file by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the file. |

**Returns:**
[FileSpecification](../../com.aspose.pdf/filespecification) - FileSpecification instance File specification object if found; otherwise, null.
### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


Delete embedded file by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the embedded file which should be deleted. |

### delete() {#delete--}
```
public void delete()
```


Remove all embedded files from document.

### remove(FileSpecification item) {#remove-com.aspose.pdf.FileSpecification-}
```
public boolean remove(FileSpecification item)
```


Removes specified FileSpecification from collection. Not supported.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [FileSpecification](../../com.aspose.pdf/filespecification) | FileSpecification instance |

**Returns:**
boolean - boolean value
### contains(FileSpecification item) {#contains-com.aspose.pdf.FileSpecification-}
```
public boolean contains(FileSpecification item)
```


Determines if collection contains specified FileSpecification. Not supported.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [FileSpecification](../../com.aspose.pdf/filespecification) | FileSpecification instance |

**Returns:**
boolean - boolean value
### clear() {#clear--}
```
public void clear()
```


Remove all embedded files from document.

### get_Item(int index) {#get-Item-int-}
```
public FileSpecification get_Item(int index)
```


Gets embedded file by its index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of embedded file. Numbering is started from 1. |

**Returns:**
[FileSpecification](../../com.aspose.pdf/filespecification) - Retreived embedded file specification
### get_Item(String name) {#get-Item-java.lang.String-}
```
public FileSpecification get_Item(String name)
```


Gets embedded file by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Embedded file name. |

**Returns:**
[FileSpecification](../../com.aspose.pdf/filespecification) - Retreived embedded file specification.
