---
title: "GraphicsAbsorber.SuppressUpdate"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة GraphicsAbsorber. يمنع التحديث لـ Contents وجميع Contents تم لزيادة الأداء، انظر أيضًا"
type: docs
weight: 50
url: /ar/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## GraphicsAbsorber.SuppressUpdate method

يمنع التحديث لـ [`Contents`](../../../aspose.pdf/page/contents/) وجميع [`Contents`](../../../aspose.pdf/xform/contents/) تم لزيادة الأداء، انظر أيضًا.

```csharp
public void SuppressUpdate()
```

## أمثلة

```csharp
va.SuppressUpdate();
foreach (var el in graphicAbsorber.Elements)
{
    var pos = el.Position;
    el.Position = new Point(pos.X - 100, pos.Y);
}
va.ResumeUpdate();
```

### انظر أيضًا

* class [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


