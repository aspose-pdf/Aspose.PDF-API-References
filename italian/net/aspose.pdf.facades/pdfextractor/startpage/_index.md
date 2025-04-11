---
title: PdfExtractor.StartPage
second_title: Aspose.PDF for .NET API Reference
description: Proprietà di PdfExtractor. Ottiene o imposta la pagina iniziale nell'intervallo di pagine in cui verrà eseguita l'operazione di estrazione
type: docs
weight: 80
url: /it/net/aspose.pdf.facades/pdfextractor/startpage/
---
## Proprietà PdfExtractor.StartPage

Ottiene o imposta la pagina iniziale nell'intervallo di pagine in cui verrà eseguita l'operazione di estrazione.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 5;
ext.ExtractText();
```

```csharp
public int StartPage { get; set; }
```

### Vedi Anche

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)