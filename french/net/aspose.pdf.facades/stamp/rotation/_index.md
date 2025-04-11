---
title: Stamp.Rotation
second_title: Aspose.PDF for .NET API Reference
description: Propriété Stamp. Obtient ou définit la rotation du tampon en degrés
type: docs
weight: 80
url: /fr/net/aspose.pdf.facades/stamp/rotation/
---
## Propriété Stamp.Rotation

Obtient ou définit la rotation du tampon en degrés.

```csharp
public float Rotation { get; set; }
```

## Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.Rotation = 90;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Voir aussi

* classe [Stamp](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)