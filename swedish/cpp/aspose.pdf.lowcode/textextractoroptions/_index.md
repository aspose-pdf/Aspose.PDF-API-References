---
title: "Aspose::Pdf::LowCode::TextExtractorOptions klass"
linktitle: "TextExtractorOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::TextExtractorOptions klass. Representerar alternativ för textutdrag för TextExtractor-pluginet i C++."
type: docs
weight: 8700
url: /sv/cpp/aspose.pdf.lowcode/textextractoroptions/
---
## TextExtractorOptions class


Representerar alternativ för textutdrag för [TextExtractor](../textextractor/) pluginet.

```cpp
class TextExtractorOptions : public Aspose::Pdf::LowCode::PdfExtractorOptions
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [TextFormattingMode](./textformattingmode/) | Definierar olika lägen som kan användas vid konvertering av ett PDF-dokument till text. Se klassen [TextExtractorOptions](./). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_FormattingMode](./get_formattingmode/)() const | Hämtar formateringsläge. |
| [get_OperationName](./get_operationname/)() override | Returnerar namn på operationen. |
| [TextExtractorOptions](./textextractoroptions/)(TextExtractorOptions::TextFormattingMode) | Initierar en ny instans av objektet [TextExtractorOptions](./) för det angivna textformateringsläget. |
| [TextExtractorOptions](./textextractoroptions/)() | Initierar en ny instans av objektet [TextExtractorOptions ](./) med 'Raw' (standard) textformateringsläge. |
## Anmärkningar


Objektet [TextExtractorOptions](./) används för att ställa in [TextFormattingMode](./textformattingmode/) och andra alternativ för textutvinningsoperationen. Dessutom ärver det funktioner för att lägga till data (filer, strömmar) som representerar inmatnings‑PDF‑dokument.
## Se även

* Class [PdfExtractorOptions](../pdfextractoroptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
