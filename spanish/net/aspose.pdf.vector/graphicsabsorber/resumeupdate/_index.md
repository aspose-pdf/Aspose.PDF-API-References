---
title: GraphicsAbsorber.ResumeUpdate
second_title: Aspose.PDF for .NET API Reference
description: Método GraphicsAbsorber. Reanudar actualización para Contenidos y todos los Contenidos se hizo para aumentar el rendimiento, ver también
type: docs
weight: 40
url: /es/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## Método GraphicsAbsorber.ResumeUpdate

Reanudar actualización para [`Contents`](../../../aspose.pdf/page/contents/) y todos los [`Contents`](../../../aspose.pdf/xform/contents/) se hizo para aumentar el rendimiento, ver también .

```csharp
public void ResumeUpdate()
```

## Ejemplos

```csharp
va.SuppressUpdate();
foreach (var el in graphicAbsorber.Elements)
{
    var pos = el.Position;
    el.Position = new Point(pos.X - 100, pos.Y);
}
va.ResumeUpdate();
```

### Ver También

* clase [GraphicsAbsorber](../)
* espacio de nombres [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* ensamblaje [Aspose.PDF](../../../)