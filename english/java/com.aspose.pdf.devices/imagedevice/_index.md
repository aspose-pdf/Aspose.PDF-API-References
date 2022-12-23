---
title: ImageDevice
second_title: Aspose.PDF for Java API Reference
description: An abstract class for image devices.
type: docs
weight: 20
url: /java/com.aspose.pdf.devices/imagedevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice)
```
public abstract class ImageDevice extends PageDevice
```

An abstract class for image devices.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImageDevice()](#ImageDevice--) | Abstract initializer for  ImageDevice  descendants, set resolution to 150x150. |
| [ImageDevice(Resolution resolution)](#ImageDevice-com.aspose.pdf.devices.Resolution-) | Abstract initializer for  ImageDevice  descendants. |
| [ImageDevice(int width, int height)](#ImageDevice-int-int-) | Initializes a new instance of the  JpegDevice  class with provided image dimensions and default resolution (=150). |
| [ImageDevice(PageSize pageSize)](#ImageDevice-com.aspose.pdf.PageSize-) | Initializes a new instance of the  JpegDevice  class with provided image dimensions and default resolution (=150). |
| [ImageDevice(int width, int height, Resolution resolution)](#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  JpegDevice  class with provided image dimensions and resolution. |
| [ImageDevice(PageSize pageSize, Resolution resolution)](#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  JpegDevice  class with provided image dimensions and resolution. |
## Methods

| Method | Description |
| --- | --- |
| [isShadingPerformanceHigh()](#isShadingPerformanceHigh--) | Is the performance of shading processes High. |
| [setShadingPerformanceHigh(boolean value)](#setShadingPerformanceHigh-boolean-) | Sets the the performance of shading processes High or not. |
| [getCoordinateType()](#getCoordinateType--) | Gets the page coordinate type (Media/Crop boxes). |
| [setCoordinateType(int value)](#setCoordinateType-int-) | Sets the page coordinate type (Media/Crop boxes). |
| [getRenderingOptions()](#getRenderingOptions--) | Gets rendering options. |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Sets rendering options. |
| [getFormPresentationMode()](#getFormPresentationMode--) | Gets form presentation mode. |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) | Sets form presentation mode. |
| [getResolution()](#getResolution--) | Gets image resolution. |
| [getWidth()](#getWidth--) | Gets image output width. |
| [getHeight()](#getHeight--) | Gets image output height. |
| [getCropRectangle()](#getCropRectangle--) | Get rectangle that defines the area that will be converted into a picture. |
| [setCropRectangle(Rectangle cropRectangle)](#setCropRectangle-com.aspose.pdf.Rectangle-) | Set rectangle that defines the area that will be converted into a picture. |
### ImageDevice() {#ImageDevice--}
```
public ImageDevice()
```


Abstract initializer for  ImageDevice  descendants, set resolution to 150x150.

### ImageDevice(Resolution resolution) {#ImageDevice-com.aspose.pdf.devices.Resolution-}
```
public ImageDevice(Resolution resolution)
```


Abstract initializer for  ImageDevice  descendants.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### ImageDevice(int width, int height) {#ImageDevice-int-int-}
```
public ImageDevice(int width, int height)
```


Initializes a new instance of the  JpegDevice  class with provided image dimensions and default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |

### ImageDevice(PageSize pageSize) {#ImageDevice-com.aspose.pdf.PageSize-}
```
public ImageDevice(PageSize pageSize)
```


Initializes a new instance of the  JpegDevice  class with provided image dimensions and default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |

### ImageDevice(int width, int height, Resolution resolution) {#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-}
```
public ImageDevice(int width, int height, Resolution resolution)
```


Initializes a new instance of the  JpegDevice  class with provided image dimensions and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### ImageDevice(PageSize pageSize, Resolution resolution) {#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
```
public ImageDevice(PageSize pageSize, Resolution resolution)
```


Initializes a new instance of the  JpegDevice  class with provided image dimensions and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### isShadingPerformanceHigh() {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```


Is the performance of shading processes High.
By default it true.

**Returns:**
boolean - boolean value
### setShadingPerformanceHigh(boolean value) {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```


Sets the the performance of shading processes High or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getCoordinateType() {#getCoordinateType--}
```
public int getCoordinateType()
```


Gets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

**Returns:**
int - PageCoordinateType element
### setCoordinateType(int value) {#setCoordinateType-int-}
```
public void setCoordinateType(int value)
```


Sets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PageCoordinateType element |

### getRenderingOptions() {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```


Gets rendering options.

**Returns:**
[RenderingOptions](../../com.aspose.pdf/renderingoptions) - RenderingOptions element
### setRenderingOptions(RenderingOptions value) {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
```
public void setRenderingOptions(RenderingOptions value)
```


Sets rendering options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RenderingOptions](../../com.aspose.pdf/renderingoptions) | RenderingOptions element |

### getFormPresentationMode() {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```


Gets form presentation mode.

**Returns:**
int - FormPresentationMode element
### setFormPresentationMode(int value) {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```


Sets form presentation mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | FormPresentationMode element |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Gets image resolution.

**Returns:**
[Resolution](../../com.aspose.pdf.devices/resolution) - Resolution element
### getWidth() {#getWidth--}
```
public int getWidth()
```


Gets image output width.

**Returns:**
int - int value
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets image output height.

**Returns:**
int - int value
### getCropRectangle() {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```


Get rectangle that defines the area that will be converted into a picture. The default is null, in which case the whole page is converted to an image.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### setCropRectangle(Rectangle cropRectangle) {#setCropRectangle-com.aspose.pdf.Rectangle-}
```
public void setCropRectangle(Rectangle cropRectangle)
```


Set rectangle that defines the area that will be converted into a picture. The default is null, in which case the whole page is converted to an image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cropRectangle | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

