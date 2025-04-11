---
title: PdfFileStamp.AddStamp
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileStamp. Ajoute un tampon au fichier
type: docs
weight: 140
url: /fr/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## Méthode PdfFileStamp.AddStamp

Ajoute un tampon au fichier.

```csharp
public void AddStamp(Stamp stamp)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stamp | Stamp | Objet tampon qui. |

## Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.SetOrigin(140, 400);
stamp.SetImageSize(50, 50);
stamp.Opacity = 0.8f;
stamp.IsBackground = true;
stamp.BindImage("image.jpg");
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Voir aussi

* classe [Stamp](../../stamp/)
* classe [PdfFileStamp](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)