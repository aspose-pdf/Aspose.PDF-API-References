---
title: PngDevice
second_title: Aspose.PDF for Java API Reference
description: Represents image device that helps to save pdf document pages into png.
type: docs
weight: 23
url: /java/com.aspose.pdf.devices/pngdevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.devices.Device](../../com.aspose.pdf.devices/device), [com.aspose.pdf.devices.PageDevice](../../com.aspose.pdf.devices/pagedevice), [com.aspose.pdf.devices.ImageDevice](../../com.aspose.pdf.devices/imagedevice)
```
public final class PngDevice extends ImageDevice
```

Represents image device that helps to save pdf document pages into png.
## Constructors

| Constructor | Description |
| --- | --- |
| [PngDevice()](#PngDevice--) | Initializes a new instance of the  PngDevice  class with default resolution. |
| [PngDevice(Resolution resolution)](#PngDevice-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  PngDevice  class. |
| [PngDevice(int width, int height, Resolution resolution)](#PngDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  PngDevice  class with provided image dimensions and resolution. |
| [PngDevice(PageSize pageSize, Resolution resolution)](#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  PngDevice  class with provided page size and resolution. |
| [PngDevice(int width, int height)](#PngDevice-int-int-) | Initializes a new instance of the  PngDevice  class with provided image dimensions, default resolution (=150). |
| [PngDevice(PageSize pageSize)](#PngDevice-com.aspose.pdf.PageSize-) | Initializes a new instance of the  PngDevice  class with provided page size, default resolution (=150). |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCoordinateType()](#getCoordinateType--) | Gets the page coordinate type (Media/Crop boxes). |
| [getCropRectangle()](#getCropRectangle--) | Get rectangle that defines the area that will be converted into a picture. |
| [getFormPresentationMode()](#getFormPresentationMode--) | Gets form presentation mode. |
| [getHeight()](#getHeight--) | Gets image output height. |
| [getRenderingOptions()](#getRenderingOptions--) | Gets rendering options. |
| [getResolution()](#getResolution--) | Gets image resolution. |
| [getWidth()](#getWidth--) | Gets image output width. |
| [hashCode()](#hashCode--) |  |
| [isShadingPerformanceHigh()](#isShadingPerformanceHigh--) | Is the performance of shading processes High. |
| [isTransparentBackground()](#isTransparentBackground--) | Gets or sets if image has transparent background. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [process(Page page, System.Drawing.Graphics gr)](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | Renders page on the graphics |
| [process(Page page, OutputStream output)](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converts the page into png and saves it in the output stream. |
| [process(Page page, String outputFileName)](#process-com.aspose.pdf.Page-java.lang.String-) | Performs some operation on the given page and saves results into the file. |
| [processInternal(Page page, System.IO.Stream output)](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converts the page into png and saves it in the output stream. |
| [processToBufferedImage(Page page)](#processToBufferedImage-com.aspose.pdf.Page-) | Converts the page into BufferedImage. |
| [processToBufferedImageBinarized(Page page, double threshold)](#processToBufferedImageBinarized-com.aspose.pdf.Page-double-) | Converts the page into BufferedImage with Bradley binarization. |
| [setCoordinateType(int value)](#setCoordinateType-int-) | Sets the page coordinate type (Media/Crop boxes). |
| [setCropRectangle(Rectangle cropRectangle)](#setCropRectangle-com.aspose.pdf.Rectangle-) | Set rectangle that defines the area that will be converted into a picture. |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) | Sets form presentation mode. |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Sets rendering options. |
| [setShadingPerformanceHigh(boolean value)](#setShadingPerformanceHigh-boolean-) | Sets the the performance of shading processes High or not. |
| [setTransparentBackground(boolean value)](#setTransparentBackground-boolean-) | Gets or sets if image has transparent background. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PngDevice() {#PngDevice--}
```
public PngDevice()
```


Initializes a new instance of the  PngDevice  class with default resolution.

### PngDevice(Resolution resolution) {#PngDevice-com.aspose.pdf.devices.Resolution-}
```
public PngDevice(Resolution resolution)
```


Initializes a new instance of the  PngDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### PngDevice(int width, int height, Resolution resolution) {#PngDevice-int-int-com.aspose.pdf.devices.Resolution-}
```
public PngDevice(int width, int height, Resolution resolution)
```


Initializes a new instance of the  PngDevice  class with provided image dimensions and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### PngDevice(PageSize pageSize, Resolution resolution) {#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
```
public PngDevice(PageSize pageSize, Resolution resolution)
```


Initializes a new instance of the  PngDevice  class with provided page size and resolution.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the result image file, see  Resolution  class. |

### PngDevice(int width, int height) {#PngDevice-int-int-}
```
public PngDevice(int width, int height)
```


Initializes a new instance of the  PngDevice  class with provided image dimensions, default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | Image output width. |
| height | int | Image output height. |

### PngDevice(PageSize pageSize) {#PngDevice-com.aspose.pdf.PageSize-}
```
public PngDevice(PageSize pageSize)
```


Initializes a new instance of the  PngDevice  class with provided page size, default resolution (=150).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCoordinateType() {#getCoordinateType--}
```
public int getCoordinateType()
```


Gets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

**Returns:**
int - PageCoordinateType element
### getCropRectangle() {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```


Get rectangle that defines the area that will be converted into a picture. The default is null, in which case the whole page is converted to an image.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### getFormPresentationMode() {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```


Gets form presentation mode.

**Returns:**
int - FormPresentationMode element
### getHeight() {#getHeight--}
```
public int getHeight()
```


Gets image output height.

**Returns:**
int - int value
### getRenderingOptions() {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```


Gets rendering options.

**Returns:**
[RenderingOptions](../../com.aspose.pdf/renderingoptions) - RenderingOptions element
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isShadingPerformanceHigh() {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```


Is the performance of shading processes High.
By default it true.

**Returns:**
boolean - boolean value
### isTransparentBackground() {#isTransparentBackground--}
```
public final boolean isTransparentBackground()
```


Gets or sets if image has transparent background.

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### process(Page page, System.Drawing.Graphics gr) {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
```
public void process(Page page, System.Drawing.Graphics gr)
```


Renders page on the graphics

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | Page object |
| gr | com.aspose.ms.System.Drawing.Graphics | internal object |

### process(Page page, OutputStream output) {#process-com.aspose.pdf.Page-java.io.OutputStream-}
```
public void process(Page page, OutputStream output)
```


Converts the page into png and saves it in the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | java.io.OutputStream | Output stream with png image. |

### process(Page page, String outputFileName) {#process-com.aspose.pdf.Page-java.lang.String-}
```
public void process(Page page, String outputFileName)
```


Performs some operation on the given page and saves results into the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to process. |
| outputFileName | java.lang.String | This file contains the results of processing. |

### processInternal(Page page, System.IO.Stream output) {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(Page page, System.IO.Stream output)
```


Converts the page into png and saves it in the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| output | com.aspose.ms.System.IO.Stream | Output stream with png image. |

### processToBufferedImage(Page page) {#processToBufferedImage-com.aspose.pdf.Page-}
```
public BufferedImage processToBufferedImage(Page page)
```


Converts the page into BufferedImage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |

**Returns:**
java.awt.image.BufferedImage - BufferedImage Output BufferedImage image.
### processToBufferedImageBinarized(Page page, double threshold) {#processToBufferedImageBinarized-com.aspose.pdf.Page-double-}
```
public BufferedImage processToBufferedImageBinarized(Page page, double threshold)
```


Converts the page into BufferedImage with Bradley binarization.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | The page to convert. |
| threshold | double | The threshold value between 0.0 and 1.0. |

**Returns:**
java.awt.image.BufferedImage - BufferedImage Output BufferedImage image.
### setCoordinateType(int value) {#setCoordinateType-int-}
```
public void setCoordinateType(int value)
```


Sets the page coordinate type (Media/Crop boxes). CropBox value is used by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PageCoordinateType element |

### setCropRectangle(Rectangle cropRectangle) {#setCropRectangle-com.aspose.pdf.Rectangle-}
```
public void setCropRectangle(Rectangle cropRectangle)
```


Set rectangle that defines the area that will be converted into a picture. The default is null, in which case the whole page is converted to an image.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cropRectangle | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

### setFormPresentationMode(int value) {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```


Sets form presentation mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | FormPresentationMode element |

### setRenderingOptions(RenderingOptions value) {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
```
public void setRenderingOptions(RenderingOptions value)
```


Sets rendering options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RenderingOptions](../../com.aspose.pdf/renderingoptions) | RenderingOptions element |

### setShadingPerformanceHigh(boolean value) {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```


Sets the the performance of shading processes High or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setTransparentBackground(boolean value) {#setTransparentBackground-boolean-}
```
public final void setTransparentBackground(boolean value)
```


Gets or sets if image has transparent background.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

