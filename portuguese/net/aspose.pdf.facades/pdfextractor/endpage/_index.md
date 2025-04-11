---
title: PdfExtractor.EndPage
second_title: Aspose.PDF for .NET API Reference
description: Propriedade PdfExtractor. Obtém ou define a página final no intervalo de páginas onde a operação de extração será realizada
type: docs
weight: 20
url: /pt/net/aspose.pdf.facades/pdfextractor/endpage/
---
## Propriedade PdfExtractor.EndPage

Obtém ou define a página final no intervalo de páginas onde a operação de extração será realizada.

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

### Veja Também

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)