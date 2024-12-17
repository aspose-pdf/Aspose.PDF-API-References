---
title: SvgExtractionOptions.MinStrokeWidth
second_title: Aspose.PDF for .NET API Reference
description: SvgExtractionOptions property. Gets or sets the minimum stroke width that will be used in the resulting SVG. If the PDF use a thinner stroke width it will be replaced with this width. The default value is 0.5
type: docs
weight: 60
url: /net/aspose.pdf.vector/svgextractionoptions/minstrokewidth/
---
## SvgExtractionOptions.MinStrokeWidth property

Gets or sets the minimum stroke width that will be used in the resulting SVG. If the PDF use a thinner stroke width, it will be replaced with this width. The default value is 0.5.

```csharp
public double MinStrokeWidth { get; set; }
```

## Remarks

The value is expressed in transformed user space units of the converted PDF page. By default 1 user space unit is 1/72 inch (0.35 mm), but this can be overridden by the PDF document. Transforms can affect the actual minimum width in the generated SVG.

### See Also

* class [SvgExtractionOptions](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


