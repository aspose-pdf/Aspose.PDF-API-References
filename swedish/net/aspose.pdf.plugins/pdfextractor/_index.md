---
title: "Klassen PdfExtractor"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.PdfExtractor-klass. Representerar grundfunktionalitet för att extrahera text, bilder och andra typer av innehåll som kan förekomma på sidorna i PDF-dokument."
type: docs
weight: 9210
url: /sv/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor class

Representerar grundfunktionalitet för att extrahera text, bilder och andra typer av innehåll som kan förekomma på sidorna i PDF-dokument.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | Implementering av IDisposable. Faktiskt är det inte nödvändigt för PdfExtractor. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | Startar PdfExtractor‑bearbetning med de angivna parametrarna. |

## Anmärkningar

Objektet [`TextExtractor`](../textextractor/) används för att extrahera text, eller [`ImageExtractor`](../imageextractor/) för att extrahera bilder.

## Exempel

Exemplet visar hur man extraherar textinnehållet i ett PDF‑dokument.

```csharp
// skapa TextExtractor‑objekt för att extrahera PDF‑innehåll
using (TextExtractor extractor = new TextExtractor())
{
    // Skapa TextExtractorOptions-objekt för att ange instruktioner
    textExtractorOptions = new TextExtractorOptions();
    
    // lägg till inmatningsfilens sökväg till datakällorna
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // utför extraktionsprocessen
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // hämta den extraherade texten från ResultContainer‑objektet
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### Se även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


