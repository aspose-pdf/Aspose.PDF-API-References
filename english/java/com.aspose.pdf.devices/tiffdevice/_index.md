---
title: TiffDevice
second_title: Aspose.PDF for Java API Reference
description: This class helps to save pdf document page by page into the one tiff image.
type: docs
weight: 28
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
| [TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings)](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(int width, int height, Resolution resolution)](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(PageSize pageSize, Resolution resolution)](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(int width, int height, TiffSettings settings)](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(int width, int height, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(PageSize pageSize, TiffSettings settings, IIndexBitmapConverter converter)](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(PageSize pageSize, TiffSettings settings)](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(int width, int height)](#TiffDevice-int-int-) | Initializes a new instance of the  TiffDevice  class. |
| [TiffDevice(PageSize pageSize)](#TiffDevice-com.aspose.pdf.PageSize-) | Initializes a new instance of the  TiffDevice  class. |
## Methods

| Method | Description |
| --- | --- |
| [binarizeBradley(InputStream inputImageStream, OutputStream outputImageStream, double threshold)](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | Do Bradley binarization for input stream. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCropRectangle()](#getCropRectangle--) | Get rectangle that defines the area that will be converted into a picture. |
| [getFormPresentationMode()](#getFormPresentationMode--) | Gets form presentation mode. |
| [getHeight()](#getHeight--) | Gets image output height. |
| [getRenderingOptions()](#getRenderingOptions--) | Gets rendering options. |
| [getResolution()](#getResolution--) | Gets image resolution. |
| [getSettings()](#getSettings--) | Gets settings for mapping pdf into tiff image. |
| [getWidth()](#getWidth--) | Gets image output width. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [process(IDocument document, int fromPage, int toPage, OutputStream output)](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Converts certain document pages into tiff and save it in the output stream. |
| [process(IDocument document, int fromPage, int toPage, String outputFileName)](#process-com.aspose.pdf.IDocument-int-int-java.lang.String-) | Processes certain pages of the document and saves results into file. |
| [process(IDocument document, OutputStream output)](#process-com.aspose.pdf.IDocument-java.io.OutputStream-) | Processes the whole document and saves results into stream. |
| [process(IDocument document, String outputFileName)](#process-com.aspose.pdf.IDocument-java.lang.String-) | Processes the whole document and saves results into file. |
| [processInternal(IDocument document, System.IO.Stream output)](#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Processes the whole document and saves results into stream. |
| [processInternal(IDocument document, int fromPage, int toPage, System.IO.Stream output)](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Converts certain document pages into tiff and save it in the output stream. |
| [setCropRectangle(Rectangle cropRectangle)](#setCropRectangle-com.aspose.pdf.Rectangle-) | Set rectangle that defines the area that will be converted into a picture. |
| [setFormPresentationMode(int value)](#setFormPresentationMode-int-) | Gets form presentation mode. |
| [setRenderingOptions(RenderingOptions value)](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Sets rendering options. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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

### TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings) {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |
| resolution | [Resolution](../../com.aspose.pdf.devices/resolution) | Resolution for the output image. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff settings, see  TiffSettings  class. |

### TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(PageSize pageSize, Resolution resolution, TiffSettings settings, IIndexBitmapConverter converter)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |
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

### TiffDevice(PageSize pageSize, Resolution resolution) {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
```
public TiffDevice(PageSize pageSize, Resolution resolution)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |
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

### TiffDevice(PageSize pageSize, TiffSettings settings, IIndexBitmapConverter converter) {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
```
public TiffDevice(PageSize pageSize, TiffSettings settings, IIndexBitmapConverter converter)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |
| settings | [TiffSettings](../../com.aspose.pdf.devices/tiffsettings) | Tiff settings, see  TiffSettings  class. |
| converter | [IIndexBitmapConverter](../../com.aspose.pdf/iindexbitmapconverter) | External converter |

### TiffDevice(PageSize pageSize, TiffSettings settings) {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
```
public TiffDevice(PageSize pageSize, TiffSettings settings)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |
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

### TiffDevice(PageSize pageSize) {#TiffDevice-com.aspose.pdf.PageSize-}
```
public TiffDevice(PageSize pageSize)
```


Initializes a new instance of the  TiffDevice  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.aspose.pdf/pagesize) | Page size of the output image. |

### binarizeBradley(InputStream inputImageStream, OutputStream outputImageStream, double threshold) {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
```
public void binarizeBradley(InputStream inputImageStream, OutputStream outputImageStream, double threshold)
```


Do Bradley binarization for input stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputImageStream | java.io.InputStream | The input image stream. |
| outputImageStream | java.io.OutputStream | The output image stream. |
| threshold | double | The threshold value between 0.0 and 1.0. |

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
### getCropRectangle() {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```


Get rectangle that defines the area that will be converted into a picture. The default is null, in which case the all image is converted to a page

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Rectangle object
### getFormPresentationMode() {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```


Gets form presentation mode.

**Returns:**
int - FormPresentationMode value
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
[RenderingOptions](../../com.aspose.pdf/renderingoptions) - rendering options.
### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Gets image resolution.

**Returns:**
[Resolution](../../com.aspose.pdf.devices/resolution) - Resolution element
### getSettings() {#getSettings--}
```
public TiffSettings getSettings()
```


Gets settings for mapping pdf into tiff image.

**Returns:**
[TiffSettings](../../com.aspose.pdf.devices/tiffsettings) - TiffSettings element
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### process(IDocument document, int fromPage, int toPage, OutputStream output) {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
```
public void process(IDocument document, int fromPage, int toPage, OutputStream output)
```


Converts certain document pages into tiff and save it in the output stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | The document to convert. |
| fromPage | int | Defines page number from which converting will start. |
| toPage | int | Defines page number which will end the converting. |
| output | java.io.OutputStream | Output stream with tiff image. |

### process(IDocument document, int fromPage, int toPage, String outputFileName) {#process-com.aspose.pdf.IDocument-int-int-java.lang.String-}
```
public void process(IDocument document, int fromPage, int toPage, String outputFileName)
```


Processes certain pages of the document and saves results into file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | The document to process. |
| fromPage | int | The first page to start processing. |
| toPage | int | The last page of processing. |
| outputFileName | java.lang.String | Defines file where the results of processing are stored. |

### process(IDocument document, OutputStream output) {#process-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public void process(IDocument document, OutputStream output)
```


Processes the whole document and saves results into stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | The document to process. |
| output | java.io.OutputStream | Defines stream where the results of processing are stored. |

### process(IDocument document, String outputFileName) {#process-com.aspose.pdf.IDocument-java.lang.String-}
```
public void process(IDocument document, String outputFileName)
```


Processes the whole document and saves results into file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | The document to process. |
| outputFileName | java.lang.String | Defines file where the results of processing are stored. |

### processInternal(IDocument document, System.IO.Stream output) {#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
```
public void processInternal(IDocument document, System.IO.Stream output)
```


Processes the whole document and saves results into stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | The document to process. |
| output | com.aspose.ms.System.IO.Stream | Defines stream where the results of processing are stored. |

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

### setCropRectangle(Rectangle cropRectangle) {#setCropRectangle-com.aspose.pdf.Rectangle-}
```
public void setCropRectangle(Rectangle cropRectangle)
```


Set rectangle that defines the area that will be converted into a picture. The default is null, in which case the all image is converted to a page

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cropRectangle | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle object |

### setFormPresentationMode(int value) {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```


Gets form presentation mode.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setRenderingOptions(RenderingOptions value) {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
```
public void setRenderingOptions(RenderingOptions value)
```


Sets rendering options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [RenderingOptions](../../com.aspose.pdf/renderingoptions) | rendering options. |

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

