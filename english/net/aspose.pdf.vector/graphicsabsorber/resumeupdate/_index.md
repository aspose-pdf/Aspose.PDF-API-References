---
title: GraphicsAbsorber.ResumeUpdate
second_title: Aspose.PDF for .NET API Reference
description: GraphicsAbsorber method. Resume update for Contents and all Contents Was made for performance increase see also 
type: docs
weight: 40
url: /net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## GraphicsAbsorber.ResumeUpdate method

Resume update for [`Contents`](../../../aspose.pdf/page/contents/) and all [`Contents`](../../../aspose.pdf/xform/contents/) Was made for performance increase, see also .

```csharp
public void ResumeUpdate()
```

## Examples

```csharp
va.SuppressUpdate();
foreach (var el in graphicAbsorber.Elements)
{
    var pos = el.Position;
    el.Position = new Point(pos.X - 100, pos.Y);
}
va.ResumeUpdate();
```

### See Also

* class [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


