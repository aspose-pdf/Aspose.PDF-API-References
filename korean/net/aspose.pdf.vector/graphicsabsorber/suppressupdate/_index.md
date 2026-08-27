---
title: "GraphicsAbsorber.SuppressUpdate"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "GraphicsAbsorber 메서드. Contents 및 모든 Contents에 대한 업데이트를 억제합니다. 성능 향상을 위해 만들어졌으며, 자세한 내용은 참고하십시오."
type: docs
weight: 50
url: /ko/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## GraphicsAbsorber.SuppressUpdate method

[`Contents`](../../../aspose.pdf/page/contents/) 및 모든 [`Contents`](../../../aspose.pdf/xform/contents/)에 대한 업데이트를 억제합니다. 성능 향상을 위해 만들어졌으며, 자세한 내용은 참고하십시오.

```csharp
public void SuppressUpdate()
```

## 예제

```csharp
va.SuppressUpdate();
foreach (var el in graphicAbsorber.Elements)
{
    var pos = el.Position;
    el.Position = new Point(pos.X - 100, pos.Y);
}
va.ResumeUpdate();
```

### 또 보기

* class [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


