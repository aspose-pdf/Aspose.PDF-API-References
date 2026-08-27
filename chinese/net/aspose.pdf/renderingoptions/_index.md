---
title: "类 RenderingOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.RenderingOptions 类。表示渲染选项"
type: docs
weight: 9910
url: /zh/net/aspose.pdf/renderingoptions/
---
## RenderingOptions class

表示渲染选项。

```csharp
public sealed class RenderingOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | 根据需要替换字体，以确保文本中的所有字符都能显示。字体替换算法遵循以下步骤：1. 如果用户显式设置了 DefaultFontName 属性，检查指定的字体是否能够显示所需字符。2. 如果未设置用户自定义字体，则搜索通过 !:FontRepository.Sources 添加的字体。3. 分析文本以识别其字母表或文字脚本，并相应地建议字体名称。尝试从系统中定位并使用这些字体。4. 作为后备方案，搜索系统中任何能够显示所需字符的字体。 |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | 获取或设置条形码优化模式。 |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | 指示所有字体将转换为 TTF Unicode 版本。这对于兼容性和优化字体使用很有用，因为每个新的 TTF 字体将不包含源字体的所有符号，而仅包含文本中使用的符号。 |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | 获取/设置用于替代缺失字体的默认字体名称。 |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | 获取或设置用于增大或减小 AppendRectangle 操作符矩形宽度的值。 |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | 获取或设置指示是否忽略与缺少字体相关错误的标志。true - 表示将忽略缺少字体的错误。处理期间将跳过引用不正确资源的文本段。默认值为 false。 |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | 获取或设置插值的高质量模式。 |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | 字体缓存中的最大字体数量。默认值为 10。 |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | 符号缓存中的最大符号数量。默认值为 100。 |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | 获取或设置优化尺寸模式。 |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | 获取或设置系统字体以本机方式呈现的模式。 |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | 使用此标志可开启字体微调机制。字体微调是使用数学指令来调整轮廓字体的显示方式。在某些情况下，打开此标志可能会解决文本可读性问题。目前，此标志的使用仅对 TTF 字体生效，如果这些字体在源文档中使用的话。 |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | 获取或设置用于增大或减小 AppendRectangle 操作符矩形宽度的值。 |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


