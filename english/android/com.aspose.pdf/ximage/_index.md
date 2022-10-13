---
title: XImage
second_title: Aspose.PDF for Java API Reference
description: Class representing image X-Object.
type: docs
weight: 325
url: /java/com.aspose.pdf/ximage/
---
**Inheritance:**
java.lang.Object
```
public final class XImage
```

Class representing image X-Object.
## Constructors

| Constructor | Description |
| --- | --- |
| [XImage(IPdfDataStream image)](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getGrayscaled()](#getGrayscaled--) | Gets grayscaled version of image. |
| [delete()](#delete--) | Deletes image from the parent collection. |
| [replace(InputStream image)](#replace-java.io.InputStream-) | Replaces image onto stream specified in  image . |
| [getEngineImg()](#getEngineImg--) |  |
| [getWidth()](#getWidth--) | Gets width of the image. |
| [getHeight()](#getHeight--) | Gets height of the image. |
| [getName()](#getName--) | Gets or sets image name. |
| [setName(String value)](#setName-java.lang.String-) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) |  |
| [save(OutputStream stream, ImageType format)](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) |  |
| [getImage()](#getImage--) |  |
| [saveInternal(System.IO.Stream stream, int resolution)](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | Saves image data into stream as JPEG image with specified resolution. |
| [save(OutputStream stream, int resolution)](#save-java.io.OutputStream-int-) | Saves image into stream with requested format with specified resolution. |
| [saveInternal(System.IO.Stream stream, ImageType format, int resolution)](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [save(OutputStream stream, ImageType format, int resolution)](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) |  |
| [isImage(IPdfPrimitive primitive)](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | Returns true if the primitive is an image. |
### XImage(IPdfDataStream image) {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
```
public XImage(IPdfDataStream image)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [IPdfDataStream](../../com.aspose.pdf.engine.data/ipdfdatastream) |  |

### getGrayscaled() {#getGrayscaled--}
```
public System.Drawing.Image getGrayscaled()
```


Gets grayscaled version of image.

**Returns:**
[Image](../../com.aspose.ms.system.drawing/image)
### delete() {#delete--}
```
public void delete()
```


Deletes image from the parent collection.

### replace(InputStream image) {#replace-java.io.InputStream-}
```
public void replace(InputStream image)
```


Replaces image onto stream specified in  image .

\*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.io.InputStream | Stream with image data. |

### getEngineImg() {#getEngineImg--}
```
public IPdfDataStream getEngineImg()
```




**Returns:**
[IPdfDataStream](../../com.aspose.pdf.engine.data/ipdfdatastream)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets width of the image.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets height of the image.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Gets or sets image name.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |

### save(OutputStream stream, ImageType format) {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
```
public void save(OutputStream stream, ImageType format)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| format | [ImageType](../../com.aspose.pdf/imagetype) |  |

### getImage() {#getImage--}
```
public System.Drawing.Image getImage()
```




**Returns:**
[Image](../../com.aspose.ms.system.drawing/image)
### saveInternal(System.IO.Stream stream, int resolution) {#saveInternal-com.aspose.ms.System.IO.Stream-int-}
```
public void saveInternal(System.IO.Stream stream, int resolution)
```


Saves image data into stream as JPEG image with specified resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Stream where image data will be saved. |
| resolution | int | Image resolution |

### save(OutputStream stream, int resolution) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream stream, int resolution)
```


Saves image into stream with requested format with specified resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream where image will be saved |
| resolution | int | Image resolution |

### saveInternal(System.IO.Stream stream, ImageType format, int resolution) {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-}
```
public void saveInternal(System.IO.Stream stream, ImageType format, int resolution)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| format | [ImageType](../../com.aspose.pdf/imagetype) |  |
| resolution | int |  |

### save(OutputStream stream, ImageType format, int resolution) {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
```
public void save(OutputStream stream, ImageType format, int resolution)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream |  |
| format | [ImageType](../../com.aspose.pdf/imagetype) |  |
| resolution | int |  |

### isImage(IPdfPrimitive primitive) {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public static boolean isImage(IPdfPrimitive primitive)
```


Returns true if the primitive is an image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| primitive | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |

**Returns:**
boolean
