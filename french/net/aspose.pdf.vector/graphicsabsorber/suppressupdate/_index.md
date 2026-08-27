---
title: "GraphicsAbsorber.SuppressUpdate"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode GraphicsAbsorber. Supprime la mise à jour pour Contents et tous les Contents. Cela a été fait pour améliorer les performances, voir aussi."
type: docs
weight: 50
url: /fr/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## GraphicsAbsorber.SuppressUpdate method

Supprime la mise à jour pour [`Contents`](../../../aspose.pdf/page/contents/) et tous les [`Contents`](../../../aspose.pdf/xform/contents/). Cela a été fait pour améliorer les performances, voir aussi.

```csharp
public void SuppressUpdate()
```

## Exemples

```csharp
va.SuppressUpdate();
foreach (var el in graphicAbsorber.Elements)
{
    var pos = el.Position;
    el.Position = new Point(pos.X - 100, pos.Y);
}
va.ResumeUpdate();
```

### Voir aussi

* class [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


