---
title: System::Drawing::Imaging::ImageAttributes::SetColorKey method
linktitle: SetColorKey
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::ImageAttributes::SetColorKey method. Sets the color range that is made transparent during rendering in C++.'
type: docs
weight: 1500
url: /cpp/system.drawing.imaging/imageattributes/setcolorkey/
---
## ImageAttributes::SetColorKey method


Sets the color range that is made transparent during rendering.

```cpp
void System::Drawing::Imaging::ImageAttributes::SetColorKey(Color colorLow, Color colorHigh, ColorAdjustType type=ColorAdjustType::Default)
```


| Parameter | Type | Description |
| --- | --- | --- |
| colorLow | Color | The lowest color-key value. |
| colorHigh | Color | The highest color-key value. |
| type | ColorAdjustType | The category for which the color key is set. |
## Remarks



[Color](../../../system.drawing/color/) keys are currently applied only by supported [Graphics::DrawImage](../../../system.drawing/graphics/drawimage/) overloads. Only the Default and [Bitmap](../../../system.drawing/bitmap/) adjustment categories affect image rendering. 

## See Also

* Class [Color](../../../system.drawing/color/)
* Enum [ColorAdjustType](../../coloradjusttype/)
* Class [ImageAttributes](../)
* Namespace [System::Drawing::Imaging](../../)
* Library [Aspose.PDF for C++](../../../)
