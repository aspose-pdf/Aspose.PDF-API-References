---
title: Document.OptimizationOptions
second_title: Aspose.PDF for Java API Reference
description: Class which describes document optimization algorithm.
type: docs
weight: 10
url: /java/com.aspose.pdf/document.optimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.optimization.OptimizationOptions](../../com.aspose.pdf.optimization/optimizationoptions)
```
public static class Document.OptimizationOptions extends OptimizationOptions
```

Class which describes document optimization algorithm. Instance of this class may be used as parameter of OptimizeResources() method.
## Constructors

| Constructor | Description |
| --- | --- |
| [OptimizationOptions()](#OptimizationOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [all()](#all--) | Creates optimization strategy will all options activated. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowReusePageContent()](#getAllowReusePageContent--) | If true page contents will be reused when document is optimized for equal pages. |
| [getClass()](#getClass--) |  |
| [getCompressImages()](#getCompressImages--) | If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property. |
| [getImageCompressionOptions()](#getImageCompressionOptions--) | Set of options which describe will images in the document be compressed and parameters of the compression. |
| [getImageEncoding()](#getImageEncoding--) | Image encodre which will be used. |
| [getImageQuality()](#getImageQuality--) | Specifies level of image compression when CompressIamges flag is used. |
| [getLinkDuplcateStreams()](#getLinkDuplcateStreams--) | If this flag is set to true, Resource streams will be analyzed. |
| [getMaxResoultion()](#getMaxResoultion--) | Specifies maximum resolution of images. |
| [getMaximumImageDimension()](#getMaximumImageDimension--) | Specifies maximum image dimension. |
| [getRemovePrivateInfo()](#getRemovePrivateInfo--) | Remove private information (page piece info). |
| [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document. |
| [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | If this flag set to true, every resource is checked on it's usage. |
| [getResizeImages()](#getResizeImages--) | If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter. |
| [getResolution()](#getResolution--) | Specifies new image dpi when CompressIamges flag is used. |
| [getSubsetFonts()](#getSubsetFonts--) | Fonts will be converted into subsets if set to true. |
| [getUnembedFonts()](#getUnembedFonts--) | Make fonts not embedded if set to true. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowReusePageContent(boolean value)](#setAllowReusePageContent-boolean-) | If true page contents will be reused when document is optimized for equal pages. |
| [setCompressImages(boolean value)](#setCompressImages-boolean-) | If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property. |
| [setImageEncoding(int value)](#setImageEncoding-int-) | Image encodre which will be used. |
| [setImageQuality(int value)](#setImageQuality-int-) | Specifies level of image compression when CompressIamges flag is used. |
| [setLinkDuplcateStreams(boolean value)](#setLinkDuplcateStreams-boolean-) | If this flag is set to true, Resource streams will be analyzed. |
| [setMaxResoultion(int value)](#setMaxResoultion-int-) | Specifies maximum resolution of images. |
| [setMaximumImageDimension(int dimension)](#setMaximumImageDimension-int-) | Specifies maximum image dimension. |
| [setRemovePrivateInfo(boolean value)](#setRemovePrivateInfo-boolean-) | Remove private information (page piece info). |
| [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document. |
| [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | If this flag set to true, every resource is checked on it's usage. |
| [setResizeImages(boolean value)](#setResizeImages-boolean-) | If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter. |
| [setResolution(int dpi)](#setResolution-int-) | Specifies new image dpi when CompressIamges flag is used. |
| [setSubsetFonts(boolean value)](#setSubsetFonts-boolean-) | Fonts will be converted into subsets if set to true. |
| [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | Make fonts not embedded if set to true. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OptimizationOptions() {#OptimizationOptions--}
```
public OptimizationOptions()
```


### all() {#all--}
```
public static Document.OptimizationOptions all()
```


Creates optimization strategy will all options activated.

**Returns:**
[OptimizationOptions](../../com.aspose.pdf/optimizationoptions) - OptimizationOptions object.
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
### getAllowReusePageContent() {#getAllowReusePageContent--}
```
public final boolean getAllowReusePageContent()
```


If true page contents will be reused when document is optimized for equal pages.

**Returns:**
boolean - boolean value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property.

**Returns:**
boolean - boolean value
### getImageCompressionOptions() {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```


Set of options which describe will images in the document be compressed and parameters of the compression.

**Returns:**
[ImageCompressionOptions](../../com.aspose.pdf.optimization/imagecompressionoptions) - ImageCompressionOptions instance
### getImageEncoding() {#getImageEncoding--}
```
public final int getImageEncoding()
```


Image encodre which will be used.

**Returns:**
int - ImageEncoding element
### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Specifies level of image compression when CompressIamges flag is used.

**Returns:**
int - int value
### getLinkDuplcateStreams() {#getLinkDuplcateStreams--}
```
public final boolean getLinkDuplcateStreams()
```


If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then those streams will be stored as one object. This allows to decrease document size in some cases (for example, when same document was concatenated multiple times).

**Returns:**
boolean - boolean value
### getMaxResoultion() {#getMaxResoultion--}
```
public final int getMaxResoultion()
```


Specifies maximum resolution of images. If image has higher resolition it will be scaled

**Returns:**
int - int value
### getMaximumImageDimension() {#getMaximumImageDimension--}
```
public int getMaximumImageDimension()
```


Specifies maximum image dimension. If the image width or height of the existing image is greater than this value - the image size will be proportionally reduced.

**Returns:**
int - image maximum dimension
### getRemovePrivateInfo() {#getRemovePrivateInfo--}
```
public final boolean getRemovePrivateInfo()
```


Remove private information (page piece info).

**Returns:**
boolean - boolean value
### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document.

**Returns:**
boolean - boolean value
### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. This may decrease document size for example when pages were extracted from document.

**Returns:**
boolean - boolean value
### getResizeImages() {#getResizeImages--}
```
public final boolean getResizeImages()
```


If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter.

**Returns:**
boolean - boolean value
### getResolution() {#getResolution--}
```
public int getResolution()
```


Specifies new image dpi when CompressIamges flag is used.

**Returns:**
int - image resolution
### getSubsetFonts() {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```


Fonts will be converted into subsets if set to true.

**Returns:**
boolean - boolean value
### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


Make fonts not embedded if set to true.

**Returns:**
boolean - boolean value
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




### setAllowReusePageContent(boolean value) {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```


If true page contents will be reused when document is optimized for equal pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setImageEncoding(int value) {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```


Image encodre which will be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ImageEncoding element |

### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Specifies level of image compression when CompressIamges flag is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setLinkDuplcateStreams(boolean value) {#setLinkDuplcateStreams-boolean-}
```
public final void setLinkDuplcateStreams(boolean value)
```


If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then those streams will be stored as one object. This allows to decrease document size in some cases (for example, when same document was concatenated multiple times).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setMaxResoultion(int value) {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```


Specifies maximum resolution of images. If image has higher resolition it will be scaled

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setMaximumImageDimension(int dimension) {#setMaximumImageDimension-int-}
```
public void setMaximumImageDimension(int dimension)
```


Specifies maximum image dimension. If the image width or height of the existing image is greater than this value - the image size will be proportionally reduced.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dimension | int | image maximum dimension |

### setRemovePrivateInfo(boolean value) {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```


Remove private information (page piece info).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. This may decrease document size for example when pages were extracted from document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setResizeImages(boolean value) {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```


If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setResolution(int dpi) {#setResolution-int-}
```
public void setResolution(int dpi)
```


Specifies new image dpi when CompressIamges flag is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dpi | int | image resolution |

### setSubsetFonts(boolean value) {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```


Fonts will be converted into subsets if set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


Make fonts not embedded if set to true.

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

