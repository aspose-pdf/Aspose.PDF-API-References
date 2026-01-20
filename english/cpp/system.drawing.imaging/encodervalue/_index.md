---
title: System::Drawing::Imaging::EncoderValue enum
linktitle: EncoderValue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::EncoderValue enum. Specifies the parameter value passed to a JPEG or TIFF image encoder in C++.'
type: docs
weight: 2100
url: /cpp/system.drawing.imaging/encodervalue/
---
## EncoderValue enum


Specifies the parameter value passed to a JPEG or TIFF image encoder.

```cpp
enum class EncoderValue
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| ColorTypeCMYK | 0 | The CMYK color space. |
| ColorTypeYCCK | 1 | The YCCK color space. |
| CompressionLZW | 2 | The LZW compression method. |
| CompressionCCITT3 | 3 | Specifies the CCITT3 compression method for a TIFF image. |
| CompressionCCITT4 | 4 | Specifies the CCITT4 compression method for a TIFF image. |
| CompressionRle | 5 | Specifies he RLE compression method for a TIFF image. |
| CompressionNone | 6 | Specifies no compression for a TIFF image. |
| ScanMethodInterlaced | 7 | Interlaced mode. |
| ScanMethodNonInterlaced | 8 | Non-interlaced mode. |
| VersionGif87 | 9 | Specifies version 87 for a TIFF image. |
| VersionGif89 | 10 | Specifies version 89a for a GIF image. |
| RenderProgressive | 11 | Progressive mode. |
| RenderNonProgressive | 12 | Non-progressive mode. |
| TransformRotate90 | 13 | Specifies lossless 90-degree clockwise rotation for a JPEG image. |
| TransformRotate180 | 14 | Specifies lossless 180-degree rotation for a JPEG image. |
| TransformRotate270 | 15 | Specifies lossless 270-degree clockwise rotation for a JPEG image. |
| TransformFlipHorizontal | 16 | Specifies a lossless horizontal flip for a JPEG image. |
| TransformFlipVertical | 17 | Specifies a lossless vertical flip for a JPEG image. |
| MultiFrame | 18 | Multiframe encoding. |
| LastFrame | 19 | The last frame of a multiframe image. |
| Flush | 20 | The encoder object is to be closed. |
| FrameDimensionTime | 21 | Specifies the time frame dimension for a GIF image. |
| FrameDimensionResolution | 22 | The resolution frame dimension. |
| FrameDimensionPage | 23 | Specifies the page frame dimension for a TIFF image. |

## See Also

* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
