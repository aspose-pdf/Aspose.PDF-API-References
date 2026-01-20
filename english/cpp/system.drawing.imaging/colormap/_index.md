---
title: System::Drawing::Imaging::ColorMap class
linktitle: ColorMap
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::ColorMap class. Represents a map for converting colors. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 200
url: /cpp/system.drawing.imaging/colormap/
---
## ColorMap class


Represents a map for converting colors. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ColorMap : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_NewColor](./get_newcolor/)() const | Returns the new [Color](../../system.drawing/color/) object representing the color to which to convert. |
| [get_OldColor](./get_oldcolor/)() const | Returns the old [Color](../../system.drawing/color/) object representing the color to be converted. |
| [set_NewColor](./set_newcolor/)(const Color\&) | Sets the new [Color](../../system.drawing/color/) object representing the color to which to convert. |
| [set_OldColor](./set_oldcolor/)(const Color\&) | Sets the old [Color](../../system.drawing/color/) object representing the color to be converted. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
