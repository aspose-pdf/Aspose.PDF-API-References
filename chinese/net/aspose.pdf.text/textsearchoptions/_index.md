---
title: "类 TextSearchOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.TextSearchOptions 类。表示文本搜索选项。"
type: docs
weight: 11230
url: /zh/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions class

表示文本搜索选项。

```csharp
public sealed class TextSearchOptions : TextOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | 初始化 `TextSearchOptions` 对象的新实例。指定正则表达式的使用模式。 |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | 初始化 `TextSearchOptions` 对象的新实例。指定限定搜索文本的矩形区域。 |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | 初始化 `TextSearchOptions` 对象的新实例。指定限定搜索文本的矩形区域以及正则表达式的使用模式。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | 获取或设置指示文本（片段）吸收器是否忽略与缺少字体相关的错误。true - 表示将忽略缺少字体的错误。引用不正确资源的文本段将在处理期间被跳过。false（默认） - 缺少字体错误将通过抛出异常终止处理。 |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | 获取或设置指示在搜索期间是否忽略表示普通文本阴影的文本片段。true - 表示不会找到阴影文本（如果文本搜索在相近位置返回重复片段，可尝试此设置）。false - 表示阴影文本将与普通文本一起被找到（默认值）。 |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | 获取或设置指示是否使用正则表达式。 |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | 获取或设置指示是否在页面边界内搜索文本。 |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | 获取或设置指示是否将在文本（片段）吸收器中记录文本提取（解码）错误。true - 表示将记录文本提取（解码）错误，这可能会降低性能。false（默认） - 不记录错误。 |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | 获取或设置限定搜索文本的矩形区域。 |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | 获取或设置允许在文本搜索期间搜索与文本相关的图形（下划线、背景等）的值。true - 将执行文本相关图形的搜索（默认值）。false - 将忽略源文档中可能出现的图形元素。若出现性能问题或不需要处理下划线、背景或裁剪，可将其设为 false。 |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | 获取或设置允许在 Annotations 中搜索文本的值。true - 将在 Annotations 中搜索文本。false - TextFragmentAbsorber 不会解析 Annotations 中的文本。 |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | 获取或设置限制在 Page 上搜索指定数量文本相关图形（下划线、背景等）的值。默认值为 250。若出现性能问题，可设置较小的值；若有图形元素未被找到，可尝试更大的值。 |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | 获取或设置指示是否使用字体引擎编码进行文本搜索。true - 表示将使用字体引擎编码（如果文本搜索因文档中编码不完整而失败，可尝试此设置）。false - 表示将使用文档字体编码（默认值）。 |

### 另请参见

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


