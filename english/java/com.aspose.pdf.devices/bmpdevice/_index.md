---
title: BmpDevice
linktitle: BmpDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that helps to save pdf document pages into bmp.
type: docs
weight: 10
url: /java/com.aspose.pdf.devices/bmpdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.BmpDevice

```
public final class BmpDevice extends ImageDevice
```

Represents image device that helps to save pdf document pages into bmp.

## Constructors

| Constructor | Description |
| --- | --- |
| [BmpDevice](#BmpDevice--) | Initializes a new instance of the {@code BmpDevice} class with default resolution. |
| [BmpDevice](#BmpDevice-int-int-) | Initializes a new instance of the {@code BmpDevice} class with provided image dimensions, default resolution (=150). |
| [BmpDevice](#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code BmpDevice} class with default resolution. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-) | Initializes a new instance of the {@code BmpDevice} class with default resolution. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code BmpDevice} class with default resolution. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code BmpDevice} class with default resolution. |

## Methods

| Method | Description |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | renders page on the graphics |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converts the page into bmp and saves it in the output stream. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | For Internal usage only! |

### BmpDevice {#BmpDevice--}
```
public BmpDevice()
```

Initializes a new instance of the {@code BmpDevice} class with default resolution.

### BmpDevice {#BmpDevice-int-int-}
```
public BmpDevice(int width, int height)
```

Initializes a new instance of the {@code BmpDevice} class with provided image dimensions, default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | Image output width. |
| height |  | Image output height. |

### BmpDevice {#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code BmpDevice} class with default resolution.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-}
Initializes a new instance of the {@code BmpDevice} class with default resolution.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code BmpDevice} class with default resolution.

### BmpDevice {#BmpDevice-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code BmpDevice} class with default resolution.

### process {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
renders page on the graphics

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Converts the page into bmp and saves it in the output stream.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
For Internal usage only!
