---
title: GifDevice
linktitle: GifDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that helps to save pdf document pages into gif.
type: docs
weight: 90
url: /java/com.aspose.pdf.devices/gifdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.GifDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.GifDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.GifDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.GifDevice

```
public final class GifDevice extends ImageDevice
```

Represents image device that helps to save pdf document pages into gif.

## Constructors

| Constructor | Description |
| --- | --- |
| [GifDevice](#GifDevice--) | Initializes a new instance of the {@code GifDevice} class with default resolution. |
| [GifDevice](#GifDevice-int-int-) | Initializes a new instance of the {@code GifDevice} class with provided image dimensions, default resolution (=150). |
| [GifDevice](#GifDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code GifDevice} class with default resolution. |
| [GifDevice](#GifDevice-com.aspose.pdf.PageSize-) | Initializes a new instance of the {@code GifDevice} class with default resolution. |
| [GifDevice](#GifDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code GifDevice} class with default resolution. |
| [GifDevice](#GifDevice-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code GifDevice} class with default resolution. |

## Methods

| Method | Description |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converts the page into gif and saves it in the output stream. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converts the page into gif and saves it in the output stream. |

### GifDevice {#GifDevice--}
```
public GifDevice()
```

Initializes a new instance of the {@code GifDevice} class with default resolution.

### GifDevice {#GifDevice-int-int-}
```
public GifDevice(int width, int height)
```

Initializes a new instance of the {@code GifDevice} class with provided image dimensions, default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | Image output width. |
| height |  | Image output height. |

### GifDevice {#GifDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code GifDevice} class with default resolution.

### GifDevice {#GifDevice-com.aspose.pdf.PageSize-}
Initializes a new instance of the {@code GifDevice} class with default resolution.

### GifDevice {#GifDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code GifDevice} class with default resolution.

### GifDevice {#GifDevice-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code GifDevice} class with default resolution.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Converts the page into gif and saves it in the output stream.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Converts the page into gif and saves it in the output stream.
