---
title: "Font Class"
linktitle: "Font"
articleTitle: "Font"
second_title: "Aspose.PDF for .NET"
description: "Represents font object."
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
| [DecodedFontName](./decodedfontname/) { get; } | Sometimes PDF fonts(usually Chinese/Japanese/Korean fonts) could have specificical font name. |
| [FontName](./fontname/) { get; } | Gets font name of the [`Font`](../../aspose.pdf.text/font/) object. |
| [FontOptions](./fontoptions/) { get; } | Useful properties to tune Font behaviour. |
| [IsAccessible](./isaccessible/) { get; } | Gets indicating whether the font is present (installed) in the system. |
| [IsEmbedded](./isembedded/) { get; set; } | Gets or sets a value that indicates whether the font is embedded. |
| [IsSubset](./issubset/) { get; set; } | Gets or sets a value that indicates whether the font is a subset. |

## Methods

| Name | Description |
| --- | --- |
| [GetLastFontEmbeddingError](./getlastfontembeddingerror/) | An objective of this method - to return description of error if an attempt. |
| [MeasureString](./measurestring/)(*string, float*) | Measures the string. |
| [Save](./save/)(*Stream*) | Saves the font into the stream. |

### See Also

* [TextFragmentAbsorber](../textfragmentabsorber/)
* [FontRepository](../fontrepository/)
* [Document](../document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

