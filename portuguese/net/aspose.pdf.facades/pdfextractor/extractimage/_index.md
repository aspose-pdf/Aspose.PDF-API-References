---
title: PdfExtractor.ExtractImage
second_title: Aspose.PDF for .NET API Reference
description: Método PdfExtractor. Extrair imagens de arquivo PDF
type: docs
weight: 120
url: /pt/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## Método PdfExtractor.ExtractImage

Extrair imagens de arquivo PDF.

```csharp
public void ExtractImage()
```

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