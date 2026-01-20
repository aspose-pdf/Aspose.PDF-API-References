---
title: Aspose::Pdf::Text::Font::get_DecodedFontName method
linktitle: get_DecodedFontName
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::Font::get_DecodedFontName method. Sometimes PDF fonts(usually Chinese/Japanese/Korean fonts) could have specificical font name. This name is value of PDF font property "BaseFont" and sometimes this property could be represented in hexademical form. If read this name directly it could be represented in non-readable form. To get readable form it''s necessary to decode font''s name by rules specifical for this font. This property returns decoded font name, so use it for cases when you meet with a non-readable FontName. If property FontName has readable form this property will be the same as FontName, so you can use this property for any cases when you need to get font name in a readable form in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.text/font/get_decodedfontname/
---
## Font::get_DecodedFontName method


Sometimes PDF fonts(usually Chinese/Japanese/Korean fonts) could have specificical font name. This name is value of PDF font property "BaseFont" and sometimes this property could be represented in hexademical form. If read this name directly it could be represented in non-readable form. To get readable form it's necessary to decode font's name by rules specifical for this font. This property returns decoded font name, so use it for cases when you meet with a non-readable [FontName](../). If property [FontName](../) has readable form this property will be the same as [FontName](../), so you can use this property for any cases when you need to get font name in a readable form.

```cpp
System::String Aspose::Pdf::Text::Font::get_DecodedFontName()
```

## See Also

* Class [String](../../../system/string/)
* Class [Font](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
