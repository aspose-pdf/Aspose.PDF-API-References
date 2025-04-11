---
title: GraphicsAbsorber.ResumeUpdate
second_title: Aspose.PDF for .NET API Reference
description: Méthode GraphicsAbsorber. Reprendre la mise à jour pour les [`Contents`](../../../aspose.pdf/page/contents/) et tous les [`Contents`](../../../aspose.pdf/xform/contents/) a été réalisée pour augmenter les performances, voir aussi .
type: docs
weight: 40
url: /fr/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## Méthode GraphicsAbsorber.ResumeUpdate

Reprendre la mise à jour pour les [`Contents`](../../../aspose.pdf/page/contents/) et tous les [`Contents`](../../../aspose.pdf/xform/contents/) a été réalisée pour augmenter les performances, voir aussi .

```csharp
public void ResumeUpdate()
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

* classe [GraphicsAbsorber](../)
* espace de noms [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)