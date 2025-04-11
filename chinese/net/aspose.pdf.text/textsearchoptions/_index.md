---
title: Class TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextSearchOptions class. 表示文本搜索选项
type: docs
weight: 11040
url: /zh/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions class

表示文本搜索选项

```csharp
public sealed class TextSearchOptions : TextOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | 初始化 `TextSearchOptions` 对象的新实例。指定正则表达式使用模式。 |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | 初始化 `TextSearchOptions` 对象的新实例。指定限制搜索文本的矩形。 |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | 初始化 `TextSearchOptions` 对象的新实例。指定限制搜索文本的矩形和正则表达式使用模式。 |

## Properties

| Name | Description |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | 获取或设置指示文本（片段）吸收器将忽略与字体缺失相关的错误。 true - 表示将忽略字体缺失的错误。处理过程中将跳过引用不正确资源的文本段。 false（默认） - 字体缺失错误将通过抛出异常终止处理。 |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | 获取或设置指示在搜索过程中将忽略表示正常文本阴影的文本片段。 true - 表示将不会找到阴影文本（如果文本搜索返回重复片段在接近的位置，请尝试此选项） false - 表示将找到阴影文本以及正常文本（默认值） |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | 获取或设置指示是否使用正则表达式。 |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | 获取或设置指示文本是否在页面边界内进行搜索。 |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | 获取或设置指示文本提取（解码）错误是否将在文本（片段）吸收器中记录。 true - 表示将记录文本提取（解码）错误。这可能会降低性能。 false（默认） - 不记录错误。 |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | 获取或设置限制搜索文本的矩形。 |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | 获取或设置允许在文本搜索过程中搜索与文本相关的图形（下划线、背景等）的值。 true - 将执行与文本相关的图形搜索（默认值）。 false - 将忽略可能出现在源文档中的图形元素。在性能问题或不需要处理下划线、背景或剪裁的情况下设置此项。 |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | 获取或设置允许在注释中搜索文本的值。 true - 将在注释中搜索文本。 false - 注释中的文本将不会被 TextFragmentAbsorber 解析。 |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | 获取或设置限制在页面上搜索与文本相关的图形（下划线、背景等）的值，指定元素的数量。默认值为 250。在性能问题的情况下设置较小的值，在某些图形元素未找到的情况下尝试较大的值。 |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | 获取或设置指示文本是否将使用字体引擎编码进行搜索。 true - 表示将使用字体引擎编码（如果文本搜索因文档中的编码不完善而失败，请尝试此选项） false - 表示将使用文档字体编码（默认值） |

### See Also

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)