---
title: EmfDevice
linktitle: EmfDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that helps to save pdf document pages into emf.
type: docs
weight: 70
url: /java/com.aspose.pdf.devices/emfdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.EmfDevice

```
public final class EmfDevice extends ImageDevice
```

Represents image device that helps to save pdf document pages into emf.

## Constructors

| Constructor | Description |
| --- | --- |
| [EmfDevice](#EmfDevice--) | Initializes a new instance of the {@code EmfDevice} class with default resolution of raster image written to emf. |
| [EmfDevice](#EmfDevice-int-int-) | Initializes a new instance of the {@code EmfDevice} class with provided image dimensions, and default resolution for the raster image written to emf (=150) |
| [EmfDevice](#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code EmfDevice} class with default resolution of raster image written to emf. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.PageSize-) | Initializes a new instance of the {@code EmfDevice} class with default resolution of raster image written to emf. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code EmfDevice} class with default resolution of raster image written to emf. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code EmfDevice} class with default resolution of raster image written to emf. |

## Methods

| Method | Description |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converts the page into emf and saves it in the output stream. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converts the page into emf and saves it in the output stream. |

### EmfDevice {#EmfDevice--}
```
public EmfDevice()
```

Initializes a new instance of the {@code EmfDevice} class with default resolution of raster image written to emf.

### EmfDevice {#EmfDevice-int-int-}
```
public EmfDevice(int width, int height)
```

Initializes a new instance of the {@code EmfDevice} class with provided image dimensions, and default resolution for the raster image written to emf (=150)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | Image output width. |
| height |  | Image output height. |

### EmfDevice {#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code EmfDevice} class with default resolution of raster image written to emf.

### EmfDevice {#EmfDevice-com.aspose.pdf.PageSize-}
Initializes a new instance of the {@code EmfDevice} class with default resolution of raster image written to emf.

### EmfDevice {#EmfDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code EmfDevice} class with default resolution of raster image written to emf.

### EmfDevice {#EmfDevice-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code EmfDevice} class with default resolution of raster image written to emf.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Converts the page into emf and saves it in the output stream.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Converts the page into emf and saves it in the output stream.
