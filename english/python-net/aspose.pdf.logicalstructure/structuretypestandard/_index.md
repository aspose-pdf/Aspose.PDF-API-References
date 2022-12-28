---
title: StructureTypeStandard
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents Standard Structure Types.
type: docs
weight: 560
url: /python-net/aspose.pdf.logicalstructure/structuretypestandard/
---

## StructureTypeStandard class

Represents Standard Structure Types.

The StructureTypeStandard type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|tag|Gets tag name of [StructureElement](/pdf/python-net/aspose.pdf.logicalstructure/structureelement/).|
|category|Gets category of Standard Structure Type.|
|DOCUMENT|(Document) A complete document. This is the root element of any structure tree containing multiple parts or multiple articles.|
|PART|(Part) A large-scale division of a document. This type of element is appropriate for grouping articles or sections.|
|ART|(Article) A relatively self-contained body of text constituting a single narrative or exposition. Articles should be disjoint; that is, they should not contain other articles as constituent elements.|
|SECT|(Section) A container for grouping related content elements.|
|DIV|(Division) A generic block-level element or group of elements.|
|BLOCK_QUOTE|(Block quotation) A portion of text consisting of one or more paragraphs attributed to someone other than the author of the surrounding text.|
|CAPTION|(Caption) A brief portion of text describing a table or figure.|
|TOC|(Table of contents) A list made up of table of contents item entries (structure type TOCI) and/or other nested table of contents entries (TOC).|
|TOCI|(Table of contents item) An individual member of a table of contents. This entry’s children may be any of the following structure types:|
|INDEX|(Index) A sequence of entries containing identifying text accompanied by reference elements that point out occurrences of the specified text in the main body of a document.|
|NON_STRUCT|(Nonstructural element) A grouping element having no inherent structural significance; it serves solely for grouping purposes. This type of element differs from a division (structure type Div) in that it shall not be interpreted or exported to other document formats; however, its descendants shall be processed normally.|
|PRIVATE|(Private element) A grouping element containing private content belonging to the application producing it. The structural significance of this type of element is unspecified and shall be determined entirely by the conforming writer. Neither the Private element nor any of its descendants shall be interpreted or exported to other document formats.|
|P|(Paragraph) A low-level division of text.|
|H|(Heading) A label for a subdivision of a document's content. It should be the first child of the division that it heads.|
|H1|Level 1 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting.|
|H2|Level 2 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting.|
|H3|Level 3 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting.|
|H4|Level 4 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting.|
|H5|Level 5 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting.|
|H6|Level 6 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting.|
|L|(List) A sequence of items of like meaning and importance. Its immediate children should be an optional caption (structure type Caption) followed by one or more list items (structure type LI).|
|LI|(List item) An individual member of a list. Its children may be one or more labels, list bodies, or both (structure types Lbl or LBody).|
|LBL|(Label) A name or number that distinguishes a given item from others in the same list or other group of like items.|
|L_BODY|(List body) The descriptive content of a list item. In a dictionary list, for example, it contains the definition of the term. It may either contain the content directly or have other BLSEs, perhaps including nested lists, as children.|
|TABLE|(Table) A two-dimensional layout of rectangular data cells, possibly having a complex substructure. It contains either one or more table rows (structure type TR) as children; or an optional table head (structure type THead) followed by one or more table body elements (structure type TBody) and an optional table footer (structure type TFoot). In addition, a table may have a caption (structure type Caption) as its first or last child.|
|T_HEAD|(Table header row group; PDF 1.5) A group of rows that constitute the header of a table. If the table is split across multiple pages, these rows may be redrawn at the top of each table fragment (although there is only one THead element).|
|T_BODY|(Table body row group; PDF 1.5) A group of rows that constitute the main body portion of a table. If the table is split across multiple pages, the body area may be broken apart on a row boundary. A table may have multiple TBody elements to allow for the drawing of a border or background for a set of rows.|
|T_FOOT|(Table footer row group; PDF 1.5) A group of rows that constitute the footer of a table. If the table is split across multiple pages, these rows may be redrawn at the bottom of each table fragment (although there is only one TFoot element.)|
|TR|(Table row) A row of headings or data in a table. It may contain table header cells and table data cells (structure types TH and TD).|
|TH|(Table header cell) A table cell containing header text describing one or more rows or columns of the table.|
|TD|(Table data cell) A table cell containing data that is part of the table's content.|
|SPAN|(Span) A generic inline portion of text having no particular inherent characteristics. It can be used, for example, to delimit a range of text with a given set of styling attributes.|
|QUOTE|(Quotation) An inline portion of text attributed to someone other than the author of the surrounding text.|
|NOTE|(Note) An item of explanatory text, such as a footnote or an endnote, that is referred to from within the body of the document. It may have a label (structure type Lbl) as a child. The note may be included as a child of the structure element in the body text that refers to it, or it may be included elsewhere (such as in an endnotes section) and accessed by means of a reference (structure type Reference).|
|REFERENCE|(Reference) A citation to content elsewhere in the document.|
|BIB_ENTRY|(Bibliography entry) A reference identifying the external source of some cited content. It may contain a label (structure type Lbl) as a child.|
|CODE|(Code) A fragment of computer program text.|
|LINK|(Link) An association between a portion of the ILSE's content and a corresponding link annotation or annotations. Its children should be one or more content items or child ILSEs and one or more object references identifying the associated link annotations.|
|ANNOT|(Annotation; PDF 1.5) An association between a portion of the ILSE's content and a corresponding PDF annotation. Annot shall be used for all PDF annotations except link annotations and widget annotations.|
|RUBY|(Ruby; PDF 1.5) A side-note (annotation) written in a smaller text size and placed adjacent to the base text to which it refers. A Ruby element may also contain the RB, RT, and RP elements.|
|RB|(Ruby base text) The full-size text to which the ruby annotation is applied. RB may contain text, other inline elements, or a mixture of both. It may have the RubyAlignattribute.|
|RT|(Ruby annotation text) The smaller-size text that shall be placed adjacent to the ruby base text. It may contain text, other inline elements, or a mixture of both. It may have the RubyAlign and RubyPosition attributes.|
|RP|(Ruby punctuation) Punctuation surrounding the ruby annotation text. It is used only when a ruby annotation cannot be properly formatted in a ruby style and instead is formatted as a normal comment, or when it is formatted as a warichu. It contains text (usually a single LEFT or RIGHT PARENTHESIS or similar bracketing character).|
|WARICHU|(Warichu; PDF 1.5) A comment or annotation in a smaller text size and formatted onto two smaller lines within the height of the containing text line and placed following (inline) the base text to which it refers. A Warichu element may also contain the WT and WP elements.|
|WT|(Warichu text) The smaller-size text of a warichu comment that is formatted into two lines and placed between surrounding WP elements.|
|WP|(Warichu punctuation) The punctuation that surrounds the WT text. It contains text (usually a single LEFT or RIGHT PARENTHESIS or similar bracketing character). According to JIS X 4051-1995, the parentheses surrounding a warichu may be converted to a SPACE (nominally 1/4 EM in width) at the discretion of the formatter.|
|FIGURE|(Figure) An item of graphical content. Its placement may be specified with the Placement layout attribute.|
|FORMULA|(Formula) A mathematical formula.|
|FORM|(Form) A widget annotation representing an interactive form field.|

### See Also

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

