---
title: System::Drawing::Imaging::ImageAttributes class
linktitle: ImageAttributes
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::ImageAttributes class. Represents information about how image colors are manipulated during rendering. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 900
url: /cpp/system.drawing.imaging/imageattributes/
---
## ImageAttributes class


Represents information about how image colors are manipulated during rendering. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ImageAttributes : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [ClearBrushRemapTable](./clearbrushremaptable/)() | NOT IMPLEMENTED. |
| [ClearColorKey](./clearcolorkey/)(ColorAdjustType) | NOT IMPLEMENTED. |
| [ClearColorMatrix](./clearcolormatrix/)(ColorAdjustType) | NOT IMPLEMENTED. |
| [ClearGamma](./cleargamma/)(ColorAdjustType) | NOT IMPLEMENTED. |
| [ClearNoOp](./clearnoop/)(ColorAdjustType) | NOT IMPLEMENTED. |
| [ClearOutputChannel](./clearoutputchannel/)(ColorAdjustType) | NOT IMPLEMENTED. |
| [ClearOutputChannelColorProfile](./clearoutputchannelcolorprofile/)(ColorAdjustType) | NOT IMPLEMENTED. |
| [ClearRemapTable](./clearremaptable/)(ColorAdjustType) | NOT IMPLEMENTED. |
| [ClearThreshold](./clearthreshold/)(ColorAdjustType) | NOT IMPLEMENTED. |
| [Clone](./clone/)() | Creates a copy of the current object. |
| [Dispose](./dispose/)() | Releases all operating system resources acquired by the current object. |
| [GetAdjustedPalette](./getadjustedpalette/)(const SharedPtr\<ColorPalette\>\&, ColorAdjustType) | NOT IMPLEMENTED. |
| [ImageAttributes](./imageattributes/)() | Default constructor. |
| [SetBrushRemapTable](./setbrushremaptable/)(const ArrayPtr\<SharedPtr\<ColorMap\>\>\&) | NOT IMPLEMENTED. |
| [SetColorKey](./setcolorkey/)(Color, Color, ColorAdjustType) | NOT IMPLEMENTED. |
| [SetColorMatrices](./setcolormatrices/)(const SharedPtr\<ColorMatrix\>\&, const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) | NOT IMPLEMENTED. |
| [SetColorMatrix](./setcolormatrix/)(const SharedPtr\<ColorMatrix\>\&, ColorMatrixFlag, ColorAdjustType) | Sets the color-adjustment matrix. |
| [SetGamma](./setgamma/)(float, ColorAdjustType) | NOT IMPLEMENTED. |
| [SetNoOp](./setnoop/)(ColorAdjustType) | NOT IMPLEMENTED. |
| [SetOutputChannel](./setoutputchannel/)(ColorChannelFlag, ColorAdjustType) | NOT IMPLEMENTED. |
| [SetOutputChannelColorProfile](./setoutputchannelcolorprofile/)(const String\&, ColorAdjustType) | NOT IMPLEMENTED. |
| [SetRemapTable](./setremaptable/)(const ArrayPtr\<SharedPtr\<ColorMap\>\>\&, ColorAdjustType) | NOT IMPLEMENTED. |
| [SetThreshold](./setthreshold/)(float, ColorAdjustType) | NOT IMPLEMENTED. |
| [SetWrapMode](./setwrapmode/)(Drawing2D::WrapMode, Color, bool) | Sets the wrap mode and color used to decide how to tile a texture across a shape, or at shape boundaries. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
