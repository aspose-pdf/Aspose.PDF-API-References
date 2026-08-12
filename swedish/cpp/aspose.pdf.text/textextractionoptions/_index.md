---
title: "Aspose::Pdf::Text::TextExtractionOptions-klass"
linktitle: "TextExtractionOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextExtractionOptions-klass. Representerar alternativ för textutvinning i C++."
type: docs
weight: 4100
url: /sv/cpp/aspose.pdf.text/textextractionoptions/
---
## TextExtractionOptions class


Representerar alternativ för textextraktion.

```cpp
class TextExtractionOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [TextFormattingMode](./textformattingmode/) | Definierar olika lägen som kan användas vid konvertering av pdf-dokument till text. Se klassen [TextDevice](../). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_FormattingMode](./get_formattingmode/)() const | Hämtar formateringsläge. |
| [get_ScaleFactor](./get_scalefactor/)() const | Hämtar faktorn som kommer att tillämpas för att skala teckenstorlek under extrahering i ren läge. En lägre inställning ger fler mellanslag i den extraherade texten. Standardvärdet är 1 – ingen skalning; Att sätta värdet till noll låter algoritmen välja skalning automatiskt. |
| [set_FormattingMode](./set_formattingmode/)(TextExtractionOptions::TextFormattingMode) | Hämtar formateringsläge. |
| [set_ScaleFactor](./set_scalefactor/)(double) | Ställer in faktorn som kommer att tillämpas för att skala teckenstorlek under extrahering i ren läge. En lägre inställning ger fler mellanslag i den extraherade texten. Standardvärdet är 1 – ingen skalning; Att sätta värdet till noll låter algoritmen välja skalning automatiskt. |
| [TextExtractionOptions](./textextractionoptions/)(TextExtractionOptions::TextFormattingMode) | Initierar en ny instans av objektet [TextExtractionOptions](./) för det angivna textformateringsläget. |
## Se även

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
