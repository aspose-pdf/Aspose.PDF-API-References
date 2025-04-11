---
title: Class HtmlFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlFragment 类。表示 HTML 片段
type: docs
weight: 5520
url: /zh/net/aspose.pdf/htmlfragment/
---
## HtmlFragment 类

表示 HTML 片段。

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | 初始化 HtmlFragment 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 获取或设置段落的水平对齐方式 |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | 获取或设置将用于加载（和渲染）HTML到此类实例的 HtmlLoadOptions。当需要为此或那种实例使用特定设置导入 HTML 时，请使用它（例如，当此或那种实例应该使用特定的 BasePath 导入 HTML 或应该使用特定的外部资源加载器时）。如果参数为默认值（null），则将使用标准 HTML 加载选项。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 获取或设置片段超链接（用于 PDF 生成器）。 |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | 获取或设置单词换行 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示此段落是否将在下一列。默认值为 false。（用于 PDF 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为行内。默认值为 false。（用于 PDF 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制此段落在新页面生成。默认值为 false。（用于 PDF 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面。默认值为 false。（用于 PDF 生成） |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | 获取或设置段落是否具有默认边距，否则边距为 0 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 PDF 生成） |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | 获取 HtmlFragment 的矩形 |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | 获取或设置字体 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 获取或设置段落的垂直对齐方式 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，指示图形的 Z 顺序。具有较大 ZIndex 的图形将放置在具有较小 ZIndex 的图形上方。ZIndex 可以为负数。具有负 ZIndex 的图形将放置在页面文本后面。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | 克隆 HTML 片段。 |

### 另请参阅

* 类 [FormattedFragment](../formattedfragment/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)