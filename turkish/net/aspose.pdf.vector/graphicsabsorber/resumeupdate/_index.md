---
title: GraphicsAbsorber.ResumeUpdate
second_title: Aspose.PDF for .NET API Reference
description: GraphicsAbsorber metodu. İçerikler için güncellemeyi devam ettirin ve tüm İçerikler performans artışı için yapıldı, ayrıca bakınız
type: docs
weight: 40
url: /tr/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## GraphicsAbsorber.ResumeUpdate metodu

[`Contents`](../../../aspose.pdf/page/contents/) ve tüm [`Contents`](../../../aspose.pdf/xform/contents/) için güncellemeyi devam ettirin, performans artışı için yapıldı, ayrıca bakınız .

```csharp
public void ResumeUpdate()
```

## Örnekler

```csharp
va.SuppressUpdate();
foreach (var el in graphicAbsorber.Elements)
{
    var pos = el.Position;
    el.Position = new Point(pos.X - 100, pos.Y);
}
va.ResumeUpdate();
```

### Ayrıca Bakınız

* sınıf [GraphicsAbsorber](../)
* ad alanı [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* derleme [Aspose.PDF](../../../)