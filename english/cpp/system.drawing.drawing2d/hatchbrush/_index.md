---
title: System::Drawing::Drawing2D::HatchBrush class
linktitle: HatchBrush
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Drawing2D::HatchBrush class. Represents a rectangular brush with a hatch style, a foreground color, and a background color. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 800
url: /cpp/system.drawing.drawing2d/hatchbrush/
---
## HatchBrush class


Represents a rectangular brush with a hatch style, a foreground color, and a background color. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HatchBrush : public System::Drawing::Brush
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Creates an exact copy of the current object. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Returns a value that indicates the background color of this brush. |
| [get_ForegroundColor](./get_foregroundcolor/)() const | Returns a value that indicates the foreground color of this brush. |
| [get_HatchStyle](./get_hatchstyle/)() const | Returns a value that indicates the hatch style of this brush. |
| [HatchBrush](./hatchbrush/)(HatchStyle, Color, Color) | RTTI information. |
## See Also

* Class [Brush](../../system.drawing/brush/)
* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.PDF for C++](../../)
