---
title: PngDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that helps to save pdf document pages into png.
type: docs
weight: 23
url: /java/com.aspose.pdf.devices/pngdevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice), [com.aspose.pdf.devices.ImageDevice](../../com.aspose.pdf.devices/imagedevice)
```
public final class PngDevice extends ImageDevice
```

Represents image device that helps to save pdf document pages into png.
## Constructors

| Constructor | Description |
| --- | --- |
| [PngDevice()](#PngDevice--) | Initializes a new instance of the  PngDevice  class with default resolution. |
| [PngDevice(Resolution resolution)](#PngDevice-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  PngDevice  class. |
| [PngDevice(int width, int height, Resolution resolution)](#PngDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  PngDevice  class with provided image dimensions and resolution. |
| [PngDevice(PageSize pageSize, Resolution resolution)](#PngDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  PngDevice  class with provided page size and resolution. |
| [PngDevice(int width, int height)](#PngDevice-int-int-) | Initializes a new instance of the  PngDevice  class with provided image dimensions, default resolution (=150). |
| [PngDevice(PageSize pageSize)](#PngDevice-com.aspose.pdf.facades.PageSize-) | Initializes a new instance of the  PngDevice  class with provided page size, default resolution (=150). |
## Methods

| Method | Description |
| --- | --- |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converts the page into png and saves it in the output stream. |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) |  |
### PngDevice() {#PngDevice--}
```
public PngDevice()
```


Initializes a new instance of the  PngDevice  class with default resolution.

### PngDevice(Resolution resolution) {#PngDevice-com.aspose.pdf.devices.Resolution-}
```
public PngDevice(Resolution resolution)
```


Initializes a new instance of the  PngDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### PngDevice(int width, int height, Resolution resolution) {#PngDevice-int-int-com.aspose.pdf.devices.Resolution-}
```
public PngDevice(int width, int height, Resolution resolution)
```


Initializes a new instance of the  PngDevice  class with provided image dimensions and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### PngDevice(PageSize pageSize, Resolution resolution) {#PngDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.Resolution-}
```
public PngDevice(PageSize pageSize, Resolution resolution)
```


Initializes a new instance of the  PngDevice  class with provided page size and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | Page size of the output image. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### PngDevice(int width, int height) {#PngDevice-int-int-}
```
public PngDevice(int width, int height)
```


Initializes a new instance of the  PngDevice  class with provided image dimensions, default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |

### PngDevice(PageSize pageSize) {#PngDevice-com.aspose.pdf.facades.PageSize-}
```
public PngDevice(PageSize pageSize)
```


Initializes a new instance of the  PngDevice  class with provided page size, default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | Page size of the output image. |

### processInternal(Page page, System.IO.Stream output) {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(Page page, System.IO.Stream output)
```


Converts the page into png and saves it in the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | com.aspose.ms.System.IO.Stream | Output stream with png image. |

### process(Page page, OutputStream output) {#process-com.aspose.pdf.Page-java.io.OutputStream-}
```
public void process(Page page, OutputStream output)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| output | java.io.OutputStream |  |

