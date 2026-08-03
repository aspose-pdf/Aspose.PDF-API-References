---
title: "GraphicsAbsorber.SuppressUpdate"
second_title: "Aspose.PDF för .NET API‑referens"
description: "GraphicsAbsorber‑metod. Undertrycker uppdatering för Contents och alla Contents gjordes för prestandaförbättring, se även"
type: docs
weight: 50
url: /sv/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## GraphicsAbsorber.SuppressUpdate method

Undertrycker uppdatering för [`Contents`](../../../aspose.pdf/page/contents/) och alla [`Contents`](../../../aspose.pdf/xform/contents/) gjordes för prestandaförbättring, se även.

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

### Se även

* class [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


