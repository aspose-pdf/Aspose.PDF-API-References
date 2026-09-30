---
title: "RenderingOptions Class"
linktitle: "RenderingOptions"
articleTitle: "RenderingOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.RenderingOptions class. Represents rendering options."
type: docs
weight: 2610
url: "/net/aspose.pdf/renderingoptions/"
keywords: "RenderingOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## RenderingOptions class

Represents rendering options.

```csharp
public sealed class RenderingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [RenderingOptions](./renderingoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AnalyzeFonts](./analyzefonts/) { get; set; } | Replaces fonts as necessary to ensure all characters in the text can be displayed. The font substitution algorithm follows these steps: 1. If the user explicitly sets the DefaultFontName property, check if the specified font can display the desired characters. 2. If no user-defined font is set, search through fonts added via the `Sources`. 3. Analyze the text to identify its alphabet or script and suggest font names accordingly. Attempt to locate and use these fonts from the system. 4. As a fallback, search the system for any font capable of displaying the required characters. |
| [BarcodeOptimization](./barcodeoptimization/) { get; set; } | Gets or sets barcode optimization mode. |
| [ConvertFontsToUnicodeTTF](./convertfontstounicodettf/) { get; set; } | Indicates that all fonts will be converted to TTF unicode versions. That is useful for compatibility reasons and to optimize font usage, cause every new TTF font will have not all the symbols from source font, but only symbols which are used in text. |
| [DefaultFontName](./defaultfontname/) { get; set; } | Gets/sets the default name of font used to substitute of missing fonts. |
| [HeightExtraUnits](./heightextraunits/) { get; set; } | Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |
| [IgnoreResourceFontErrors](./ignoreresourcefonterrors/) { get; set; } | Gets or sets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false by default |
| [InterpolationHighQuality](./interpolationhighquality/) { get; set; } | Gets or sets hiqh quality mode for interpolation. |
| [MaxFontsCacheSize](./maxfontscachesize/) { get; set; } | Maximum count of fonts in fonts cache. Default value is 10. |
| [MaxSymbolsCacheSize](./maxsymbolscachesize/) { get; set; } | Maximum count of symbols in symbol cache. Default value is 100. |
| [OptimizeDimensions](./optimizedimensions/) { get; set; } | Gets or sets optimize dimensions mode. |
| [SystemFontsNativeRendering](./systemfontsnativerendering/) { get; set; } | Gets or sets a mode where system fonts are rendered natively. |
| [UseFontHinting](./usefonthinting/) { get; set; } | Usage of this flag turn on font hinting mechanism. Font hinting is the use of mathematical instructions to adjust the display of an outline font. In some cases turning this flag on may solve problems with text legibility. At current moment usage of this flag could give effect only for TTF fonts, if these fonts are used in source document. |
| [WidthExtraUnits](./widthextraunits/) { get; set; } | Gets or sets a value used to increase or decrease the width of rectangle for AppendRectangle operator. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

