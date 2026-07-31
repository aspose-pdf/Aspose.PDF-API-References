---
title: "GraphicsAbsorber.SuppressUpdate"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo GraphicsAbsorber. Sopprime l'aggiornamento per i Contenuti e tutti i Contenuti. È stato realizzato per aumentare le prestazioni, vedi anche"
type: docs
weight: 50
url: /it/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## GraphicsAbsorber.SuppressUpdate method

Sopprime l'aggiornamento per [`Contents`](../../../aspose.pdf/page/contents/) e tutti i [`Contents`](../../../aspose.pdf/xform/contents/). È stato realizzato per aumentare le prestazioni, vedi anche.

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

### Vedi anche

* class [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


