---
title: TiffDevice
second_title: Aspose.PDF for Java API Reference
description: This class helps to save pdf document page by page into the one tiff image.
type: docs
weight: 27
url: /java/com.aspose.pdf.devices/tiffdevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.DocumentDevice](../../com.aspose.pdf.devices/documentdevice)
```
public final class TiffDevice extends DocumentDevice
```

This class helps to save pdf document page by page into the one tiff image.
## Constructors

| Constructor | Description |
| --- | --- |
| [TiffDevice(Resolution resolution)](#TiffDevice-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(Resolution resolution, TiffSettings settings)](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(TiffSettings settings)](#TiffDevice-com.aspose.pdf.devices.TiffSettings-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice()](#TiffDevice--) | Initializes a new instance of the  TiffDevice  class with default settings. |
| [TiffDevice(int width, int height, Resolution resolution, TiffSettings settings)](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(int width, int height, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings)](#TiffDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(int width, int height, Resolution resolution)](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(PageSize pageSize, Resolution resolution)](#TiffDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(int width, int height, TiffSettings settings)](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(int width, int height, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(PageSize pageSize, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(PageSize pageSize, TiffSettings settings)](#TiffDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.TiffSettings-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(int width, int height)](#TiffDevice-int-int-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(PageSize pageSize)](#TiffDevice-com.aspose.pdf.facades.PageSize-) | Initializes a new instance of the  TiffDevice  class. |
## Methods

| Method | Description |
| --- | --- |
| [getRenderingOptions()](#getRenderingOptions--) | Gets or sets rendering options. |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) |  |
| [getFormPresentationMode()](#getFormPresentationMode--) | Gets or sets form presentation mode. |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) |  |
| [getSettings()](#getSettings--) | Gets settings for mapping pdf into tiff image. |
| [getResolution()](#getResolution--) | Gets image resolution. |
| [processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output)](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Converts certain document pages into tiff and save it in the output stream. |
| [process(IDocument document, int fromPage, int toPage, OutputStream output)](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) |  |
| [getWidth()](#getWidth--) | Gets image output width. |
| [getHeight()](#getHeight--) | Gets image output height. |
| [getCropRectangle()](#getCropRectangle--) | Get rectangle that defines the area that will be converted into a picture. |
| [setCropRectangle(Rectangle cropRectangle)](#setCropRectangle-com.aspose.pdf.Rectangle-) | Set rectangle that defines the area that will be converted into a picture. |
### TiffDevice(Resolution resolution) {#TiffDevice-com.aspose.pdf.devices.Resolution-}
```
public TiffDevice(Resolution resolution)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file. |

### TiffDevice(Resolution resolution, TiffSettings settings) {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(Resolution resolution, TiffSettings settings)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the output image. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff settings, see  TiffSettings  class. |

### TiffDevice(Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the output image. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff settings, see  TiffSettings  class. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | External converter |

### TiffDevice(TiffSettings settings) {#TiffDevice-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(TiffSettings settings)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff settings, see  TiffSettings  class. |

### TiffDevice(TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(TiffSettings settings, IIndexBitmapConverter converter)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff settings, see  TiffSettings  class. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | External converter |

### TiffDevice() {#TiffDevice--}
```
public TiffDevice()
```


Initializes a new instance of the  TiffDevice  class with default settings.

### TiffDevice(int width, int height, Resolution resolution, TiffSettings settings) {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(int width, int height, Resolution resolution, TiffSettings settings)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the output image. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff settings, see  TiffSettings  class. |

### TiffDevice(int width, int height, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(int width, int height, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the output image. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff settings, see  TiffSettings  class. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | External converter |

### TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings) {#TiffDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | Page size of the output image. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the output image. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff settings, see  TiffSettings  class. |

### TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | Page size of the output image. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the output image. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff settings, see  TiffSettings  class. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | External converter |

### TiffDevice(int width, int height, Resolution resolution) {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-}
```
public TiffDevice(int width, int height, Resolution resolution)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the output image. |

### TiffDevice(PageSize pageSize, Resolution resolution) {#TiffDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.Resolution-}
```
public TiffDevice(PageSize pageSize, Resolution resolution)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | Page size of the output image. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the output image. |

### TiffDevice(int width, int height, TiffSettings settings) {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(int width, int height, TiffSettings settings)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff settings, see  TiffSettings  class. |

### TiffDevice(int width, int height, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(int width, int height, TiffSettings settings, IIndexBitmapConverter converter)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff settings, see  TiffSettings  class. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | External converter |

### TiffDevice(PageSize pageSize, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(PageSize pageSize, TiffSettings settings, IIndexBitmapConverter converter)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | Page size of the output image. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff settings, see  TiffSettings  class. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | External converter |

### TiffDevice(PageSize pageSize, TiffSettings settings) {#TiffDevice-com.aspose.pdf.facades.PageSize-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(PageSize pageSize, TiffSettings settings)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | Page size of the output image. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff settings, see  TiffSettings  class. |

### TiffDevice(int width, int height) {#TiffDevice-int-int-}
```
public TiffDevice(int width, int height)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |

### TiffDevice(PageSize pageSize) {#TiffDevice-com.aspose.pdf.facades.PageSize-}
```
public TiffDevice(PageSize pageSize)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf.facades/pagesize) | Page size of the output image. |

### getRenderingOptions() {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```


Gets or sets rendering options.

**Returns:**
[RenderingOptions](../../com.aspose.pdf/renderingoptions)
### setRenderingOptions(RenderingOptions value) {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
```
public void setRenderingOptions(RenderingOptions value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RenderingOptions](../../com.aspose.pdf/renderingoptions) |  |

### getFormPresentationMode() {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```


Gets or sets form presentation mode.

**Returns:**
int
### setFormPresentationMode(int value) {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSettings() {#getSettings--}
```
public TiffSettings getSettings()
```


Gets settings for mapping pdf into tiff image.

**Returns:**
[TiffSettings](../../com.aspose.pdf.devices/tiffsettings)
### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Gets image resolution.

**Returns:**
[Resolution](../../com.aspose.pdf.devices/resolution)
### processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output) {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output)
```


Converts certain document pages into tiff and save it in the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | The document to convert. |
| fromPage | int | Defines page number from which converting will start. |
| toPage | int | Defines page number which will end the converting. |
| output | com.aspose.ms.System.IO.Stream | Output stream with tiff image. |

### process(IDocument document, int fromPage, int toPage, OutputStream output) {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
```
public void process(IDocument document, int fromPage, int toPage, OutputStream output)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) |  |
| fromPage | int |  |
| toPage | int |  |
| output | java.io.OutputStream |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets image output width.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets image output height.

**Returns:**
int
### getCropRectangle() {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```


Get rectangle that defines the area that will be converted into a picture. The default is null, in which case the all image is converted to a page

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### setCropRectangle(Rectangle cropRectangle) {#setCropRectangle-com.aspose.pdf.Rectangle-}
```
public void setCropRectangle(Rectangle cropRectangle)
```


Set rectangle that defines the area that will be converted into a picture. The default is null, in which case the all image is converted to a page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cropRectangle | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

