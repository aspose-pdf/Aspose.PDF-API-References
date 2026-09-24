---
title: "SvgExtractionOptions.GroupStrength"
linktitle: "GroupStrength"
articleTitle: "GroupStrength"
second_title: "Aspose.PDF for .NET API Reference"
description: "SvgExtractionOptions property. Gets and sets an option The strength of grouping subpaths into images. Allows you to configure the degree of grouping of subpa..."
type: docs
weight: 70
url: "/net/aspose.pdf.vector/svgextractionoptions/groupstrength/"
product_version: "26.9.0"
---
## SvgExtractionOptions.GroupStrength property

Gets and sets an option The strength of grouping subpaths into images. Allows you to configure the degree of grouping of subpaths.
 The value ranges is from 0 to 1. A value of 0 corresponds to the `ExtractEverySubPathToSvg` option being enabled.
 A value of 1 will create single image for all vector paths on the page.
 The option has an effect when `AutoGrouping` is false.
 The default value is `0.8`.

```csharp
public double GroupStrength { get; set; }
```

### Property Value

double

### See Also

* class [SvgExtractionOptions](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

