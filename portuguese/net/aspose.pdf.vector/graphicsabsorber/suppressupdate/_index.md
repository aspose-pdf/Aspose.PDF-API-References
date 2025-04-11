---
title: GraphicsAbsorber.SuppressUpdate
second_title: Aspose.PDF for .NET API Reference
description: Método GraphicsAbsorber. Suprime a atualização para Contents e todos os Contents. Foi feito para aumentar o desempenho, veja também
type: docs
weight: 50
url: /pt/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## Método GraphicsAbsorber.SuppressUpdate

Suprime a atualização para [`Contents`](../../../aspose.pdf/page/contents/) e todos os [`Contents`](../../../aspose.pdf/xform/contents/). Foi feito para aumentar o desempenho, veja também .

```csharp
public void SuppressUpdate()
```

## Exemplos

```csharp
va.SuppressUpdate();
foreach (var el in graphicAbsorber.Elements)
{
    var pos = el.Position;
    el.Position = new Point(pos.X - 100, pos.Y);
}
va.ResumeUpdate();
```

### Veja Também

* classe [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)