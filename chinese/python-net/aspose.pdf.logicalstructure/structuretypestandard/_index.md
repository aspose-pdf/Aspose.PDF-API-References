---
title: "StructureTypeStandard"
second_title: "Aspose.PDF for Python via .NET API 参考"
description: "表示标准结构类型。"
type: docs
weight: 560
url: /zh/python-net/aspose.pdf.logicalstructure/structuretypestandard/
---

## StructureTypeStandard class

表示标准结构类型。

StructureTypeStandard 类型公开以下成员：
## 属性
| 名称 | 描述 |
| :- | :- |
| tag | 获取 [StructureElement](/pdf/python-net/aspose.pdf.logicalstructure/structureelement/) 的标签名称。 |
| 类别 | 获取 Standard Structure Type 的类别。 |
| DOCUMENT | (Document) 完整文档。这是任何包含多个部分或多个文章的结构树的根元素。 |
| PART | (Part) 文档的大规模划分。此类元素适用于对文章或章节进行分组。 |
| ART | (Article) 相对独立的文本主体，构成单一叙事或阐述。文章应相互独立；也就是说，它们不应包含其他文章作为组成元素。 |
| SECT | (Section) 用于分组相关内容元素的容器。 |
| DIV | (Division) 通用的块级元素或元素组。 |
| BLOCK_QUOTE | (块引用) 一段由一个或多个段落组成的文本，归因于除周围文本作者之外的其他人。 |
| CAPTION | (标题) 描述表格或图形的简短文字。 |
| TOC | (目录) 由目录项条目（结构类型 TOCI）和/或其他嵌套的目录条目（TOC）组成的列表。 |
| TOCI | (目录项) 目录的单个成员。此条目的子项可以是以下任意结构类型： |
| INDEX | (索引) 包含标识文本以及指示文档主体中指定文本出现位置的参考元素的条目序列。 |
| NON_STRUCT | (非结构元素) 没有固有结构意义的分组元素；仅用于分组目的。此类元素不同于 division（结构类型 Div），它不应被解释或导出到其他文档格式；但其后代应正常处理。 |
| PRIVATE | (私有元素) 包含属于生成它的应用程序的私有内容的分组元素。此类元素的结构意义未指定，应完全由符合规范的写作者决定。私有元素及其任何后代均不得被解释或导出到其他文档格式。 |
| P | (段落) 文本的低层次划分。 |
| H | (标题) 文档内容子划分的标签。它应当是其所标头的划分的第一个子元素。 |
| H1 | 一级标题，供无法层级嵌套章节且因此无法从嵌套层级确定标题级别的符合规范的写作者使用。 |
| H2 | 二级标题，供无法层级嵌套章节且因此无法从嵌套层级确定标题级别的符合规范的写作者使用。 |
| H3 | 三级标题，供无法层级嵌套章节且因此无法从嵌套层级确定标题级别的符合规范的写作者使用。 |
| H4 | 第4级标题，供无法层级嵌套其章节且因此无法从嵌套层级确定标题级别的符合规范的写入器使用。 |
| H5 | 第5级标题，供无法层级嵌套其章节且因此无法从嵌套层级确定标题级别的符合规范的写入器使用。 |
| H6 | 第6级标题，供无法层级嵌套其章节且因此无法从嵌套层级确定标题级别的符合规范的写入器使用。 |
| L | (List) 一系列意义和重要性相同的项目。其直接子元素应为可选的标题（结构类型 Caption），随后是一项或多项列表项（结构类型 LI）。 |
| LI | (List item) 列表的单个成员。其子元素可以是一个或多个标签、列表主体，或两者兼有（结构类型 Lbl 或 LBody）。 |
| LBL | (Label) 用于区分同一列表或其他相似项目组中给定项目与其他项目的名称或编号。 |
| L_BODY | (List body) 列表项的描述性内容。例如，在词典列表中，它包含术语的定义。它可以直接包含内容，也可以拥有其他 BLSE 作为子元素，可能包括嵌套列表。 |
| TABLE | (Table) 矩形数据单元格的二维布局，可能具有复杂的子结构。它的子元素可以是一个或多个表格行（结构类型 TR）；或者是可选的表头（结构类型 THead），随后是一项或多项表体元素（结构类型 TBody）以及可选的表脚（结构类型 TFoot）。此外，表格还可以在首部或末尾拥有一个标题（结构类型 Caption）。 |
| T_HEAD | (Table header row group; PDF 1.5) 构成表格标题的行组。如果表格跨多页拆分，这些行可能会在每个表格片段的顶部重新绘制（尽管只有一个 THead 元素）。 |
| T_BODY | (Table body row group; PDF 1.5) 构成表格主体部分的行组。如果表格跨多页拆分，主体区域可能在行边界处被分割。表格可以拥有多个 TBody 元素，以便为一组行绘制边框或背景。 |
| T_FOOT | (Table footer row group; PDF 1.5) 构成表格页脚的行组。如果表格跨多页拆分，这些行可能会在每个表格片段的底部重新绘制（尽管只有一个 TFoot 元素）。 |
| TR | (Table row) 表格中的标题行或数据行。它可能包含表头单元格和表数据单元格（结构类型 TH 和 TD）。 |
| TH | (Table header cell) 包含描述表格一行或多行、或一列或多列的标题文本的表格单元格。 |
| TD | (Table data cell) 包含表格内容数据的表格单元格。 |
| SPAN | (Span) 通用的内联文本片段，没有特定的固有特性。例如，它可用于使用给定的一组样式属性来限定文本范围。 |
| QUOTE | (Quotation) 属于除周围文本作者之外的其他人的内联文本片段。 |
| 注意 | (Note) 说明性文本项，例如脚注或尾注，可在文档正文中引用。它可能有一个标签（结构类型 Lbl）作为子元素。该注释可以作为正文中引用它的结构元素的子元素包含，或者可以放在其他位置（例如尾注章节），并通过引用（结构类型 Reference）来访问。 |
| REFERENCE | (Reference) 对文档其他位置内容的引用。 |
| BIB_ENTRY | (Bibliography entry) 标识某些被引用内容的外部来源的参考。它可能包含一个标签（结构类型 Lbl）作为子元素。 |
| CODE | (Code) 计算机程序文本的片段。 |
| LINK | (Link) ILSE 内容的一部分与相应的链接注释或多个链接注释之间的关联。其子项应为一个或多个内容项或子 ILSE，以及一个或多个对象引用，用于标识关联的链接注释。 |
| ANNOT | (Annotation; PDF 1.5) ILSE 内容的一部分与相应的 PDF 注释之间的关联。Annot 应用于除链接注释和小部件注释之外的所有 PDF 注释。 |
| RUBY | (Ruby; PDF 1.5) 以较小字号书写并放置在其所指基准文本旁边的旁注（注释）。Ruby 元素还可以包含 RB、RT 和 RP 元素。 |
| RB | (Ruby base text) 应用于 ruby 注释的完整大小文本。RB 可以包含文本、其他内联元素或两者的混合。它可能具有 RubyAlign 属性。 |
| RT | (Ruby annotation text) 应放置在 ruby 基准文本旁边的较小字号文本。它可以包含文本、其他内联元素或两者的混合。它可能具有 RubyAlign 和 RubyPosition 属性。 |
| RP | (Ruby punctuation) 环绕 ruby 注释文本的标点符号。仅在 ruby 注释无法以 ruby 样式正确排版而改为普通注释，或以 warichu 形式排版时使用。它包含文本（通常是单个左括号或右括号或类似的括号字符）。 |
| WARICHU | (Warichu; PDF 1.5) 以较小字号书写的评论或注释，排版在包含文本行的高度内的两行较小行中，并紧随（内联）其所指基准文本之后。Warichu 元素还可以包含 WT 和 WP 元素。 |
| WT | (Warichu text) 较小尺寸的 warichu 注释文本，格式为两行，放置在周围的 WP 元素之间。 |
| WP | (Warichu punctuation) 环绕 WT 文本的标点符号。它包含文本（通常是单个左括号或右括号或类似的括号字符）。根据 JIS X 4051-1995，围绕 warichu 的括号可以根据格式化程序的酌情决定转换为空格（名义上宽度为 1/4 EM）。 |
| FIGURE | (Figure) 图形内容项。其放置位置可以通过 Placement 布局属性指定。 |
| FORMULA | (Formula) 数学公式。 |
| FORM | (Form) 表示交互式表单字段的部件注释。 |

### 另请参阅

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

