---
title: GifDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that helps to save pdf document pages into gif.
type: docs
weight: 18
url: /java/com.aspose.pdf.devices/gifdevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice), [com.aspose.pdf.devices.ImageDevice](../../com.aspose.pdf.devices/imagedevice)
```
public final class GifDevice extends ImageDevice
```

Represents image device that helps to save pdf document pages into gif.
## Constructors

| Constructor | Description |
| --- | --- |
| [GifDevice()](#GifDevice--) | Initializes a new instance of the  GifDevice  class with default resolution. |
| [GifDevice(Resolution resolution)](#GifDevice-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  GifDevice  class. |
| [GifDevice(int width, int height, Resolution resolution)](#GifDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  GifDevice  class with provided image dimensions and resolution. |
| [GifDevice(PageSize pageSize, Resolution resolution)](#GifDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  GifDevice  class with provided page size and resolution. |
| [GifDevice(int width, int height)](#GifDevice-int-int-) | Initializes a new instance of the  GifDevice  class with provided image dimensions, default resolution (=150). |
| [GifDevice(PageSize pageSize)](#GifDevice-com.aspose.pdf.PageSize-) | Initializes a new instance of the  GifDevice  class with provided page size, default resolution (=150). |
## Methods

| Method | Description |
| --- | --- |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converts the page into gif and saves it in the output stream. |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converts the page into gif and saves it in the output stream. |
### GifDevice() {#GifDevice--}
```
public GifDevice()
```


Initializes a new instance of the  GifDevice  class with default resolution.

### GifDevice(Resolution resolution) {#GifDevice-com.aspose.pdf.devices.Resolution-}
```
public GifDevice(Resolution resolution)
```


Initializes a new instance of the  GifDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### GifDevice(int width, int height, Resolution resolution) {#GifDevice-int-int-com.aspose.pdf.devices.Resolution-}
```
public GifDevice(int width, int height, Resolution resolution)
```


Initializes a new instance of the  GifDevice  class with provided image dimensions and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### GifDevice(PageSize pageSize, Resolution resolution) {#GifDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
```
public GifDevice(PageSize pageSize, Resolution resolution)
```


Initializes a new instance of the  GifDevice  class with provided page size and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### GifDevice(int width, int height) {#GifDevice-int-int-}
```
public GifDevice(int width, int height)
```


Initializes a new instance of the  GifDevice  class with provided image dimensions, default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |

### GifDevice(PageSize pageSize) {#GifDevice-com.aspose.pdf.PageSize-}
```
public GifDevice(PageSize pageSize)
```


Initializes a new instance of the  GifDevice  class with provided page size, default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |

### processInternal(Page page, System.IO.Stream output) {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(Page page, System.IO.Stream output)
```


Converts the page into gif and saves it in the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | com.aspose.ms.System.IO.Stream | Output stream with gif image. |

### process(Page page, OutputStream output) {#process-com.aspose.pdf.Page-java.io.OutputStream-}
```
public void process(Page page, OutputStream output)
```


Converts the page into gif and saves it in the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | java.io.OutputStream | Output stream with gif image. |

