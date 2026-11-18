---
title: System::Drawing::Imaging::ImageAttributes::ClearColorKey method
linktitle: ClearColorKey
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::ImageAttributes::ClearColorKey method. Clears the color key for the specified category in C++.'
type: docs
weight: 300
url: /cpp/system.drawing.imaging/imageattributes/clearcolorkey/
---
## ImageAttributes::ClearColorKey method


Clears the color key for the specified category.

```cpp
void System::Drawing::Imaging::ImageAttributes::ClearColorKey(ColorAdjustType type=ColorAdjustType::Default)
```


| Parameter | Type | Description |
| --- | --- | --- |
| type | ColorAdjustType | The category for which the color key is cleared. |
## Remarks



[Color](../../../system.drawing/color/) keys are currently applied only by supported [Graphics::DrawImage](../../../system.drawing/graphics/drawimage/) overloads. Only the Default and [Bitmap](../../../system.drawing/bitmap/) adjustment categories affect image rendering. 

## See Also

* Enum [ColorAdjustType](../../coloradjusttype/)
* Class [ImageAttributes](../)
* Namespace [System::Drawing::Imaging](../../)
* Library [Aspose.PDF for C++](../../../)
