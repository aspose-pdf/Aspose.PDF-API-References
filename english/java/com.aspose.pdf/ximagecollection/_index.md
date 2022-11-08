---
title: XImageCollection
second_title: Aspose.PDF for Java API Reference
description: Class representing XImage collection.
type: docs
weight: 410
url: /java/com.aspose.pdf/ximagecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class XImageCollection implements Iterable<XImage>
```

Class representing XImage collection.
## Methods

| Method | Description |
| --- | --- |
| [add(XImage image)](#add-com.aspose.pdf.XImage-) | Adds new image to Image list. |
| [add(BufferedImage image)](#add-java.awt.image.BufferedImage-) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [add(InputStream image)](#add-java.io.InputStream-) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [add(InputStream image, int quality)](#add-java.io.InputStream-int-) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [addWithImageFilterType(InputStream image, int filterType)](#addWithImageFilterType-java.io.InputStream-int-) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [clear()](#clear--) | Clears all items from the collection. |
| [contains(XImage item)](#contains-com.aspose.pdf.XImage-) | Determines whether the collection contains a specific value. |
| [copyTo(XImage[] array, int index)](#copyTo-com.aspose.pdf.XImage---int-) | Copies array of images into collection. |
| [delete()](#delete--) | Deletes images from collection. |
| [delete(int index)](#delete-int-) | Removes index from collection by index. |
| [delete(int index, int action)](#delete-int-int-) | Removes index from collection by index performing action specified by action parameter. |
| [delete(String name)](#delete-java.lang.String-) | Removes item from collection by name. |
| [delete(String name, int action)](#delete-java.lang.String-int-) | Removes item from collection by name. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getImageName(XImage image)](#getImageName-com.aspose.pdf.XImage-) | Returns name in images list which is key of the given image. |
| [getNames()](#getNames--) | Gets array of image names. |
| [getSyncRoot()](#getSyncRoot--) | Returns synchronization object. |
| [get_Item(int index)](#get-Item-int-) | Gets image from collection by its index. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets image from collection by its name. |
| [hasImage(String imgName)](#hasImage-java.lang.String-) |  |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the collection is read-only. |
| [isSynchronized()](#isSynchronized--) | Returns true if object is synchronized. |
| [iterator()](#iterator--) | Returns collection enumerator. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(XImage item)](#remove-com.aspose.pdf.XImage-) | Not supported yet, throws exception. |
| [replace(int index, InputStream stream)](#replace-int-java.io.InputStream-) | Replace image in collection with another image. |
| [replace(int index, InputStream stream, int quality)](#replace-int-java.io.InputStream-int-) | Replace image in collection with another image. |
| [replace(int index, InputStream stream, int quality, boolean isBlackAndWhite)](#replace-int-java.io.InputStream-int-boolean-) | Replace image in collection with another image. |
| [size()](#size--) | Count of images in collection. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### add(XImage image) {#add-com.aspose.pdf.XImage-}
```
public String add(XImage image)
```


Adds new image to Image list. This method adds image as reference to the same PdfObject (which allows to decrease file size)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [XImage](../../com.aspose.pdf/ximage) | XImage to be added. |

**Returns:**
java.lang.String - Name of the added image.
### add(BufferedImage image) {#add-java.awt.image.BufferedImage-}
```
public String add(BufferedImage image)
```


Adds entity to the end of the collection, so entity can be accessed by the last index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | BufferedImage containing image data. |

**Returns:**
java.lang.String - Name of the added image.
### add(InputStream image) {#add-java.io.InputStream-}
```
public String add(InputStream image)
```


Adds entity to the end of the collection, so entity can be accessed by the last index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.io.InputStream | Stream containing image data (in JPEG format). |

**Returns:**
java.lang.String - Name of the added image.
### add(InputStream image, int quality) {#add-java.io.InputStream-int-}
```
public String add(InputStream image, int quality)
```


Adds entity to the end of the collection, so entity can be accessed by the last index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.io.InputStream | Stream containing image data (in JPEG format). |
| quality | int | JPEG quality. |

**Returns:**
java.lang.String - Name of the added image.
### addWithImageFilterType(InputStream image, int filterType) {#addWithImageFilterType-java.io.InputStream-int-}
```
public String addWithImageFilterType(InputStream image, int filterType)
```


Adds entity to the end of the collection, so entity can be accessed by the last index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.io.InputStream | Stream containing image data. |
| filterType | int | The image filter type. |

**Returns:**
java.lang.String - Name of the added image.
### clear() {#clear--}
```
public void clear()
```


Clears all items from the collection.

### contains(XImage item) {#contains-com.aspose.pdf.XImage-}
```
public boolean contains(XImage item)
```


Determines whether the collection contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [XImage](../../com.aspose.pdf/ximage) | The object to locate in the collection |

**Returns:**
boolean - true if item is found in the collection; otherwise, false.
### copyTo(XImage[] array, int index) {#copyTo-com.aspose.pdf.XImage---int-}
```
public void copyTo(XImage[] array, int index)
```


Copies array of images into collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [XImage\[\]](../../com.aspose.pdf/ximage) | Array to be copied. |
| index | int | Index where images will be copied into collection. |

### delete() {#delete--}
```
public void delete()
```


Deletes images from collection.

### delete(int index) {#delete-int-}
```
public void delete(int index)
```


Removes index from collection by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Image index. |

### delete(int index, int action) {#delete-int-int-}
```
public final void delete(int index, int action)
```


Removes index from collection by index performing action specified by action parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the image to be removed. |
| action | int | ImageDeleteAction element. Action performed after image deleting. |

### delete(String name) {#delete-java.lang.String-}
```
public void delete(String name)
```


Removes item from collection by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of image which must to be deleted. |

### delete(String name, int action) {#delete-java.lang.String-int-}
```
public final void delete(String name, int action)
```


Removes item from collection by name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of image which must to be deleted. |
| action | int | Action to be performed with image object. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getImageName(XImage image) {#getImageName-com.aspose.pdf.XImage-}
```
public String getImageName(XImage image)
```


Returns name in images list which is key of the given image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [XImage](../../com.aspose.pdf/ximage) | Image to search. |

**Returns:**
java.lang.String - Name (key) of the found image; null if images was not found.
### getNames() {#getNames--}
```
public String[] getNames()
```


Gets array of image names.

**Returns:**
java.lang.String[] - String[] array
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Returns synchronization object.

**Returns:**
java.lang.Object - Object element
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
[XImage](../../com.aspose.pdf/ximage) - Retrieved image.
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
[XImage](../../com.aspose.pdf/ximage) - Retrieved image.
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Gets a value indicating whether the collection is read-only.

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Returns true if object is synchronized.

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public Iterator<XImage> iterator()
```


Returns collection enumerator.

**Returns:**
java.util.Iterator<com.aspose.pdf.XImage> - Enumerator of collection
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(XImage item) {#remove-com.aspose.pdf.XImage-}
```
public boolean remove(XImage item)
```


Not supported yet, throws exception.

Always throws NotImplementedException

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [XImage](../../com.aspose.pdf/ximage) | XImage instance Item to remove. |

**Returns:**
boolean - boolean value
### replace(int index, InputStream stream) {#replace-int-java.io.InputStream-}
```
public void replace(int index, InputStream stream)
```


Replace image in collection with another image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of collection item which will be replaced. |
| stream | java.io.InputStream | Stream containing image data (in JPEG format). |

### replace(int index, InputStream stream, int quality) {#replace-int-java.io.InputStream-int-}
```
public void replace(int index, InputStream stream, int quality)
```


Replace image in collection with another image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of collection item which will be replaced. |
| stream | java.io.InputStream | Stream containing image data (in JPEG format). |
| quality | int | JPEG quality. |

### replace(int index, InputStream stream, int quality, boolean isBlackAndWhite) {#replace-int-java.io.InputStream-int-boolean-}
```
public final void replace(int index, InputStream stream, int quality, boolean isBlackAndWhite)
```


Replace image in collection with another image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of collection item which will be replaced. |
| stream | java.io.InputStream | Stream containing image data (in JPEG format). |
| quality | int | Quality of JPEG compression, in percent (valid vaues are 0..100). |
| isBlackAndWhite | boolean | If true, image is compressed with CCITT compression method which provides better compression for black nad white image. May be used only for black and white images. |

### size() {#size--}
```
public int size()
```


Count of images in collection.

**Returns:**
int - int value
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

