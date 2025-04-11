---
title: Class TextExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TextExtractorOptions klass. Representerar alternativ för textutvinning för TextExtractor-plugin
type: docs
weight: 9390
url: /sv/net/aspose.pdf.plugins/textextractoroptions/
---
## TextExtractorOptions klass

Representerar alternativ för textutvinning för TextExtractor-plugin.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | Initierar en ny instans av `TextExtractorOptions`-objektet med 'Raw' (standard) textformateringsläge. |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | Initierar en ny instans av `TextExtractorOptions`-objektet för det angivna textformateringsläget. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | Hämtar formateringsläge. |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Returnerar PdfExtractor-pluginens datainsamling. |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | Returnerar namnet på operationen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Lägger till en ny datakälla till PdfExtractor-pluginens datainsamling. |

## Andra Medlemmar

| Namn | Beskrivning |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | Definierar olika lägen som kan användas vid konvertering av ett PDF-dokument till text. Se `TextExtractorOptions` klass. |

## Kommentarer

`TextExtractorOptions`-objektet används för att ställa in [`TextFormattingMode`](../textextractoroptions.textformattingmode/) och andra alternativ för textutvinningsoperationen. Det är ocksåverkar funktioner för att lägga till data (filer, strömmar) som representerar inmatnings-PDF-dokument.

## Exempel

Exemplet visar hur man extraherar textinnehållet i ett PDF-dokument.

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set TextFormattingMode (Pure,  or Raw - default)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // add input file path to data sources
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Se Även

* klass [PdfExtractorOptions](../pdfextractoroptions/)
* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)