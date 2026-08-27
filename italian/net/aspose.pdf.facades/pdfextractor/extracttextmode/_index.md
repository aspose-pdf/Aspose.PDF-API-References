---
title: "PdfExtractor.ExtractTextMode"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "PdfExtractor property. Imposta la modalità per il risultato dell'estrazione del testo"
type: docs
weight: 40
url: /it/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## PdfExtractor.ExtractTextMode property

Imposta la modalità per il risultato dell'estrazione del testo.

```csharp
public int ExtractTextMode { get; set; }
```

### Property Value

0 è la modalità testo puro e 1 è la modalità ordine grezzo. Il valore predefinito è 0.

## Esempi

L'esempio dimostra l'uso della proprietà `ExtractTextMode` nello scenario di estrazione del testo.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### Vedi anche

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


