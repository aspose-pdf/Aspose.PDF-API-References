---
title: GraphicsAbsorber.ResumeUpdate
second_title: Aspose.PDF for .NET API Reference
description: GraphicsAbsorber 메서드. 성능 향상을 위해 Contents 및 모든 Contents의 업데이트를 재개합니다. 또한 참조하십시오.
type: docs
weight: 40
url: /ko/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## GraphicsAbsorber.ResumeUpdate 메서드

[`Contents`](../../../aspose.pdf/page/contents/) 및 모든 [`Contents`](../../../aspose.pdf/xform/contents/)의 업데이트를 재개합니다. 성능 향상을 위해 만들어졌습니다. 또한 참조하십시오.

```csharp
public void ResumeUpdate()
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

### 참조

* 클래스 [GraphicsAbsorber](../)
* 네임스페이스 [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* 어셈블리 [Aspose.PDF](../../../)