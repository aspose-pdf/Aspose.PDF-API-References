---
title: PdfFileStamp.StartingNumber
second_title: Aspose.PDF for .NET API Reference
description: Propriedade PdfFileStamp. Obtém ou define o número inicial para a primeira página no arquivo de entrada. As próximas páginas serão numeradas a partir deste valor. Por exemplo, se o StartingNumber for definido como 100, as páginas do documento terão os números 100, 101, 102
type: docs
weight: 100
url: /pt/net/aspose.pdf.facades/pdffilestamp/startingnumber/
---
## Propriedade PdfFileStamp.StartingNumber

Obtém ou define o número inicial para a primeira página no arquivo de entrada. As próximas páginas serão numeradas a partir deste valor. Por exemplo, se o StartingNumber for definido como 100, as páginas do documento terão os números 100, 101, 102...

```csharp
public int StartingNumber { get; set; }
```

## Exemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.StartingNumber = 100;
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Veja Também

* classe [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)