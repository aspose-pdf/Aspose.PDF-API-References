---
title: PdfExtractor.ExtractTextMode
second_title: Aspose.PDF for .NET API Reference
description: Propriedade PdfExtractor. Define o modo para o resultado da extração de textos
type: docs
weight: 40
url: /pt/net/aspose.pdf.facades/pdfextractor/extracttextmode/
---
## Propriedade PdfExtractor.ExtractTextMode

Define o modo para o resultado da extração de texto.

```csharp
public int ExtractTextMode { get; set; }
```

### Valor da Propriedade

0 é o modo de texto puro e 1 é o modo de ordenação bruta. O padrão é 0.

## Exemplos

O exemplo demonstra o uso da propriedade `ExtractTextMode` em um cenário de extração de texto.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractTextMode = 1;
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

### Veja Também

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)