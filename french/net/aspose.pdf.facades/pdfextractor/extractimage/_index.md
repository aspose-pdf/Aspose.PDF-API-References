---
title: "PdfExtractor.ExtractImage"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfExtractor. Extraire les images du fichier PDF"
type: docs
weight: 120
url: /fr/net/aspose.pdf.facades/pdfextractor/extractimage/
---
## PdfExtractor.ExtractImage method

Extrait les images du fichier PDF.

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


