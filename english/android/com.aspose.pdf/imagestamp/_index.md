---
title: ImageStamp
second_title: Aspose.PDF for Java API Reference
description: Reresents graphic stamp.
type: docs
weight: 147
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
| [ImageStamp(System.IO.Stream image)](#ImageStamp-com.aspose.ms.System.IO.Stream-) | Initializes a new instance of the  ImageStamp  class. |
| [ImageStamp(InputStream image)](#ImageStamp-java.io.InputStream-) |  |
| [ImageStamp(String fileName)](#ImageStamp-java.lang.String-) | Creates image stamp by image in the specified file. |
## Methods

| Method | Description |
| --- | --- |
| [getImage()](#getImage--) |  |
| [getWidth()](#getWidth--) | Gets image width. |
| [setWidth(double value)](#setWidth-double-) | Sets image width. |
| [getHeight()](#getHeight--) | Gets image height. |
| [setHeight(double value)](#setHeight-double-) |  |
| [put(Page page)](#put-com.aspose.pdf.Page-) | Adds graphic stamp on the page. |
| [close()](#close--) |  |
### ImageStamp(System.IO.Stream image) {#ImageStamp-com.aspose.ms.System.IO.Stream-}
```
public ImageStamp(System.IO.Stream image)
```


Initializes a new instance of the  ImageStamp  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | com.aspose.ms.System.IO.Stream | Stream which contains image data. |

### ImageStamp(InputStream image) {#ImageStamp-java.io.InputStream-}
```
public ImageStamp(InputStream image)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.io.InputStream |  |

### ImageStamp(String fileName) {#ImageStamp-java.lang.String-}
```
public ImageStamp(String fileName)
```


Creates image stamp by image in the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String |  |

### getImage() {#getImage--}
```
public InputStream getImage()
```




**Returns:**
java.io.InputStream
### getWidth() {#getWidth--}
```
public double getWidth()
```


Gets image width. Setting this property allos to scal image horizontally.

**Returns:**
double
### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


Sets image width. Setting this property allos to scal image horizontally.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getHeight() {#getHeight--}
```
public double getHeight()
```


Gets image height. Setting this image allows to scale image vertically.

**Returns:**
double
### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

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




