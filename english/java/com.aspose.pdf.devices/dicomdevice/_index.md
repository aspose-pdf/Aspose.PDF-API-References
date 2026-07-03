---
title: DicomDevice
linktitle: DicomDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that helps to save pdf document pages into Dicom format.
type: docs
weight: 50
url: /java/com.aspose.pdf.devices/dicomdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.DicomDevice

```
public final class DicomDevice extends ImageDevice
```

Represents image device that helps to save pdf document pages into Dicom format.

## Constructors

| Constructor | Description |
| --- | --- |
| [DicomDevice](#DicomDevice--) | Initializes a new instance of the {@link DicomDevice} class with default resolution. |
| [DicomDevice](#DicomDevice-int-int-) | Initializes a new instance of the {@link DicomDevice} class with provided image dimensions, with default resolution (=150). |
| [DicomDevice](#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@link DicomDevice} class with default resolution. |
| [DicomDevice](#DicomDevice-com.aspose.pdf.PageSize-) | Initializes a new instance of the {@link DicomDevice} class with default resolution. |
| [DicomDevice](#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@link DicomDevice} class with default resolution. |
| [DicomDevice](#DicomDevice-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@link DicomDevice} class with default resolution. |

## Methods

| Method | Description |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converts the page into Dicom and saves it in the output stream. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Performs some operation on the given page, e.g. |

### DicomDevice {#DicomDevice--}
```
public DicomDevice()
```

Initializes a new instance of the {@link DicomDevice} class with default resolution.

### DicomDevice {#DicomDevice-int-int-}
```
public DicomDevice(int width, int height)
```

Initializes a new instance of the {@link DicomDevice} class with provided image dimensions, with default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | Image output width. |
| height |  | Image output height. |

### DicomDevice {#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@link DicomDevice} class with default resolution.

### DicomDevice {#DicomDevice-com.aspose.pdf.PageSize-}
Initializes a new instance of the {@link DicomDevice} class with default resolution.

### DicomDevice {#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@link DicomDevice} class with default resolution.

### DicomDevice {#DicomDevice-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@link DicomDevice} class with default resolution.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Converts the page into Dicom and saves it in the output stream.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Performs some operation on the given page, e.g.
