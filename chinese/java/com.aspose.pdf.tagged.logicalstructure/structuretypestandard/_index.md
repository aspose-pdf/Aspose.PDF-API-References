---
title: "StructureTypeStandard"
linktitle: "StructureTypeStandard"
second_title: "Aspose.PDF for Java API 参考"
description: "表示标准结构类型。"
type: docs
weight: 130
url: /zh/java/com.aspose.pdf.tagged.logicalstructure/structuretypestandard/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard

```
public final class StructureTypeStandard extends Object
```

表示标准结构类型。

## 字段

| 字段 | 描述 |
| --- | --- |
| [Annot](#Annot) | (注释；PDF 1.5) 将 ILSE 内容的一部分与相应的 PDF 注释关联起来。Annot 应用于除链接注释和小部件注释之外的所有 PDF 注释。 |
| [Art](#Art) | (文章) 相对独立的文本主体，构成单一的叙述或说明。文章应当相互独立；即它们不应包含其他文章作为组成元素。 |
| [BibEntry](#BibEntry) | (参考文献条目) 用于标识某些被引用内容的外部来源的参考。它可能包含一个标签（结构类型 Lbl）作为子项。虽然参考文献条目可能包括标识被引用内容的作者、作品、出版商等组成部分，但在此细节层级上未定义标准结构类型。 |
| [BlockQuote](#BlockQuote) | (块引用) 由一个或多个段落组成的文本，归属于除周围文本作者之外的其他人。 |
| [Caption](#Caption) | (标题) 对表格或图形的简要描述文本。 |
| [Code](#Code) | (代码) 计算机程序文本的片段。 |
| [Div](#Div) | (分区) 通用的块级元素或元素组。 |
| [Document](#Document) | (文档) 完整的文档。这是包含多个部分或多个文章的任何结构树的根元素。 |
| [Figure](#Figure) | (图形) 图形内容的一个项目。其位置可通过 Placement 布局属性指定。 |
| [Form](#Form) | (表单) 表示交互式表单字段的小部件注释。 |
| [Formula](#Formula) | (公式) 数学公式。此结构类型仅用于将整个内容元素标识为公式。未定义用于标识公式内部各个组件的标准结构类型。从排版角度看，公式应与图形（结构类型 Figure）类似对待。 |
| [H](#H) | (标题) 文档内容子划分的标签。它应当是其所在分区的第一个子元素。 |
| [H1](#H1) | 一级标题，供无法层级嵌套章节且因此无法从嵌套层级确定标题级别的符合规范的写作者使用。 |
| [H2](#H2) | 二级标题，供无法层级嵌套章节且因此无法从嵌套层级确定标题级别的符合规范的写作者使用。 |
| [H3](#H3) | Level 3 Heading，供无法层次嵌套其章节且因此无法从嵌套层级确定标题级别的符合规范的写作者使用。 |
| [H4](#H4) | Level 4 Heading，供无法层次嵌套其章节且因此无法从嵌套层级确定标题级别的符合规范的写作者使用。 |
| [H5](#H5) | Level 5 Heading，供无法层次嵌套其章节且因此无法从嵌套层级确定标题级别的符合规范的写作者使用。 |
| [H6](#H6) | Level 6 Heading，供无法层次嵌套其章节且因此无法从嵌套层级确定标题级别的符合规范的写作者使用。 |
| [Index](#Index) | (Index) 包含标识文本的条目序列，并伴随引用元素指示文档主体中指定文本的出现位置。 |
| [L](#L) | (List) 具有相同意义和重要性的项目序列。其直接子元素应为可选的标题（结构类型 Caption），随后是一项或多项列表项（结构类型 LI）。 |
| [Lbl](#Lbl) | (Label) 用于区分同一列表或其他同类项目组中某项的名称或编号。 |
| [LBody](#LBody) | (List body) 列表项的描述性内容。例如在词典列表中，它包含术语的定义。它可以直接包含内容，或拥有其他 BLSE 作为子元素，可能包括嵌套列表。 |
| [LI](#LI) | (List item) 列表的单个成员。其子元素可以是一个或多个标签、列表主体，或两者兼有（结构类型 Lbl 或 LBody）。 |
| [Link](#Link) | (Link) ILSE 内容的一部分与相应链接注释之间的关联。其子元素应为一个或多个内容项或子 ILSE，以及一个或多个标识关联链接注释的对象引用。 |
| [NonStruct](#NonStruct) | (Nonstructural element) 没有固有结构意义的分组元素，仅用于分组目的。此类元素不同于 division（结构类型 Div），因为它不应被解释或导出到其他文档格式；但其后代应正常处理。 |
| [Note](#Note) | (Note) 解释性文本项，例如脚注或尾注，可在文档正文中被引用。它可以有一个标签（结构类型 Lbl）作为子元素。该注释可以作为引用它的正文结构元素的子元素包含，也可以放在其他位置（如尾注章节），并通过引用（结构类型 Reference）访问。标记 PDF 并未规定脚注在页面内容顺序中的放置位置。它们可以以内联形式出现，也可以在页面末尾，由符合规范的写作者自行决定。 |
| [P](#P) | (Paragraph) 文本的低层次划分。 |
| [Part](#Part) | (Part) 文档的大规模划分。此类元素适用于对文章或章节进行分组。 |
| [Private](#Private) | (Private element) 包含属于生成它的应用程序的私有内容的分组元素。此类元素的结构意义未指定，应完全由符合规范的写作者决定。Private element 及其任何后代均不得被解释或导出到其他文档格式。 |
| [Quote](#Quote) | (Quotation) 属于除周围文本作者之外的其他人的内联文本片段。引用的文本应在单个段落内内联包含。这与块级元素 BlockQuote 不同，后者由一个或多个完整段落（或呈现为完整段落的其他元素）组成。 |
| [RB](#RB) | (Ruby base text) 应用于 ruby 注释的全尺寸文本。RB 可以包含文本、其他内联元素或两者的混合。它可能具有 RubyAlign 属性。 |
| [Reference](#Reference) | (Reference) 对文档其他位置内容的引用。 |
| [RP](#RP) | (Ruby punctuation) 环绕 ruby 注释文本的标点符号。仅在 ruby 注释无法以 ruby 样式正确格式化而以普通注释形式，或以 warichu 形式格式化时使用。它包含文本（通常是单个左或右括号或类似的括号字符）。 |
| [RT](#RT) | (Ruby annotation text) 应放置在 ruby 基本文本旁边的较小尺寸文本。它可以包含文本、其他内联元素或两者的混合。它可能具有 RubyAlign 和 RubyPosition 属性。 |
| [Ruby](#Ruby) | (Ruby; PDF 1.5) 以较小文本尺寸书写并放置在其所指基文本旁边的旁注（注释）。Ruby 元素还可以包含 RB、RT 和 RP 元素。(Ruby) 包裹整个 ruby 组合的外壳。它应包含一个 RB 元素，随后是一个 RT 元素或由 RP、RT、RP 组成的三元素组。Ruby 元素及其内容元素不得跨多行断开。 |
| [Sect](#Sect) | (Section) 用于分组相关内容元素的容器。 |
| [Span](#Span) | (Span) 没有特定固有特征的通用内联文本片段。例如，可用于使用给定的样式属性界定文本范围。 |
| [Table](#Table) | (Table) 矩形数据单元格的二维布局，可能具有复杂的子结构。它的子元素可以是一个或多个表格行（结构类型 TR）；或者可选的表头（结构类型 THead），随后是一项或多项表体元素（结构类型 TBody）以及可选的表脚（结构类型 TFoot）。此外，表格可以在首个或最后一个子元素中包含标题（结构类型 Caption）。 |
| [TBody](#TBody) | (Table body row group; PDF 1.5) 构成表格主体部分的行组。如果表格跨多页拆分，主体区域可能在行边界处被分割。表格可以拥有多个 TBody 元素，以便为一组行绘制边框或背景。 |
| [TD](#TD) | (Table data cell) 表格单元格包含作为表格内容一部分的数据。 |
| [TFoot](#TFoot) | (Table footer row group; PDF 1.5) 构成表格页脚的一组行。如果表格跨多页拆分，这些行可能会在每个表格片段的底部重新绘制（尽管只有一个 TFoot 元素）。 |
| [TH](#TH) | (Table header cell) 包含描述表格一行或多行或列的标题文本的表格单元格。 |
| [THead](#THead) | (Table header row group; PDF 1.5) 构成表格标题的一组行。如果表格跨多页拆分，这些行可能会在每个表格片段的顶部重新绘制（尽管只有一个 THead 元素）。 |
| [TOC](#TOC) | (Table of contents) 由目录项条目（结构类型 TOCI）和/或其他嵌套目录条目（TOC）组成的列表。仅包含 TOCI 条目的目录条目表示平面层次结构。包含其他嵌套 TOC 条目（以及可能的 TOCI 条目）的目录条目表示更复杂的层次结构。理想情况下，顶层目录条目的层次结构反映文档主体的结构。 |
| [TOCI](#TOCI) | (Table of contents item) 目录的单个成员。此条目的子项可以是以下任意结构类型：Lbl - 标签；Reference - 指向标题和页码的引用；NonStruct - 用于包装引导元素的非结构元素；P - 描述性文本；TOC - 如目录条目所述的层次目录元素。 |
| [TR](#TR) | (Table row) 表格中的标题行或数据行。它可能包含表头单元格和表格数据单元格（结构类型 TH 和 TD）。 |
| [Warichu](#Warichu) | (Warichu; PDF 1.5) 以较小字号显示的评论或注释，格式化为两行，位于包含文本行的高度内，并在其所指的基准文本之后（内联）放置。Warichu 元素还可能包含 WT 和 WP 元素。(Warichu) 包裹整个 warichu 组合的外壳。它可能包含由 WP、WT 和 WP 组成的三元素组。Warichu 元素（及其内容元素）可根据日本工业标准 (JIS) X 4051-1995 中描述的 warichu 换行规则跨多行换行。 |
| [WP](#WP) | (Warichu punctuation) 包围 WT 文本的标点符号。它包含文本（通常是单个左或右括号或类似的括号字符）。根据 JIS X 4051-1995，围绕 warichu 的括号可由格式化程序自行决定转换为空格（名义宽度为 1/4 EM）。 |
| [WT](#WT) | (Warichu text) warichu 注释的较小字号文本，格式化为两行并置于周围的 WP 元素之间。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [canBeAppended](#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-) |  |
| [createElement](#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
| [getCategory](#getCategory--) | 获取标准结构类型的类别。 |
| [getTag](#getTag--) | 获取 {@code StructureElement} 的标签名称。 |
| [to_StructureTypeStandard](#to_StructureTypeStandard-java.lang.String-) | 执行从 {@link String} 到 {@link StructureTypeStandard} 的显式转换。 |
| [toString](#toString--) | 返回表示当前对象的字符串。 |

### Annot {#Annot}
```
public static final StructureTypeStandard Annot
```

(注释；PDF 1.5) 将 ILSE 内容的一部分与相应的 PDF 注释关联起来。Annot 应用于除链接注释和小部件注释之外的所有 PDF 注释。

### Art {#Art}
```
public static final StructureTypeStandard Art
```

(文章) 相对独立的文本主体，构成单一的叙述或说明。文章应当相互独立；即它们不应包含其他文章作为组成元素。

### BibEntry {#BibEntry}
```
public static final StructureTypeStandard BibEntry
```

(参考文献条目) 用于标识某些被引用内容的外部来源的参考。它可能包含一个标签（结构类型 Lbl）作为子项。虽然参考文献条目可能包括标识被引用内容的作者、作品、出版商等组成部分，但在此细节层级上未定义标准结构类型。

### BlockQuote {#BlockQuote}
```
public static final StructureTypeStandard BlockQuote
```

(块引用) 由一个或多个段落组成的文本，归属于除周围文本作者之外的其他人。

### Caption {#Caption}
```
public static final StructureTypeStandard Caption
```

(标题) 对表格或图形的简要描述文本。

### Code {#Code}
```
public static final StructureTypeStandard Code
```

(代码) 计算机程序文本的片段。

### Div {#Div}
```
public static final StructureTypeStandard Div
```

(分区) 通用的块级元素或元素组。

### Document {#Document}
```
public static final StructureTypeStandard Document
```

(文档) 完整的文档。这是包含多个部分或多个文章的任何结构树的根元素。

### Figure {#Figure}
```
public static final StructureTypeStandard Figure
```

(图形) 图形内容的一个项目。其位置可通过 Placement 布局属性指定。

### Form {#Form}
```
public static final StructureTypeStandard Form
```

(表单) 表示交互式表单字段的小部件注释。

### Formula {#Formula}
```
public static final StructureTypeStandard Formula
```

(公式) 数学公式。此结构类型仅用于将整个内容元素标识为公式。未定义用于标识公式内部各个组件的标准结构类型。从排版角度看，公式应与图形（结构类型 Figure）类似对待。

### H {#H}
```
public static final StructureTypeStandard H
```

(标题) 文档内容子划分的标签。它应当是其所在分区的第一个子元素。

### H1 {#H1}
```
public static final StructureTypeStandard H1
```

一级标题，供无法层级嵌套章节且因此无法从嵌套层级确定标题级别的符合规范的写作者使用。

### H2 {#H2}
```
public static final StructureTypeStandard H2
```

二级标题，供无法层级嵌套章节且因此无法从嵌套层级确定标题级别的符合规范的写作者使用。

### H3 {#H3}
```
public static final StructureTypeStandard H3
```

Level 3 Heading，供无法层次嵌套其章节且因此无法从嵌套层级确定标题级别的符合规范的写作者使用。

### H4 {#H4}
```
public static final StructureTypeStandard H4
```

Level 4 Heading，供无法层次嵌套其章节且因此无法从嵌套层级确定标题级别的符合规范的写作者使用。

### H5 {#H5}
```
public static final StructureTypeStandard H5
```

Level 5 Heading，供无法层次嵌套其章节且因此无法从嵌套层级确定标题级别的符合规范的写作者使用。

### H6 {#H6}
```
public static final StructureTypeStandard H6
```

Level 6 Heading，供无法层次嵌套其章节且因此无法从嵌套层级确定标题级别的符合规范的写作者使用。

### Index {#Index}
```
public static final StructureTypeStandard Index
```

(Index) 包含标识文本的条目序列，并伴随引用元素指示文档主体中指定文本的出现位置。

### L {#L}
```
public static final StructureTypeStandard L
```

(List) 具有相同意义和重要性的项目序列。其直接子元素应为可选的标题（结构类型 Caption），随后是一项或多项列表项（结构类型 LI）。

### Lbl {#Lbl}
```
public static final StructureTypeStandard Lbl
```

(Label) 用于区分同一列表或其他同类项目组中某项的名称或编号。

### LBody {#LBody}
```
public static final StructureTypeStandard LBody
```

(List body) 列表项的描述性内容。例如在词典列表中，它包含术语的定义。它可以直接包含内容，或拥有其他 BLSE 作为子元素，可能包括嵌套列表。

### LI {#LI}
```
public static final StructureTypeStandard LI
```

(List item) 列表的单个成员。其子元素可以是一个或多个标签、列表主体，或两者兼有（结构类型 Lbl 或 LBody）。

### Link {#Link}
```
public static final StructureTypeStandard Link
```

(Link) ILSE 内容的一部分与相应链接注释之间的关联。其子元素应为一个或多个内容项或子 ILSE，以及一个或多个标识关联链接注释的对象引用。

### NonStruct {#NonStruct}
```
public static final StructureTypeStandard NonStruct
```

(Nonstructural element) 没有固有结构意义的分组元素，仅用于分组目的。此类元素不同于 division（结构类型 Div），因为它不应被解释或导出到其他文档格式；但其后代应正常处理。

### Note {#Note}
```
public static final StructureTypeStandard Note
```

(Note) 解释性文本项，例如脚注或尾注，可在文档正文中被引用。它可以有一个标签（结构类型 Lbl）作为子元素。该注释可以作为引用它的正文结构元素的子元素包含，也可以放在其他位置（如尾注章节），并通过引用（结构类型 Reference）访问。标记 PDF 并未规定脚注在页面内容顺序中的放置位置。它们可以以内联形式出现，也可以在页面末尾，由符合规范的写作者自行决定。

### P {#P}
```
public static final StructureTypeStandard P
```

(Paragraph) 文本的低层次划分。

### Part {#Part}
```
public static final StructureTypeStandard Part
```

(Part) 文档的大规模划分。此类元素适用于对文章或章节进行分组。

### Private {#Private}
```
public static final StructureTypeStandard Private
```

(Private element) 包含属于生成它的应用程序的私有内容的分组元素。此类元素的结构意义未指定，应完全由符合规范的写作者决定。Private element 及其任何后代均不得被解释或导出到其他文档格式。

### Quote {#Quote}
```
public static final StructureTypeStandard Quote
```

(Quotation) 属于除周围文本作者之外的其他人的内联文本片段。引用的文本应在单个段落内内联包含。这与块级元素 BlockQuote 不同，后者由一个或多个完整段落（或呈现为完整段落的其他元素）组成。

### RB {#RB}
```
public static final StructureTypeStandard RB
```

(Ruby base text) 应用于 ruby 注释的全尺寸文本。RB 可以包含文本、其他内联元素或两者的混合。它可能具有 RubyAlign 属性。

### Reference {#Reference}
```
public static final StructureTypeStandard Reference
```

(Reference) 对文档其他位置内容的引用。

### RP {#RP}
```
public static final StructureTypeStandard RP
```

(Ruby punctuation) 环绕 ruby 注释文本的标点符号。仅在 ruby 注释无法以 ruby 样式正确格式化而以普通注释形式，或以 warichu 形式格式化时使用。它包含文本（通常是单个左或右括号或类似的括号字符）。

### RT {#RT}
```
public static final StructureTypeStandard RT
```

(Ruby annotation text) 应放置在 ruby 基本文本旁边的较小尺寸文本。它可以包含文本、其他内联元素或两者的混合。它可能具有 RubyAlign 和 RubyPosition 属性。

### Ruby {#Ruby}
```
public static final StructureTypeStandard Ruby
```

(Ruby; PDF 1.5) 以较小文本尺寸书写并放置在其所指基文本旁边的旁注（注释）。Ruby 元素还可以包含 RB、RT 和 RP 元素。(Ruby) 包裹整个 ruby 组合的外壳。它应包含一个 RB 元素，随后是一个 RT 元素或由 RP、RT、RP 组成的三元素组。Ruby 元素及其内容元素不得跨多行断开。

### Sect {#Sect}
```
public static final StructureTypeStandard Sect
```

(Section) 用于分组相关内容元素的容器。

### Span {#Span}
```
public static final StructureTypeStandard Span
```

(Span) 没有特定固有特征的通用内联文本片段。例如，可用于使用给定的样式属性界定文本范围。

### Table {#Table}
```
public static final StructureTypeStandard Table
```

(Table) 矩形数据单元格的二维布局，可能具有复杂的子结构。它的子元素可以是一个或多个表格行（结构类型 TR）；或者可选的表头（结构类型 THead），随后是一项或多项表体元素（结构类型 TBody）以及可选的表脚（结构类型 TFoot）。此外，表格可以在首个或最后一个子元素中包含标题（结构类型 Caption）。

### TBody {#TBody}
```
public static final StructureTypeStandard TBody
```

(Table body row group; PDF 1.5) 构成表格主体部分的行组。如果表格跨多页拆分，主体区域可能在行边界处被分割。表格可以拥有多个 TBody 元素，以便为一组行绘制边框或背景。

### TD {#TD}
```
public static final StructureTypeStandard TD
```

(Table data cell) 表格单元格包含作为表格内容一部分的数据。

### TFoot {#TFoot}
```
public static final StructureTypeStandard TFoot
```

(Table footer row group; PDF 1.5) 构成表格页脚的一组行。如果表格跨多页拆分，这些行可能会在每个表格片段的底部重新绘制（尽管只有一个 TFoot 元素）。

### TH {#TH}
```
public static final StructureTypeStandard TH
```

(Table header cell) 包含描述表格一行或多行或列的标题文本的表格单元格。

### THead {#THead}
```
public static final StructureTypeStandard THead
```

(Table header row group; PDF 1.5) 构成表格标题的一组行。如果表格跨多页拆分，这些行可能会在每个表格片段的顶部重新绘制（尽管只有一个 THead 元素）。

### TOC {#TOC}
```
public static final StructureTypeStandard TOC
```

(Table of contents) 由目录项条目（结构类型 TOCI）和/或其他嵌套目录条目（TOC）组成的列表。仅包含 TOCI 条目的目录条目表示平面层次结构。包含其他嵌套 TOC 条目（以及可能的 TOCI 条目）的目录条目表示更复杂的层次结构。理想情况下，顶层目录条目的层次结构反映文档主体的结构。

### TOCI {#TOCI}
```
public static final StructureTypeStandard TOCI
```

(Table of contents item) 目录的单个成员。此条目的子项可以是以下任意结构类型：Lbl - 标签；Reference - 指向标题和页码的引用；NonStruct - 用于包装引导元素的非结构元素；P - 描述性文本；TOC - 如目录条目所述的层次目录元素。

### TR {#TR}
```
public static final StructureTypeStandard TR
```

(Table row) 表格中的标题行或数据行。它可能包含表头单元格和表格数据单元格（结构类型 TH 和 TD）。

### Warichu {#Warichu}
```
public static final StructureTypeStandard Warichu
```

(Warichu; PDF 1.5) 以较小字号显示的评论或注释，格式化为两行，位于包含文本行的高度内，并在其所指的基准文本之后（内联）放置。Warichu 元素还可能包含 WT 和 WP 元素。(Warichu) 包裹整个 warichu 组合的外壳。它可能包含由 WP、WT 和 WP 组成的三元素组。Warichu 元素（及其内容元素）可根据日本工业标准 (JIS) X 4051-1995 中描述的 warichu 换行规则跨多行换行。

### WP {#WP}
```
public static final StructureTypeStandard WP
```

(Warichu punctuation) 包围 WT 文本的标点符号。它包含文本（通常是单个左或右括号或类似的括号字符）。根据 JIS X 4051-1995，围绕 warichu 的括号可由格式化程序自行决定转换为空格（名义宽度为 1/4 EM）。

### WT {#WT}
```
public static final StructureTypeStandard WT
```

(Warichu text) warichu 注释的较小字号文本，格式化为两行并置于周围的 WP 元素之间。

### canBeAppended {#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-}


### createElement {#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### getCategory {#getCategory--}
```
public final StructureTypeCategory getCategory()
```

获取标准结构类型的类别。

**Returns:**
值：标准结构类型的类别。

### getTag {#getTag--}
```
public final String getTag()
```

获取 {@code StructureElement} 的标签名称。

**Returns:**
{@code StructureElement} 的标签名称。

### to_StructureTypeStandard {#to_StructureTypeStandard-java.lang.String-}
执行从 {@link String} 到 {@link StructureTypeStandard} 的显式转换。

### toString {#toString--}
```
public String toString()
```

返回表示当前对象的字符串。

**Returns:**
表示当前对象的字符串。
