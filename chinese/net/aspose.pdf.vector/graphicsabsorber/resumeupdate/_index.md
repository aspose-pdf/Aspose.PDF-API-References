---
title: GraphicsAbsorber.ResumeUpdate
second_title: Aspose.PDF for .NET API Reference
description: GraphicsAbsorber 方法。恢复对 [`Contents`](../../../aspose.pdf/page/contents/) 和所有 [`Contents`](../../../aspose.pdf/xform/contents/) 的更新，以提高性能，另见。
type: docs
weight: 40
url: /zh/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## GraphicsAbsorber.ResumeUpdate 方法

恢复对 [`Contents`](../../../aspose.pdf/page/contents/) 和所有 [`Contents`](../../../aspose.pdf/xform/contents/) 的更新，以提高性能，另见。

```csharp
public void ResumeUpdate()
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