---
title: "Klass PdfAConverter"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Plugins.PdfAConverter‑klass. Representerar ett plugin för att hantera konvertering av PDF-dokument till PDF/A-format och för validering av PDF/A‑överensstämmelse."
type: docs
weight: 9150
url: /sv/net/aspose.pdf.plugins/pdfaconverter/
---
## PdfAConverter class

Representerar en plugin för hantering av konvertering av PDF-dokument till PDF/A-format och för validering av PDF/A‑överensstämmelse.

```csharp
public sealed class PdfAConverter : IPlugin
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | Påbörjar en PDF/A‑konverterings‑ eller valideringsprocess med angivna alternativ. |

## Exempel

Exemplet visar hur man validerar PDF-dokumentets överensstämmelse med PDF/A-formatet (PDF/A-1a i detta fall):

```csharp
// Skapa alternativklassen för att konfigurera valideringsprocessen
var options = new PdfAValidateOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_1A
};

// Lägg till en eller flera filer som ska valideras
options.AddInput(new FileDataSource("path_to_your_first_pdf_file.pdf")); // replace with your actual file path
options.AddInput(new FileDataSource("path_to_your_second_pdf_file.pdf"));
// lägg till fler filer vid behov

// Skapa plugin-instansen
var plugin = new PdfAConverter();

// Kör valideringen och hämta resultaten
var resultContainer = plugin.Process(options);

// Kontrollera egenskapen resultContainer.ResultCollection för valideringsresultat för varje fil:
for (var i = 0; i < resultContainer.ResultCollection.Count; i++)
{
    var result = resultContainer.ResultCollection[i];
    var validationResult = (PdfAValidationResult) result.Data;
    var isValid = validationResult.IsValid; // Validation result for the i-th document
}
```

Exemplet visar hur man konverterar PDF-dokumentet till PDF/A-format (PDF/A-3b i detta fall):

```csharp
// Skapa alternativklassen för att konfigurera konverteringsprocessen
var options = new PdfAConvertOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_3B
};

// Lägg till källfilen
options.AddInput(new FileDataSource("path_to_your_pdf_file.pdf")); // replace with your actual file path

// Lägg till sökvägen för att spara den konverterade filen
options.AddOutput(new FileDataSource("path_to_the_converted_file.pdf"));

// Skapa plugin-instansen
var plugin = new PdfAConverter();

// Kör konverteringen
plugin.Process(options);
```

### Se även

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


