---
title: Stamp.Pages
second_title: Aspose.PDF for .NET API Reference
description: Propriété Stamp. Obtient ou définit un tableau avec les numéros de pages qui seront affectées par le tampon. Si Pages = null, toutes les pages du document sont affectées.
type: docs
weight: 60
url: /fr/net/aspose.pdf.facades/stamp/pages/
---
## Propriété Stamp.Pages

Obtient ou définit un tableau avec les numéros de pages qui seront affectées par le tampon. Si Pages = null, toutes les pages du document sont affectées.

```csharp
public int[] Pages { get; set; }
```

## Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Aspose.Pdf.Facades.Stamp();
stamp.BindLogo(new FormattedText(text));
//put stamp only on 1st, 4th and 6th page.
stamp.Pages = new int[] { 1, 4, 6 };
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Voir aussi

* classe [Stamp](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)