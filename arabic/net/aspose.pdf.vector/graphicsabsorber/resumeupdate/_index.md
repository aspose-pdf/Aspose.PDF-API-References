---
title: GraphicsAbsorber.ResumeUpdate
second_title: Aspose.PDF for .NET API Reference
description: طريقة GraphicsAbsorber. استئناف التحديث للمحتويات وجميع المحتويات تم إنشاؤه لزيادة الأداء انظر أيضًا
type: docs
weight: 40
url: /ar/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## طريقة GraphicsAbsorber.ResumeUpdate

استئناف التحديث لـ [`Contents`](../../../aspose.pdf/page/contents/) وجميع [`Contents`](../../../aspose.pdf/xform/contents/) تم إنشاؤه لزيادة الأداء، انظر أيضًا .

```csharp
public void ResumeUpdate()
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