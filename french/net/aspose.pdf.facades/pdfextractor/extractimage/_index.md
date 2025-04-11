---
title: PdfExtractor.ExtractImage
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfExtractor. Extraire des images d'un fichier PDF
type: docs
weight: 120
url: /fr/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## Méthode PdfExtractor.ExtractImage

Extraire des images d'un fichier PDF.

```csharp
public void ExtractImage()
```

## Exemples

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

### Voir aussi

* classe [PdfExtractor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)