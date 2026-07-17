---
title: PngDevice
linktitle: PngDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that helps to save pdf document pages into png.
type: docs
weight: 160
url: /java/com.aspose.pdf.devices/pngdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PngDevice

```
public final class PngDevice extends ImageDevice
```

Represents image device that helps to save pdf document pages into png.

## Constructors

| Constructor | Description |
| --- | --- |
| [PngDevice](#PngDevice--) | Initializes a new instance of the {@code PngDevice} class with default resolution. |
| [PngDevice](#PngDevice-int-int-) | Initializes a new instance of the {@code PngDevice} class with provided image dimensions, default resolution (=150). |
| [PngDevice](#PngDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code PngDevice} class with default resolution. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-) | Initializes a new instance of the {@code PngDevice} class with default resolution. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code PngDevice} class with default resolution. |
| [PngDevice](#PngDevice-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code PngDevice} class with default resolution. |

## Methods

| Method | Description |
| --- | --- |
| [isTransparentBackground](#isTransparentBackground--) | Gets or sets if image has transparent background. |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converts the page into png and saves it in the output stream. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converts the page into png and saves it in the output stream. |
| [processToBufferedImage](#processToBufferedImage-com.aspose.pdf.Page-) | Converts the page into BufferedImage. |
| [processToBufferedImageBinarized](#processToBufferedImageBinarized-com.aspose.pdf.Page-double-) | Converts the page into BufferedImage with Bradley binarization. |
| [setTransparentBackground](#setTransparentBackground-boolean-) | Gets or sets if image has transparent background. |

### PngDevice {#PngDevice--}
```
public PngDevice()
```

Initializes a new instance of the {@code PngDevice} class with default resolution.

### PngDevice {#PngDevice-int-int-}
```
public PngDevice(int width, int height)
```

Initializes a new instance of the {@code PngDevice} class with provided image dimensions, default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | Image output width. |
| height |  | Image output height. |

### PngDevice {#PngDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code PngDevice} class with default resolution.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-}
Initializes a new instance of the {@code PngDevice} class with default resolution.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code PngDevice} class with default resolution.

### PngDevice {#PngDevice-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code PngDevice} class with default resolution.

### isTransparentBackground {#isTransparentBackground--}
```
public final boolean isTransparentBackground()
```

Gets or sets if image has transparent background.

**Returns:**
boolean value

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Converts the page into png and saves it in the output stream.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Converts the page into png and saves it in the output stream.

### processToBufferedImage {#processToBufferedImage-com.aspose.pdf.Page-}
Converts the page into BufferedImage.

### processToBufferedImageBinarized {#processToBufferedImageBinarized-com.aspose.pdf.Page-double-}
Converts the page into BufferedImage with Bradley binarization.

### setTransparentBackground {#setTransparentBackground-boolean-}
```
public final void setTransparentBackground(boolean value)
```

Gets or sets if image has transparent background.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
