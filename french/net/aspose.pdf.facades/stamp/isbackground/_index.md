---
title: "Stamp.IsBackground"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété Stamp. Obtient ou définit l'état d'arrière-plan. Si vrai, le tampon sera placé en arrière-plan de la page tamponnée. Par défaut, il est défini sur false"
type: docs
weight: 30
url: /fr/net/aspose.pdf.facades/stamp/isbackground/
---
## Stamp.IsBackground property

Obtient ou définit le statut d'arrière-plan. Si true, le tampon sera placé en arrière-plan de la page estampillée. Par défaut, il est défini sur false.

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

* class [Stamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


