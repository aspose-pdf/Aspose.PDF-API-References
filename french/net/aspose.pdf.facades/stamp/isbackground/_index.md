---
title: Stamp.IsBackground
second_title: Aspose.PDF for .NET API Reference
description: Propriété Stamp. Obtient ou définit l'état de fond. Si vrai, le tampon sera placé en tant que fond de la page tamponnée. Par défaut, il est défini sur faux.
type: docs
weight: 30
url: /fr/net/aspose.pdf.facades/stamp/isbackground/
---
## Propriété Stamp.IsBackground

Obtient ou définit l'état de fond. Si vrai, le tampon sera placé en tant que fond de la page tamponnée. Par défaut, il est défini sur faux.

```csharp
public bool IsBackground { get; set; }
```

## Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
Stamp stamp = new Stamp();
stamp.BindLogo(new FormattedText("STAMP"));
stamp.IsBackground = true;
fileStamp.AddStamp(stamp);
fileStamp.Close();
```

### Voir aussi

* classe [Stamp](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)