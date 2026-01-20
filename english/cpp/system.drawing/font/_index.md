---
title: System::Drawing::Font class
linktitle: Font
second_title: Aspose.PDF for C++ API Reference
description: 'System::Drawing::Font class. Represents a particular format for text, including font face, size, and style. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 700
url: /cpp/system.drawing/font/
---
## Font class


Represents a particular format for text, including font face, size, and style. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Font : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() | Returns a copy of the current font. |
| [Dispose](./dispose/)() | Releases all operating system resources acquired by the current object. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Determines if the current and the specified objects are identical. |
| [Font](./font/)(const SharedPtr\<Font\>\&, FontStyle) | Constructs a new instance of [Font](./) class that represents the specified existing font with the specified font style. |
| [Font](./font/)(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) | Constructs a new instance of [Font](./) class. |
| [Font](./font/)(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) | Constructs a new instance of [Font](./) class. |
| [Font](./font/)(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) | Constructs a new instance of [Font](./) class. |
| [Font](./font/)(const String\&, float, GraphicsUnit) | Constructs a new instance of [Font](./) class. |
| static [FromLogFont](./fromlogfont/)(const SharedPtr\<Object\>\&) | NOT IMPLEMENTED. |
| [get_Bold](./get_bold/)() | Determines if the font represented by the current object has the bold style applied. |
| [get_FontFamily](./get_fontfamily/)() | Returns the font family of the font represented by the current object. |
| [get_FontStyle](./get_fontstyle/)() | Returns the font style of the font represneted by the current object. |
| [get_GdiCharSet](./get_gdicharset/)() | Returns a value that indicates the GDI character set used by the font represented by the current object. |
| [get_Height](./get_height/)() | Returns the line spacing of the font represented by the current object in pixels. |
| [get_Italic](./get_italic/)() | Determines if the font represented by the current object has the italic style applied. |
| [get_Name](./get_name/)() | Returns the face name of the font represented by the current object. |
| [get_OriginalFontName](./get_originalfontname/)() | Returns the originally specified name of the font. |
| [get_Size](./get_size/)() | Returns the em size of the font represented by the current object measured in the units specified by the Unit property. |
| [get_SizeInPoints](./get_sizeinpoints/)() | Returns the em size of the font represented by the current object in points. |
| [get_Strikeout](./get_strikeout/)() | Determines if the font represented by the current object has the strikeout style applied. |
| [get_Style](./get_style/)() | Returns the font style of the font represented by the current object. |
| [get_Underline](./get_underline/)() | Determines if the font represented by the current object has the underline style applied. |
| [get_Unit](./get_unit/)() | Returns the measurement unit for the font represented by the current object. |
| [GetHeight](./getheight/)(const SharedPtr\<Graphics\>\&) | Returns the line spacing of the font represented by the current object, in the current unit of a specified [Graphics](../graphics/) object. |
| [GetHeight](./getheight/)(float) | Returns the height of the font represented by the current object when drawn to a display device with the specified vertical resolution. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Drawing](../)
* Library [Aspose.PDF for C++](../../)
