---
title: "类 ParagraphAbsorber"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Text.ParagraphAbsorber 类。表示页面结构对象（如章节和段落）的吸收器对象。执行文本章节和段落的搜索，并提供对在文本坐标空间中描述它们的矩形和多边形的访问。还执行文本片段搜索，并通过按结构元素分组的 TextFragments 集合提供搜索结果的访问。"
type: docs
weight: 10850
url: /zh/net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class

表示页面结构对象（如节和段落）的吸收器对象。执行对文本节和段落的搜索，并提供对在文本坐标空间中描述它们的矩形和多边形的访问。还执行文本片段搜索，并通过 !:TextFragments 集合（按结构元素分组）提供对搜索结果的访问。

```csharp
public class ParagraphAbsorber
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | 初始化 `ParagraphAbsorber` 的新实例，用于搜索文档或页面的章节/段落。 |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | 初始化 `ParagraphAbsorber` 的新实例，用于搜索文档或页面的章节/段落。 |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | 使用指定参数初始化 `ParagraphAbsorber` 的新实例，以搜索文档或页面的章节/段落。 |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | 使用指定参数初始化 `ParagraphAbsorber` 的新实例，以搜索文档或页面的章节/段落。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | 获取或设置指示是否可以将下一节的起始文本行视为前一节最后一个段落的延续的值。 |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | 获取已吸收的 [`PageMarkup`](../pagemarkup/) 集合。 |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | 获取或设置 ParagraphAbsorberOptions。 |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | 获取或设置指示对结构更细元素进行顺序搜索次数的值。默认搜索深度为 3。这意味着对水平划分的章节（标题、段落等）进行三次搜索，对垂直划分的章节（列）也进行三次搜索。 |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | 获取或设置 TextReplaceOptions。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | 在指定的[`Document`](../../aspose.pdf/document/)上执行对章节和段落的搜索。 |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | 在指定的[`Page`](../../aspose.pdf/page/)上执行搜索。 |

## 备注

搜索完成后，[`PageMarkups`](./pagemarkups/) 集合将包含表示页面结构的 [`PageMarkup`](../pagemarkup/) 对象，这些对象由 [`MarkupSection`](../markupsection/) 和 [`MarkupParagraph`](../markupparagraph/) 的集合组成。[`TextFragment`](../textfragment/) 对象提供对搜索到的文本、文本属性的访问，并允许编辑文本和更改文本状态（字体、字号、颜色等）。

## 示例

示例演示如何在第一个 PDF 文档页上查找每个段落的第一个文本片段并对其进行高亮显示。

```csharp
// 打开文档
Document doc = new Document("input.pdf");

// 创建 ParagraphAbsorber 对象
ParagraphAbsorber absorber = new ParagraphAbsorber();

// 接受第一页的吸收器
absorber.Visit(doc.Pages[1]);

// 获取第一页的标记对象
PageMarkup markup = absorber.PageMarkups[0];

// 遍历页面文本的结构元素，以查找每个段落的第一个文本片段
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // 更新文本属性
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// 保存文档
doc.Save(GetOutputPath("output.pdf"));
```

### 另请参见

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


