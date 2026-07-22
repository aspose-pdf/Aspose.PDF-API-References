---
title: "Aspose::Pdf::Text::TextFormattingOptions-klass"
linktitle: "TextFormattingOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextFormattingOptions-klass. Representerar textformateringsalternativ i C++."
type: docs
weight: 4200
url: /sv/cpp/aspose.pdf.text/textformattingoptions/
---
## TextFormattingOptions class


Representerar alternativ för textformatering.

```cpp
class TextFormattingOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [LineSpacingMode](./linespacingmode/) | Definierar specifika radavstånd. |
| [WordWrapMode](./wordwrapmode/) | Definierar strategier för radbrytning. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_FirstLineIndent](./get_firstlineindent/)() const | Hämtar värdet för indrag på första raden. |
| [get_HyphenSymbol](./get_hyphensymbol/)() const | Hämtar bindestreckssymbolen som används i avstavningsprocessen. |
| [get_LineSpacing](./get_linespacing/)() const | Hämtar radavståndsläge. Standardvärdet är [LineSpacingMode.FontSize](./linespacingmode/). |
| [get_SubsequentLinesIndent](./get_subsequentlinesindent/)() const | Hämtar värdet för indrag på efterföljande rader. |
| [get_WrapMode](./get_wrapmode/)() const | Hämtar ordbrytningsläge. Standardvärdet är [WordWrapMode.NoWrap](./wordwrapmode/). |
| [set_FirstLineIndent](./set_firstlineindent/)(float) | Ställer in värdet för indrag på första raden. |
| [set_HyphenSymbol](./set_hyphensymbol/)(const System::String\&) | Ställer in bindestreckssymbolen som används i avstavningsprocessen. |
| [set_LineSpacing](./set_linespacing/)(TextFormattingOptions::LineSpacingMode) | Ställer in radavståndsläge. Standardvärdet är [LineSpacingMode.FontSize](./linespacingmode/). |
| [set_SubsequentLinesIndent](./set_subsequentlinesindent/)(float) | Ställer in indragsvärdet för efterföljande rader. |
| [set_WrapMode](./set_wrapmode/)(TextFormattingOptions::WordWrapMode) | Ställer in radbrytningsläge. Standardvärdet är [WordWrapMode.NoWrap](./wordwrapmode/). |
| [TextFormattingOptions](./textformattingoptions/)(TextFormattingOptions::WordWrapMode) | Initierar en ny instans av objektet [TextFormattingOptions](./) för det angivna radbrytningsläget. |
| [TextFormattingOptions](./textformattingoptions/)() | Initierar en ny instans av objektet [TextFormattingOptions](./) med odefinierat radbrytningsläge. |
## Se även

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
