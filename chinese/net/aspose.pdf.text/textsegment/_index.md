---
title: TextSegment
second_title: Aspose.PDF for .NET API 参考
description: 表示 Pdf 文本的段
type: docs
weight: 7210
url: /zh/net/aspose.pdf.text/textsegment/
---
## TextSegment class

表示 Pdf 文本的段。

```csharp
public sealed class TextSegment
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TextSegment](textsegment#constructor)() | 创建 TextSegment 对象。 |
| [TextSegment](textsegment#constructor_1)(string) | 创建 TextSegment 对象。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition) { get; set; } | 获取文本的文本位置，用[`TextSegment`](../textsegment)object. Position 结构的 YIndent 表示文本段的基线坐标。 |
| [Characters](../../aspose.pdf.text/textsegment/characters) { get; } | 获取代表文本段中字符信息的 CharInfo 对象集合。 |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex) { get; } | 获取显示文本运算符（Tj，TJ）段中当前段的结束字符索引。 |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink) { get; set; } | 获取或设置段超链接（用于pdf生成器）。 |
| [Position](../../aspose.pdf.text/textsegment/position) { get; set; } | 获取文本的文本位置，用[`TextSegment`](../textsegment)对象. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle) { get; } | 获取 TextSegment 的矩形 |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex) { get; } | 获取显示文本运算符（Tj，TJ）段中当前段的起始字符索引。 |
| [Text](../../aspose.pdf.text/textsegment/text) { get; set; } | 获取或设置String文本对象[`TextSegment`](../textsegment)对象代表. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions) { get; set; } | 获取或设置文本编辑选项。当请求的符号不能用字体写入时，选项定义特殊行为。 |
| [TextState](../../aspose.pdf.text/textsegment/textstate) { get; set; } | 获取或设置文本的文本状态[`TextSegment`](../textsegment)对象代表. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode)(string) | 将字符串编码为 html. |

### 评论

简而言之，[`TextSegment`](../textsegment)对象是[`TextFragment`](../textfragment) object. 详细说明： pdf 文档中的文本Pdf由两个基本对象表示：[`TextFragment`](../textfragment)和[`TextSegment`](../textsegment) 它们之间的差异主要取决于上下文。 让我们考虑以下场景。用户搜索文本“hello world”以对其进行操作，更改其属性，查看等。 物理上pdf文本的表示非常复杂。 文本“hello world”可能由几个物理上独立的文本段组成。 Aspose.Pdf文本模型基本上建立了[`TextFragment`](../textfragment)object 在物理上提供单一逻辑操作集[`TextSegment`](../textsegment)代表用户查询的对象集。 在文本搜索场景中，[`TextFragment`](../textfragment)是逻辑“hello world”文本表示， 和[`TextSegment`](../textsegment)对象集合表示构造“hello world”文本对象的所有物理段。 所以，[`TextFragment`](../textfragment)接近逻辑文本表示。 和[`TextSegment`](../textsegment)接近物理文本表示。 显然每个[`TextSegment`](../textsegment)对象可能有它自己的字体、颜色、定位属性。 [`TextFragment`](../textfragment)提供简单的方法来更改文本的属性：设置字体、设置字体大小、设置字体颜色等。 同时[`TextSegment`](../textsegment)对象是可访问的，用户可以使用[`TextSegment`](../textsegment)独立的对象。

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

### 例子

该示例演示了如何更改文本的颜色和字体大小[`TextState`](./textstate)的对象[`TextSegment`](../textsegment)对象.

```csharp
// 打开文档
Document doc = new Document(@"D:\Tests\input.pdf");

// 创建 TextFragmentAbsorber 对象以查找所有“hello world”文本出现
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 接受第一页的吸收器
doc.Pages[1].Accept(absorber);

// 更改第一个文本出现的第一个文本段的前景色
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// 更改第一个文本出现的第一个文本段的字体大小
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// 保存文档
doc.Save(@"D:\Tests\output.pdf");  
```

### 也可以看看

* 命名空间 [Aspose.Pdf.Text](../../aspose.pdf.text)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->