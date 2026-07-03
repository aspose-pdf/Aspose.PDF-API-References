---
title: OptimizationOptions
second_title: Aspose.PDF for Java API Reference
description: Class which describes document optimization algorithm. Instance of this class may be used as parameter of OptimizeResources() method.
type: docs
weight: 40
url: /java/com.aspose.pdf.optimization/optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions

```
public class OptimizationOptions extends Object
```

Class which describes document optimization algorithm. Instance of this class may be used as parameter of OptimizeResources() method.

## Constructors

| Constructor | Description |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) |  |

## Methods

| Method | Description |
| --- | --- |
| [all](#all--) | Creates optimization strategy will all options activated. Please note that activated only options which does not change any functionality of the document. I.e. image compressing and fonts unembedding will not enabled (and can be embedded manually). |
| [getCompressAllContentStreams](#getCompressAllContentStreams--) | If set to {@link}, all uncompressed page content streams will be compressed using the FlateDecode filter during {@code Document#OptimizeResources()}. Default is {@link} to preserve backward compatibility. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Set of options which describe will images in the document be compressed and parameters of the compression. |
| [getImageEncoding](#getImageEncoding--) | Image encodre which will be used. |
| [getImageQuality](#getImageQuality--) | Specifies level of image compression when CompressIamges flag is used. |
| [getMaxResoultion](#getMaxResoultion--) | Specifies maximum resolution of images. If image has higher resolition it will be scaled |
| [isAllowReusePageContent](#isAllowReusePageContent--) | If true page contents will be reused when document is optimized for equal pages. |
| [isCompressImages](#isCompressImages--) | If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property. |
| [isCompressObjects](#isCompressObjects--) | If this flag is set to {@code }, Pdf objects will be packed into Objest Streams and compressed to reduce pdf file size. |
| [isLinkDuplicateStreams](#isLinkDuplicateStreams--) | If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then those streams will be stored as one object. This allows to decrease document size in some cases (for example, when same document was concatenated multiple times). |
| [isRemovePrivateInfo](#isRemovePrivateInfo--) | Remove private information (page piece info). |
| [isRemoveUnusedObjects](#isRemoveUnusedObjects--) | If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document. |
| [isRemoveUnusedStreams](#isRemoveUnusedStreams--) | If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. This may decrease document size for example when pages were extracted from document. |
| [isResizeImages](#isResizeImages--) | If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter. |
| [isSubsetFonts](#isSubsetFonts--) | Fonts will be converted into subsets if set to true. |
| [isUnembedFonts](#isUnembedFonts--) | Make fonts not embedded if set to true. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | If true page contents will be reused when document is optimized for equal pages. |
| [setCompressAllContentStreams](#setCompressAllContentStreams-boolean-) | If set to {@link}, all uncompressed page content streams will be compressed using the FlateDecode filter during {@code Document#OptimizeResources()}. Default is {@link} to preserve backward compatibility. |
| [setCompressImages](#setCompressImages-boolean-) | If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property. |
| [setCompressObjects](#setCompressObjects-boolean-) | If this flag is set to {@code }, Pdf objects will be packed into Objest Streams and compressed to reduce pdf file size. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Set of options which describe will images in the document be compressed and parameters of the compression. |
| [setImageEncoding](#setImageEncoding-int-) | Image encodre which will be used. |
| [setImageQuality](#setImageQuality-int-) | Specifies level of image compression when CompressIamges flag is used. |
| [setLinkDuplicateStreams](#setLinkDuplicateStreams-boolean-) | If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then those streams will be stored as one object. This allows to decrease document size in some cases (for example, when same document was concatenated multiple times). |
| [setMaxResoultion](#setMaxResoultion-int-) | Specifies maximum resolution of images. If image has higher resolition it will be scaled |
| [setRemovePrivateInfo](#setRemovePrivateInfo-boolean-) | Remove private information (page piece info). |
| [setRemoveUnusedObjects](#setRemoveUnusedObjects-boolean-) | If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document. |
| [setRemoveUnusedStreams](#setRemoveUnusedStreams-boolean-) | If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. This may decrease document size for example when pages were extracted from document. |
| [setResizeImages](#setResizeImages-boolean-) | If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Fonts will be converted into subsets if set to true. |
| [setUnembedFonts](#setUnembedFonts-boolean-) | Make fonts not embedded if set to true. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```



### all {#all--}
```
public static OptimizationOptions all()
```

Creates optimization strategy will all options activated. Please note that activated only options which does not change any functionality of the document. I.e. image compressing and fonts unembedding will not enabled (and can be embedded manually).

**Returns:**
OptimizationOptions object.

### getCompressAllContentStreams {#getCompressAllContentStreams--}
```
public final boolean getCompressAllContentStreams()
```

If set to {@link}, all uncompressed page content streams will be compressed using the FlateDecode filter during {@code Document#OptimizeResources()}. Default is {@link} to preserve backward compatibility.

**Returns:**
boolean value

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Set of options which describe will images in the document be compressed and parameters of the compression.

**Returns:**
ImageCompressionOptions instance

### getImageEncoding {#getImageEncoding--}
```
public final int getImageEncoding()
```

Image encodre which will be used.

**Returns:**
ImageEncoding element

### getImageQuality {#getImageQuality--}
```
@Deprecated public final int getImageQuality()
```

Specifies level of image compression when CompressIamges flag is used.

**Returns:**
int value @deprecated Please use ImageCompressionOptions.ImageQuality instead.

### getMaxResoultion {#getMaxResoultion--}
```
public final int getMaxResoultion()
```

Specifies maximum resolution of images. If image has higher resolition it will be scaled

**Returns:**
int value

### isAllowReusePageContent {#isAllowReusePageContent--}
```
public final boolean isAllowReusePageContent()
```

If true page contents will be reused when document is optimized for equal pages.

**Returns:**
boolean value

### isCompressImages {#isCompressImages--}
```
@Deprecated public final boolean isCompressImages()
```

If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property.

**Returns:**
boolean value @deprecated Please use ImageCompressionOptions.CompressImages instead.

### isCompressObjects {#isCompressObjects--}
```
public final boolean isCompressObjects()
```

If this flag is set to {@code }, Pdf objects will be packed into Objest Streams and compressed to reduce pdf file size.

**Returns:**
boolean value

### isLinkDuplicateStreams {#isLinkDuplicateStreams--}
```
public final boolean isLinkDuplicateStreams()
```

If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then those streams will be stored as one object. This allows to decrease document size in some cases (for example, when same document was concatenated multiple times).

**Returns:**
boolean value

### isRemovePrivateInfo {#isRemovePrivateInfo--}
```
public final boolean isRemovePrivateInfo()
```

Remove private information (page piece info).

**Returns:**
boolean value

### isRemoveUnusedObjects {#isRemoveUnusedObjects--}
```
public final boolean isRemoveUnusedObjects()
```

If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document.

**Returns:**
boolean value

### isRemoveUnusedStreams {#isRemoveUnusedStreams--}
```
public final boolean isRemoveUnusedStreams()
```

If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. This may decrease document size for example when pages were extracted from document.

**Returns:**
boolean value

### isResizeImages {#isResizeImages--}
```
@Deprecated public final boolean isResizeImages()
```

If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter.

**Returns:**
boolean value @deprecated Please use ImageCompressionOptions.ResizeImages instead.

### isSubsetFonts {#isSubsetFonts--}
```
public final boolean isSubsetFonts()
```

Fonts will be converted into subsets if set to true.

**Returns:**
boolean value

### isUnembedFonts {#isUnembedFonts--}
```
public final boolean isUnembedFonts()
```

Make fonts not embedded if set to true.

**Returns:**
boolean value

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```

If true page contents will be reused when document is optimized for equal pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setCompressAllContentStreams {#setCompressAllContentStreams-boolean-}
```
public final void setCompressAllContentStreams(boolean value)
```

If set to {@link}, all uncompressed page content streams will be compressed using the FlateDecode filter during {@code Document#OptimizeResources()}. Default is {@link} to preserve backward compatibility.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setCompressImages {#setCompressImages-boolean-}
```
@Deprecated public final void setCompressImages(boolean value)
```

If this flag is set to true images will be compressed in the document. compression level is specfied with ImageQuality property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value @deprecated Please use ImageCompressionOptions.CompressImages instead. |

### setCompressObjects {#setCompressObjects-boolean-}
```
public final void setCompressObjects(boolean value)
```

If this flag is set to {@code }, Pdf objects will be packed into Objest Streams and compressed to reduce pdf file size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Set of options which describe will images in the document be compressed and parameters of the compression.

### setImageEncoding {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```

Image encodre which will be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | ImageEncoding element |

### setImageQuality {#setImageQuality-int-}
```
@Deprecated public final void setImageQuality(int value)
```

Specifies level of image compression when CompressIamges flag is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value @deprecated Please use ImageCompressionOptions.ImageQuality instead. |

### setLinkDuplicateStreams {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```

If this flag is set to true, Resource streams will be analyzed. If duplicate streams are found (i.e. if stream contents is equal), then those streams will be stored as one object. This allows to decrease document size in some cases (for example, when same document was concatenated multiple times).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setMaxResoultion {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```

Specifies maximum resolution of images. If image has higher resolition it will be scaled

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setRemovePrivateInfo {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```

Remove private information (page piece info).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRemoveUnusedObjects {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```

If this flag is set to true, all document objects will be checked and unused objects (i.e. objects which does not have any reference) are removed from document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRemoveUnusedStreams {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```

If this flag set to true, every resource is checked on it's usage. If resource is never used, then resources is removed. This may decrease document size for example when pages were extracted from document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setResizeImages {#setResizeImages-boolean-}
```
@Deprecated public final void setResizeImages(boolean value)
```

If this flag set to true and CompressImages is true images will be resized if image resoultion is greater then specified MaxResolution parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value @deprecated Please use ImageCompressionOptions.ResizeImages instead. |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Fonts will be converted into subsets if set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setUnembedFonts {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```

Make fonts not embedded if set to true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
