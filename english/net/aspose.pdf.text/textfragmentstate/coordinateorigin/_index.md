---
title: "TextFragmentState.CoordinateOrigin"
linktitle: "CoordinateOrigin"
articleTitle: "CoordinateOrigin"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextFragmentState property. Gets or sets text CoordinateOrigin. If CoordinateOrigin is Descender, the text Y coordinate corresponds to the font's lowest poin..."
type: docs
weight: 250
url: "/net/aspose.pdf.text/textfragmentstate/coordinateorigin/"
product_version: "26.9"
---
## TextFragmentState.CoordinateOrigin property

Gets or sets text CoordinateOrigin.
 If CoordinateOrigin is Descender, the text Y coordinate corresponds to the font's lowest point.
 If CoordinateOrigin is BaseLine, the text Y coordinate corresponds to the font's baseline.
 The default value is Descender.
 If the font's Descent value is too big, text can be rendered higher than other fonts.
 In this case, CoordinateOrigin BaseLine can be selected for better text rendering.

```csharp
public override CoordinateOrigin CoordinateOrigin { get; set; }
```

### See Also

* enum [CoordinateOrigin](../../coordinateorigin/)
* class [TextFragmentState](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

