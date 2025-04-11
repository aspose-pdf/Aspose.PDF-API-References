---
title: PdfExtractor.HasNextImage
second_title: Aspose.PDF for .NET API Reference
description: Método PdfExtractor. Verifica se mais imagens estão acessíveis no documento PDF. Nota: ExtractImage deve ser chamado antes de usar este método
type: docs
weight: 200
url: /pt/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## Método PdfExtractor.HasNextImage

Verifica se mais imagens estão acessíveis no documento PDF. Nota: ExtractImage deve ser chamado antes de usar este método.

```csharp
public bool HasNextImage()
```

### Valor de Retorno

Verdadeiro se mais imagens estão acessíveis

## Exemplos

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### Veja Também

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)