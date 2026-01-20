---
title: System::Drawing::Imaging::ImageFlags enum
linktitle: ImageFlags
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::ImageFlags enum. Represents attributes of the pixel data represented by an Image object in C++.'
type: docs
weight: 2200
url: /cpp/system.drawing.imaging/imageflags/
---
## ImageFlags enum


Represents attributes of the pixel data represented by an [Image](../../system.drawing/image/) object.

```cpp
enum class ImageFlags
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | 0 |  |
| Scalable | 1 | Scalable. |
| HasAlpha | 2 | Contains alpha information. |
| HasTranslucent | 4 | There are alpha values greater than 0 and less than 255. |
| PartiallyScalable | 8 |  |
| ColorSpaceRgb | 16 | The pixel data is represented in RGB color space. |
| ColorSpaceCmyk | 32 | The pixel data is represented in CMYK color space. |
| ColorSpaceGray | 64 | The pixel data is grayscale. |
| ColorSpaceYcbcr | 128 | The pixel data is represented in YCBCR color space. |
| ColorSpaceYcck | 256 | The pixel data is represented in YCCK color space. |
| HasRealDpi | 4096 | The DPI information is stored in the image. |
| HasRealPixelSize | 8192 | The size of a pixel is stored in the image. |
| ReadOnly | 65536 | The pixel data is read-only. |
| Caching | 131072 | Can be cached for faster access. |

## See Also

* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
