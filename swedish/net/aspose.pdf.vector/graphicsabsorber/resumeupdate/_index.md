---
title: "GraphicsAbsorber.ResumeUpdate"
second_title: "Aspose.PDF för .NET API‑referens"
description: "GraphicsAbsorber‑metod. Återuppta uppdatering för Contents och alla Contents gjordes för prestandaförbättring, se även"
type: docs
weight: 40
url: /sv/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## GraphicsAbsorber.ResumeUpdate method

Återuppta uppdatering för [`Contents`](../../../aspose.pdf/page/contents/) och alla [`Contents`](../../../aspose.pdf/xform/contents/) gjordes för prestandaförbättring, se även.

```csharp
public void ResumeUpdate()
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


