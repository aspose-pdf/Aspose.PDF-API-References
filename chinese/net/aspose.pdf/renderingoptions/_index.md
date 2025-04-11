---
title: Class RenderingOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.RenderingOptions class. 表示渲染选项
type: docs
weight: 9760
url: /zh/net/aspose.pdf/renderingoptions/
---
## RenderingOptions class

表示渲染选项。

```csharp
public sealed class RenderingOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | 默认构造函数。 |

## Properties

| Name | Description |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | 根据需要替换字体，以确保文本中的所有字符都可以显示。字体替换算法遵循以下步骤：1. 如果用户明确设置了 DefaultFontName 属性，请检查指定的字体是否可以显示所需的字符。2. 如果未设置用户定义的字体，则通过 !:FontRepository.Sources 搜索添加的字体。3. 分析文本以识别其字母表或脚本，并相应地建议字体名称。尝试从系统中定位并使用这些字体。4. 作为后备，搜索系统中任何能够显示所需字符的字体。 |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | 获取或设置条形码优化模式。 |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | 表示所有字体将转换为 TTF unicode 版本。这对于兼容性和优化字体使用非常有用，因为每个新的 TTF 字体将不包含源字体中的所有符号，而仅包含文本中使用的符号。 |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | 获取/设置用于替代缺失字体的默认字体名称。 |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | 获取或设置用于增加或减少 AppendRectangle 操作符的矩形宽度的值。 |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | 获取或设置指示将忽略与缺少字体相关的错误。 true - 表示将忽略缺少字体的错误。处理过程中将跳过引用不正确资源的文本段。默认值为 false |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | 获取或设置高质量插值模式。 |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | 字体缓存中的最大字体数量。默认值为 10。 |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | 符号缓存中的最大符号数量。默认值为 100。 |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | 获取或设置优化尺寸模式。 |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | 获取或设置系统字体以原生方式渲染的模式。 |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | 使用此标志开启字体提示机制。字体提示是使用数学指令调整轮廓字体显示的过程。在某些情况下，开启此标志可能解决文本可读性问题。目前，使用此标志仅对 TTF 字体有效，如果这些字体在源文档中使用。 |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | 获取或设置用于增加或减少 AppendRectangle 操作符的矩形宽度的值。 |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)