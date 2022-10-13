---
title: EmbeddedFileCollection
second_title: Aspose.PDF for Java API Reference
description: Class representing embedded files collection.
type: docs
weight: 83
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
| [iterator()](#iterator--) | Returns colleciton enumerator. |
| [add(FileSpecification file)](#add-com.aspose.pdf.FileSpecification-) | Adds embedded file specification into collection. |
| [add(String key, FileSpecification file)](#add-java.lang.String-com.aspose.pdf.FileSpecification-) | Adds file to embedded files with the specified key. |
| [deleteByKey(String key)](#deleteByKey-java.lang.String-) | Deletes file from the collection by its key in the collection. |
| [delete(String name)](#delete-java.lang.String-) | Delete embedded file by name. |
| [delete()](#delete--) | Remove all embedded files from document. |
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
### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```


Returns colleciton enumerator.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Enumerator of colleciton.
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
| key | java.lang.String | String object |

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
