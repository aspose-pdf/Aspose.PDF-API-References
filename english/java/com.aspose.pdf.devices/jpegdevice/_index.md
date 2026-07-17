---
title: JpegDevice
linktitle: JpegDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that helps to save pdf document pages into jpeg.
type: docs
weight: 130
url: /java/com.aspose.pdf.devices/jpegdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.JpegDevice

```
public final class JpegDevice extends ImageDevice
```

Represents image device that helps to save pdf document pages into jpeg.

## Constructors

| Constructor | Description |
| --- | --- |
| [JpegDevice](#JpegDevice--) | Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality. |
| [JpegDevice](#JpegDevice-int-) | Initializes a new instance of the {@code JpegDevice} class. |
| [JpegDevice](#JpegDevice-int-int-) | Initializes a new instance of the {@code JpegDevice} class with provided image dimensions, default resolution (=150) and maximum quality. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-) | Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-) | Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-) | Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-int-) | Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality. |

## Methods

| Method | Description |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converts the page into jpeg and saves it in the output stream. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converts the page into jpeg and saves it in the output stream. |

### JpegDevice {#JpegDevice--}
```
public JpegDevice()
```

Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality.

### JpegDevice {#JpegDevice-int-}
```
public JpegDevice(int quality)
```

Initializes a new instance of the {@code JpegDevice} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| quality |  | Specifies the level of compression for an image. The range of useful values for the quality is from 0 to 100. The lower the number specified, the higher the compression and therefore the lower the quality of the image. Zero would give you the lowest quality image and 100 the highest. |

### JpegDevice {#JpegDevice-int-int-}
```
public JpegDevice(int width, int height)
```

Initializes a new instance of the {@code JpegDevice} class with provided image dimensions, default resolution (=150) and maximum quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | Image output width. |
| height |  | Image output height. |

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality.

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-}
Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-}
Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-}
Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-int-}
Initializes a new instance of the {@code JpegDevice} class with default resolution and maximum quality.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Converts the page into jpeg and saves it in the output stream.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Converts the page into jpeg and saves it in the output stream.
