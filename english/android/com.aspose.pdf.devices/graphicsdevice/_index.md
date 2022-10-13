---
title: GraphicsDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that helps to render pdf document pages into graphics.
type: docs
weight: 18
url: /java/com.aspose.pdf.devices/graphicsdevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice), [com.aspose.pdf.devices.ImageDevice](../../com.aspose.pdf.devices/imagedevice)
```
public final class GraphicsDevice extends ImageDevice
```

Represents image device that helps to render pdf document pages into graphics.
## Constructors

| Constructor | Description |
| --- | --- |
| [GraphicsDevice(Point origin, int paperWidth, int paperHeight, System.Drawing.Rectangle marginBounds, float scaleFactor, Resolution resolution, int rotateDegrees, boolean autoSize, int verticalAlignment, int horizontalAlignment, boolean isXpsPrinting)](#GraphicsDevice-com.aspose.pdf.Point-int-int-com.aspose.ms.System.Drawing.Rectangle-float-com.aspose.pdf.devices.Resolution-int-boolean-int-int-boolean-) | Initializes a new instance of the  GraphicsDevice  class with provided image dimensions and resolution. |
## Methods

| Method | Description |
| --- | --- |
| [process(Page page, System.IO.Stream output)](#process-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Perfoms some operation on the given page, e.g. converts page into graphic image. |
| [process(Page page, System.Drawing.Graphics gr)](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | renders page on the graphics |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) |  |
### GraphicsDevice(Point origin, int paperWidth, int paperHeight, System.Drawing.Rectangle marginBounds, float scaleFactor, Resolution resolution, int rotateDegrees, boolean autoSize, int verticalAlignment, int horizontalAlignment, boolean isXpsPrinting) {#GraphicsDevice-com.aspose.pdf.Point-int-int-com.aspose.ms.System.Drawing.Rectangle-float-com.aspose.pdf.devices.Resolution-int-boolean-int-int-boolean-}
```
public GraphicsDevice(Point origin, int paperWidth, int paperHeight, System.Drawing.Rectangle marginBounds, float scaleFactor, Resolution resolution, int rotateDegrees, boolean autoSize, int verticalAlignment, int horizontalAlignment, boolean isXpsPrinting)
```


Initializes a new instance of the  GraphicsDevice  class with provided image dimensions and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| origin | [Point](../../com.aspose.pdf/point) | Top Left image coordinate |
| paperWidth | int | Width that the image is auto-sized to |
| paperHeight | int | Height that the image is auto-sized to |
| marginBounds | com.aspose.ms.System.Drawing.Rectangle |  |
| scaleFactor | float | Scale factor of the outpot image. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |
| rotateDegrees | int | degrees |
| autoSize | boolean |  |
| verticalAlignment | int |  |
| horizontalAlignment | int |  |
| isXpsPrinting | boolean |  |

### process(Page page, System.IO.Stream output) {#process-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
```
public void process(Page page, System.IO.Stream output)
```


Perfoms some operation on the given page, e.g. converts page into graphic image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to process. |
| output | com.aspose.ms.System.IO.Stream | This stream contains the results of processing. |

### process(Page page, System.Drawing.Graphics gr) {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
```
public void process(Page page, System.Drawing.Graphics gr)
```


renders page on the graphics

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| gr | com.aspose.ms.System.Drawing.Graphics |  |

### processInternal(Page page, System.IO.Stream output) {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(Page page, System.IO.Stream output)
```


Perfoms some operation on the given page, e.g. converts page into graphic image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| output | com.aspose.ms.System.IO.Stream |  |

