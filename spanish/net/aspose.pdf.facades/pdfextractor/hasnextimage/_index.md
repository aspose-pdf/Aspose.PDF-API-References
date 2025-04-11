---
title: PdfExtractor.HasNextImage
second_title: Aspose.PDF for .NET API Reference
description: Método PdfExtractor. Verifica si hay más imágenes accesibles en el documento PDF. Nota: ExtractImage debe ser llamado antes de usar este método
type: docs
weight: 200
url: /es/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## Método PdfExtractor.HasNextImage

Verifica si hay más imágenes accesibles en el documento PDF. Nota: ExtractImage debe ser llamado antes de usar este método.

```csharp
public bool HasNextImage()
```

### Valor de Retorno

Verdadero si hay más imágenes accesibles

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

### Véase También

* clase [PdfExtractor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)