---
title: OptimizationOptions
second_title: Aspose.PDF for Java API Reference
description: Class which describes document optimization algorithm.
type: docs
weight: 13
url: /java/com.aspose.pdf.optimization/optimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class OptimizationOptions
```

Class which describes document optimization algorithm. Instance of this class may be used as parameter of OptimizeResources() method.
## Constructors

| Constructor | Description |
| --- | --- |
| [OptimizationOptions()](#OptimizationOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [isCompressObjects()](#isCompressObjects--) | If this flag is set to  , Pdf objects will be packed into Objest Streams and compressed to reduce pdf file size. |
| [setCompressObjects(boolean value)](#setCompressObjects-boolean-) | If this flag is set to  , Pdf objects will be packed into Objest Streams and compressed to reduce pdf file size. |
| [getLinkDuplcateStreams()](#getLinkDuplcateStreams--) | If this flag is set to true, Resource streams will be analyzed. |
| [setLinkDuplcateStreams(boolean value)](#setLinkDuplcateStreams-boolean-) | If this flag is set to true, Resource streams will be analyzed. |
| [getAllowReusePageContent()](#getAllowReusePageContent--) | If true page contents will be reused when document is optimized for equal pages. |
| [setAllowReusePageContent(boolean value)](#setAllowReusePageContent-boolean-) | If true page contents will be reused when document is optimized for equal pages. |
| [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | If this flag set to true, every resource is checked on it's usage. |
| [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | If this flag set to true, every resource is checked on it's usage. |
| [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | If this flag is set to true, all document objects will be checked and unused objects (i.e. |
| [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | If this flag is set to true, all document objects will be checked and unused objects (i.e. |
| [getImageCompressionOptions()](#getImageCompressionOptions--) | Set of options which describe will images in the document be compressed and parameters of the compression. |
| [setImageCompressionOptions(ImageCompressionOptions value)](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Set of options which describe will images in the document be compressed and parameters of the compression. |
| [getCompressImages()](#getCompressImages--) | If this flag is set to true images will be compressed in the document. |
| [setCompressImages(boolean value)](#setCompressImages-boolean-) | If this flag is set to true images will be compressed in the document. |
| [getResizeImages()](#getResizeImages--) | If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter. |
| [setResizeImages(boolean value)](#setResizeImages-boolean-) | If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter. |
| [getImageQuality()](#getImageQuality--) | Specifies level of image compression when CompressIamges flag is used. |
| [setImageQuality(int value)](#setImageQuality-int-) | Specifies level of image compression when CompressIamges flag is used. |
| [getMaxResoultion()](#getMaxResoultion--) | Specifies maximum resolution of images. |
| [setMaxResoultion(int value)](#setMaxResoultion-int-) | Specifies maximum resolution of images. |
| [getUnembedFonts()](#getUnembedFonts--) | Make fonts not embedded if set to true. |
| [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | Make fonts not embedded if set to true. |
| [getSubsetFonts()](#getSubsetFonts--) | Fonts will be converted into subsets if set to true. |
| [setSubsetFonts(boolean value)](#setSubsetFonts-boolean-) | Fonts will be converted into subsets if set to true. |
| [getRemovePrivateInfo()](#getRemovePrivateInfo--) | Remove private information (page piece info). |
| [setRemovePrivateInfo(boolean value)](#setRemovePrivateInfo-boolean-) | Remove private information (page piece info). |
| [getImageEncoding()](#getImageEncoding--) | Image encodre which will be used. |
| [setImageEncoding(int value)](#setImageEncoding-int-) | Image encodre which will be used. |
| [all()](#all--) | Creates optimization strategy will all options activated. |
### OptimizationOptions() {#OptimizationOptions--}
```
public OptimizationOptions()
```


### isCompressObjects() {#isCompressObjects--}
```
public final boolean isCompressObjects()
```


If this flag is set to  , Pdf objects will be packed into Objest Streams and compressed to reduce pdf file size.

**Returns:**
boolean - boolean value
### setCompressObjects(boolean value) {#setCompressObjects-boolean-}
```
public final void setCompressObjects(boolean value)
```


If this flag is set to  , Pdf objects will be packed into Objest Streams and compressed to reduce pdf file size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getLinkDuplcateStreams() {#getLinkDuplcateStreams--}
```
public final boolean getLinkDuplcateStreams()
```


If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then those streams will be stored as one object. This allows to decrease document size in some cases (for example, when same document was concatenated multiple times).

**Returns:**
boolean - boolean value
### setLinkDuplcateStreams(boolean value) {#setLinkDuplcateStreams-boolean-}
```
public final void setLinkDuplcateStreams(boolean value)
```


If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then those streams will be stored as one object. This allows to decrease document size in some cases (for example, when same document was concatenated multiple times).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getAllowReusePageContent() {#getAllowReusePageContent--}
```
public final boolean getAllowReusePageContent()
```


If true page contents will be reused when document is optimized for equal pages.

**Returns:**
boolean - boolean value
### setAllowReusePageContent(boolean value) {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```


If true page contents will be reused when document is optimized for equal pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. This may decrease document size for example when pages were extracted from document.

**Returns:**
boolean - boolean value
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. This may decrease document size for example when pages were extracted from document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document.

**Returns:**
boolean - boolean value
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getImageCompressionOptions() {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```


Set of options which describe will images in the document be compressed and parameters of the compression.

**Returns:**
[ImageCompressionOptions](../../com.aspose.pdf.optimization/imagecompressionoptions) - ImageCompressionOptions instance
### setImageCompressionOptions(ImageCompressionOptions value) {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
```
public final void setImageCompressionOptions(ImageCompressionOptions value)
```


Set of options which describe will images in the document be compressed and parameters of the compression.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ImageCompressionOptions](../../com.aspose.pdf.optimization/imagecompressionoptions) | ImageCompressionOptions instance |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property.

**Returns:**
boolean - boolean value
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getResizeImages() {#getResizeImages--}
```
public final boolean getResizeImages()
```


If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter.

**Returns:**
boolean - boolean value
### setResizeImages(boolean value) {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```


If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Specifies level of image compression when CompressIamges flag is used.

**Returns:**
int - int value
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Specifies level of image compression when CompressIamges flag is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getMaxResoultion() {#getMaxResoultion--}
```
public final int getMaxResoultion()
```


Specifies maximum resolution of images. If image has higher resolition it will be scaled

**Returns:**
int - int value
### setMaxResoultion(int value) {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```


Specifies maximum resolution of images. If image has higher resolition it will be scaled

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


Make fonts not embedded if set to true.

**Returns:**
boolean - boolean value
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


Make fonts not embedded if set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getSubsetFonts() {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```


Fonts will be converted into subsets if set to true.

**Returns:**
boolean - boolean value
### setSubsetFonts(boolean value) {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```


Fonts will be converted into subsets if set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getRemovePrivateInfo() {#getRemovePrivateInfo--}
```
public final boolean getRemovePrivateInfo()
```


Remove private information (page piece info).

**Returns:**
boolean - boolean value
### setRemovePrivateInfo(boolean value) {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```


Remove private information (page piece info).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getImageEncoding() {#getImageEncoding--}
```
public final int getImageEncoding()
```


Image encodre which will be used.

**Returns:**
int - ImageEncoding element
### setImageEncoding(int value) {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```


Image encodre which will be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ImageEncoding element |

### all() {#all--}
```
public static OptimizationOptions all()
```


Creates optimization strategy will all options activated. Please note that activated only options which does not change any functionality of the document. I.e. image compressing and fonts unembedding will not enabled (and can be embedded manually).

**Returns:**
[OptimizationOptions](../../com.aspose.pdf.optimization/optimizationoptions) - OptimizationOptions object.
