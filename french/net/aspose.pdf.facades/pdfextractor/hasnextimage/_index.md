---
title: PdfExtractor.HasNextImage
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfExtractor. Vérifie si d'autres images sont accessibles dans le document PDF. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode
type: docs
weight: 200
url: /fr/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## Méthode PdfExtractor.HasNextImage

Vérifie si d'autres images sont accessibles dans le document PDF. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode.

```csharp
public bool HasNextImage()
```

### Valeur de retour

Vrai si d'autres images sont accessibles

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