---
title: GraphicsAbsorber.ResumeUpdate
second_title: Aspose.PDF for .NET API Reference
description: Метод GraphicsAbsorber. Возобновить обновление для Contents и всех Contents было сделано для увеличения производительности, см. также
type: docs
weight: 40
url: /ru/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## Метод GraphicsAbsorber.ResumeUpdate

Возобновить обновление для [`Contents`](../../../aspose.pdf/page/contents/) и всех [`Contents`](../../../aspose.pdf/xform/contents/) было сделано для увеличения производительности, см. также .

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

* класс [GraphicsAbsorber](../)
* пространство имен [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* сборка [Aspose.PDF](../../../)