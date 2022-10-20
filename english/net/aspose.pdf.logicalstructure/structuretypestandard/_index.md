---
title: StructureTypeStandard
second_title: Aspose.PDF for .NET API Reference
description: Represents Standard Structure Types.
type: docs
weight: 4570
url: /net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class

Represents Standard Structure Types.

```csharp
public sealed class StructureTypeStandard
```

## Properties

| Name | Description |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category) { get; } | Gets category of Standard Structure Type. |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag) { get; } | Gets tag name of [`StructureElement`](../structureelement). |

## Methods

| Name | Description |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring)() | Returns a string that represents the current object. |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit) | Performs an explicit conversion from String to [`StructureTypeStandard`](../structuretypestandard). |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot) | (Annotation; PDF 1.5) An association between a portion of the ILSE's content and a corresponding PDF annotation. Annot shall be used for all PDF annotations except link annotations and widget annotations. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art) | (Article) A relatively self-contained body of text constituting a single narrative or exposition. Articles should be disjoint; that is, they should not contain other articles as constituent elements. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry) | (Bibliography entry) A reference identifying the external source of some cited content. It may contain a label (structure type Lbl) as a child. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote) | (Block quotation) A portion of text consisting of one or more paragraphs attributed to someone other than the author of the surrounding text. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption) | (Caption) A brief portion of text describing a table or figure. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code) | (Code) A fragment of computer program text. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div) | (Division) A generic block-level element or group of elements. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document) | (Document) A complete document. This is the root element of any structure tree containing multiple parts or multiple articles. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure) | (Figure) An item of graphical content. Its placement may be specified with the Placement layout attribute. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form) | (Form) A widget annotation representing an interactive form field. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula) | (Formula) A mathematical formula. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h) | (Heading) A label for a subdivision of a document's content. It should be the first child of the division that it heads. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1) | Level 1 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2) | Level 2 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3) | Level 3 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4) | Level 4 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5) | Level 5 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6) | Level 6 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index) | (Index) A sequence of entries containing identifying text accompanied by reference elements that point out occurrences of the specified text in the main body of a document. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l) | (List) A sequence of items of like meaning and importance. Its immediate children should be an optional caption (structure type Caption) followed by one or more list items (structure type LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl) | (Label) A name or number that distinguishes a given item from others in the same list or other group of like items. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody) | (List body) The descriptive content of a list item. In a dictionary list, for example, it contains the definition of the term. It may either contain the content directly or have other BLSEs, perhaps including nested lists, as children. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li) | (List item) An individual member of a list. Its children may be one or more labels, list bodies, or both (structure types Lbl or LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link) | (Link) An association between a portion of the ILSE's content and a corresponding link annotation or annotations. Its children should be one or more content items or child ILSEs and one or more object references identifying the associated link annotations. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct) | (Nonstructural element) A grouping element having no inherent structural significance; it serves solely for grouping purposes. This type of element differs from a division (structure type Div) in that it shall not be interpreted or exported to other document formats; however, its descendants shall be processed normally. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note) | (Note) An item of explanatory text, such as a footnote or an endnote, that is referred to from within the body of the document. It may have a label (structure type Lbl) as a child. The note may be included as a child of the structure element in the body text that refers to it, or it may be included elsewhere (such as in an endnotes section) and accessed by means of a reference (structure type Reference). |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p) | (Paragraph) A low-level division of text. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part) | (Part) A large-scale division of a document. This type of element is appropriate for grouping articles or sections. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private) | (Private element) A grouping element containing private content belonging to the application producing it. The structural significance of this type of element is unspecified and shall be determined entirely by the conforming writer. Neither the Private element nor any of its descendants shall be interpreted or exported to other document formats. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote) | (Quotation) An inline portion of text attributed to someone other than the author of the surrounding text. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb) | (Ruby base text) The full-size text to which the ruby annotation is applied. RB may contain text, other inline elements, or a mixture of both. It may have the RubyAlignattribute. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference) | (Reference) A citation to content elsewhere in the document. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp) | (Ruby punctuation) Punctuation surrounding the ruby annotation text. It is used only when a ruby annotation cannot be properly formatted in a ruby style and instead is formatted as a normal comment, or when it is formatted as a warichu. It contains text (usually a single LEFT or RIGHT PARENTHESIS or similar bracketing character). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt) | (Ruby annotation text) The smaller-size text that shall be placed adjacent to the ruby base text. It may contain text, other inline elements, or a mixture of both. It may have the RubyAlign and RubyPosition attributes. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby) | (Ruby; PDF 1.5) A side-note (annotation) written in a smaller text size and placed adjacent to the base text to which it refers. A Ruby element may also contain the RB, RT, and RP elements. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect) | (Section) A container for grouping related content elements. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span) | (Span) A generic inline portion of text having no particular inherent characteristics. It can be used, for example, to delimit a range of text with a given set of styling attributes. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table) | (Table) A two-dimensional layout of rectangular data cells, possibly having a complex substructure. It contains either one or more table rows (structure type TR) as children; or an optional table head (structure type THead) followed by one or more table body elements (structure type TBody) and an optional table footer (structure type TFoot). In addition, a table may have a caption (structure type Caption) as its first or last child. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody) | (Table body row group; PDF 1.5) A group of rows that constitute the main body portion of a table. If the table is split across multiple pages, the body area may be broken apart on a row boundary. A table may have multiple TBody elements to allow for the drawing of a border or background for a set of rows. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td) | (Table data cell) A table cell containing data that is part of the table's content. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot) | (Table footer row group; PDF 1.5) A group of rows that constitute the footer of a table. If the table is split across multiple pages, these rows may be redrawn at the bottom of each table fragment (although there is only one TFoot element.) |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th) | (Table header cell) A table cell containing header text describing one or more rows or columns of the table. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead) | (Table header row group; PDF 1.5) A group of rows that constitute the header of a table. If the table is split across multiple pages, these rows may be redrawn at the top of each table fragment (although there is only one THead element). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc) | (Table of contents) A list made up of table of contents item entries (structure type TOCI) and/or other nested table of contents entries (TOC). |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci) | (Table of contents item) An individual member of a table of contents. This entry’s children may be any of the following structure types: |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr) | (Table row) A row of headings or data in a table. It may contain table header cells and table data cells (structure types TH and TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu) | (Warichu; PDF 1.5) A comment or annotation in a smaller text size and formatted onto two smaller lines within the height of the containing text line and placed following (inline) the base text to which it refers. A Warichu element may also contain the WT and WP elements. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp) | (Warichu punctuation) The punctuation that surrounds the WT text. It contains text (usually a single LEFT or RIGHT PARENTHESIS or similar bracketing character). According to JIS X 4051-1995, the parentheses surrounding a warichu may be converted to a SPACE (nominally 1/4 EM in width) at the discretion of the formatter. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt) | (Warichu text) The smaller-size text of a warichu comment that is formatted into two lines and placed between surrounding WP elements. |

### See Also

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
