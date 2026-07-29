---
title: "类 TextSegment"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.TextSegment 类。表示 PDF 文本的片段"
type: docs
weight: 11240
url: /zh/net/aspose.pdf.text/textsegment/
---
## TextSegment class

表示 Pdf 文本段。

```csharp
public sealed class TextSegment
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | 创建 TextSegment 对象。 |
| [TextSegment](textsegment/#constructor_1)(string) | 创建 TextSegment 对象。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | 获取文本的位置，使用 `TextSegment` 对象表示。Position 结构体的 YIndent 表示文本片段的基线坐标。 |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | 获取 CharInfo 对象的集合，这些对象表示文本片段中字符的信息。 |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | 获取当前片段在显示文本操作符 (Tj, TJ) 中的结束字符索引。 |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | 获取或设置片段的超链接（用于 PDF 生成器）。 |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | 获取文本的位置，使用 `TextSegment` 对象表示。 |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | 获取 TextSegment 的矩形区域 |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | 获取当前片段在显示文本操作符 (Tj, TJ) 中的起始字符索引。 |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | 获取或设置 `TextSegment` 对象所表示的字符串文本对象。 |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | 获取或设置文本编辑选项。该选项定义当请求的符号无法使用字体写入时的特殊行为。 |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | 获取或设置 `TextSegment` 对象所表示的文本的文本状态。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | 将字符串编码为 HTML。 |

## 备注

简而言之，`TextSegment` 对象是 [`TextFragment`](../textfragment/) 对象的子对象。详细说明：Pdf 文档的文本由两个基本对象表示：[`TextFragment`](../textfragment/) 和 `TextSegment`。它们之间的差异主要取决于上下文。让我们考虑以下情形。用户搜索文本 "hello world" 以进行操作、修改其属性、查看等。

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

PDF 文本的物理表示非常复杂。文本 "hello world" 可能由多个物理上独立的文本片段组成。Aspose.Pdf 文本模型基本上规定，[`TextFragment`](../textfragment/) 对象提供对用户查询所代表的物理 `TextSegment` 对象集合的单一逻辑操作集。在文本搜索场景中，[`TextFragment`](../textfragment/) 是逻辑上的 "hello world" 文本表示，而 `TextSegment` 对象集合则表示构成 "hello world" 文本对象的所有物理片段。因此，[`TextFragment`](../textfragment/) 接近逻辑文本表示，而 `TextSegment` 接近物理文本表示。显然，每个 `TextSegment` 对象可能拥有其自己的字体、颜色、定位属性。[`TextFragment`](../textfragment/) 提供了一种简单的方式来更改文本及其属性：设置字体、设置字体大小、设置字体颜色等。与此同时，`TextSegment` 对象是可访问的，用户能够独立地对 `TextSegment` 对象进行操作。

## 示例

示例演示了如何使用 `TextSegment` 对象的 [`TextState`](./textstate/) 对象来更改文本的颜色和字体大小。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有 "hello world" 文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改第一次出现的文本的第一个文本片段的前景颜色
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// 更改第一次出现的文本的第一个文本片段的字体大小
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 另请参见

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


