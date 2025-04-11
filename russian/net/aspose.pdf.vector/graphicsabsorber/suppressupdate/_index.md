---
title: GraphicsAbsorber.SuppressUpdate
second_title: Aspose.PDF for .NET API Reference
description: Метод GraphicsAbsorber. Подавляет обновление для Contents и всех Contents. Был создан для повышения производительности, см. также
type: docs
weight: 50
url: /ru/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## Метод GraphicsAbsorber.SuppressUpdate

Подавляет обновление для [`Contents`](../../../aspose.pdf/page/contents/) и всех [`Contents`](../../../aspose.pdf/xform/contents/). Был создан для повышения производительности, см. также .

```csharp
public void SuppressUpdate()
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