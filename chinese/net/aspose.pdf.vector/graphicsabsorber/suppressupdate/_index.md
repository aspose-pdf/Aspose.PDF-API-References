---
title: "GraphicsAbsorber.SuppressUpdate"
second_title: "Aspose.PDF for .NET API 参考"
description: "GraphicsAbsorber 方法。抑制对 Contents 及所有 Contents 的更新，此操作为提升性能而创建，另请参见。"
type: docs
weight: 50
url: /zh/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## GraphicsAbsorber.SuppressUpdate method

抑制对 [`Contents`](../../../aspose.pdf/page/contents/) 及所有 [`Contents`](../../../aspose.pdf/xform/contents/) 的更新，此操作为提升性能而创建，另请参见。

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

### 另请参见

* class [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


