---
title: JpegDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that helps to save pdf document pages into jpeg.
type: docs
weight: 20
url: /java/com.aspose.pdf.devices/jpegdevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice), [com.aspose.pdf.devices.ImageDevice](../../com.aspose.pdf.devices/imagedevice)
```
public final class JpegDevice extends ImageDevice
```

Represents image device that helps to save pdf document pages into jpeg.
## Constructors

| Constructor | Description |
| --- | --- |
| [JpegDevice()](#JpegDevice--) | Initializes a new instance of the  JpegDevice  class with default resolution and maximum quality. |
| [JpegDevice(Resolution resolution)](#JpegDevice-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  JpegDevice  class. |
| [JpegDevice(int quality)](#JpegDevice-int-) | Initializes a new instance of the  JpegDevice  class. |
| [JpegDevice(Resolution resolution, int quality)](#JpegDevice-com.aspose.pdf.devices.Resolution-int-) | Initializes a new instance of the  JpegDevice  class. |
| [JpegDevice(int width, int height)](#JpegDevice-int-int-) | Initializes a new instance of the  JpegDevice  class with provided image dimensions, default resolution (=150) and maximum quality. |
| [JpegDevice(PageSize pageSize)](#JpegDevice-com.aspose.pdf.PageSize-) | Initializes a new instance of the  JpegDevice  class with provided page size, default resolution (=150) and maximum quality. |
| [JpegDevice(int width, int height, Resolution resolution)](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  JpegDevice  class with provided image dimensions, resolution and maximum quality. |
| [JpegDevice(PageSize pageSize, Resolution resolution)](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  JpegDevice  class with provided page size, resolution and maximum quality. |
| [JpegDevice(int width, int height, Resolution resolution, int quality)](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-) | Initializes a new instance of the  JpegDevice  class with provided image dimensions, resolution and quality. |
| [JpegDevice(PageSize pageSize, Resolution resolution, int quality)](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-) | Initializes a new instance of the  JpegDevice  class with provided page size, resolution and quality. |
## Methods

| Method | Description |
| --- | --- |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converts the page into jpeg and saves it in the output stream. |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converts the page into jpeg and saves it in the output stream. |
### JpegDevice() {#JpegDevice--}
```
public JpegDevice()
```


Initializes a new instance of the  JpegDevice  class with default resolution and maximum quality.

### JpegDevice(Resolution resolution) {#JpegDevice-com.aspose.pdf.devices.Resolution-}
```
public JpegDevice(Resolution resolution)
```


Initializes a new instance of the  JpegDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### JpegDevice(int quality) {#JpegDevice-int-}
```
public JpegDevice(int quality)
```


Initializes a new instance of the  JpegDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| quality | int | Specifies the level of compression for an image. The range of useful values for the quality is from 0 to 100. The lower the number specified, the higher the compression and therefore the lower the quality of the image. Zero would give you the lowest quality image and 100 the highest. |

### JpegDevice(Resolution resolution, int quality) {#JpegDevice-com.aspose.pdf.devices.Resolution-int-}
```
public JpegDevice(Resolution resolution, int quality)
```


Initializes a new instance of the  JpegDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |
| quality | int | Specifies the level of compression for an image. The range of useful values for the quality is from 0 to 100. The lower the number specified, the higher the compression and therefore the lower the quality of the image. Zero would give you the lowest quality image and 100 the highest. |

### JpegDevice(int width, int height) {#JpegDevice-int-int-}
```
public JpegDevice(int width, int height)
```


Initializes a new instance of the  JpegDevice  class with provided image dimensions, default resolution (=150) and maximum quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |

### JpegDevice(PageSize pageSize) {#JpegDevice-com.aspose.pdf.PageSize-}
```
public JpegDevice(PageSize pageSize)
```


Initializes a new instance of the  JpegDevice  class with provided page size, default resolution (=150) and maximum quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |

### JpegDevice(int width, int height, Resolution resolution) {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-}
```
public JpegDevice(int width, int height, Resolution resolution)
```


Initializes a new instance of the  JpegDevice  class with provided image dimensions, resolution and maximum quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### JpegDevice(PageSize pageSize, Resolution resolution) {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
```
public JpegDevice(PageSize pageSize, Resolution resolution)
```


Initializes a new instance of the  JpegDevice  class with provided page size, resolution and maximum quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### JpegDevice(int width, int height, Resolution resolution, int quality) {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-}
```
public JpegDevice(int width, int height, Resolution resolution, int quality)
```


Initializes a new instance of the  JpegDevice  class with provided image dimensions, resolution and quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |
| quality | int | Specifies the level of compression for an image. The range of useful values for the quality is from 0 to 100. The lower the number specified, the higher the compression and therefore the lower the quality of the image. Zero would give you the lowest quality image and 100 the highest. |

### JpegDevice(PageSize pageSize, Resolution resolution, int quality) {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-}
```
public JpegDevice(PageSize pageSize, Resolution resolution, int quality)
```


Initializes a new instance of the  JpegDevice  class with provided page size, resolution and quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |
| quality | int | Specifies the level of compression for an image. The range of useful values for the quality is from 0 to 100. The lower the number specified, the higher the compression and therefore the lower the quality of the image. Zero would give you the lowest quality image and 100 the highest. |

### processInternal(Page page, System.IO.Stream output) {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(Page page, System.IO.Stream output)
```


Converts the page into jpeg and saves it in the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | com.aspose.ms.System.IO.Stream | Output stream with jpeg image. |

### process(Page page, OutputStream output) {#process-com.aspose.pdf.Page-java.io.OutputStream-}
```
public void process(Page page, OutputStream output)
```


Converts the page into jpeg and saves it in the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | java.io.OutputStream | Output stream with jpeg image. |

