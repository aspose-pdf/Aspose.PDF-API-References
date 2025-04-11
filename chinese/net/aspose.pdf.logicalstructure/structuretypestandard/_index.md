---
title: Class StructureTypeStandard
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.StructureTypeStandard 类。表示标准结构类型
type: docs
weight: 6730
url: /zh/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard 类

表示标准结构类型。

```csharp
public sealed class StructureTypeStandard
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category/) { get; } | 获取标准结构类型的类别。 |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag/) { get; } | 获取 [`StructureElement`](../structureelement/) 的标签名称。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring/)() | 返回一个表示当前对象的字符串。 |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit/) | 执行从字符串到 `StructureTypeStandard` 的显式转换。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot/) | （注释；PDF 1.5）ILSE 内容的一部分与相应 PDF 注释之间的关联。Annot 应用于所有 PDF 注释，除了链接注释和小部件注释。 |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art/) | （文章）构成单一叙述或阐述的相对自包含的文本主体。文章应当是互不重叠的；即，它们不应包含其他文章作为组成元素。 |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry/) | （参考文献条目）识别某些引用内容的外部来源的引用。它可以包含一个标签（结构类型 Lbl）作为子元素。 |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote/) | （块引用）由一个或多个段落组成的文本部分，归属于周围文本的作者以外的其他人。 |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption/) | （标题）描述表格或图形的简短文本部分。 |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code/) | （代码）计算机程序文本的片段。 |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div/) | （分区）一个通用的块级元素或元素组。 |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document/) | （文档）完整的文档。这是包含多个部分或多个文章的任何结构树的根元素。 |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure/) | （图形）图形内容的项目。其放置可以通过放置布局属性指定。 |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form/) | （表单）表示交互式表单字段的小部件注释。 |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula/) | （公式）数学公式。 |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h/) | （标题）文档内容子部分的标签。它应当是其所处分区的第一个子元素。 |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1/) | 级别 1 标题，用于无法分层嵌套其部分的符合标准的写作工具，因此无法根据嵌套级别确定标题级别。 |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2/) | 级别 2 标题，用于无法分层嵌套其部分的符合标准的写作工具，因此无法根据嵌套级别确定标题级别。 |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3/) | 级别 3 标题，用于无法分层嵌套其部分的符合标准的写作工具，因此无法根据嵌套级别确定标题级别。 |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4/) | 级别 4 标题，用于无法分层嵌套其部分的符合标准的写作工具，因此无法根据嵌套级别确定标题级别。 |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5/) | 级别 5 标题，用于无法分层嵌套其部分的符合标准的写作工具，因此无法根据嵌套级别确定标题级别。 |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6/) | 级别 6 标题，用于无法分层嵌套其部分的符合标准的写作工具，因此无法根据嵌套级别确定标题级别。 |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index/) | （索引）包含识别文本的条目序列，伴随指向文档主体中指定文本出现位置的引用元素。 |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l/) | （列表）具有相似意义和重要性的项目序列。其直接子元素应为可选标题（结构类型 Caption），后跟一个或多个列表项（结构类型 LI）。 |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl/) | （标签）一个名称或数字，用于区分同一列表或其他相似项目组中的给定项目。 |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody/) | （列表主体）列表项的描述性内容。在字典列表中，例如，它包含术语的定义。它可以直接包含内容，也可以有其他 BLSE，可能包括嵌套列表，作为子元素。 |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li/) | （列表项）列表的单个成员。其子元素可以是一个或多个标签、列表主体，或两者（结构类型 Lbl 或 LBody）。 |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link/) | （链接）ILSE 内容的一部分与相应链接注释或注释之间的关联。其子元素应为一个或多个内容项或子 ILSE，以及一个或多个对象引用，标识相关的链接注释。 |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct/) | （非结构元素）没有固有结构意义的分组元素；仅用于分组目的。这种类型的元素与分区（结构类型 Div）不同，因为它不应被解释或导出到其他文档格式；然而，其后代应正常处理。 |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note/) | （注释）解释性文本的项目，例如脚注或尾注，从文档主体中引用。它可以有一个标签（结构类型 Lbl）作为子元素。注释可以作为引用它的主体文本中的结构元素的子元素包含，或者可以包含在其他地方（例如在尾注部分）并通过引用（结构类型 Reference）访问。 |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p/) | （段落）文本的低级分区。 |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part/) | （部分）文档的大规模分区。这种类型的元素适合于分组文章或部分。 |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private/) | （私有元素）包含属于生成它的应用程序的私有内容的分组元素。这种类型元素的结构意义未指定，完全由符合标准的写作工具决定。私有元素及其任何后代不应被解释或导出到其他文档格式。 |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote/) | （引用）归属于周围文本的作者以外的其他人的内联文本部分。 |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb/) | （平假名基础文本）应用于平假名注释的全尺寸文本。RB 可以包含文本、其他内联元素或两者的混合。它可以具有 RubyAlign 属性。 |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference/) | （引用）对文档中其他内容的引用。 |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp/) | （平假名标点）围绕平假名注释文本的标点。仅在平假名注释无法以平假名样式正确格式化时使用，而是格式化为普通注释，或当其格式化为分隔注释时。它包含文本（通常是一个左括号或右括号或类似的括号字符）。 |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt/) | （平假名注释文本）应放置在平假名基础文本旁边的较小尺寸文本。它可以包含文本、其他内联元素或两者的混合。它可以具有 RubyAlign 和 RubyPosition 属性。 |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby/) | （平假名；PDF 1.5）以较小文本大小书写的旁注（注释），并放置在其所指的基础文本旁边。平假名元素还可以包含 RB、RT 和 RP 元素。 |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect/) | （节）用于分组相关内容元素的容器。 |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span/) | （跨度）没有特定固有特征的通用内联文本部分。例如，可以用来限定一段具有给定样式属性的文本。 |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table/) | （表格）矩形数据单元的二维布局，可能具有复杂的子结构。它包含一个或多个表格行（结构类型 TR）作为子元素；或者一个可选的表头（结构类型 THead），后跟一个或多个表体元素（结构类型 TBody）和一个可选的表尾（结构类型 TFoot）。此外，表格可以有一个标题（结构类型 Caption）作为其第一个或最后一个子元素。 |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody/) | （表体行组；PDF 1.5）构成表格主体部分的一组行。如果表格跨多个页面，则主体区域可能在行边界处被拆分。表格可以有多个 TBody 元素，以允许为一组行绘制边框或背景。 |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td/) | （表格数据单元）包含表格内容数据的表格单元。 |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot/) | （表格尾部行组；PDF 1.5）构成表格尾部的一组行。如果表格跨多个页面，则这些行可能在每个表格片段的底部重新绘制（尽管只有一个 TFoot 元素）。 |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th/) | （表格头单元）包含描述一个或多个表格行或列的标题文本的表格单元。 |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead/) | （表格头行组；PDF 1.5）构成表格头部的一组行。如果表格跨多个页面，则这些行可能在每个表格片段的顶部重新绘制（尽管只有一个 THead 元素）。 |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc/) | （目录）由目录项条目（结构类型 TOCI）和/或其他嵌套目录项（TOC）组成的列表。 |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci/) | （目录项）目录的单个成员。此条目的子元素可以是以下任何结构类型： |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr/) | （表格行）表格中的标题或数据行。它可以包含表格头单元和表格数据单元（结构类型 TH 和 TD）。 |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu/) | （分隔注释；PDF 1.5）以较小文本大小书写的注释或注释，格式化为在包含文本行的高度内的两行，并放置在其所指的基础文本之后（内联）。分隔注释元素还可以包含 WT 和 WP 元素。 |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp/) | （分隔注释标点）围绕 WT 文本的标点。它包含文本（通常是一个左括号或右括号或类似的括号字符）。根据 JIS X 4051-1995，围绕分隔注释的括号可以根据格式化程序的自由裁量权转换为一个空格（名义上宽度为 1/4 EM）。 |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt/) | （分隔注释文本）格式化为两行并放置在周围 WP 元素之间的分隔注释的较小文本。 |

### 另请参见

* 命名空间 [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* 程序集 [Aspose.PDF](../../)