---
title: "Font Class"
linktitle: "Font"
articleTitle: "Font"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.Font class. Represents font object."
type: docs
weight: 120
url: "/net/aspose.pdf.text/font/"
keywords: "Font, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Font class

Represents font object.

```csharp
public sealed class Font
```

## Properties

| Name | Description |
| --- | --- |
| [BaseFont](./basefont/) { get; } | Gets BaseFont value of PDF font object. Also known as PostScript name of the font. |
| [DecodedFontName](./decodedfontname/) { get; } | Sometimes PDF fonts(usually Chinese/Japanese/Korean fonts) could have specificical font name. This name is value of PDF font property "BaseFont" and sometimes this property could be represented in hexademical form. If read this name directly it could be represented in non-readable form. To get readable form it's necessary to decode font's name by rules specifical for this font. This property returns decoded font name, so use it for cases when you meet with a non-readable `FontName`. If property `FontName` has readable form this property will be the same as `FontName`, so you can use this property for any cases when you need to get font name in a readable form. |
| [FontName](./fontname/) { get; } | Gets font name of the [`Font`](../../aspose.pdf.text/font/) object. |
| [FontOptions](./fontoptions/) { get; } | Useful properties to tune Font behaviour |
| [IsAccessible](./isaccessible/) { get; } | Gets indicating whether the font is present (installed) in the system. |
| [IsEmbedded](./isembedded/) { get; set; } | Gets or sets a value that indicates whether the font is embedded. Font based on IFont will automatically be subset and embedded |
| [IsSubset](./issubset/) { get; set; } | Gets or sets a value that indicates whether the font is a subset. Font based on IFont will automatically be subset and embedded |

## Methods

| Name | Description |
| --- | --- |
| [GetLastFontEmbeddingError](./getlastfontembeddingerror/)() | An objective of this method - to return description of error if an attempt to embed font was failed. If there are no error cases it returns empty string. |
| [MeasureString](./measurestring/)(string, float) | Measures the string. |
| [Save](./save/)(Stream) | Saves the font into the stream. Note that the font is saved to intermediate TTF format intended to be used in a converted copy of the original document only. The font file is not intended to be used outside the original document context. |

### See Also

* [TextFragmentAbsorber](../textfragmentabsorber/)
* [FontRepository](../fontrepository/)
* [Document](../document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

