---
title: "PdfExtractor.HasNextImage"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfExtractor. Vérifie si d'autres images sont accessibles dans le document PDF. Note : ExtractImage doit être appelé avant l'utilisation de cette méthode"
type: docs
weight: 200
url: /fr/net/aspose.pdf.facades/pdfextractor/hasnextimage/
---
## PdfExtractor.HasNextImage method

Vérifie si d'autres images sont accessibles dans le document PDF. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode.

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


