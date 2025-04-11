---
title: PdfExtractor.GetAttachNames
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfExtractor. Renvoie la liste des pièces jointes dans le fichier PDF. Remarque : ExtractAttachments doit être appelé avant d'utiliser cette méthode
type: docs
weight: 160
url: /fr/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## Méthode PdfExtractor.GetAttachNames

Renvoie la liste des pièces jointes dans le fichier PDF. Remarque : ExtractAttachments doit être appelé avant d'utiliser cette méthode.

```csharp
public IList<string> GetAttachNames()
```

### Valeur de retour

Liste des pièces jointes

## Exemples

L'exemple démontre comment extraire les noms des pièces jointes d'un fichier PDF.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### Voir aussi

* classe [PdfExtractor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)