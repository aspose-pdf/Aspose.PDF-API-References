---
title: ThumbnailDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that save pdf document pages into Thumbnail image.
type: docs
weight: 28
url: /java/com.aspose.pdf.devices/thumbnaildevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice), [com.aspose.pdf.devices.ImageDevice](../../com.aspose.pdf.devices/imagedevice)
```
public final class ThumbnailDevice extends ImageDevice
```

Represents image device that save pdf document pages into Thumbnail image.
## Constructors

| Constructor | Description |
| --- | --- |
| [ThumbnailDevice()](#ThumbnailDevice--) | Initializes a new instance of the [ThumbnailDevice](../../com.aspose.pdf.devices/thumbnaildevice) class with default size of thumbnail image (200x200 pixels). |
| [ThumbnailDevice(int width, int height)](#ThumbnailDevice-int-int-) | Initializes a new instance of the [ThumbnailDevice](../../com.aspose.pdf.devices/thumbnaildevice) class. |
## Methods

| Method | Description |
| --- | --- |
| [processInternal(Page page, OutputStream output)](#processInternal-com.aspose.pdf.Page-java.io.OutputStream-) | Converts the page into thumbnail image png and saves it in the output stream. |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) |  |
### ThumbnailDevice() {#ThumbnailDevice--}
```
public ThumbnailDevice()
```


Initializes a new instance of the [ThumbnailDevice](../../com.aspose.pdf.devices/thumbnaildevice) class with default size of thumbnail image (200x200 pixels).

### ThumbnailDevice(int width, int height) {#ThumbnailDevice-int-int-}
```
public ThumbnailDevice(int width, int height)
```


Initializes a new instance of the [ThumbnailDevice](../../com.aspose.pdf.devices/thumbnaildevice) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Thumbnail image output width. |
| height | int | Thumbnail image output height. |

### processInternal(Page page, OutputStream output) {#processInternal-com.aspose.pdf.Page-java.io.OutputStream-}
```
public void processInternal(Page page, OutputStream output)
```


Converts the page into thumbnail image png and saves it in the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | java.io.OutputStream | Output stream with png image. |

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

