---
title: System::Drawing::Imaging::ColorPalette class
linktitle: ColorPalette
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Imaging::ColorPalette class. Represents a set of 32-bit ARGB colors that make up a color palette. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 400
url: /cpp/system.drawing.imaging/colorpalette/
---
## ColorPalette class


Represents a set of 32-bit ARGB colors that make up a color palette. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ColorPalette : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Entries](./get_entries/)() const | Returns an array of [Color](../../system.drawing/color/) objects represented by the current object. |
| [get_Flags](./get_flags/)() const | Returns a value that specifies how the color values in the array of colors should be interpreted. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
