---
title: Class TextExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TextExtractorOptions-Klasse. Stellt Optionen zur Textextraktion für das TextExtractor-Plugin dar
type: docs
weight: 9390
url: /de/net/aspose.pdf.plugins/textextractoroptions/
---
## TextExtractorOptions-Klasse

Stellt Optionen zur Textextraktion für das TextExtractor-Plugin dar.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | Initialisiert eine neue Instanz des `TextExtractorOptions`-Objekts mit dem Textformatierungsmodus 'Raw' (Standard). |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | Initialisiert eine neue Instanz des `TextExtractorOptions`-Objekts für den angegebenen Textformatierungsmodus. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | Gibt den Formatierungsmodus zurück. |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | Gibt die Datensammlung des PdfExtractor-Plugins zurück. |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | Gibt den Namen der Operation zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | Fügt der Datensammlung des PdfExtractor-Plugins eine neue Datenquelle hinzu. |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | Definiert verschiedene Modi, die beim Konvertieren eines PDF-Dokuments in Text verwendet werden können. Siehe `TextExtractorOptions`-Klasse. |

## Bemerkungen

Das `TextExtractorOptions`-Objekt wird verwendet, um [`TextFormattingMode`](../textextractoroptions.textformattingmode/) und andere Optionen für die Textextraktionsoperation festzulegen. Außerdem erbt es Funktionen zum Hinzufügen von Daten (Dateien, Streams), die Eingabe-PDF-Dokumente darstellen.

## Beispiele

Das Beispiel zeigt, wie man den Textinhalt eines PDF-Dokuments extrahiert.

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

### Siehe auch

* Klasse [PdfExtractorOptions](../pdfextractoroptions/)
* Namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* Assembly [Aspose.PDF](../../)