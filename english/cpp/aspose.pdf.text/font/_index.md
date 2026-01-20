---
title: Aspose::Pdf::Text::Font class
linktitle: Font
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::Font class. Represents font object in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf.text/font/
---
## Font class


Represents font object.

```cpp
class Font : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [CppIsSetTrailerable](./cppissettrailerable/)() |  |
| [get_BaseFont](./get_basefont/)() | Gets BaseFont value of PDF font object. Also known as PostScript name of the font. |
| [get_DecodedFontName](./get_decodedfontname/)() | Sometimes PDF fonts(usually Chinese/Japanese/Korean fonts) could have specificical font name. This name is value of PDF font property "BaseFont" and sometimes this property could be represented in hexademical form. If read this name directly it could be represented in non-readable form. To get readable form it's necessary to decode font's name by rules specifical for this font. This property returns decoded font name, so use it for cases when you meet with a non-readable [FontName](../). If property [FontName](../) has readable form this property will be the same as [FontName](../), so you can use this property for any cases when you need to get font name in a readable form. |
| [get_FontName](./get_fontname/)() const | Gets font name of the [Font](./) object. |
| [get_FontOptions](./get_fontoptions/)() | Useful properties to tune [Font](./) behaviour. |
| [get_IsAccessible](./get_isaccessible/)() const | Gets indicating whether the font is present (installed) in the system. |
| [get_IsEmbedded](./get_isembedded/)() const | Gets a value that indicates whether the font is embedded. [Font](./) based on IFont will automatically be subset and embedded. |
| [get_IsSubset](./get_issubset/)() | Gets a value that indicates whether the font is a subset. [Font](./) based on IFont will automatically be subset and embedded. |
| [GetLastFontEmbeddingError](./getlastfontembeddingerror/)() | An objective of this method - to return description of error if an attempt to embed font was failed. If there are no error cases it returns empty string. |
| [MeasureString](./measurestring/)(System::String, float) | Measures the string. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) | Saves the font into the stream. [Note](../../aspose.pdf/note/) that the font is saved to intermediate TTF format intended to be used in a converted copy of the original document only. The font file is not intended to be used outside the original document context. |
| [set_IsEmbedded](./set_isembedded/)(bool) | Sets a value that indicates whether the font is embedded. [Font](./) based on IFont will automatically be subset and embedded. |
| [set_IsSubset](./set_issubset/)(bool) | Sets a value that indicates whether the font is a subset. [Font](./) based on IFont will automatically be subset and embedded. |



## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
