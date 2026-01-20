---
title: System::Drawing::Drawing2D::ColorBlend class
linktitle: ColorBlend
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Drawing2D::ColorBlend class. Contains arrays of colors and positions used for interpolating color blending in a multicolor gradient. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.drawing.drawing2d/colorblend/
---
## ColorBlend class


Contains arrays of colors and positions used for interpolating color blending in a multicolor gradient. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ColorBlend : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [ColorBlend](./colorblend/)() | Constructs a new instance of [ColorBlend](./) class. |
| [ColorBlend](./colorblend/)(int) | Constructs a new instance of [Blend](../blend/) class. |
| [get_Colors](./get_colors/)() | Returns an array of colors to use at corresponding positions along a gradient. |
| [get_Positions](./get_positions/)() | Returns the array of blend positions along a gradient. |
| [set_Colors](./set_colors/)(const ArrayPtr\<Color\>\&) | Sets an array of colors to use at corresponding positions along a gradient. |
| [set_Positions](./set_positions/)(const ArrayPtr\<float\>\&) | Sets the array of blend positions along a gradient. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
