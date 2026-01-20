---
title: System::Drawing::FontFamily class
linktitle: FontFamily
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::FontFamily class. Represents a group of type faces that share a similar basic design. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 900
url: /cpp/system.drawing/fontfamily/
---
## FontFamily class


Represents a group of type faces that share a similar basic design. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FontFamily : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() | Returns a copy of the current [FontFamily](./) object. |
| [Dispose](./dispose/)() | Releases all operating system resources acquired by the current object. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determines if the current and the specified objects are identical. |
| [FontFamily](./fontfamily/)(const String\&) | Constructs a new instance of [FontFamily](./) class that represents a font family with the specified name. |
| [FontFamily](./fontfamily/)(const String\&, const SharedPtr\<Text::FontCollection\>\&) | Constructs a new instance of [FontFamily](./) in the specified FontCollection with the specified name. |
| [FontFamily](./fontfamily/)(Text::GenericFontFamilies) | Constructs a new instance of [FontFamily](./) from the specified generic font family. |
| static [get_Families](./get_families/)() | Returns an array containing all [FontFamily](./) objects associated with the current graphics context. |
| static [get_GenericMonospace](./get_genericmonospace/)() | Returns a [FontFamily](./) object that represents a Generic Monospace font family. |
| static [get_GenericSansSerif](./get_genericsansserif/)() | Returns a [FontFamily](./) object that represents a Generic Sans Serif font family. |
| static [get_GenericSerif](./get_genericserif/)() | Returns a [FontFamily](./) object that represents a Generic Serif font family. |
| [get_Name](./get_name/)() const | Returns the name of the font family represented by the current object. |
| [GetCellAscent](./getcellascent/)(FontStyle) | Returns the cell ascent of the font family represented by the current object for the specified font style. |
| [GetCellDescent](./getcelldescent/)(FontStyle) | Returns the cell descent of the font family represented by the current object for the specified font style. |
| [GetEmHeight](./getemheight/)(FontStyle) | Returns the height of em square in font design units for the specified style. |
| [GetLineSpacing](./getlinespacing/)(FontStyle) | Returns the line spacing of the font family represented by the current object for the specified font style. |
| [GetName](./getname/)(int) const | Returns the name of the font family represented by the current object. |
| [IsStyleAvailable](./isstyleavailable/)(FontStyle) | Determines if the specified font style is available. |
| virtual [~FontFamily](./~fontfamily/)() | Destructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
