---
title: GraphicsAbsorber.SuppressUpdate
second_title: Aspose.PDF for .NET API Reference
description: Método GraphicsAbsorber. Suprime la actualización de Contents y todos los Contents. Fue creado para aumentar el rendimiento, ver también
type: docs
weight: 50
url: /es/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## Método GraphicsAbsorber.SuppressUpdate

Suprime la actualización de [`Contents`](../../../aspose.pdf/page/contents/) y todos los [`Contents`](../../../aspose.pdf/xform/contents/). Fue creado para aumentar el rendimiento, ver también .

```csharp
public void SuppressUpdate()
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
* ensamblado [Aspose.PDF](../../../)