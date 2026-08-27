---
title: "GraphicsAbsorber.ResumeUpdate"
second_title: "Aspose.PDF for .NET API 参考"
description: "GraphicsAbsorber 方法。恢复对 Contents 及所有 Contents 的更新，此操作为提升性能而创建，另请参见。"
type: docs
weight: 40
url: /zh/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## GraphicsAbsorber.ResumeUpdate method

恢复对 [`Contents`](../../../aspose.pdf/page/contents/) 及所有 [`Contents`](../../../aspose.pdf/xform/contents/) 的更新，此操作为提升性能而创建，另请参见。

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

### 另请参见

* class [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


