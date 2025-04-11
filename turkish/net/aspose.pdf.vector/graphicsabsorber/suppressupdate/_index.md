---
title: GraphicsAbsorber.SuppressUpdate
second_title: Aspose.PDF for .NET API Reference
description: GraphicsAbsorber metodu. İçerikler için güncellemeyi bastırır ve tüm İçerikler performans artışı için yapıldı, ayrıca bakınız
type: docs
weight: 50
url: /tr/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## GraphicsAbsorber.SuppressUpdate metodu

[`Contents`](../../../aspose.pdf/page/contents/) ve tüm [`Contents`](../../../aspose.pdf/xform/contents/) için güncellemeyi bastırır, performans artışı için yapıldı, ayrıca bakınız .

```csharp
public void SuppressUpdate()
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