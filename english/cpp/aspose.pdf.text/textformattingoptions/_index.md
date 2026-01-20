---
title: Aspose::Pdf::Text::TextFormattingOptions class
linktitle: TextFormattingOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextFormattingOptions class. Represents text formatting options in C++.'
type: docs
weight: 4200
url: /cpp/aspose.pdf.text/textformattingoptions/
---
## TextFormattingOptions class


Represents text formatting options.

```cpp
class TextFormattingOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Enum | Description |
| --- | --- |
| [LineSpacingMode](./linespacingmode/) | Defines line spacing specifics. |
| [WordWrapMode](./wordwrapmode/) | Defines word wrapping strategies. |
## Methods

| Method | Description |
| --- | --- |
| [get_FirstLineIndent](./get_firstlineindent/)() const | Gets first line indent value. |
| [get_HyphenSymbol](./get_hyphensymbol/)() const | Gets hyphen symbol that is used in hyphenation process. |
| [get_LineSpacing](./get_linespacing/)() const | Gets line spacing mode. Default value is [LineSpacingMode.FontSize](./linespacingmode/). |
| [get_SubsequentLinesIndent](./get_subsequentlinesindent/)() const | Gets subsequent lines indent value. |
| [get_WrapMode](./get_wrapmode/)() const | Gets word wrap mode. Default value is [WordWrapMode.NoWrap](./wordwrapmode/). |
| [set_FirstLineIndent](./set_firstlineindent/)(float) | Sets first line indent value. |
| [set_HyphenSymbol](./set_hyphensymbol/)(System::String) | Sets hyphen symbol that is used in hyphenation process. |
| [set_LineSpacing](./set_linespacing/)(TextFormattingOptions::LineSpacingMode) | Sets line spacing mode. Default value is [LineSpacingMode.FontSize](./linespacingmode/). |
| [set_SubsequentLinesIndent](./set_subsequentlinesindent/)(float) | Sets subsequent lines indent value. |
| [set_WrapMode](./set_wrapmode/)(TextFormattingOptions::WordWrapMode) | Sets word wrap mode. Default value is [WordWrapMode.NoWrap](./wordwrapmode/). |
| [TextFormattingOptions](./textformattingoptions/)(TextFormattingOptions::WordWrapMode) | Initializes new instance of the [TextFormattingOptions](./) object for the specified word wrap mode. |
| [TextFormattingOptions](./textformattingoptions/)() | Initializes new instance of the [TextFormattingOptions](./) object with undefined word wrap mode. |
## See Also

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
