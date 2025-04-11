---
title: GraphicsAbsorber.SuppressUpdate
second_title: Aspose.PDF for .NET API Reference
description: Metodo GraphicsAbsorber. Sopprime l'aggiornamento per i Contenuti e tutti i Contenuti È stato creato per aumentare le prestazioni, vedere anche
type: docs
weight: 50
url: /it/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## Metodo GraphicsAbsorber.SuppressUpdate

Sopprime l'aggiornamento per [`Contents`](../../../aspose.pdf/page/contents/) e tutti i [`Contents`](../../../aspose.pdf/xform/contents/) È stato creato per aumentare le prestazioni, vedere anche .

```csharp
public void SuppressUpdate()
```

## Esempi

```csharp
va.SuppressUpdate();
foreach (var el in graphicAbsorber.Elements)
{
    var pos = el.Position;
    el.Position = new Point(pos.X - 100, pos.Y);
}
va.ResumeUpdate();
```

### Vedi Anche

* classe [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)