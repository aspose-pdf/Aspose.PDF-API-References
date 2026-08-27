---
title: "Klass TextExtractorOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.TextExtractorOptions klass. Representerar alternativ för textutdragning för TextExtractor‑pluginet."
type: docs
weight: 9540
url: /sv/net/aspose.pdf.plugins/textextractoroptions/
---
## TextExtractorOptions class

Representerar alternativ för textutdragning för TextExtractor‑plugin.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | Initierar en ny instans av `TextExtractorOptions`‑objektet med 'Raw' (standard) textformateringsläge. |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | Initierar en ny instans av `TextExtractorOptions`‑objektet för det angivna textformateringsläget. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | Hämtar formateringsläge. |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Returnerar PdfExtractor‑pluginens datainsamling. |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | Returnerar operationens namn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Lägger till en ny datakälla i PdfExtractor‑pluginens datainsamling. |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | Definierar olika lägen som kan användas vid konvertering av ett PDF‑dokument till text. Se `TextExtractorOptions`‑klass. |

## Anmärkningar

Objektet `TextExtractorOptions` används för att ange [`TextFormattingMode`](../textextractoroptions.textformattingmode/) och andra alternativ för textutdragsoperationen. Dessutom ärver det funktioner för att lägga till data (filer, strömmar) som representerar inmatnings‑PDF‑dokument.

## Exempel

Exemplet visar hur man extraherar textinnehållet i ett PDF‑dokument.

```csharp
// skapa TextExtractor‑objekt för att extrahera PDF‑innehåll
using (TextExtractor extractor = new TextExtractor())
{
    // skapa TextExtractorOptions‑objekt för att ange TextFormattingMode (Pure, eller Raw – standard)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // lägg till inmatningsfilens sökväg till datakällorna
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // utför extraktionsprocessen
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // hämta den extraherade texten från ResultContainer‑objektet
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Se även

* class [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


