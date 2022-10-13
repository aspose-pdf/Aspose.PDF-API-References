---
title: BmpDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that helps to save pdf document pages into bmp.
type: docs
weight: 10
url: /java/com.aspose.pdf.devices/bmpdevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice), [com.aspose.pdf.devices.ImageDevice](../../com.aspose.pdf.devices/imagedevice)
```
public final class BmpDevice extends ImageDevice
```

Represents image device that helps to save pdf document pages into bmp.
## Constructors

| Constructor | Description |
| --- | --- |
| [BmpDevice()](#BmpDevice--) | Initializes a new instance of the  BmpDevice  class with default resolution. |
| [BmpDevice(Resolution resolution)](#BmpDevice-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  BmpDevice  class. |
| [BmpDevice(int width, int height, Resolution resolution)](#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  BmpDevice  class with provided image dimensions and resolution. |
| [BmpDevice(PageSize pageSize, Resolution resolution)](#BmpDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  BmpDevice  class with provided page size and resolution. |
| [BmpDevice(int width, int height)](#BmpDevice-int-int-) | Initializes a new instance of the  BmpDevice  class with provided image dimensions, default resolution (=150). |
| [BmpDevice(PageSize pageSize)](#BmpDevice-com.aspose.pdf.facades.PageSize-) | Initializes a new instance of the  BmpDevice  class with provided page size, default resolution (=150). |
## Methods

| Method | Description |
| --- | --- |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converts the page into bmp and saves it in the output stream. |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) |  |
| [process(Page page, System.Drawing.Graphics gr)](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | renders page on the graphics |
### BmpDevice() {#BmpDevice--}
```
public BmpDevice()
```


Initializes a new instance of the  BmpDevice  class with default resolution.

### BmpDevice(Resolution resolution) {#BmpDevice-com.aspose.pdf.devices.Resolution-}
```
public BmpDevice(Resolution resolution)
```


Initializes a new instance of the  BmpDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### BmpDevice(int width, int height, Resolution resolution) {#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-}
```
public BmpDevice(int width, int height, Resolution resolution)
```


Initializes a new instance of the  BmpDevice  class with provided image dimensions and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### BmpDevice(PageSize pageSize, Resolution resolution) {#BmpDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.Resolution-}
```
public BmpDevice(PageSize pageSize, Resolution resolution)
```


Initializes a new instance of the  BmpDevice  class with provided page size and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | Page size of the output image. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### BmpDevice(int width, int height) {#BmpDevice-int-int-}
```
public BmpDevice(int width, int height)
```


Initializes a new instance of the  BmpDevice  class with provided image dimensions, default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |

### BmpDevice(PageSize pageSize) {#BmpDevice-com.aspose.pdf.facades.PageSize-}
```
public BmpDevice(PageSize pageSize)
```


Initializes a new instance of the  BmpDevice  class with provided page size, default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | Page size of the output image. |

### processInternal(Page page, System.IO.Stream output) {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(Page page, System.IO.Stream output)
```


Converts the page into bmp and saves it in the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | com.aspose.ms.System.IO.Stream | Output stream with bmp image. |

### process(Page page, OutputStream output) {#process-com.aspose.pdf.Page-java.io.OutputStream-}
```
public void process(Page page, OutputStream output)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| output | java.io.OutputStream |  |

### process(Page page, System.Drawing.Graphics gr) {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
```
public void process(Page page, System.Drawing.Graphics gr)
```


renders page on the graphics

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| gr | com.aspose.ms.System.Drawing.Graphics |  |

