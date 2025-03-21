---
title: Class SvgExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.SvgExtractionOptions class. Represents an options class for extracting vector graphics from the pdf document page
type: docs
weight: 11240
url: /net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class

Represents an options class for extracting vector graphics from the pdf document page.

```csharp
public class SvgExtractionOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | Gets and sets the option to automatically group subpaths into images. This option excludes the [`GroupStrength`](./groupstrength/) option. |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | Gets and sets opttion to extracts every subpath from a PDF document to separate SVG images. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | Gets and sets the bounding rectangle that defines the extraction area for SVG extraction. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | Gets and sets an option The strength of grouping subpaths into images. Allows you to configure the degree of grouping of subpaths. The value ranges is from 0 to 1. A value of 0 corresponds to the [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) option being enabled. A value of 1 will create single image for all vector paths on the page. The option has an effect when [`AutoGrouping`](./autogrouping/) is false. The default value is `0.8`. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | Gets or sets the minimum stroke width that will be used in the resulting SVG. If the PDF use a thinner stroke width, it will be replaced with this width. The default value is 0.5. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | Gets and sets an option to define strictly checks whether subpaths are within the specified rectangle in [`ExtractionAreaBound`](./extractionareabound/). If set to false, then subpaths that are not completely included in [`ExtractionAreaBound`](./extractionareabound/) will be extracted. The default value is `True`. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | Gets and sets a flag that determines whether XFrom found on pages should be unpacked or not. XFrom elements can end up in different SVG files. Only XForms that are rendered by Do statements from the page content are unpacked. Nested XForms are not unpacked. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | Gets and sets option to unpack only the XForm corresponding to the specified predicate. |

### See Also

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


