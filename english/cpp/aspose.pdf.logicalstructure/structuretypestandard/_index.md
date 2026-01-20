---
title: Aspose::Pdf::LogicalStructure::StructureTypeStandard class
linktitle: StructureTypeStandard
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::StructureTypeStandard class. Represents Standard Structure Types in C++.'
type: docs
weight: 5900
url: /cpp/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class


Represents Standard [Structure](../../aspose.pdf.structure/) Types.

```cpp
class StructureTypeStandard : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Category](./get_category/)() const | Gets category of Standard [Structure](../../aspose.pdf.structure/) Type. |
| [get_Tag](./get_tag/)() const | Gets tag name of [Aspose::Pdf::LogicalStructure::StructureElement](../structureelement/). |
| static [to_StructureTypeStandard](./to_structuretypestandard/)(System::String) | Performs an explicit conversion from [System::String](../../system/string/) to [Aspose::Pdf::LogicalStructure::StructureTypeStandard](./). |
| [ToString](./tostring/)() const override | Returns a string that represents the current object. |
## Fields

| Field | Description |
| --- | --- |
| static [Annot](./annot/) | (Annotation; PDF 1.5) An association between a portion of the ILSE's content and a corresponding PDF annotation. Annot shall be used for all PDF annotations except link annotations and widget annotations. |
| static [Art](./art/) | (Article) A relatively self-contained body of text constituting a single narrative or exposition. Articles should be disjoint; that is, they should not contain other articles as constituent elements. |
| static [BibEntry](./bibentry/) |  |
| static [BlockQuote](./blockquote/) | (Block quotation) A portion of text consisting of one or more paragraphs attributed to someone other than the author of the surrounding text. |
| static [Caption](./caption/) | (Caption) A brief portion of text describing a table or figure. |
| static [Code](./code/) | (Code) A fragment of computer program text. |
| static [Div](./div/) | (Division) A generic block-level element or group of elements. |
| static [Document](./document/) | ([Document](../../aspose.pdf/document/)) A complete document. This is the root element of any structure tree containing multiple parts or multiple articles. |
| static [Figure](./figure/) | (Figure) An item of graphical content. Its placement may be specified with the Placement layout attribute. |
| static [Form](./form/) | (Form) A widget annotation representing an interactive form field. |
| static [Formula](./formula/) |  |
| static [H](./h/) | ([Heading](../../aspose.pdf/heading/)) A label for a subdivision of a document's content. It should be the first child of the division that it heads. |
| static [H1](./h1/) | Level 1 [Heading](../../aspose.pdf/heading/), for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| static [H2](./h2/) | Level 2 [Heading](../../aspose.pdf/heading/), for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| static [H3](./h3/) | Level 3 [Heading](../../aspose.pdf/heading/), for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| static [H4](./h4/) | Level 4 [Heading](../../aspose.pdf/heading/), for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| static [H5](./h5/) | Level 5 [Heading](../../aspose.pdf/heading/), for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| static [H6](./h6/) | Level 6 [Heading](../../aspose.pdf/heading/), for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| static [Index](./index/) | (Index) A sequence of entries containing identifying text accompanied by reference elements that point out occurrences of the specified text in the main body of a document. |
| static [L](./l/) | (List) A sequence of items of like meaning and importance. Its immediate children should be an optional caption (structure type Caption) followed by one or more list items (structure type LI). |
| static [Lbl](./lbl/) | (Label) A name or number that distinguishes a given item from others in the same list or other group of like items. |
| static [LBody](./lbody/) | (List body) The descriptive content of a list item. In a dictionary list, for example, it contains the definition of the term. It may either contain the content directly or have other BLSEs, perhaps including nested lists, as children. |
| static [LI](./li/) | (List item) An individual member of a list. Its children may be one or more labels, list bodies, or both (structure types Lbl or LBody). |
| static [Link](./link/) | (Link) An association between a portion of the ILSE's content and a corresponding link annotation or annotations. Its children should be one or more content items or child ILSEs and one or more object references identifying the associated link annotations. |
| static [NonStruct](./nonstruct/) | (Nonstructural element) A grouping element having no inherent structural significance; it serves solely for grouping purposes. This type of element differs from a division (structure type Div) in that it shall not be interpreted or exported to other document formats; however, its descendants shall be processed normally. |
| static [Note](./note/) |  |
| static [P](./p/) | (Paragraph) A low-level division of text. |
| static [Part](./part/) | (Part) A large-scale division of a document. This type of element is appropriate for grouping articles or sections. |
| static [Private](./private/) | (Private element) A grouping element containing private content belonging to the application producing it. The structural significance of this type of element is unspecified and shall be determined entirely by the conforming writer. Neither the Private element nor any of its descendants shall be interpreted or exported to other document formats. |
| static [Quote](./quote/) |  |
| static [RB](./rb/) | (Ruby base text) The full-size text to which the ruby annotation is applied. RB may contain text, other inline elements, or a mixture of both. It may have the RubyAlignattribute. |
| static [Reference](./reference/) | (Reference) A citation to content elsewhere in the document. |
| static [RP](./rp/) | (Ruby punctuation) Punctuation surrounding the ruby annotation text. It is used only when a ruby annotation cannot be properly formatted in a ruby style and instead is formatted as a normal comment, or when it is formatted as a warichu. It contains text (usually a single LEFT or RIGHT PARENTHESIS or similar bracketing character). |
| static [RT](./rt/) | (Ruby annotation text) The smaller-size text that shall be placed adjacent to the ruby base text. It may contain text, other inline elements, or a mixture of both. It may have the RubyAlign and RubyPosition attributes. |
| static [Ruby](./ruby/) |  |
| static [Sect](./sect/) | (Section) A container for grouping related content elements. |
| static [Span](./span/) | (Span) A generic inline portion of text having no particular inherent characteristics. It can be used, for example, to delimit a range of text with a given set of styling attributes. |
| static [Table](./table/) | ([Table](../../aspose.pdf/table/)) A two-dimensional layout of rectangular data cells, possibly having a complex substructure. It contains either one or more table rows (structure type TR) as children; or an optional table head (structure type THead) followed by one or more table body elements (structure type TBody) and an optional table footer (structure type TFoot). In addition, a table may have a caption (structure type Caption) as its first or last child. |
| static [TBody](./tbody/) | ([Table](../../aspose.pdf/table/) body row group; PDF 1.5) A group of rows that constitute the main body portion of a table. If the table is split across multiple pages, the body area may be broken apart on a row boundary. A table may have multiple TBody elements to allow for the drawing of a border or background for a set of rows. |
| static [TD](./td/) | ([Table](../../aspose.pdf/table/) data cell) A table cell containing data that is part of the table's content. |
| static [TFoot](./tfoot/) | ([Table](../../aspose.pdf/table/) footer row group; PDF 1.5) A group of rows that constitute the footer of a table. If the table is split across multiple pages, these rows may be redrawn at the bottom of each table fragment (although there is only one TFoot element.) |
| static [TH](./th/) | ([Table](../../aspose.pdf/table/) header cell) A table cell containing header text describing one or more rows or columns of the table. |
| static [THead](./thead/) | ([Table](../../aspose.pdf/table/) header row group; PDF 1.5) A group of rows that constitute the header of a table. If the table is split across multiple pages, these rows may be redrawn at the top of each table fragment (although there is only one THead element). |
| static [TOC](./toc/) |  |
| static [TOCI](./toci/) |  |
| static [TR](./tr/) | ([Table](../../aspose.pdf/table/) row) A row of headings or data in a table. It may contain table header cells and table data cells (structure types TH and TD). |
| static [Warichu](./warichu/) |  |
| static [WP](./wp/) | (Warichu punctuation) The punctuation that surrounds the WT text. It contains text (usually a single LEFT or RIGHT PARENTHESIS or similar bracketing character). According to JIS X 4051-1995, the parentheses surrounding a warichu may be converted to a SPACE (nominally 1/4 EM in width) at the discretion of the formatter. |
| static [WT](./wt/) | (Warichu text) The smaller-size text of a warichu comment that is formatted into two lines and placed between surrounding WP elements. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
