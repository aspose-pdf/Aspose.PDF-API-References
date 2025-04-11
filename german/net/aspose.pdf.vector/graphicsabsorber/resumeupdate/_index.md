---
title: GraphicsAbsorber.ResumeUpdate
second_title: Aspose.PDF for .NET API Reference
description: GraphicsAbsorber-Methode. Aktualisierung fortsetzen für Inhalte und alle Inhalte wurde zur Leistungssteigerung erstellt, siehe auch
type: docs
weight: 40
url: /de/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## GraphicsAbsorber.ResumeUpdate-Methode

Aktualisierung fortsetzen für [`Contents`](../../../aspose.pdf/page/contents/) und alle [`Contents`](../../../aspose.pdf/xform/contents/) wurde zur Leistungssteigerung erstellt, siehe auch .

```csharp
public void ResumeUpdate()
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