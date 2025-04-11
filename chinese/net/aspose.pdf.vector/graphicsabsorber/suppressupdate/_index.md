---
title: GraphicsAbsorber.SuppressUpdate
second_title: Aspose.PDF for .NET API Reference
description: GraphicsAbsorber 方法。抑制对 Contents 和所有 Contents 的更新，旨在提高性能，另见
type: docs
weight: 50
url: /zh/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## GraphicsAbsorber.SuppressUpdate 方法

抑制对 [`Contents`](../../../aspose.pdf/page/contents/) 和所有 [`Contents`](../../../aspose.pdf/xform/contents/) 的更新，旨在提高性能，另见 。

```csharp
public void SuppressUpdate()
```

## 示例

```csharp
va.SuppressUpdate();
foreach (var el in graphicAbsorber.Elements)
{
    var pos = el.Position;
    el.Position = new Point(pos.X - 100, pos.Y);
}
va.ResumeUpdate();
```

### 另见

* 类 [GraphicsAbsorber](../)
* 命名空间 [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* 程序集 [Aspose.PDF](../../../)