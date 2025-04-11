---
title: GraphicsAbsorber.SuppressUpdate
second_title: Aspose.PDF for .NET API Reference
description: Metode GraphicsAbsorber. Menekan pembaruan untuk Contents dan semua Contents Dibuat untuk peningkatan kinerja lihat juga
type: docs
weight: 50
url: /id/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## Metode GraphicsAbsorber.SuppressUpdate

Menekan pembaruan untuk [`Contents`](../../../aspose.pdf/page/contents/) dan semua [`Contents`](../../../aspose.pdf/xform/contents/) Dibuat untuk peningkatan kinerja, lihat juga .

```csharp
public void SuppressUpdate()
```

## Contoh

```csharp
va.SuppressUpdate();
foreach (var el in graphicAbsorber.Elements)
{
    var pos = el.Position;
    el.Position = new Point(pos.X - 100, pos.Y);
}
va.ResumeUpdate();
```

### Lihat Juga

* kelas [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)