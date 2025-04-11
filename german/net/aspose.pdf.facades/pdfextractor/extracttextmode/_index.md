---
title: PdfExtractor.ExtractTextMode
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-Eigenschaft. Legt den Modus für das Ergebnis der Textextraktion fest
type: docs
weight: 40
url: /de/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode-Eigenschaft

Legt den Modus für das Ergebnis der Textextraktion fest.

```csharp
public int ExtractTextMode { get; set; }
```

### Eigenschaftswert

0 ist der Modus für reinen Text und 1 ist der Modus für rohe Anordnung. Standard ist 0.

## Beispiele

Das Beispiel demonstriert die Verwendung der `ExtractTextMode`-Eigenschaft im Szenario der Textextraktion.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### Siehe auch

* Klasse [PdfExtractor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)