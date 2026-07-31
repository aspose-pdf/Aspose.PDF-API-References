---
title: "GraphicsAbsorber.ResumeUpdate"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode GraphicsAbsorber. Lanjutkan pembaruan untuk Konten dan semua Konten dibuat untuk meningkatkan kinerja, lihat juga"
type: docs
weight: 40
url: /id/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## GraphicsAbsorber.ResumeUpdate method

Lanjutkan pembaruan untuk [`Contents`](../../../aspose.pdf/page/contents/) dan semua [`Contents`](../../../aspose.pdf/xform/contents/) dibuat untuk meningkatkan kinerja, lihat juga.

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

* class [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


