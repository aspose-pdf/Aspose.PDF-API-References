---
title: "类 HtmlFragment"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.HtmlFragment 类。表示 html 片段"
type: docs
weight: 5650
url: /zh/net/aspose.pdf/htmlfragment/
---
## HtmlFragment class

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
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | 获取或设置用于将 HTML 加载（和呈现）到此类实例中的 HtmlLoadOptions。请在需要为此实例或该实例的 HTML 导入使用特定设置时使用它（例如，当此实例或该实例应使用特定的 BasePath 来导入 HTML，或应使用特定的外部资源加载器时）。如果参数为默认值（null），则使用标准的 HTML 加载选项。 |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 获取或设置片段超链接（用于 PDF 生成器）。 |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | 获取或设置单词换行 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 获取或设置一个布尔值，指示此段落是否将在下一列。默认值为 false。（用于 pdf 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 获取或设置段落是否为内联。默认值为 false。（用于 pdf 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 获取或设置一个布尔值，强制此段落在新页面生成。默认值为 false。（用于 pdf 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一段落保持在同一页。默认值为 false。（用于 pdf 生成） |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | 获取或设置段落是否具有默认边距，否则边距为 0 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 获取或设置段落的外边距（用于 pdf 生成） |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | 获取 HtmlFragment 的矩形 |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | 获取或设置字体 |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 获取或设置段落的垂直对齐方式 |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 获取或设置一个整数值，指示图形的 Z 顺序。ZIndex 较大的图形将位于 ZIndex 较小的图形之上。ZIndex 可以为负数。ZIndex 为负的图形将位于页面文本的后面。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | 克隆 html 片段。 |

### 另请参见

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


