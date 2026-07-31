---
title: "PdfExtractor.EndPage"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "PdfExtractor property. Ottiene o imposta la pagina finale nell'intervallo di pagine in cui verrà eseguita l'operazione di estrazione"
type: docs
weight: 20
url: /it/net/aspose.pdf.facades/pdfextractor/endpage/
---
## PdfExtractor.EndPage property

Ottiene o imposta la Page finale nell'intervallo di Page in cui verrà eseguita l'operazione di estrazione.

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

### Vedi anche

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


