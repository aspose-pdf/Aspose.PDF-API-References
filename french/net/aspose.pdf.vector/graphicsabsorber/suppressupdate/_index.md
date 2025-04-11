---
title: GraphicsAbsorber.SuppressUpdate
second_title: Aspose.PDF for .NET API Reference
description: Méthode GraphicsAbsorber. Supprime la mise à jour pour Contents et tous les Contents a été conçu pour augmenter les performances voir aussi
type: docs
weight: 50
url: /fr/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## Méthode GraphicsAbsorber.SuppressUpdate

Supprime la mise à jour pour [`Contents`](../../../aspose.pdf/page/contents/) et tous les [`Contents`](../../../aspose.pdf/xform/contents/) a été conçu pour augmenter les performances, voir aussi .

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

* classe [GraphicsAbsorber](../)
* espace de noms [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)