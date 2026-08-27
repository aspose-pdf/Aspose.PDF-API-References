---
title: "Klass TextExtractor"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.TextExtractor-klass. Representerar TextExtractor‑plugin."
type: docs
weight: 9530
url: /sv/net/aspose.pdf.plugins/textextractor/
---
## TextExtractor class

Representerar TextExtractor‑plugin.

```csharp
public class TextExtractor : PdfExtractor
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TextExtractor](textextractor/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementering av IDisposable. Faktiskt är det inte nödvändigt för PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Startar PdfExtractor‑bearbetning med de angivna parametrarna. |

## Anmärkningar

Objektet `TextExtractor` används för att extrahera text i PDF‑dokument.

## Exempel

Exemplet visar hur man extraherar textinnehållet i ett PDF‑dokument.

```csharp
// skapa TextExtractor‑objekt för att extrahera text i PDF‑innehåll
using (TextExtractor extractor = new TextExtractor())
{
    // skapa TextExtractorOptions
    textExtractorOptions = new TextExtractorOptions();
    
    // lägg till inmatningsfilens sökväg till datakällorna
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));
    
    // utför extraktionsprocessen
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // hämta den extraherade texten från ResultContainer‑objektet
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Se även

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


