---
title: PdfExtractor.StartPage
second_title: Aspose.PDF for .NET API Reference
description: Propriedade PdfExtractor. Obtém ou define a página inicial no intervalo de páginas onde a operação de extração será realizada
type: docs
weight: 80
url: /pt/net/aspose.pdf.facades/pdfextractor/startpage/
---
## Propriedade PdfExtractor.StartPage

Obtém ou define a página inicial no intervalo de páginas onde a operação de extração será realizada.

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

### Veja Também

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)