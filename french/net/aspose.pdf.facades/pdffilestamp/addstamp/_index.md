---
title: "PdfFileStamp.AddStamp"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileStamp. Ajoute un tampon au fichier"
type: docs
weight: 140
url: /fr/net/aspose.pdf.facades/pdffilestamp/addstamp/
---
## PdfFileStamp.AddStamp method

Ajoute un tampon au fichier.

```csharp
public void AddStamp(Stamp stamp)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| tampon | Tampon | Objet Tampon qui. |

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

* class [Stamp](../../stamp/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


