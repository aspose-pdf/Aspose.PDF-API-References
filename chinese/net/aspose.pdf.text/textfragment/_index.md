---
title: TextFragment
second_title: Aspose.PDF for .NET API 参考
description: 表示 Pdf 文本的片段
type: docs
weight: 7100
url: /zh/net/aspose.pdf.text/textfragment/
---
## TextFragment class

表示 Pdf 文本的片段。

```csharp
public class TextFragment : BaseParagraph
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TextFragment](textfragment#constructor)() | 初始化[`TextFragment`](../textfragment)对象. |
| [TextFragment](textfragment#constructor_2)(string) | 创建[`TextFragment`](../textfragment)对象单[`TextSegment`](../textsegment)里面的对象。 指定段内的文本字符串。 |
| [TextFragment](textfragment#constructor_1)(TabStops) | 初始化[`TextFragment`](../textfragment)具有预定义的对象[`TabStops`](../tabstops)位置. |
| [TextFragment](textfragment#constructor_3)(string, TabStops) | 创建[`TextFragment`](../textfragment)对象单[`TextSegment`](../textsegment)内部和预定义的对象[`TabStops`](../tabstops)位置. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | 获取文本的文本位置，用[`TextFragment`](../textfragment)object. Position 结构的 YIndent 表示文本片段的基线坐标。 |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | 获取或设置段落尾注。（仅用于 pdf 生成） |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | 获取或设置段落脚注。（仅用于 pdf 生成） |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | 获取包含 TextFragment 的表单对象 |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | 获取或设置文本片段的水平对齐方式。 |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | 设置片段超链接 |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | 获取或设置一个布尔值，指示此段落是否将在下一列。 默认为 false。（用于 pdf 生成） |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | 获取或设置段落是内联的。 默认为 false。（用于 pdf 生成） |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | 获取或设置一个 bool 值，强制此段落在新页面生成。 默认为 false。（用于 pdf 生成） |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | 获取或设置一个布尔值，指示当前段落是否与下一个段落保持在同一页面中。 默认为 false。（用于 pdf 生成） |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | 获取或设置段落的外边距（用于生成 pdf） |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | 获取包含 TextFragment 的页面 |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | 获取或设置文本的文本位置，用[`TextFragment`](../textfragment)对象. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | 获取 TextFragment 的矩形 |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | 获取文本替换选项。选项定义片段文本替换为更短/更长时的行为。 |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | 获取当前文本段[`TextFragment`](../textfragment). |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | 获取或设置String文本对象[`TextFragment`](../textfragment)对象代表. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | 获取或设置文本的文本状态[`TextFragment`](../textfragment)对象代表. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | 获取或设置文本片段的垂直对齐方式。 |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | 获取或设置此段落的换行数（仅用于 pdf 生成） |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | 获取或设置一个 int 值，指示图形的 Z 顺序。 ZIndex 较大的图将放置在 ZIndex 较小的图上。 ZIndex 可以是负数。带有负数 ZIndex 的图形将被放置在页面中的文本后面。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone)() | 克隆片段。 |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments)() | 克隆所有片段的片段。 |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | 获取[`TextSegment`](../textsegment)(s) 代表指定部分[`TextFragment`](../textfragment)文本. |

### 评论

简而言之，[`TextFragment`](../textfragment)对象包含列表[`TextSegment`](../textsegment)objects. 详细信息： pdf 文档中的文本Pdf由两个基本对象表示：[`TextFragment`](../textfragment)和[`TextSegment`](../textsegment) 它们之间的差异主要取决于上下文。 让我们考虑以下场景。用户搜索文本“hello world”以对其进行操作，更改其属性，查看等。 物理上pdf文本的表示非常复杂。 文本“hello world”可能由几个物理上独立的文本段组成。 Aspose.Pdf文本模型基本上建立了[`TextFragment`](../textfragment)object 在物理上提供单一逻辑操作集[`TextSegment`](../textsegment)代表用户查询的对象集。 在文本搜索场景中，[`TextFragment`](../textfragment)是逻辑“hello world”文本表示， 和[`TextSegment`](../textsegment)对象集合表示构造“hello world”文本对象的所有物理段。 所以，[`TextFragment`](../textfragment)接近逻辑文本表示。 和[`TextSegment`](../textsegment)接近物理文本表示。 显然每个[`TextSegment`](../textsegment)对象可能有它自己的字体、颜色、定位属性。 [`TextFragment`](../textfragment)提供简单的方法来更改文本的属性：设置字体、设置字体大小、设置字体颜色等。 同时[`TextSegment`](../textsegment)对象是可访问的，用户可以使用[`TextSegment`](../textsegment)对象独立。 请注意，更改 TextFragment 属性可能会更改内部[`Segments`](./segments)集合，因为 TextFragment 是一个聚合对象 并且它可能会重新排列内部段或将它们合并为单个段。 如果您的要求是离开[`Segments`](./segments)集合不变，请单独更改内部段。

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### 例子

该示例演示如何在第一个 PDF 文档页面上查找文本并替换文本及其字体。

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 查找将用于更改文档文本字体的字体
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// 创建 TextFragmentAbsorber 对象以查找所有“hello world”文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改第一个文本出现的文本和字体
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 也可以看看

* class [BaseParagraph](../../aspose.pdf/baseparagraph)
* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
