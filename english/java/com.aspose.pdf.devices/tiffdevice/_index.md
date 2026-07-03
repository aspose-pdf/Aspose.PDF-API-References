---
title: TiffDevice
second_title: Aspose.PDF for Java API Reference
description: This class helps to save pdf document page by page into the one tiff image.
type: docs
weight: 210
url: /java/com.aspose.pdf.devices/tiffdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.TiffDevice

```
public final class TiffDevice extends DocumentDevice
```

This class helps to save pdf document page by page into the one tiff image.

## Constructors

| Constructor | Description |
| --- | --- |
| [TiffDevice](#TiffDevice--) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-int-int-) | Initializes a new instance of the {@code TiffDevice} class. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initializes a new instance of the {@code TiffDevice} class with default settings. |

## Methods

| Method | Description |
| --- | --- |
| [binarizeBradley](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | Do Bradley binarization for input stream. |
| [getCropRectangle](#getCropRectangle--) | Get rectangle that defines the area that will be converted into a picture. The default is null, in which case the all image is converted to a page |
| [getFormPresentationMode](#getFormPresentationMode--) | Gets form presentation mode. |
| [getHeight](#getHeight--) | Gets image output height. |
| [getRenderingOptions](#getRenderingOptions--) | Gets rendering options. |
| [getResolution](#getResolution--) | Gets image resolution. |
| [getSettings](#getSettings--) | Gets settings for mapping pdf into tiff image. |
| [getWidth](#getWidth--) | Gets image output width. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Converts certain document pages into tiff and save it in the output stream. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Converts certain document pages into tiff and save it in the output stream. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Performs some operation on the given page, e.g. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Set rectangle that defines the area that will be converted into a picture. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Gets form presentation mode. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Sets rendering options. |

### TiffDevice {#TiffDevice--}
```
public TiffDevice()
```

Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-int-int-}
```
public TiffDevice(int width, int height)
```

Initializes a new instance of the {@code TiffDevice} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | Image output width. |
| height |  | Image output height. |

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initializes a new instance of the {@code TiffDevice} class with default settings.

### binarizeBradley {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
Do Bradley binarization for input stream.

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Get rectangle that defines the area that will be converted into a picture. The default is null, in which case the all image is converted to a page

**Returns:**
Rectangle object

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Gets form presentation mode.

**Returns:**
FormPresentationMode value @see FormPresentationMode

### getHeight {#getHeight--}
```
public int getHeight()
```

Gets image output height.

**Returns:**
int value

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Gets rendering options.

**Returns:**
rendering options.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Gets image resolution.

**Returns:**
Resolution element

### getSettings {#getSettings--}
```
public TiffSettings getSettings()
```

Gets settings for mapping pdf into tiff image.

**Returns:**
TiffSettings element

### getWidth {#getWidth--}
```
public int getWidth()
```

Gets image output width.

**Returns:**
int value

### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Converts certain document pages into tiff and save it in the output stream.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Converts certain document pages into tiff and save it in the output stream.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Performs some operation on the given page, e.g.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Set rectangle that defines the area that will be converted into a picture.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Gets form presentation mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Sets rendering options.
