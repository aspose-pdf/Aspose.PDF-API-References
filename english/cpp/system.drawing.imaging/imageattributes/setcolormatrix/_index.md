---
title: System::Drawing::Imaging::ImageAttributes::SetColorMatrix method
linktitle: SetColorMatrix
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::ImageAttributes::SetColorMatrix method. Sets the color-adjustment matrix in C++.'
type: docs
weight: 1700
url: /cpp/system.drawing.imaging/imageattributes/setcolormatrix/
---
## ImageAttributes::SetColorMatrix method


Sets the color-adjustment matrix.

```cpp
void System::Drawing::Imaging::ImageAttributes::SetColorMatrix(const SharedPtr<ColorMatrix> &newColorMatrix, ColorMatrixFlag mode=ColorMatrixFlag::Default, ColorAdjustType type=ColorAdjustType::Default)
```


| Parameter | Type | Description |
| --- | --- | --- |
| newColorMatrix | const SharedPtr\<ColorMatrix\>\& | The color-adjustment matrix to set |
| mode | ColorMatrixFlag | Specifies the type of image and color that will be affected by the color-adjustment matrix |
| type | ColorAdjustType | Specifies the type of objects for which the color-adjustment matrix is set |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ColorMatrix](../../colormatrix/)
* Enum [ColorMatrixFlag](../../colormatrixflag/)
* Enum [ColorAdjustType](../../coloradjusttype/)
* Class [ImageAttributes](../)
* Namespace [System::Drawing::Imaging](../../)
* Library [Aspose.PDF for C++](../../../)
