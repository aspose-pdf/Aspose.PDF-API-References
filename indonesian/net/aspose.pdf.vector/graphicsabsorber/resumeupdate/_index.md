---
title: GraphicsAbsorber.ResumeUpdate
second_title: Aspose.PDF for .NET API Reference
description: Metode GraphicsAbsorber. Melanjutkan pembaruan untuk Konten dan semua Konten dibuat untuk peningkatan kinerja lihat juga
type: docs
weight: 40
url: /id/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## Metode GraphicsAbsorber.ResumeUpdate

Melanjutkan pembaruan untuk [`Contents`](../../../aspose.pdf/page/contents/) dan semua [`Contents`](../../../aspose.pdf/xform/contents/) dibuat untuk peningkatan kinerja, lihat juga .

```csharp
public void ResumeUpdate()
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
* ruang nama [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)