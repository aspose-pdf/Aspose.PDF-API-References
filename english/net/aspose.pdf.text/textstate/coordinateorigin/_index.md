---
title: "TextState.CoordinateOrigin"
linktitle: "CoordinateOrigin"
articleTitle: "CoordinateOrigin"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextState property. Gets or sets text CoordinateOrigin. If CoordinateOrigin is Descender, the text Y coordinate corresponds to the font's lowest point. If Co..."
type: docs
weight: 290
url: "/net/aspose.pdf.text/textstate/coordinateorigin/"
product_version: "26.9"
---
## TextState.CoordinateOrigin property

Gets or sets text CoordinateOrigin.
 If CoordinateOrigin is Descender, the text Y coordinate corresponds to the font's lowest point.
 If CoordinateOrigin is BaseLine, the text Y coordinate corresponds to the font's baseline.
 The default value is Descender.
 If the font's Descent value is too big, text can be rendered higher than other fonts.
 In this case, CoordinateOrigin BaseLine can be selected for better text rendering.

```csharp
public virtual CoordinateOrigin CoordinateOrigin { get; set; }
```

### See Also

* enum [CoordinateOrigin](../../coordinateorigin/)
* class [TextState](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

