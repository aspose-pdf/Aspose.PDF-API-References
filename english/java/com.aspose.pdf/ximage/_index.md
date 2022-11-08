---
title: XImage
second_title: Aspose.PDF for Java API Reference
description: Class representing image X-Object.
type: docs
weight: 409
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
| [XImage(IPdfDataStream image)](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) | for internal usage only |
## Methods

| Method | Description |
| --- | --- |
| [containsTransparency()](#containsTransparency--) | If the image contains transparancy than return true; otherwise, false. |
| [delete()](#delete--) | Deletes image from the parent collection. |
| [detectColorType(BufferedImage bmp)](#detectColorType-java.awt.image.BufferedImage-) | Returns color type of image. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Returns color type of image. |
| [getEngineImg()](#getEngineImg--) | IPdfImage object which decribes image. |
| [getFilterType()](#getFilterType--) | Gets image filter type. |
| [getGrayscaled()](#getGrayscaled--) | Gets grayscaled version of image. |
| [getHeight()](#getHeight--) | Gets height of the image. |
| [getImage()](#getImage--) | For internal use only |
| [getMetadata()](#getMetadata--) | Metadata of the image. |
| [getName()](#getName--) | Gets image name. |
| [getNameInCollection()](#getNameInCollection--) | Returns name of the image in its collection. |
| [getRawBytes()](#getRawBytes--) | Returns raw bytes for the image without decoding. |
| [getRawParameters()](#getRawParameters--) | Gets raw image parameters |
| [getWidth()](#getWidth--) | Gets width of the image. |
| [hashCode()](#hashCode--) |  |
| [isImage(IPdfPrimitive primitive)](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | Returns true if the primitive is an image. |
| [isTheSameObject(XImage image)](#isTheSameObject-com.aspose.pdf.XImage-) | Returns true if both images references to the same object. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [rename(String name)](#rename-java.lang.String-) | Renames image and replaces all references to the image with the new name |
| [replace(InputStream image)](#replace-java.io.InputStream-) | Replaces image onto stream specified in  image . |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves image data into stream as JPEG image. |
| [save(OutputStream stream, ImageType format)](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Saves image into stream with requested format. |
| [save(OutputStream stream, ImageType format, int resolution)](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Saves image into stream with requested format. |
| [save(OutputStream stream, float xDpi, float yDpi)](#save-java.io.OutputStream-float-float-) | Saves image into stream with requested format. |
| [save(OutputStream stream, int resolution)](#save-java.io.OutputStream-int-) | Saves image into stream with requested format with specified resolution. |
| [saveInternal(System.IO.Stream stream, ImageType format, int resolution)](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [saveInternal(System.IO.Stream stream, int resolution)](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | Saves image data into stream as JPEG image with specified resolution. |
| [setName(String value)](#setName-java.lang.String-) | Sets image name. |
| [toStream()](#toStream--) | Returns the original image stream. |
| [toString()](#toString--) | Returns a string representation XImage object properties. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XImage(IPdfDataStream image) {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
```
public XImage(IPdfDataStream image)
```


for internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [IPdfDataStream](../../com.aspose.pdf.engine.data/ipdfdatastream) | internal instance |

### containsTransparency() {#containsTransparency--}
```
public boolean containsTransparency()
```


If the image contains transparancy than return true; otherwise, false.

**Returns:**
boolean - boolean value
### delete() {#delete--}
```
public void delete()
```


Deletes image from the parent collection.

### detectColorType(BufferedImage bmp) {#detectColorType-java.awt.image.BufferedImage-}
```
public static int detectColorType(BufferedImage bmp)
```


Returns color type of image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| bmp | java.awt.image.BufferedImage | Image. |

**Returns:**
int - Color type.
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
### getColorType() {#getColorType--}
```
public int getColorType()
```


Returns color type of image.

**Returns:**
int - The color type value.
### getEngineImg() {#getEngineImg--}
```
public IPdfDataStream getEngineImg()
```


IPdfImage object which decribes image. Internal only

**Returns:**
[IPdfDataStream](../../com.aspose.pdf.engine.data/ipdfdatastream) - IPdfDataStream
### getFilterType() {#getFilterType--}
```
public final int getFilterType()
```


Gets image filter type.

**Returns:**
int - ImageFilterType element
### getGrayscaled() {#getGrayscaled--}
```
public BufferedImage getGrayscaled()
```


Gets grayscaled version of image.

**Returns:**
java.awt.image.BufferedImage - BufferedImage
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets height of the image.

**Returns:**
int - int value
### getImage() {#getImage--}
```
public System.Drawing.Bitmap getImage()
```


For internal use only

**Returns:**
com.aspose.ms.System.Drawing.Bitmap - Image
### getMetadata() {#getMetadata--}
```
public final Metadata getMetadata()
```


Metadata of the image.

**Returns:**
[Metadata](../../com.aspose.pdf/metadata) - Metadata instance
### getName() {#getName--}
```
public String getName()
```


Gets image name. Please note that if you change name of the image which has references in page contents, document may became incorrect. Please use XImage.Rename method in this case.

**Returns:**
java.lang.String - String
### getNameInCollection() {#getNameInCollection--}
```
public String getNameInCollection()
```


Returns name of the image in its collection.

**Returns:**
java.lang.String - Image key (name).
### getRawBytes() {#getRawBytes--}
```
public byte[] getRawBytes()
```


Returns raw bytes for the image without decoding.

**Returns:**
byte[] - byte array
### getRawParameters() {#getRawParameters--}
```
public XImage.RawParameters getRawParameters()
```


Gets raw image parameters

**Returns:**
[RawParameters](../../com.aspose.pdf/rawparameters) - RawParameters instance
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets width of the image.

**Returns:**
int - int value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isImage(IPdfPrimitive primitive) {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public static boolean isImage(IPdfPrimitive primitive)
```


Returns true if the primitive is an image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| primitive | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) | IPdfPrimitive |

**Returns:**
boolean - boolean
### isTheSameObject(XImage image) {#isTheSameObject-com.aspose.pdf.XImage-}
```
public boolean isTheSameObject(XImage image)
```


Returns true if both images references to the same object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [XImage](../../com.aspose.pdf/ximage) | Image to be compared with "this" image. |

**Returns:**
boolean - Boolean value which is true if images references to the same object.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### rename(String name) {#rename-java.lang.String-}
```
public final void rename(String name)
```


Renames image and replaces all references to the image with the new name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | New image name. |

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

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Saves image data into stream as JPEG image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream where image data will be saved. |

### save(OutputStream stream, ImageType format) {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
```
public void save(OutputStream stream, ImageType format)
```


Saves image into stream with requested format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream where image will be saved |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Format which will be used for image enconding. |

### save(OutputStream stream, ImageType format, int resolution) {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
```
public void save(OutputStream stream, ImageType format, int resolution)
```


Saves image into stream with requested format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream where image will be saved |
| format | [ImageType](../../com.aspose.pdf/imagetype) | Format which will be used for image enconding. |
| resolution | int | Image resolution |

### save(OutputStream stream, float xDpi, float yDpi) {#save-java.io.OutputStream-float-float-}
```
public void save(OutputStream stream, float xDpi, float yDpi)
```


Saves image into stream with requested format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | OutputStream where image will be saved |
| xDpi | float | Image horizontal resolution |
| yDpi | float | Image vertical resolution |

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

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Sets image name. Please note that if you change name of the image which has references in page contents, document may became incorrect. Please use XImage.Rename method in this case.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### toStream() {#toStream--}
```
public InputStream toStream()
```


Returns the original image stream.

**Returns:**
java.io.InputStream - The original image stream.
### toString() {#toString--}
```
public String toString()
```


Returns a string representation XImage object properties.

**Returns:**
java.lang.String - String instance
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

