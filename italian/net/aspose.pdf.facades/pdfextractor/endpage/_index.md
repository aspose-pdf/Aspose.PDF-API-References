---
title: PdfExtractor.EndPage
second_title: Aspose.PDF for .NET API Reference
description: Proprietà PdfExtractor. Ottiene o imposta la pagina finale nell'intervallo di pagine in cui verrà eseguita l'operazione di estrazione
type: docs
weight: 20
url: /it/net/aspose.pdf.facades/pdfextractor/endpage/
---
## Proprietà PdfExtractor.EndPage

Ottiene o imposta la pagina finale nell'intervallo di pagine in cui verrà eseguita l'operazione di estrazione.

```csharp
PdfExtractor ext = new PdfExtractor();
ext.BindBdf("sample.pdf");
ext.StartPage = 2;
ext.EndPage = 3;
ext.ExtractText();
```

```csharp
public int EndPage { get; set; }
```

### Vedi Anche

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)