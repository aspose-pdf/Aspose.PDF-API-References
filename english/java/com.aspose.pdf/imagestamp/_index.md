---
title: ImageStamp
second_title: Aspose.PDF for Java API Reference
description: Reresents graphic stamp.
type: docs
weight: 175
url: /java/com.aspose.pdf/imagestamp/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.Stamp](../../com.aspose.pdf/stamp)
```
public final class ImageStamp extends Stamp
```

Reresents graphic stamp.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageStamp(InputStream image)](#ImageStamp-java.io.InputStream-) | Initializes a new instance of the  ImageStamp  class. |
| [ImageStamp(String fileName)](#ImageStamp-java.lang.String-) | Creates image stamp by image in the specified file. |
## Methods

| Method | Description |
| --- | --- |
| [getImage()](#getImage--) | Gets image stream used for stamping. |
| [getWidth()](#getWidth--) | Gets image width. |
| [setWidth(double value)](#setWidth-double-) | Sets image width. |
| [getHeight()](#getHeight--) | Gets image height. |
| [setHeight(double value)](#setHeight-double-) | Sets image height. |
| [getQuality()](#getQuality--) | Gets quality of image stamp in percent. |
| [setQuality(int value)](#setQuality-int-) | Sets quality of image stamp in percent. |
| [put(Page page)](#put-com.aspose.pdf.Page-) | Adds graphic stamp on the page. |
| [close()](#close--) | Closes this instance |
### ImageStamp(InputStream image) {#ImageStamp-java.io.InputStream-}
```
public ImageStamp(InputStream image)
```


Initializes a new instance of the  ImageStamp  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.io.InputStream | Stream which contains image data. |

### ImageStamp(String fileName) {#ImageStamp-java.lang.String-}
```
public ImageStamp(String fileName)
```


Creates image stamp by image in the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file which contains image. |

### getImage() {#getImage--}
```
public InputStream getImage()
```


Gets image stream used for stamping.

**Returns:**
java.io.InputStream - InputStream object
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets image width. Setting this property allos to scal image horizontally.

**Returns:**
double - double value
### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets image width. Setting this property allos to scal image horizontally.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets image height. Setting this image allows to scale image vertically.

**Returns:**
double - double value
### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


Sets image height. Setting this image allows to scale image vertically.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getQuality() {#getQuality--}
```
public int getQuality()
```


Gets quality of image stamp in percent. Valid values are 0..100%.

**Returns:**
int - int value
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Sets quality of image stamp in percent. Valid values are 0..100%.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### put(Page page) {#put-com.aspose.pdf.Page-}
```
public void put(Page page)
```


Adds graphic stamp on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page for stamping. |

### close() {#close--}
```
public void close()
```


Closes this instance

