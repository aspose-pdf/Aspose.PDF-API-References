---
title: ImageDevice
linktitle: ImageDevice
second_title: Aspose.PDF for Java API Reference
description: An abstract class for image devices.
type: docs
weight: 110
url: /java/com.aspose.pdf.devices/imagedevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice

```
public abstract class ImageDevice extends PageDevice
```

An abstract class for image devices.

## Constructors

| Constructor | Description |
| --- | --- |
| [ImageDevice](#ImageDevice--) | Abstract initializer for {@code ImageDevice} descendants, set resolution to 150x150. |
| [ImageDevice](#ImageDevice-int-int-) | Initializes a new instance of the {@code JpegDevice} class with provided image dimensions and default resolution (=150). |
| [ImageDevice](#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-) | Abstract initializer for {@code ImageDevice} descendants, set resolution to 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-) | Abstract initializer for {@code ImageDevice} descendants, set resolution to 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Abstract initializer for {@code ImageDevice} descendants, set resolution to 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.devices.Resolution-) | Abstract initializer for {@code ImageDevice} descendants, set resolution to 150x150. |

## Methods

| Method | Description |
| --- | --- |
| [getBitmap](#getBitmap-com.aspose.pdf.Page-) | Converts the page into {@link java.awt.image.BufferedImage}. |
| [getCoordinateType](#getCoordinateType--) | Gets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [getCropRectangle](#getCropRectangle--) | Get rectangle that defines the area that will be converted into a picture. The default is null, in which case the whole page is converted to an image. |
| [getFormPresentationMode](#getFormPresentationMode--) | Gets form presentation mode. |
| [getHeight](#getHeight--) | Gets image output height. |
| [getRenderingOptions](#getRenderingOptions--) | Gets rendering options. |
| [getResolution](#getResolution--) | Gets image resolution. |
| [getWidth](#getWidth--) | Gets image output width. |
| [isShadingPerformanceHigh](#isShadingPerformanceHigh--) | Is the performance of shading processes High. By default it true. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Sets the page coordinate type (Media/Crop boxes). CropBox value is used by default. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Set rectangle that defines the area that will be converted into a picture. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Sets form presentation mode. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Sets rendering options. |
| [setShadingPerformanceHigh](#setShadingPerformanceHigh-boolean-) | Sets the the performance of shading processes High or not. |

### ImageDevice {#ImageDevice--}
```
public ImageDevice()
```

Abstract initializer for {@code ImageDevice} descendants, set resolution to 150x150.

### ImageDevice {#ImageDevice-int-int-}
```
public ImageDevice(int width, int height)
```

Initializes a new instance of the {@code JpegDevice} class with provided image dimensions and default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width |  | Image output width. |
| height |  | Image output height. |

### ImageDevice {#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-}
Abstract initializer for {@code ImageDevice} descendants, set resolution to 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-}
Abstract initializer for {@code ImageDevice} descendants, set resolution to 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Abstract initializer for {@code ImageDevice} descendants, set resolution to 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.devices.Resolution-}
Abstract initializer for {@code ImageDevice} descendants, set resolution to 150x150.

### getBitmap {#getBitmap-com.aspose.pdf.Page-}
Converts the page into {@link java.awt.image.BufferedImage}.

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Gets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

**Returns:**
PageCoordinateType element @see PageCoordinateType

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Get rectangle that defines the area that will be converted into a picture. The default is null, in which case the whole page is converted to an image.

**Returns:**
Rectangle object

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Gets form presentation mode.

**Returns:**
FormPresentationMode element @see FormPresentationMode

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
RenderingOptions element

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Gets image resolution.

**Returns:**
Resolution element

### getWidth {#getWidth--}
```
public int getWidth()
```

Gets image output width.

**Returns:**
int value

### isShadingPerformanceHigh {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```

Is the performance of shading processes High. By default it true.

**Returns:**
boolean value

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Sets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Set rectangle that defines the area that will be converted into a picture.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Sets form presentation mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | FormPresentationMode element @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Sets rendering options.

### setShadingPerformanceHigh {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```

Sets the the performance of shading processes High or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
