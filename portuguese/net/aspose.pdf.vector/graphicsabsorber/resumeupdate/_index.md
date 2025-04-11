---
title: GraphicsAbsorber.ResumeUpdate
second_title: Aspose.PDF for .NET API Reference
description: Método GraphicsAbsorber. Retomar atualização para Conteúdos e todos os Conteúdos foi feito para aumento de desempenho, veja também
type: docs
weight: 40
url: /pt/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## Método GraphicsAbsorber.ResumeUpdate

Retomar atualização para [`Contents`](../../../aspose.pdf/page/contents/) e todos os [`Contents`](../../../aspose.pdf/xform/contents/) foi feito para aumento de desempenho, veja também .

```csharp
public void ResumeUpdate()
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