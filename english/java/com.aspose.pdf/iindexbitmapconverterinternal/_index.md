---
title: IIndexBitmapConverterInternal
second_title: Aspose.PDF for Java API Reference
description: This interface declared for customization algorithms of quantization.
type: docs
weight: 440
url: /java/com.aspose.pdf/iindexbitmapconverterinternal/
---```
public interface IIndexBitmapConverterInternal
```

This interface declared for customization algorithms of quantization. Users can implement their own realization of this algorithms (for example algorithms based on unmanaged code).
## Methods

| Method | Description |
| --- | --- |
| [get1BppImageInternal(System.Drawing.Bitmap src)](#get1BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-) | Internal only Returns 1Bpp bitmap representation |
| [get4BppImageInternal(System.Drawing.Bitmap src)](#get4BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-) | Internal only Returns 4Bpp bitmap representation |
| [get8BppImageInternal(System.Drawing.Bitmap src)](#get8BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-) | Internal only Returns 8Bpp bitmap representation |
### get1BppImageInternal(System.Drawing.Bitmap src) {#get1BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-}
```
public abstract System.Drawing.Bitmap get1BppImageInternal(System.Drawing.Bitmap src)
```


Internal only Returns 1Bpp bitmap representation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | com.aspose.ms.System.Drawing.Bitmap | Source bitmap. |

**Returns:**
com.aspose.ms.System.Drawing.Bitmap - Bitmap in 1 bpp image format.
### get4BppImageInternal(System.Drawing.Bitmap src) {#get4BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-}
```
public abstract System.Drawing.Bitmap get4BppImageInternal(System.Drawing.Bitmap src)
```


Internal only Returns 4Bpp bitmap representation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | com.aspose.ms.System.Drawing.Bitmap | Source bitmap. |

**Returns:**
com.aspose.ms.System.Drawing.Bitmap - Bitmap in 4 bpp image format.
### get8BppImageInternal(System.Drawing.Bitmap src) {#get8BppImageInternal-com.aspose.ms.System.Drawing.Bitmap-}
```
public abstract System.Drawing.Bitmap get8BppImageInternal(System.Drawing.Bitmap src)
```


Internal only Returns 8Bpp bitmap representation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| src | com.aspose.ms.System.Drawing.Bitmap | Source bitmap. |

**Returns:**
com.aspose.ms.System.Drawing.Bitmap - Bitmap in 8 bpp image format.
