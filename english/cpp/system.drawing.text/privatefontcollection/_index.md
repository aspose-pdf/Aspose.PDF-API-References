---
title: System::Drawing::Text::PrivateFontCollection class
linktitle: PrivateFontCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Text::PrivateFontCollection class. Represents a collection of font families provided by the client application. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 300
url: /cpp/system.drawing.text/privatefontcollection/
---
## PrivateFontCollection class


Represents a collection of font families provided by the client application. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class PrivateFontCollection : public System::Drawing::Text::FontCollection
```

## Methods

| Method | Description |
| --- | --- |
| [AddFont](./addfont/)(const System::ArrayPtr\<uint8_t\>\&, int) | Adds the specified font to the collection. |
| [AddFontFile](./addfontfile/)(const String\&) | Adds a font from the specified file to the collection. |
| [get_Families](./get_families/)() override | Returns an array of [FontFamily](../../system.drawing/fontfamily/) objects associated with the font collection represented by the current object. |
## See Also

* Class [FontCollection](../fontcollection/)
* Namespace [System::Drawing::Text](../)
* Library [Aspose.PDF for C++](../../)
