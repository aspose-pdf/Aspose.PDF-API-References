---
title: ImagesDifference
linktitle: ImagesDifference
second_title: Aspose.PDF for Java API Reference
description: Represents the result class of comparing two PDF pages.
type: docs
weight: 20
url: /java/com.aspose.pdf.comparison.graphicalcomparison/imagesdifference/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.ImagesDifference

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class ImagesDifference extends Object implements com.aspose.ms.System.IDisposable
```

Represents the result class of comparing two PDF pages.

## Methods

| Method | Description |
| --- | --- |
| [differenceToImage](#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Converts the difference array to a bitmap image using the specified colors. |
| [dispose](#dispose--) | Performs any necessary clean up operations before the object is destroyed. |
| [getDestinationImage](#getDestinationImage--) | Returns a new bitmap representing the destination image by applying the difference array to the source image. |
| [getDifference](#getDifference--) | Gets the difference array. This array is similar to the original image data array obtained as a result of the LockBits method. |
| [getHeight](#getHeight--) | The height of difference. |
| [getSourceImage](#getSourceImage--) | Gets the image of first compared page. The image has a pixel format is 24bpp. |
| [getStride](#getStride--) | The stride of difference image data. |

### differenceToImage {#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Converts the difference array to a bitmap image using the specified colors.

### dispose {#dispose--}
```
public final void dispose()
```

Performs any necessary clean up operations before the object is destroyed.

### getDestinationImage {#getDestinationImage--}
```
public final BufferedImage getDestinationImage()
```

Returns a new bitmap representing the destination image by applying the difference array to the source image.

**Returns:**
A destination image.

### getDifference {#getDifference--}
```
public final int[] getDifference()
```

Gets the difference array. This array is similar to the original image data array obtained as a result of the LockBits method.

**Returns:**
int[] array

### getHeight {#getHeight--}
```
public final int getHeight()
```

The height of difference.

**Returns:**
int value

### getSourceImage {#getSourceImage--}
```
public final BufferedImage getSourceImage()
```

Gets the image of first compared page. The image has a pixel format is 24bpp.

**Returns:**
BufferedImage instance

### getStride {#getStride--}
```
public final int getStride()
```

The stride of difference image data.

**Returns:**
int value
