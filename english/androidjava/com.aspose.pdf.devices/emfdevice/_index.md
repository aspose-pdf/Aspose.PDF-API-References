---
title: EmfDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that helps to save pdf document pages into emf.
type: docs
weight: 15
url: /java/com.aspose.pdf.devices/emfdevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice), [com.aspose.pdf.devices.ImageDevice](../../com.aspose.pdf.devices/imagedevice)
```
public final class EmfDevice extends ImageDevice
```

Represents image device that helps to save pdf document pages into emf.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfDevice()](#EmfDevice--) | Initializes a new instance of the  EmfDevice  class with default resolution of raster image written to emf. |
| [EmfDevice(Resolution resolution)](#EmfDevice-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  EmfDevice  class. |
| [EmfDevice(int width, int height)](#EmfDevice-int-int-) | Initializes a new instance of the  EmfDevice  class with provided image dimensions, and default resolution for the raster image written to emf (=150) |
| [EmfDevice(PageSize pageSize)](#EmfDevice-com.aspose.pdf.facades.PageSize-) | Initializes a new instance of the  EmfDevice  class with provided page size, and default resolution for the raster image written to emf (=150) |
| [EmfDevice(int width, int height, Resolution resolution)](#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  JpegDevice  class with provided image dimensions, and resolution for the raster image written to emf. |
| [EmfDevice(PageSize pageSize, Resolution resolution)](#EmfDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  JpegDevice  class with provided page size, and resolution for the raster image written to emf. |
## Methods

| Method | Description |
| --- | --- |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converts the page into emf and saves it in the output stream. |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) |  |
### EmfDevice() {#EmfDevice--}
```
public EmfDevice()
```


Initializes a new instance of the  EmfDevice  class with default resolution of raster image written to emf.

### EmfDevice(Resolution resolution) {#EmfDevice-com.aspose.pdf.devices.Resolution-}
```
public EmfDevice(Resolution resolution)
```


Initializes a new instance of the  EmfDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the raster image written to emf, see  Resolution  class. |

### EmfDevice(int width, int height) {#EmfDevice-int-int-}
```
public EmfDevice(int width, int height)
```


Initializes a new instance of the  EmfDevice  class with provided image dimensions, and default resolution for the raster image written to emf (=150)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |

### EmfDevice(PageSize pageSize) {#EmfDevice-com.aspose.pdf.facades.PageSize-}
```
public EmfDevice(PageSize pageSize)
```


Initializes a new instance of the  EmfDevice  class with provided page size, and default resolution for the raster image written to emf (=150)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | Page size of the output image. |

### EmfDevice(int width, int height, Resolution resolution) {#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-}
```
public EmfDevice(int width, int height, Resolution resolution)
```


Initializes a new instance of the  JpegDevice  class with provided image dimensions, and resolution for the raster image written to emf.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the for the raster image written to emf, see  Resolution  class. |

### EmfDevice(PageSize pageSize, Resolution resolution) {#EmfDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.Resolution-}
```
public EmfDevice(PageSize pageSize, Resolution resolution)
```


Initializes a new instance of the  JpegDevice  class with provided page size, and resolution for the raster image written to emf.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | Page size of the output image. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the for the raster image written to emf, see  Resolution  class. |

### processInternal(Page page, System.IO.Stream output) {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(Page page, System.IO.Stream output)
```


Converts the page into emf and saves it in the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | com.aspose.ms.System.IO.Stream | Output stream with emf image. |

### process(Page page, OutputStream output) {#process-com.aspose.pdf.Page-java.io.OutputStream-}
```
public void process(Page page, OutputStream output)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| output | java.io.OutputStream |  |

