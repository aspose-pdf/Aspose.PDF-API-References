---
title: GraphicsAbsorber.SuppressUpdate
second_title: Aspose.PDF for .NET API Reference
description: GraphicsAbsorber-Methode. Unterdrückt das Update für Inhalte und alle Inhalte. Wurde zur Leistungssteigerung erstellt, siehe auch
type: docs
weight: 50
url: /de/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## GraphicsAbsorber.SuppressUpdate-Methode

Unterdrückt das Update für [`Contents`](../../../aspose.pdf/page/contents/) und alle [`Contents`](../../../aspose.pdf/xform/contents/). Wurde zur Leistungssteigerung erstellt, siehe auch .

```csharp
public void SuppressUpdate()
```

## Beispiele

```csharp
va.SuppressUpdate();
foreach (var el in graphicAbsorber.Elements)
{
    var pos = el.Position;
    el.Position = new Point(pos.X - 100, pos.Y);
}
va.ResumeUpdate();
```

### Siehe auch

* Klasse [GraphicsAbsorber](../)
* Namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* Assembly [Aspose.PDF](../../../)