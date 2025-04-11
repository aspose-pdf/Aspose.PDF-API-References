---
title: GraphicsAbsorber.SuppressUpdate
second_title: Aspose.PDF for .NET API Reference
description: طريقة GraphicsAbsorber. تمنع التحديث لـ Contents وجميع Contents تم إنشاؤها لزيادة الأداء انظر أيضًا
type: docs
weight: 50
url: /ar/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## طريقة GraphicsAbsorber.SuppressUpdate

تمنع التحديث لـ [`Contents`](../../../aspose.pdf/page/contents/) وجميع [`Contents`](../../../aspose.pdf/xform/contents/) تم إنشاؤها لزيادة الأداء، انظر أيضًا .

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