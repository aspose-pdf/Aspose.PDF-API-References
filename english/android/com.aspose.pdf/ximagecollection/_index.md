---
title: XImageCollection
second_title: Aspose.PDF for Java API Reference
description: Class representing XImage collection.
type: docs
weight: 326
url: /java/com.aspose.pdf/ximagecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.ICollection
```
public final class XImageCollection implements System.Collections.ICollection<XImage>
```

Class representing XImage collection.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Count of images in collection. |
| [isSynchronized()](#isSynchronized--) | Returns true if object is synchronized. |
| [getSyncRoot()](#getSyncRoot--) | Returns synchronization object. |
| [getNames()](#getNames--) | Gets array of image names. |
| [addInternal(System.IO.Stream image)](#addInternal-com.aspose.ms.System.IO.Stream-) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [add(InputStream image)](#add-java.io.InputStream-) |  |
| [delete(int index)](#delete-int-) | Removes index from collection by index. |
| [delete(String name)](#delete-java.lang.String-) | Removes index from collection by name. |
| [delete()](#delete--) | Deletes images from collection. |
| [iterator()](#iterator--) | Returns collection enumerator. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies array of images into collection. |
| [replace(int index, InputStream stream)](#replace-int-java.io.InputStream-) |  |
| [get_Item(int index)](#get-Item-int-) | Gets image from collection by its index. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets image from collection by its name. |
| [hasImage(String imgName)](#hasImage-java.lang.String-) |  |
### size() {#size--}
```
public int size()
```


Count of images in collection.

**Returns:**
int
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Returns true if object is synchronized.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Returns synchronization object.

**Returns:**
java.lang.Object
### getNames() {#getNames--}
```
public String[] getNames()
```


Gets array of image names.

**Returns:**
java.lang.String[]
### addInternal(System.IO.Stream image) {#addInternal-com.aspose.ms.System.IO.Stream-}
```
public void addInternal(System.IO.Stream image)
```


Adds entity to the end of the collection, so entity can be accessed by the last index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | com.aspose.ms.System.IO.Stream |  |

### add(InputStream image) {#add-java.io.InputStream-}
```
public void add(InputStream image)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.io.InputStream |  |

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Removes index from collection by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Image index. |

### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


Removes index from collection by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of image which must to be deleted. |

### delete() {#delete--}
```
public void delete()
```


Deletes images from collection.

### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```


Returns collection enumerator.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Enumerator of collection
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array array, int index)
```


Copies array of images into collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array to be copied. |
| index | int | Index where images will be copied into collection. |

### replace(int index, InputStream stream) {#replace-int-java.io.InputStream-}
```
public void replace(int index, InputStream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| stream | java.io.InputStream |  |

### get_Item(int index) {#get-Item-int-}
```
public XImage get_Item(int index)
```


Gets image from collection by its index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Image index |

**Returns:**
[XImage](../../com.aspose.pdf/ximage) - Retreived image.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public XImage get_Item(String name)
```


Gets image from collection by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Image name. |

**Returns:**
[XImage](../../com.aspose.pdf/ximage) - Retreived image.
### hasImage(String imgName) {#hasImage-java.lang.String-}
```
public boolean hasImage(String imgName)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imgName | java.lang.String |  |

**Returns:**
boolean
