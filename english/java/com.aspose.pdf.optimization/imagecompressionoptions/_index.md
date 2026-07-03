---
title: ImageCompressionOptions
linktitle: ImageCompressionOptions
second_title: Aspose.PDF for Java API Reference
description: Class contains set options for image compression.
type: docs
weight: 10
url: /java/com.aspose.pdf.optimization/imagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.ImageCompressionOptions

```
public class ImageCompressionOptions extends Object
```

Class contains set options for image compression.

## Constructors

| Constructor | Description |
| --- | --- |
| [ImageCompressionOptions](#ImageCompressionOptions--) |  |

## Methods

| Method | Description |
| --- | --- |
| [getEncoding](#getEncoding--) | Gets or sets encoding used to store images. |
| [getImageQuality](#getImageQuality--) | Specifies level of image compression when CompressImages flag is used. |
| [getMaxResolution](#getMaxResolution--) | Specifies maximum resolution of images. If image has higher resolution it will be scaled |
| [getResizeImages](#getResizeImages--) | If this flag set to true and CompressImages is true images will be resized if image resolution is greater than specified MaxResolution parameter. |
| [getVersion](#getVersion--) | Version of compression algorithm. Possible values are: 1. standard compression, 2. fast (improved compression which is faster then standard but may be applicable not for all images), 3. mixed (standard compression is applied to images which can not be compressed by faster algorithm, this may give best compression but more slow then "fast" algorithm. Version "Fast" is not applicable for resizing images (standard method will be used). Default is "Standard". |
| [isCompressImages](#isCompressImages--) | If this flag is set to true images will be compressed in the document. Compression level is specified with ImageQuality property. |
| [setCompressImages](#setCompressImages-boolean-) | If this flag is set to true images will be compressed in the document. Compression level is specified with ImageQuality property. |
| [setEncoding](#setEncoding-int-) | Gets or sets encoding used to store images. |
| [setImageQuality](#setImageQuality-int-) | Specifies level of image compression when CompressImages flag is used. |
| [setMaxResolution](#setMaxResolution-int-) | Specifies maximum resolution of images. If image has higher resolution it will be scaled |
| [setResizeImages](#setResizeImages-boolean-) | If this flag set to true and CompressImages is true images will be resized if image resolution is greater than specified MaxResolution parameter. |
| [setVersion](#setVersion-int-) | Version of compression algorithm. Possible values are: 1. standard compression, 2. fast (improved compression which is faster then standard but may be applicable not for all images), 3. mixed (standard compression is applied to images which can not be compressed by faster algorithm, this may give best compression but more slow then "fast" algorithm. Version "Fast" is not applicable for resizing images (standard method will be used). Default is "Standard". |

### ImageCompressionOptions {#ImageCompressionOptions--}
```
public ImageCompressionOptions()
```



### getEncoding {#getEncoding--}
```
public final int getEncoding()
```

Gets or sets encoding used to store images.

**Returns:**
ImageEncoding element

### getImageQuality {#getImageQuality--}
```
public final int getImageQuality()
```

Specifies level of image compression when CompressImages flag is used.

**Returns:**
int value

### getMaxResolution {#getMaxResolution--}
```
public final int getMaxResolution()
```

Specifies maximum resolution of images. If image has higher resolution it will be scaled

**Returns:**
int value

### getResizeImages {#getResizeImages--}
```
public final boolean getResizeImages()
```

If this flag set to true and CompressImages is true images will be resized if image resolution is greater than specified MaxResolution parameter.

**Returns:**
boolean value

### getVersion {#getVersion--}
```
public final int getVersion()
```

Version of compression algorithm. Possible values are: 1. standard compression, 2. fast (improved compression which is faster then standard but may be applicable not for all images), 3. mixed (standard compression is applied to images which can not be compressed by faster algorithm, this may give best compression but more slow then "fast" algorithm. Version "Fast" is not applicable for resizing images (standard method will be used). Default is "Standard".

**Returns:**
int value

### isCompressImages {#isCompressImages--}
```
public final boolean isCompressImages()
```

If this flag is set to true images will be compressed in the document. Compression level is specified with ImageQuality property.

**Returns:**
boolean value

### setCompressImages {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```

If this flag is set to true images will be compressed in the document. Compression level is specified with ImageQuality property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setEncoding {#setEncoding-int-}
```
public final void setEncoding(int value)
```

Gets or sets encoding used to store images.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | ImageEncoding element |

### setImageQuality {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```

Specifies level of image compression when CompressImages flag is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setMaxResolution {#setMaxResolution-int-}
```
public final void setMaxResolution(int value)
```

Specifies maximum resolution of images. If image has higher resolution it will be scaled

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |

### setResizeImages {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```

If this flag set to true and CompressImages is true images will be resized if image resolution is greater than specified MaxResolution parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setVersion {#setVersion-int-}
```
public final void setVersion(int value)
```

Version of compression algorithm. Possible values are: 1. standard compression, 2. fast (improved compression which is faster then standard but may be applicable not for all images), 3. mixed (standard compression is applied to images which can not be compressed by faster algorithm, this may give best compression but more slow then "fast" algorithm. Version "Fast" is not applicable for resizing images (standard method will be used). Default is "Standard".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value |
