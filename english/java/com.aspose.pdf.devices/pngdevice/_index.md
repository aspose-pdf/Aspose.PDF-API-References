---
title: PngDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that helps to save pdf document pages into png.
type: docs
weight: 24
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
| [PngDevice(PageSize pageSize, Resolution resolution)](#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  PngDevice  class with provided page size and resolution. |
| [PngDevice(int width, int height)](#PngDevice-int-int-) | Initializes a new instance of the  PngDevice  class with provided image dimensions, default resolution (=150). |
| [PngDevice(PageSize pageSize)](#PngDevice-com.aspose.pdf.PageSize-) | Initializes a new instance of the  PngDevice  class with provided page size, default resolution (=150). |
## Methods

| Method | Description |
| --- | --- |
| [isTransparentBackground()](#isTransparentBackground--) | Gets or sets if image has transparent background. |
| [setTransparentBackground(boolean value)](#setTransparentBackground-boolean-) | Gets or sets if image has transparent background. |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converts the page into png and saves it in the output stream. |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converts the page into png and saves it in the output stream. |
| [processToBufferedImage(Page page)](#processToBufferedImage-com.aspose.pdf.Page-) | Converts the page into BufferedImage. |
| [processToBufferedImageBinarized(Page page, double threshold)](#processToBufferedImageBinarized-com.aspose.pdf.Page-double-) | Converts the page into BufferedImage with Bradley binarization. |
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

### PngDevice(PageSize pageSize, Resolution resolution) {#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
```
public PngDevice(PageSize pageSize, Resolution resolution)
```


Initializes a new instance of the  PngDevice  class with provided page size and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |
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

### PngDevice(PageSize pageSize) {#PngDevice-com.aspose.pdf.PageSize-}
```
public PngDevice(PageSize pageSize)
```


Initializes a new instance of the  PngDevice  class with provided page size, default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |

### isTransparentBackground() {#isTransparentBackground--}
```
public final boolean isTransparentBackground()
```


Gets or sets if image has transparent background.

**Returns:**
boolean - boolean value
### setTransparentBackground(boolean value) {#setTransparentBackground-boolean-}
```
public final void setTransparentBackground(boolean value)
```


Gets or sets if image has transparent background.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

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


Converts the page into png and saves it in the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | java.io.OutputStream | Output stream with png image. |

### processToBufferedImage(Page page) {#processToBufferedImage-com.aspose.pdf.Page-}
```
public BufferedImage processToBufferedImage(Page page)
```


Converts the page into BufferedImage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |

**Returns:**
java.awt.image.BufferedImage - BufferedImage Output BufferedImage image.
### processToBufferedImageBinarized(Page page, double threshold) {#processToBufferedImageBinarized-com.aspose.pdf.Page-double-}
```
public BufferedImage processToBufferedImageBinarized(Page page, double threshold)
```


Converts the page into BufferedImage with Bradley binarization.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| threshold | double | The threshold value between 0.0 and 1.0. |

**Returns:**
java.awt.image.BufferedImage - BufferedImage Output BufferedImage image.
