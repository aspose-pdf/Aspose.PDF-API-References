---
title: System::Drawing::CopyPixelOperation enum
linktitle: CopyPixelOperation
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::CopyPixelOperation enum. Specifies how the source color in a pixel copying operation is combined with the destination color to result in a final color in C++.'
type: docs
weight: 3000
url: /cpp/system.drawing/copypixeloperation/
---
## CopyPixelOperation enum


Specifies how the source color in a pixel copying operation is combined with the destination color to result in a final color.

```cpp
enum class CopyPixelOperation
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| NoMirrorBitmap | n/a | The bitmap is not mirrored. |
| Blackness | 66 | The destination region is filled by using the color with index 0 in the physical palette. |
| NotSourceErase | 1114278 | The source and destination colors are ORed and the color that results is then inverted. |
| NotSourceCopy | 3342344 | The source region is inverted and then copied to the destination. |
| SourceErase | 4457256 | The inverted colors of the destination region are ANDed with the colors of the source region. |
| DestinationInvert | 5570569 | The destination region is inverted. |
| PatInvert | 5898313 | The colors of the brush currently selected in the destination device context are XORed with the colors of the destination. |
| SourceInvert | 6684742 | The colors of the source and destination regions are XORed. |
| SourceAnd | 8913094 | The colors of the source and destination regions are ANDed. |
| MergePaint | 12255782 | The colors of the inverted source region are ORed with the colors of the destination region. |
| MergeCopy | 12583114 | The colors of the source region are ANDed with the colors of the selected brush of the destination device context. |
| SourceCopy | 13369376 | The source region is copied directly to the destination region. |
| SourcePaint | 15597702 | The colors of the source and destination regions are ORed. |
| PatCopy | 15728673 | The brush currently selected in the destination device context is copied to the destination bitmap. |
| PatPaint | 16452105 | The colors of the brush currently selected in the destination device context are ORed with the colors of the inverted source region. The result of this operation is ORed with the colors of the destination region. |
| Whiteness | 16711778 | The destination region is filled by using the color with index 1 in the physical palette. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) that are layered on top of application's window are included in the resulting image. |

## See Also

* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
