---
title: GraphicsAbsorber.SuppressUpdate
second_title: Aspose.PDF for .NET API Reference
description: GraphicsAbsorber-metod. Suppresserar uppdatering för Innehåll och alla Innehåll. Gjord för prestandaökning, se även
type: docs
weight: 50
url: /sv/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## GraphicsAbsorber.SuppressUpdate metod

Suppresserar uppdatering för [`Contents`](../../../aspose.pdf/page/contents/) och alla [`Contents`](../../../aspose.pdf/xform/contents/). Gjord för prestandaökning, se även .

```csharp
public void SuppressUpdate()
```

## Exempel

```csharp
va.SuppressUpdate();
foreach (var el in graphicAbsorber.Elements)
{
    var pos = el.Position;
    el.Position = new Point(pos.X - 100, pos.Y);
}
va.ResumeUpdate();
```

### Se Även

* klass [GraphicsAbsorber](../)
* namnrymd [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* sammansättning [Aspose.PDF](../../../)