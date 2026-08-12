---
title: "Aspose::Pdf::Text::TextReplaceOptions klass"
linktitle: "TextReplaceOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextReplaceOptions klass. Representerar alternativ för textersättning i C++."
type: docs
weight: 4900
url: /sv/cpp/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions class


Representerar alternativ för textersättning.

```cpp
class TextReplaceOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [FontSizeAdjustment](./fontsizeadjustment/) | Anger en policy för hur teckensnittsstorleken på text ska justeras för att passa inom ett omgivande område. |
| [ReplaceAdjustment](./replaceadjustment/) | Bestämmer åtgärden som ska utföras efter att en textfragment har ersatts med en kortare. None - ingen åtgärd, ersatt text kan överlappa resten av raden; AdjustSpaceWidth - försöker justera mellanslag mellan ord för att behålla radlängden; WholeWordsHyphenation - försöker fördela ord mellan stycke rader för att behålla styckets högra kant; ShiftRestOfLine - förskjuter resten av raden enligt den förändrade textlängden, radens längd kan ändras; Standardvärdet är ShiftRestOfLine. |
| [Scope](./scope/) | [Scope](./scope/) där ersättningstextoperationen tillämpas REPLACE_FIRST som standard. Detta föråldrade alternativ behölls för kompatibilitet. Det påverkar PdfContentEditor och har ingen effekt på [TextFragmentAbsorber](../textfragmentabsorber/). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AdjustmentNewLineSpacing](./get_adjustmentnewlinespacing/)() const | Hämtar värdet för radavstånd som används om ersättningsjustering tvingas skapa en ny textrad. Det förväntade värdet är en multiplikator av teckensnittsstorleken för den ersatta texten. Standard är 1.2. |
| [get_FontSizeAdjustmentAction](./get_fontsizeadjustmentaction/)() const | Hämtar policyn för att justera teckenstorleken så att den passar inom gränserna som definieras av [TextReplaceOptions::Rectangle](../). |
| [get_IgnoreParagraphs](./get_ignoreparagraphs/)() const | Hämtar ett värde som indikerar om separata stycken ska ignoreras när text justeras på sidan efter textersättning. |
| [get_LeftAdjustment](./get_leftadjustment/)() const | Ställer in eller hämtar vänsterpositionsjustering för ersatt text när [TextReplaceOptions](./) används: |
| [get_Rectangle](./get_rectangle/)() const | Hämtar rektangeln för att passa texten efter ersättning. |
| [get_ReplaceAdjustmentAction](./get_replaceadjustmentaction/)() const | Hämtar en åtgärd som kommer att utföras efter att textfragmentet ersatts med en kortare version. |
| [get_ReplaceScope](./get_replacescope/)() const | Hämtar det område där ersättning av text utförs. |
| [get_RightAdjustment](./get_rightadjustment/)() const | Ställer in eller hämtar högerpositionsjustering för ersatt text när [TextReplaceOptions](./) används: |
| [set_AdjustmentNewLineSpacing](./set_adjustmentnewlinespacing/)(double) | Ställer in värdet för radavstånd som används om ersättningsjusteringen tvingas skapa en ny textrad. Det förväntade värdet är en multiplikator av teckenstorleken för den ersatta texten. Standardvärdet är 1,2. |
| [set_FontSizeAdjustmentAction](./set_fontsizeadjustmentaction/)(TextReplaceOptions::FontSizeAdjustment) | Ställer in policyn för att justera teckenstorleken så att den passar inom gränserna som definieras av [TextReplaceOptions::Rectangle](../). |
| [set_IgnoreParagraphs](./set_ignoreparagraphs/)(bool) | Ställer in ett värde som indikerar om separata stycken ska ignoreras när text justeras på sidan efter textersättning. |
| [set_LeftAdjustment](./set_leftadjustment/)(double) | Ställer in eller hämtar vänsterpositionsjustering för ersatt text när [TextReplaceOptions](./) används: |
| [set_Rectangle](./set_rectangle/)(const System::SharedPtr\<Aspose::Pdf::Rectangle\>\&) | Ställer in rektangeln för att passa texten efter ersättning. |
| [set_ReplaceAdjustmentAction](./set_replaceadjustmentaction/)(TextReplaceOptions::ReplaceAdjustment) | Ställer in en åtgärd som kommer att utföras efter att textfragmentet ersatts med en kortare version. |
| [set_ReplaceScope](./set_replacescope/)(TextReplaceOptions::Scope) | Ställer in det område där ersättning av text utförs. |
| [set_RightAdjustment](./set_rightadjustment/)(double) | Ställer in eller hämtar högerpositionsjustering för ersatt text när [TextReplaceOptions](./) används: |
| [TextReplaceOptions](./textreplaceoptions/)(TextReplaceOptions::Scope) | Initierar en ny instans av objektet [TextReplaceOptions](./) för det angivna området. |
| [TextReplaceOptions](./textreplaceoptions/)(TextReplaceOptions::ReplaceAdjustment) | Initierar en ny instans av objektet [TextReplaceOptions](./) för den angivna åtgärden efter ersättning. |
## Se även

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
