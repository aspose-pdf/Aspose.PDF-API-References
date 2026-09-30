---
title: "GraphicsAbsorber.SuppressUpdate"
linktitle: "SuppressUpdate"
articleTitle: "SuppressUpdate"
second_title: "Aspose.PDF for .NET API Reference"
description: "GraphicsAbsorber method. Suppresses update for Contents and all Contents Was made for performance increase, see also ."
type: docs
weight: 30
url: "/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/"
product_version: "26.9.0"
---
## GraphicsAbsorber.SuppressUpdate method

Suppresses update for `Contents` and all `Contents` 
 Was made for performance increase, see also .

```csharp
public void SuppressUpdate()
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

* [SuppressUpdate](../suppressupdate/)
* class [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

