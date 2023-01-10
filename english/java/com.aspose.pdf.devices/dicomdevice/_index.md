---
title: DicomDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that helps to save pdf document pages into Dicom format.
type: docs
weight: 14
url: /java/com.aspose.pdf.devices/dicomdevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice), [com.aspose.pdf.devices.ImageDevice](../../com.aspose.pdf.devices/imagedevice)
```
public final class DicomDevice extends ImageDevice
```

Represents image device that helps to save pdf document pages into Dicom format.
## Constructors

| Constructor | Description |
| --- | --- |
| [DicomDevice()](#DicomDevice--) | Initializes a new instance of the [DicomDevice](../../com.aspose.pdf.devices/dicomdevice) class with default resolution. |
| [DicomDevice(Resolution resolution)](#DicomDevice-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the [DicomDevice](../../com.aspose.pdf.devices/dicomdevice) class. |
| [DicomDevice(PageSize pageSize)](#DicomDevice-com.aspose.pdf.PageSize-) | Initializes a new instance of the [DicomDevice](../../com.aspose.pdf.devices/dicomdevice) class with provided page size, with default resolution (=150). |
| [DicomDevice(int width, int height)](#DicomDevice-int-int-) | Initializes a new instance of the [DicomDevice](../../com.aspose.pdf.devices/dicomdevice) class with provided image dimensions, with default resolution (=150). |
| [DicomDevice(PageSize pageSize, Resolution resolution)](#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the [DicomDevice](../../com.aspose.pdf.devices/dicomdevice) class with provided page size and resolution. |
| [DicomDevice(int width, int height, Resolution resolution)](#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the [DicomDevice](../../com.aspose.pdf.devices/dicomdevice) class with provided image dimensions and resolution. |
## Methods

| Method | Description |
| --- | --- |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converts the page into Dicom and saves it in the output stream. |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) |  |
### DicomDevice() {#DicomDevice--}
```
public DicomDevice()
```


Initializes a new instance of the [DicomDevice](../../com.aspose.pdf.devices/dicomdevice) class with default resolution.

### DicomDevice(Resolution resolution) {#DicomDevice-com.aspose.pdf.devices.Resolution-}
```
public DicomDevice(Resolution resolution)
```


Initializes a new instance of the [DicomDevice](../../com.aspose.pdf.devices/dicomdevice) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution ([ImageDevice\#getResolution](../../com.aspose.pdf.devices/imagedevice\#getResolution)) class. |

### DicomDevice(PageSize pageSize) {#DicomDevice-com.aspose.pdf.PageSize-}
```
public DicomDevice(PageSize pageSize)
```


Initializes a new instance of the [DicomDevice](../../com.aspose.pdf.devices/dicomdevice) class with provided page size, with default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |

### DicomDevice(int width, int height) {#DicomDevice-int-int-}
```
public DicomDevice(int width, int height)
```


Initializes a new instance of the [DicomDevice](../../com.aspose.pdf.devices/dicomdevice) class with provided image dimensions, with default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |

### DicomDevice(PageSize pageSize, Resolution resolution) {#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
```
public DicomDevice(PageSize pageSize, Resolution resolution)
```


Initializes a new instance of the [DicomDevice](../../com.aspose.pdf.devices/dicomdevice) class with provided page size and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution ([ImageDevice\#getResolution](../../com.aspose.pdf.devices/imagedevice\#getResolution)) class. |

### DicomDevice(int width, int height, Resolution resolution) {#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-}
```
public DicomDevice(int width, int height, Resolution resolution)
```


Initializes a new instance of the [DicomDevice](../../com.aspose.pdf.devices/dicomdevice) class with provided image dimensions and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution ([ImageDevice\#getResolution](../../com.aspose.pdf.devices/imagedevice\#getResolution)) class. |

### process(Page page, OutputStream output) {#process-com.aspose.pdf.Page-java.io.OutputStream-}
```
public void process(Page page, OutputStream output)
```


Converts the page into Dicom and saves it in the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | java.io.OutputStream | Output stream with image. |

### processInternal(Page page, System.IO.Stream output) {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(Page page, System.IO.Stream output)
```


Performs some operation on the given page, e.g. converts page into graphic image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| output | com.aspose.ms.System.IO.Stream |  |

