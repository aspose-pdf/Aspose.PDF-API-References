---
title: PdfExtractor.ExtractImage
second_title: Aspose.PDF for .NET API Reference
description: Método PdfExtractor. Extraer imágenes de un archivo PDF
type: docs
weight: 120
url: /es/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## Método PdfExtractor.ExtractImage

Extraer imágenes de un archivo PDF.

```csharp
public void ExtractImage()
```

## Ejemplos

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

### Ver También

* clase [PdfExtractor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)