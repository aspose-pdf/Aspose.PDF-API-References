---
title: StructureTypeStandard
second_title: Aspose.PDF for .NET API 参考
description: 表示标准结构类型
type: docs
weight: 4560
url: /zh/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class

表示标准结构类型。

```csharp
public sealed class StructureTypeStandard
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category) { get; } | 获取标准结构类型的类别。 |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag) { get; } | 获取标签名称[`StructureElement`](../structureelement). |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring)() | 返回代表当前对象的字符串。 |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit) | 执行显式转换String至[`StructureTypeStandard`](../structuretypestandard). |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot) | （注释；PDF 1.5）ILSE 的部分内容与相应的 PDF 注释之间的关联。 Annot 应用于除链接注释和小部件注释之外的所有 PDF 注释。 |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art) | （文章）相对独立的文本主体，构成一个单一的叙述或说明。文章应该是不连贯的；也就是说，它们不应包含其他文章作为构成元素。 |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry) | （参考书目条目）标识某些引用内容的外部来源的参考。它可能包含一个子标签（结构类型 Lbl）。 |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote) | （块引用）文本的一部分，由一个或多个段落组成，归因于周围文本作者以外的人。 |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption) | （标题）描述表格或图形的简短文本部分。 |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code) | （代码）计算机程序文本的片段。 |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div) | （分区）通用块级元素或元素组。 |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document) | （文档）完整的文档。这是包含多个部分或多个文章的任何结构树的根元素。 |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure) | （图）图形内容项。可以使用 Placement 布局属性指定其位置。 |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form) | (Form) 表示交互式表单字段的小部件注释。 |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula) | （公式）数学公式。 |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h) | （标题）用于细分文档内容的标签。它应该是它领导的部门的第一个孩子。 |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1) | 1 级标题，用于无法按层次嵌套其部分并因此无法从其嵌套级别确定标题级别的合格作者。 |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2) | 2 级标题，用于不能分层嵌套其部分并因此无法从其嵌套级别确定标题级别的符合编写者。 |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3) | 3 级标题，用于无法按层次嵌套其部分并因此无法从其嵌套级别确定标题级别的合格作者。 |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4) | 4 级标题，用于无法按层次嵌套其部分并因此无法从其嵌套级别确定标题级别的一致性编写器。 |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5) | 5 级标题，用于无法按层次嵌套其部分并因此无法从其嵌套级别确定标题级别的合格作者。 |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6) | 6 级标题，用于无法按层次嵌套其部分并因此无法从其嵌套级别确定标题级别的合格作者。 |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index) | （索引）一系列条目，其中包含标识文本以及引用元素，这些元素指出文档主体中指定文本的出现。 |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l) | （列表）具有相同含义和重要性的项目序列。它的直接子项应该是一个可选标题（结构类型 Caption），后跟一个或多个列表项（结构类型 LI）。 |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl) | （标签）将给定项目与同一列表或其他类似项目组中的其他项目区分开来的名称或编号。 |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody) | （列表正文）列表项的描述性内容。例如，在字典列表中，它包含术语的定义。它可能直接包含内容或具有其他 BLSE，可能包括嵌套列表，作为子项。 |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li) | （列表项）列表的单个成员。它的子元素可能是一个或多个标签、列表体，或两者兼有（结构类型 Lbl 或 LBody）。 |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link) | （链接）ILSE 内容的一部分与相应的链接注释或注释之间的关联。它的子项应该是一个或多个内容项或子 ILSE 以及一个或多个标识关联链接注释的对象引用。 |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct) | （非结构元素）没有内在结构意义的分组元素；它仅用于分组目的。这种类型的元素与分区（结构类型 Div）的不同之处在于它不应被解释或导出为其他文档格式；但是，它的后代应正常处理。 |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note) | （注）从文档正文中引用的解释性文本项目，例如脚注或尾注。它可能有一个子标签（结构类型 Lbl）。注释可以作为结构元素的子元素包含在引用它的正文文本中，也可以包含在其他地方（例如尾注部分）并通过参考（结构类型参考）访问。 |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p) | （段落）文本的低级划分。 |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part) | （部分）文档的大规模分割。这种类型的元素适用于对文章或部分进行分组。 |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private) | （私有元素）包含属于生成它的应用程序的私有内容的分组元素。此类元素的结构意义未指定，应完全由符合要求的作者确定。 Private 元素及其任何后代都不应被解释或导出为其他文档格式。 |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote) | （引用）文本的内联部分归因于周围文本作者以外的人。 |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb) | （Ruby 基本文本）应用了 ruby 注释的全尺寸文本。 RB 可能包含文本、其他内联元素或两者的混合。它可能有 RubyAlignattribute. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference) | （参考）对文档其他地方内容的引用。 |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp) | (Ruby punctuation) Ruby 注释文本周围的标点符号。仅当 ruby 注释无法正确格式化为 ruby 样式，而是被格式化为普通注释时，或者当它被格式化为 warichu 时，才使用它。它包含文本（通常是单个左括号或右括号或类似的括号字符）。 |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt) | （Ruby 注释文本）应放置在 Ruby 基础文本旁边的较小尺寸的文本。它可能包含文本、其他内联元素或两者的混合。它可能具有 RubyAlign 和 RubyPosition 属性。 |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby) | （Ruby；PDF 1.5）以较小的文本大小编写的旁注（注释），并与它所引用的基本文本相邻。 Ruby 元素还可以包含 RB、RT 和 RP 元素。 |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect) | (Section) 用于对相关内容元素进行分组的容器。 |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span) | （跨度）文本的通用内联部分，没有特定的固有特征。例如，它可以用于用一组给定的样式属性分隔文本范围。 |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table) | （表）矩形数据单元的二维布局，可能具有复杂的子结构。它包含一个或多个表行（结构类型 TR）作为子项；或者一个可选的表头（结构类型 THead），后跟一个或多个表体元素（结构类型 TBody）和一个可选的表尾（结构类型 TFoot）。此外，一个表可能有一个标题（结构类型 Caption）作为它的第一个或最后一个子项。 |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody) | （表格主体行组；PDF 1.5）构成表格主体部分的一组行。如果表格被拆分为多个页面，则正文区域可能会在行边界上分开。一个表格可能有多个 TBody 元素，以允许为一组行绘制边框或背景。 |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td) | （表格数据单元格）一个表格单元格，其中包含作为表格内容一部分的数据。 |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot) | （表格页脚行组；PDF 1.5）构成表格页脚的一组行。如果表格被拆分为多个页面，这些行可能会在每个表格片段的底部重新绘制（尽管只有一个 TFoot 元素。） |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th) | （表格标题单元格）包含标题文本的表格单元格，描述表格的一个或多个行或列。 |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead) | （表格标题行组；PDF 1.5）构成表格标题的一组行。如果表格被拆分为多个页面，这些行可能会在每个表格片段的顶部重新绘制（尽管只有一个 THead 元素）。 |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc) | （目录）由目录项条目（结构类型 TOCI）和/或其他嵌套目录条目 (TOC) 组成的列表。 |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci) | （目录项）目录的单个成员。此条目的子项可能是以下任何结构类型： |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr) | （表格行）表格中的一行标题或数据。它可能包含表格标题单元格和表格数据单元格（结构类型 TH 和 TD）。 |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu) | （Warichu；PDF 1.5）较小文本大小的注释或注释，并在包含文本行的高度内格式化为两个较小的行，并放置在（内联）它所引用的基本文本之后。 Warichu 元素也可以包含 WT 和 WP 元素。 |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp) | （Warichu 标点符号）围绕 WT 文本的标点符号。它包含文本（通常是单个左括号或右括号或类似的括号字符）。根据 JIS X 4051-1995，warichu 周围的括号可以根据格式化程序的判断转换为 SPACE（通常宽度为 1/4 EM）。 |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt) | （Warichu 文本）warichu 注释的较小尺寸文本，格式为两行并放置在周围的 WP 元素之间。 |

### 也可以看看

* 命名空间 [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
