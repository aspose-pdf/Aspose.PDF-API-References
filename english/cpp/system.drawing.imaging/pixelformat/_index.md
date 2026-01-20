---
title: System::Drawing::Imaging::PixelFormat enum
linktitle: PixelFormat
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::PixelFormat enum. Specifies the color data format of a pixel in C++.'
type: docs
weight: 2600
url: /cpp/system.drawing.imaging/pixelformat/
---
## PixelFormat enum


Specifies the color data format of a pixel.

```cpp
enum class PixelFormat
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Indexed | 65536 | Specifies that the pixel data contains color indexed values which means they are an index to colors in the system color table. |
| Gdi | 131072 | Specifies that the pixel data contains GDI colors. |
| Alpha | 262144 | Specifies that the pixel data contains alpha values which are not pre-multiplied. |
| PAlpha | 524288 | Specifies that the pixel data contains pre-multipled alpha values. |
| Extended | 1048576 | Reserved. |
| Canonical | 2097152 | Specifies the pixel format of 32 bits per pixel with 24-bit color depth and an 8-bit alpha channel. |
| Undefined | 0 | Specifies that the pixel format is undefined. |
| DontCare | 0 | The pixel format is not specified. |
| Format1bppIndexed | n/a | Specifies that pixel format is 1 bit per pixel indexed color. |
| Format4bppIndexed | n/a | Specifies that pixel format is 4 bits per pixel indexed color. |
| Format8bppIndexed | n/a | Specifies that pixel format is 8 bits per pixel indexed color. |
| Format16bppGrayScale | n/a | Specifies that the pixel format is 16 bits per pixel. The color information specifies 65536 shades of gray. |
| Format16bppRgb555 | n/a | Specifies that the pixel format is 16 bits per pixel with 5 bits for each of red, green, and blue components and remaining bit not used. |
| Format16bppRgb565 | n/a | Specifies that the pixel format is 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue components. |
| Format16bppArgb1555 | n/a | Specifies that the pixel format is 16 bits per pixel with 5 bits for each of red, green, and blue components and 1 bit for alpha. |
| Format24bppRgb | n/a | Specifies that the pixel format is 24 bits per pixel with 8 bits for each of red, green, and blue components. |
| Format32bppRgb | n/a | Specifies that the pixel format is 32 bits per pixel with 8 bits for each of red, green, and blue components and remaining 8 bits not used. |
| Format32bppArgb | n/a | Specifies that the pixel format is 32 bits per pixel with 8 bits for each of red, green, and blue components and 8 bits for alpha. |
| Format32bppPArgb | n/a | Specifies that the pixel format is 32 bits per pixel with 8 bits for each of red, green, and blue components and 8 bits for alpha. The red, green and blue components are pre-multiplied according to the value of alpha component. |
| Format48bppRgb | n/a | Specifies that the pixel format is 48 bits per pixel with 16 bits for each of red, green, and blue components. |
| Format64bppArgb | n/a | Specifies that the pixel format is 64 bits per pixel with 16 bits for each of red, green, and blue components and 16 bits for alpha. |
| Format64bppPArgb | n/a | Specifies that the pixel format is 64 bits per pixel with 16 bits for each of red, green, and blue components and 16 bits for alpha. The red, green and blue components are pre-multiplied according to the value of alpha component. |
| Format32bppCMYK | n/a | Specifies that the pixel format is 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and key components. |
| Max | 16 | The max value of this enum. |

## See Also

* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
