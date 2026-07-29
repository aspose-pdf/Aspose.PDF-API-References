---
title: "类 StructureTypeStandard"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.LogicalStructure.StructureTypeStandard 类。表示标准结构类型"
type: docs
weight: 6870
url: /zh/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class

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
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring/)() | 返回表示当前对象的字符串。 |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit/) | 执行从 String 到 `StructureTypeStandard` 的显式转换。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot/) | (Annotation; PDF 1.5) 在 ILSE 内容的一部分与相应 PDF 注释之间的关联。Annot 应用于除链接注释和小部件注释之外的所有 PDF 注释。 |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art/) | (Article) 相对独立的文本主体，构成单一叙述或阐述。文章应当相互独立；即它们不应包含其他文章作为组成元素。 |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry/) | (Bibliography entry) 用于标识某些被引用内容的外部来源的参考。它可能包含一个标签（结构类型 Lbl）作为子元素。 |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote/) | (Block quotation) 由一个或多个段落组成的文本片段，归属给除周围文本作者之外的其他人。 |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption/) | (Caption) 描述表格或图形的简短文字。 |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code/) | (Code) 计算机程序代码的片段。 |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div/) | (Division) 通用的块级元素或元素组。 |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document/) | (Document) 完整的文档。这是包含多个部分或多个文章的任何结构树的根元素。 |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure/) | (Figure) 图形内容项。其位置可通过 Placement 布局属性指定。 |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form/) | (Form) 表示交互式表单字段的小部件注释。 |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula/) | (Formula) 数学公式。 |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h/) | (Heading) 文档内容细分的标签。它应当是其所在 division 的第一个子元素。 |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1/) | 一级标题，供无法层级嵌套章节且因此无法从嵌套层级确定标题级别的符合规范的写入器使用。 |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2/) | 二级标题，供无法层级嵌套章节且因此无法从嵌套层级确定标题级别的符合规范的写入器使用。 |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3/) | 三级标题，供无法层级嵌套章节且因此无法从嵌套层级确定标题级别的符合规范的写入器使用。 |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4/) | 四级标题，供无法层级嵌套章节且因此无法从嵌套层级确定标题级别的符合规范的写入器使用。 |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5/) | 五级标题，供无法层级嵌套章节且因此无法从嵌套层级确定标题级别的符合规范的写入器使用。 |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6/) | 六级标题，供无法层级嵌套章节且因此无法从嵌套层级确定标题级别的符合规范的写入器使用。 |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index/) | (Index) 包含标识文本以及指向文档主体中指定文本出现位置的参考元素的条目序列。 |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l/) | (List) 具有相同意义和重要性的项目序列。其直接子元素应为可选的标题（结构类型 Caption），随后是一项或多项列表项（结构类型 LI）。 |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl/) | (Label) 用于区分同一列表或其他同类项目组中给定项目的名称或编号。 |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody/) | (列表正文) 列表项的描述性内容。例如，在词典列表中，它包含术语的定义。它可以直接包含内容，也可以拥有其他 BLSE，可能包括嵌套列表，作为子元素。 |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li/) | (列表项) 列表的单个成员。它的子元素可以是一个或多个标签、列表正文，或两者兼有（结构类型 Lbl 或 LBody）。 |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link/) | (链接) ILSE 内容的一部分与相应的链接注释或多个链接注释之间的关联。其子元素应包括一个或多个内容项或子 ILSE，以及一个或多个对象引用，用于标识关联的链接注释。 |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct/) | (非结构元素) 一个没有固有结构意义的分组元素，仅用于分组目的。此类元素不同于 division（结构类型 Div），因为它不应被解释或导出到其他文档格式；但其后代应正常处理。 |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note/) | (注释) 文档正文中引用的解释性文字项，例如脚注或尾注。它可以有一个标签（结构类型 Lbl）作为子元素。该注释可以作为引用它的正文结构元素的子元素包含，也可以放在其他位置（如尾注章节），并通过引用（结构类型 Reference）访问。 |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p/) | (段落) 文本的低层次划分。 |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part/) | (部分) 文档的大规模划分。此类元素适用于对文章或章节进行分组。 |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private/) | (私有元素) 包含属于生成它的应用程序的私有内容的分组元素。此类元素的结构意义未指定，应完全由符合规范的编写者决定。私有元素及其任何后代均不应被解释或导出到其他文档格式。 |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote/) | (引用) 文本中归属于除周围文本作者之外的其他人的内联文字部分。 |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb/) | (Ruby 基本文本) 应用于 ruby 注释的完整大小文本。RB 可以包含文本、其他内联元素或两者的混合。它可能具有 RubyAlign 属性。 |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference/) | (引用) 对文档其他位置内容的引证。 |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp/) | (Ruby 标点) 环绕 ruby 注释文本的标点符号。仅在 ruby 注释无法以 ruby 样式正确格式化而以普通注释形式呈现，或以 warichu 形式格式化时使用。它包含文本（通常是单个左或右括号或类似的括号字符）。 |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt/) | (Ruby 注释文本) 应放置在 ruby 基本文本旁边的较小尺寸文本。它可以包含文本、其他内联元素或两者的混合。它可能具有 RubyAlign 和 RubyPosition 属性。 |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby/) | (Ruby; PDF 1.5) 以较小文字大小编写并放置在其所指基本文本旁边的旁注（注释）。Ruby 元素还可以包含 RB、RT 和 RP 元素。 |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect/) | (章节) 用于分组相关内容元素的容器。 |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span/) | (跨度) 没有特定固有特征的通用内联文本部分。例如，可用于使用给定的样式属性界定文本范围。 |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table/) | (表格) 矩形数据单元格的二维布局，可能具有复杂的子结构。它的子元素可以是一个或多个表格行（结构类型 TR），或可选的表头（结构类型 THead）后跟一个或多个表体元素（结构类型 TBody）以及可选的表脚（结构类型 TFoot）。此外，表格可以有一个标题（结构类型 Caption）作为其首个或最后一个子元素。 |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody/) | (表体行组; PDF 1.5) 构成表格主体部分的行组。如果表格跨多页拆分，主体区域可能在行边界处被分割。表格可以拥有多个 TBody 元素，以便为一组行绘制边框或背景。 |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td/) | (表格数据单元格) 包含表格内容数据的单元格。 |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot/) | (表脚行组; PDF 1.5) 构成表格页脚的行组。如果表格跨多页拆分，这些行可能在每个表格片段的底部重新绘制（尽管只有一个 TFoot 元素）。 |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th/) | (表头单元格) 包含描述表格一个或多个行或列的标题文本的单元格。 |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead/) | (表头行组; PDF 1.5) 构成表格标题的行组。如果表格跨多页拆分，这些行可能在每个表格片段的顶部重新绘制（尽管只有一个 THead 元素）。 |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc/) | (目录) 由目录项条目（结构类型 TOCI）和/或其他嵌套目录条目（TOC）组成的列表。 |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci/) | (目录项) 目录的单个成员。此条目的子元素可以是以下任意结构类型： |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr/) | (表格行) 表格中的标题行或数据行。它可以包含表头单元格和表格数据单元格（结构类型 TH 和 TD）。 |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu/) | (Warichu; PDF 1.5) 一个以较小字号显示的批注或注释，格式化为两行，位于包含文本行的高度内，并紧随（内联）其所指的基准文本之后。Warichu 元素也可能包含 WT 和 WP 元素。 |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp/) | (Warichu punctuation) 环绕 WT 文本的标点符号。它包含文本（通常是单个左括号或右括号或类似的括号字符）。根据 JIS X 4051-1995，围绕 warichu 的括号可由格式化程序自行决定转换为一个空格（宽度约为 1/4 EM）。 |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt/) | (Warichu text) warichu 注释的较小字号文本，格式化为两行，位于周围的 WP 元素之间。 |

### 另请参见

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](../../)


