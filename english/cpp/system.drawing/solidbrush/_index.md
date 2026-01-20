---
title: System::Drawing::SolidBrush class
linktitle: SolidBrush
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::SolidBrush class. Represents single-color brush. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 2400
url: /cpp/system.drawing/solidbrush/
---
## SolidBrush class


Represents single-color brush. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SolidBrush : public System::Drawing::Brush
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Creates a copy of the current object. |
| [get_Color](./get_color/)() const | Returns this brush's color. |
| [set_Color](./set_color/)(Color) | Sets the color of this brush. |
| [SolidBrush](./solidbrush/)(const Color\&) | Constructs a new [SolidBrush](./) object and initalizes it with the specified color. |
## See Also

* Class [Brush](../brush/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
