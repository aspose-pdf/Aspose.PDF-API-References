---
title: ThumbnailDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that save pdf document pages into Thumbnail image.
type: docs
weight: 200
url: /java/com.aspose.pdf.devices/thumbnaildevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.ThumbnailDevice

```
public final class ThumbnailDevice extends ImageDevice
```

Represents image device that save pdf document pages into Thumbnail image.

## Constructors

| Constructor | Description |
| --- | --- |
| [ThumbnailDevice](#ThumbnailDevice--) | Initializes a new instance of the {@link ThumbnailDevice} class with default size of thumbnail image (200x200 pixels). |
| [ThumbnailDevice](#ThumbnailDevice-int-int-) | Initializes a new instance of the {@link ThumbnailDevice} class. |

## Methods

| Method | Description |
| --- | --- |
| [processInternal](#processInternal-com.aspose.pdf.Page-java.io.OutputStream-) | Converts the page into thumbnail image png and saves it in the output stream. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Performs some operation on the given page, e.g. |

### ThumbnailDevice {#ThumbnailDevice--}
```
public ThumbnailDevice()
```

Initializes a new instance of the {@link ThumbnailDevice} class with default size of thumbnail image (200x200 pixels).

### ThumbnailDevice {#ThumbnailDevice-int-int-}
```
public ThumbnailDevice(int width, int height)
```

Initializes a new instance of the {@link ThumbnailDevice} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | Thumbnail image output width. |
| height |  | Thumbnail image output height. |

### processInternal {#processInternal-com.aspose.pdf.Page-java.io.OutputStream-}
Converts the page into thumbnail image png and saves it in the output stream.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Performs some operation on the given page, e.g.
