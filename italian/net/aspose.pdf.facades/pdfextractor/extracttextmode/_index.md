---
title: PdfExtractor.ExtractTextMode
second_title: Aspose.PDF for .NET API Reference
description: Proprietà di PdfExtractor. Imposta la modalità per il risultato dell'estrazione dei testi
type: docs
weight: 40
url: /it/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## Proprietà PdfExtractor.ExtractTextMode

Imposta la modalità per il risultato dell'estrazione del testo.

```csharp
public int ExtractTextMode { get; set; }
```

### Valore della Proprietà

0 è la modalità testo puro e 1 è la modalità di ordinamento grezzo. Il valore predefinito è 0.

## Esempi

L'esempio dimostra l'uso della proprietà `ExtractTextMode` nello scenario di estrazione del testo.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### Vedi Anche

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)