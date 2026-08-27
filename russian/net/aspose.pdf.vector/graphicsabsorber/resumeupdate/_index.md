---
title: "GraphicsAbsorber.ResumeUpdate"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод GraphicsAbsorber. Возобновить обновление для Contents и всех Contents. Было сделано для повышения производительности, см. также"
type: docs
weight: 40
url: /ru/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## GraphicsAbsorber.ResumeUpdate method

Возобновить обновление для [`Contents`](../../../aspose.pdf/page/contents/) и всех [`Contents`](../../../aspose.pdf/xform/contents/). Было сделано для повышения производительности, см. также.

```csharp
public void ResumeUpdate()
```

## Примеры

```csharp
va.SuppressUpdate();
foreach (var el in graphicAbsorber.Elements)
{
    var pos = el.Position;
    el.Position = new Point(pos.X - 100, pos.Y);
}
va.ResumeUpdate();
```

### См. также

* class [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


