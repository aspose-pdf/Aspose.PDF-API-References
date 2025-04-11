---
title: GraphicsAbsorber.ResumeUpdate
second_title: Aspose.PDF for .NET API Reference
description: Metodo GraphicsAbsorber. Riprendi l'aggiornamento per i Contenuti e tutti i Contenuti è stato realizzato per aumentare le prestazioni, vedere anche
type: docs
weight: 40
url: /it/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## Metodo GraphicsAbsorber.ResumeUpdate

Riprendi l'aggiornamento per [`Contents`](../../../aspose.pdf/page/contents/) e tutti i [`Contents`](../../../aspose.pdf/xform/contents/) è stato realizzato per aumentare le prestazioni, vedere anche .

```csharp
public void ResumeUpdate()
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

### Vedi anche

* classe [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)