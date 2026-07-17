---
title: XImageCollection
linktitle: XImageCollection
second_title: Aspose.PDF for Java API Reference
description: Class representing XImage collection.
type: docs
weight: 5630
url: /java/com.aspose.pdf/ximagecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImageCollection

**All Implemented Interfaces:**
Iterable < XImage >

```
public final class XImageCollection extends Object implements Iterable < XImage >
```

Class representing XImage collection.

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.BitmapInfo-) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [add](#add-com.aspose.pdf.BitmapInfo-com.aspose.pdf.ImageFilterType-) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [add](#add-java.awt.image.BufferedImage-) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [add](#add-java.awt.image.BufferedImage-com.aspose.pdf.ImageFilterType-) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [add](#add-java.io.InputStream-) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [add](#add-java.io.InputStream-com.aspose.pdf.ImageFilterType-) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [add](#add-java.io.InputStream-int-) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [add](#add-com.aspose.pdf.XImage-) | Adds new image to Image list. This method adds image as reference to the same PdfObject (which allows to decrease file size) |
| [add](#add-com.aspose.pdf.engine.XImageAddingParams-java.lang.String:A-) |  |
| [addWithImageFilterType](#addWithImageFilterType-java.io.InputStream-com.aspose.pdf.ImageFilterType-) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [clear](#clear--) | Clears all items from the collection. |
| [contains](#contains-com.aspose.pdf.XImage-) | Determines whether the collection contains a specific value. |
| [copyTo](#copyTo-com.aspose.pdf.XImage:A-int-) | Copies array of images into collection. |
| [delete](#delete--) | Deletes images from collection. |
| [delete](#delete-int-) | Removes index from collection by index. |
| [delete](#delete-int-int-) | Removes index from collection by index performing action specified by action parameter. |
| [delete](#delete-java.lang.String-) | Deletes images from collection. |
| [delete](#delete-java.lang.String-int-) | Deletes images from collection. |
| [get_Item](#get_Item-int-) | Gets image from collection by its index. |
| [get_Item](#get_Item-java.lang.String-) | Gets image from collection by its name. |
| [getImageName](#getImageName-com.aspose.pdf.XImage-) | Returns name in images list which is key of the given image. |
| [getNames](#getNames--) | Gets array of image names. |
| [getSyncRoot](#getSyncRoot--) | Returns synchronization object. |
| [hasImage](#hasImage-java.lang.String-) |  |
| [isReadOnly](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [isSynchronized](#isSynchronized--) | Returns true if object is synchronized. |
| [iterator](#iterator--) | Returns collection enumerator. |
| [remove](#remove-com.aspose.pdf.XImage-) | Not supported yet, throws exception. Always throws NotImplementedException |
| [replace](#replace-int-java.io.InputStream-) | Replace image in collection with another image. |
| [replace](#replace-int-java.io.InputStream-int-) | Replace image in collection with another image. |
| [replace](#replace-int-java.io.InputStream-int-boolean-) | Replace image in collection with another image. |
| [saveJpxWithQuality](#saveJpxWithQuality-com.aspose.ms.System.Drawing.Image-) |  |
| [size](#size--) | Count of images in collection. |

### add {#add-com.aspose.pdf.BitmapInfo-}
Adds entity to the end of the collection, so entity can be accessed by the last index.

### add {#add-com.aspose.pdf.BitmapInfo-com.aspose.pdf.ImageFilterType-}
Adds entity to the end of the collection, so entity can be accessed by the last index.

### add {#add-java.awt.image.BufferedImage-}
Adds entity to the end of the collection, so entity can be accessed by the last index.

### add {#add-java.awt.image.BufferedImage-com.aspose.pdf.ImageFilterType-}
Adds entity to the end of the collection, so entity can be accessed by the last index.

### add {#add-java.io.InputStream-}
Adds entity to the end of the collection, so entity can be accessed by the last index.

### add {#add-java.io.InputStream-com.aspose.pdf.ImageFilterType-}
Adds entity to the end of the collection, so entity can be accessed by the last index.

### add {#add-java.io.InputStream-int-}
Adds entity to the end of the collection, so entity can be accessed by the last index.

### add {#add-com.aspose.pdf.XImage-}
Adds new image to Image list. This method adds image as reference to the same PdfObject (which allows to decrease file size)

### add {#add-com.aspose.pdf.engine.XImageAddingParams-java.lang.String:A-}


### addWithImageFilterType {#addWithImageFilterType-java.io.InputStream-com.aspose.pdf.ImageFilterType-}
Adds entity to the end of the collection, so entity can be accessed by the last index.

### clear {#clear--}
```
public void clear()
```

Clears all items from the collection.

### contains {#contains-com.aspose.pdf.XImage-}
Determines whether the collection contains a specific value.

### copyTo {#copyTo-com.aspose.pdf.XImage:A-int-}
Copies array of images into collection.

### delete {#delete--}
```
public void delete()
```

Deletes images from collection.

### delete {#delete-int-}
```
public void delete(int index)
```

Removes index from collection by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Image index. |

### delete {#delete-int-int-}
```
public final void delete(int index, int action)
```

Removes index from collection by index performing action specified by action parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of the image to be removed. |
| action |  | ImageDeleteAction element. Action performed after image deleting. |

### delete {#delete-java.lang.String-}
Deletes images from collection.

### delete {#delete-java.lang.String-int-}
Deletes images from collection.

### get_Item {#get_Item-int-}
```
public XImage get_Item(int index)
```

Gets image from collection by its index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Image index |

**Returns:**
Retrieved image.

### get_Item {#get_Item-java.lang.String-}
Gets image from collection by its name.

### getImageName {#getImageName-com.aspose.pdf.XImage-}
Returns name in images list which is key of the given image.

### getNames {#getNames--}
```
public String [] getNames()
```

Gets array of image names.

**Returns:**
String[] array

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Returns synchronization object.

**Returns:**
Object element

### hasImage {#hasImage-java.lang.String-}


### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Gets a value indicating whether the collection is read-only.

**Returns:**
boolean value

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Returns true if object is synchronized.

**Returns:**
boolean value

### iterator {#iterator--}
```
public Iterator < XImage > iterator()
```

Returns collection enumerator.

**Returns:**
Enumerator of collection

### remove {#remove-com.aspose.pdf.XImage-}
Not supported yet, throws exception. Always throws NotImplementedException

### replace {#replace-int-java.io.InputStream-}
Replace image in collection with another image.

### replace {#replace-int-java.io.InputStream-int-}
Replace image in collection with another image.

### replace {#replace-int-java.io.InputStream-int-boolean-}
Replace image in collection with another image.

### saveJpxWithQuality {#saveJpxWithQuality-com.aspose.ms.System.Drawing.Image-}


### size {#size--}
```
public int size()
```

Count of images in collection.

**Returns:**
int value
