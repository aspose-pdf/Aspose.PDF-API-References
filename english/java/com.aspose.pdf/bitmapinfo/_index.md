---
title: BitmapInfo
linktitle: BitmapInfo
second_title: Aspose.PDF for Java API Reference
description: Object containing array of pixels and bitmap information.
type: docs
weight: 300
url: /java/com.aspose.pdf/bitmapinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BitmapInfo

```
public class BitmapInfo extends Object
```

Object containing array of pixels and bitmap information.

## Constructors

| Constructor | Description |
| --- | --- |
| [BitmapInfo](#BitmapInfo-byte:A-int-int-int-) | Creates a new instance of the class. |

## Methods

| Method | Description |
| --- | --- |
| [getFormat](#getFormat--) | Gets the pixel format of the bitmap. |
| [getHeight](#getHeight--) | Gets the height of the bitmap. |
| [getPixelBytes](#getPixelBytes--) | Gets the array of pixels. |
| [getWidth](#getWidth--) | Gets the width of the bitmap. |

### BitmapInfo {#BitmapInfo-byte:A-int-int-int-}
```
public BitmapInfo(byte[] pixelBytes, int width, int height, int format)
```

Creates a new instance of the class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixelBytes |  | Array of pixels. |
| width |  | Width of the bitmap. |
| height |  | Height of the bitmap. |
| format |  | Pixel format of the bitmap. @see BitmapInfo |

### getFormat {#getFormat--}
```
public final int getFormat()
```

Gets the pixel format of the bitmap.

**Returns:**
int value PixelFormat element

### getHeight {#getHeight--}
```
public final int getHeight()
```

Gets the height of the bitmap.

**Returns:**
int value

### getPixelBytes {#getPixelBytes--}
```
public final byte[] getPixelBytes()
```

Gets the array of pixels.

**Returns:**
byte[] array

### getWidth {#getWidth--}
```
public final int getWidth()
```

Gets the width of the bitmap.

**Returns:**
int value
