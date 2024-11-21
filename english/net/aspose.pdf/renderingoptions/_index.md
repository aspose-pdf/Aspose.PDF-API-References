---
title: Class RenderingOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.RenderingOptions class. Represents rendering options
type: docs
weight: 7330
url: /net/aspose.pdf/renderingoptions/
---
## RenderingOptions class

Represents rendering options.

```csharp
public sealed class RenderingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | Gets or sets barcode optimization mode. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | Indicates that all fonts will be converted to TTF unicode versions. That is useful for compatibility reasons and to optimize font usage, cause every new TTF font will have not all the symbols from source font, but only symbols which are used in text. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | Gets/sets the default name of font used to substitute of missing fonts. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | Gets or sets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false by default |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | Gets or sets hiqh quality mode for interpolation. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | Maximum count of fonts in fonts cache. Default value is 10. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | Maximum count of symbols in symbol cache. Default value is 100. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | Gets or sets optimize dimensions mode. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | Gets or sets a mode where system fonts are rendered natively. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | Usage of this flag turn on font hinting mechanism. Font hinting is the use of mathematical instructions to adjust the display of an outline font. In some cases turning this flag on may solve problems with text legibility. At current moment usage of this flag could give effect only for TTF fonts, if these fonts are used in source document. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


