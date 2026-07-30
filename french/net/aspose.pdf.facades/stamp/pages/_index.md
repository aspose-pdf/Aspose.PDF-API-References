---
title: "Stamp.Pages"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Stamp. Obtient ou définit un tableau avec les numéros de pages qui seront affectés par le tampon. Si Pages est null, toutes les pages du document sont affectées"
type: docs
weight: 60
url: /fr/net/aspose.pdf.facades/stamp/pages/
---
## Stamp.Pages property

Obtient ou définit un tableau avec les numéros de pages qui seront affectés par le tampon. Si Pages = null, toutes les pages du document sont affectées.

```csharp
public int[] Pages { get; set; }
```

## Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//Appliquer le tampon uniquement sur les pages 1, 4 et 6.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Voir aussi

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


