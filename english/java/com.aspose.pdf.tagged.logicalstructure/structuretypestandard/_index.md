---
title: StructureTypeStandard
second_title: Aspose.PDF for Java API Reference
description: Represents Standard Structure Types.
type: docs
weight: 19
url: /java/com.aspose.pdf.tagged.logicalstructure/structuretypestandard/
---
**Inheritance:**
java.lang.Object
```
public final class StructureTypeStandard
```

Represents Standard Structure Types.
## Fields

| Field | Description |
| --- | --- |
| [Document](#Document) | (Document) A complete document. |
| [Part](#Part) | (Part) A large-scale division of a document. |
| [Art](#Art) | (Article) A relatively self-contained body of text constituting a single narrative or exposition. |
| [Sect](#Sect) | (Section) A container for grouping related content elements. |
| [Div](#Div) | (Division) A generic block-level element or group of elements. |
| [BlockQuote](#BlockQuote) | (Block quotation) A portion of text consisting of one or more paragraphs attributed to someone other than the author of the surrounding text. |
| [Caption](#Caption) | (Caption) A brief portion of text describing a table or figure. |
| [TOC](#TOC) | (Table of contents) A list made up of table of contents item entries (structure type TOCI) and/or other nested table of contents entries (TOC). |
| [TOCI](#TOCI) | (Table of contents item) An individual member of a table of contents. |
| [Index](#Index) | (Index) A sequence of entries containing identifying text accompanied by reference elements that point out occurrences of the specified text in the main body of a document. |
| [NonStruct](#NonStruct) | (Nonstructural element) A grouping element having no inherent structural significance; it serves solely for grouping purposes. |
| [Private](#Private) | (Private element) A grouping element containing private content belonging to the application producing it. |
| [P](#P) | (Paragraph) A low-level division of text. |
| [H](#H) | (Heading) A label for a subdivision of a document's content. |
| [H1](#H1) | Level 1 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| [H2](#H2) | Level 2 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| [H3](#H3) | Level 3 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| [H4](#H4) | Level 4 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| [H5](#H5) | Level 5 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| [H6](#H6) | Level 6 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting. |
| [L](#L) | (List) A sequence of items of like meaning and importance. |
| [LI](#LI) | (List item) An individual member of a list. |
| [Lbl](#Lbl) | (Label) A name or number that distinguishes a given item from others in the same list or other group of like items. |
| [LBody](#LBody) | (List body) The descriptive content of a list item. |
| [Table](#Table) | (Table) A two-dimensional layout of rectangular data cells, possibly having a complex substructure. |
| [THead](#THead) | (Table header row group; PDF 1.5) A group of rows that constitute the header of a table. |
| [TBody](#TBody) | (Table body row group; PDF 1.5) A group of rows that constitute the main body portion of a table. |
| [TFoot](#TFoot) | (Table footer row group; PDF 1.5) A group of rows that constitute the footer of a table. |
| [TR](#TR) | (Table row) A row of headings or data in a table. |
| [TH](#TH) | (Table header cell) A table cell containing header text describing one or more rows or columns of the table. |
| [TD](#TD) | (Table data cell) A table cell containing data that is part of the table's content. |
| [Span](#Span) | (Span) A generic inline portion of text having no particular inherent characteristics. |
| [Quote](#Quote) | (Quotation) An inline portion of text attributed to someone other than the author of the surrounding text. |
| [Note](#Note) | (Note) An item of explanatory text, such as a footnote or an endnote, that is referred to from within the body of the document. |
| [Reference](#Reference) | (Reference) A citation to content elsewhere in the document. |
| [BibEntry](#BibEntry) | (Bibliography entry) A reference identifying the external source of some cited content. |
| [Code](#Code) | (Code) A fragment of computer program text. |
| [Link](#Link) | (Link) An association between a portion of the ILSE's content and a corresponding link annotation or annotations. |
| [Annot](#Annot) | (Annotation; PDF 1.5) An association between a portion of the ILSE's content and a corresponding PDF annotation. |
| [Ruby](#Ruby) | (Ruby; PDF 1.5) A side-note (annotation) written in a smaller text size and placed adjacent to the base text to which it refers. |
| [RB](#RB) | (Ruby base text) The full-size text to which the ruby annotation is applied. |
| [RT](#RT) | (Ruby annotation text) The smaller-size text that shall be placed adjacent to the ruby base text. |
| [RP](#RP) | (Ruby punctuation) Punctuation surrounding the ruby annotation text. |
| [Warichu](#Warichu) | (Warichu; PDF 1.5) A comment or annotation in a smaller text size and formatted onto two smaller lines within the height of the containing text line and placed following (inline) the base text to which it refers. |
| [WT](#WT) | (Warichu text) The smaller-size text of a warichu comment that is formatted into two lines and placed between surrounding WP elements. |
| [WP](#WP) | (Warichu punctuation) The punctuation that surrounds the WT text. |
| [Figure](#Figure) | (Figure) An item of graphical content. |
| [Formula](#Formula) | (Formula) A mathematical formula. |
| [Form](#Form) | (Form) A widget annotation representing an interactive form field. |
## Methods

| Method | Description |
| --- | --- |
| [getTag()](#getTag--) | Gets tag name of  StructureElement . |
| [getCategory()](#getCategory--) | Gets category of Standard Structure Type. |
| [to_StructureTypeStandard(String tag)](#to-StructureTypeStandard-java.lang.String-) | Performs an explicit conversion from String to [StructureTypeStandard](../../com.aspose.pdf.tagged.logicalstructure/structuretypestandard). |
| [toString()](#toString--) | Returns a string that represents the current object. |
| [canBeAppended(StructureTypeStandard structureType)](#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-) |  |
### Document {#Document}
```
public static final StructureTypeStandard Document
```


(Document) A complete document. This is the root element of any structure tree containing multiple parts or multiple articles.

### Part {#Part}
```
public static final StructureTypeStandard Part
```


(Part) A large-scale division of a document. This type of element is appropriate for grouping articles or sections.

### Art {#Art}
```
public static final StructureTypeStandard Art
```


(Article) A relatively self-contained body of text constituting a single narrative or exposition. Articles should be disjoint; that is, they should not contain other articles as constituent elements.

### Sect {#Sect}
```
public static final StructureTypeStandard Sect
```


(Section) A container for grouping related content elements.

### Div {#Div}
```
public static final StructureTypeStandard Div
```


(Division) A generic block-level element or group of elements.

### BlockQuote {#BlockQuote}
```
public static final StructureTypeStandard BlockQuote
```


(Block quotation) A portion of text consisting of one or more paragraphs attributed to someone other than the author of the surrounding text.

### Caption {#Caption}
```
public static final StructureTypeStandard Caption
```


(Caption) A brief portion of text describing a table or figure.

### TOC {#TOC}
```
public static final StructureTypeStandard TOC
```


(Table of contents) A list made up of table of contents item entries (structure type TOCI) and/or other nested table of contents entries (TOC).

A TOC entry that includes only TOCI entries represents a flat hierarchy. A TOC entry that includes other nested TOC entries (and possibly TOCI entries) represents a more complex hierarchy.Ideally, the hierarchy of a top level TOC entry reflects the structure of the main body of the document.

### TOCI {#TOCI}
```
public static final StructureTypeStandard TOCI
```


(Table of contents item) An individual member of a table of contents. This entry\\u2019s children may be any of the following structure types:

Lbl - A label

Reference - A reference to the title and the page number

NonStruct - Non-structure elements for wrapping a leader artifact

P - Descriptive text

TOC - Table of content elements for hierarchical tables of content, as described for the TOC entry

### Index {#Index}
```
public static final StructureTypeStandard Index
```


(Index) A sequence of entries containing identifying text accompanied by reference elements that point out occurrences of the specified text in the main body of a document.

### NonStruct {#NonStruct}
```
public static final StructureTypeStandard NonStruct
```


(Nonstructural element) A grouping element having no inherent structural significance; it serves solely for grouping purposes. This type of element differs from a division (structure type Div) in that it shall not be interpreted or exported to other document formats; however, its descendants shall be processed normally.

### Private {#Private}
```
public static final StructureTypeStandard Private
```


(Private element) A grouping element containing private content belonging to the application producing it. The structural significance of this type of element is unspecified and shall be determined entirely by the conforming writer. Neither the Private element nor any of its descendants shall be interpreted or exported to other document formats.

### P {#P}
```
public static final StructureTypeStandard P
```


(Paragraph) A low-level division of text.

### H {#H}
```
public static final StructureTypeStandard H
```


(Heading) A label for a subdivision of a document's content. It should be the first child of the division that it heads.

### H1 {#H1}
```
public static final StructureTypeStandard H1
```


Level 1 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting.

### H2 {#H2}
```
public static final StructureTypeStandard H2
```


Level 2 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting.

### H3 {#H3}
```
public static final StructureTypeStandard H3
```


Level 3 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting.

### H4 {#H4}
```
public static final StructureTypeStandard H4
```


Level 4 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting.

### H5 {#H5}
```
public static final StructureTypeStandard H5
```


Level 5 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting.

### H6 {#H6}
```
public static final StructureTypeStandard H6
```


Level 6 Heading, for use in conforming writers that cannot hierarchically nest their sections and thus cannot determine the level of a heading from its level of nesting.

### L {#L}
```
public static final StructureTypeStandard L
```


(List) A sequence of items of like meaning and importance. Its immediate children should be an optional caption (structure type Caption) followed by one or more list items (structure type LI).

### LI {#LI}
```
public static final StructureTypeStandard LI
```


(List item) An individual member of a list. Its children may be one or more labels, list bodies, or both (structure types Lbl or LBody).

### Lbl {#Lbl}
```
public static final StructureTypeStandard Lbl
```


(Label) A name or number that distinguishes a given item from others in the same list or other group of like items.

### LBody {#LBody}
```
public static final StructureTypeStandard LBody
```


(List body) The descriptive content of a list item. In a dictionary list, for example, it contains the definition of the term. It may either contain the content directly or have other BLSEs, perhaps including nested lists, as children.

### Table {#Table}
```
public static final StructureTypeStandard Table
```


(Table) A two-dimensional layout of rectangular data cells, possibly having a complex substructure. It contains either one or more table rows (structure type TR) as children; or an optional table head (structure type THead) followed by one or more table body elements (structure type TBody) and an optional table footer (structure type TFoot). In addition, a table may have a caption (structure type Caption) as its first or last child.

### THead {#THead}
```
public static final StructureTypeStandard THead
```


(Table header row group; PDF 1.5) A group of rows that constitute the header of a table. If the table is split across multiple pages, these rows may be redrawn at the top of each table fragment (although there is only one THead element).

### TBody {#TBody}
```
public static final StructureTypeStandard TBody
```


(Table body row group; PDF 1.5) A group of rows that constitute the main body portion of a table. If the table is split across multiple pages, the body area may be broken apart on a row boundary. A table may have multiple TBody elements to allow for the drawing of a border or background for a set of rows.

### TFoot {#TFoot}
```
public static final StructureTypeStandard TFoot
```


(Table footer row group; PDF 1.5) A group of rows that constitute the footer of a table. If the table is split across multiple pages, these rows may be redrawn at the bottom of each table fragment (although there is only one TFoot element.)

### TR {#TR}
```
public static final StructureTypeStandard TR
```


(Table row) A row of headings or data in a table. It may contain table header cells and table data cells (structure types TH and TD).

### TH {#TH}
```
public static final StructureTypeStandard TH
```


(Table header cell) A table cell containing header text describing one or more rows or columns of the table.

### TD {#TD}
```
public static final StructureTypeStandard TD
```


(Table data cell) A table cell containing data that is part of the table's content.

### Span {#Span}
```
public static final StructureTypeStandard Span
```


(Span) A generic inline portion of text having no particular inherent characteristics. It can be used, for example, to delimit a range of text with a given set of styling attributes.

### Quote {#Quote}
```
public static final StructureTypeStandard Quote
```


(Quotation) An inline portion of text attributed to someone other than the author of the surrounding text.

The quoted text should be contained inline within a single paragraph. This differs from the block-level element BlockQuote, which consists of one or more complete paragraphs (or other elements presented as if they were complete paragraphs).

### Note {#Note}
```
public static final StructureTypeStandard Note
```


(Note) An item of explanatory text, such as a footnote or an endnote, that is referred to from within the body of the document. It may have a label (structure type Lbl) as a child. The note may be included as a child of the structure element in the body text that refers to it, or it may be included elsewhere (such as in an endnotes section) and accessed by means of a reference (structure type Reference).

Tagged PDF does not prescribe the placement of footnotes in the page content order. They may be either inline or at the end of the page, at the discretion of theconforming writer.

### Reference {#Reference}
```
public static final StructureTypeStandard Reference
```


(Reference) A citation to content elsewhere in the document.

### BibEntry {#BibEntry}
```
public static final StructureTypeStandard BibEntry
```


(Bibliography entry) A reference identifying the external source of some cited content. It may contain a label (structure type Lbl) as a child.

Although a bibliography entry is likely to include component parts identifying the cited content's author, work, publisher, and so forth, no standard structure types are defined at this level of detail.

### Code {#Code}
```
public static final StructureTypeStandard Code
```


(Code) A fragment of computer program text.

### Link {#Link}
```
public static final StructureTypeStandard Link
```


(Link) An association between a portion of the ILSE's content and a corresponding link annotation or annotations. Its children should be one or more content items or child ILSEs and one or more object references identifying the associated link annotations.

### Annot {#Annot}
```
public static final StructureTypeStandard Annot
```


(Annotation; PDF 1.5) An association between a portion of the ILSE's content and a corresponding PDF annotation. Annot shall be used for all PDF annotations except link annotations and widget annotations.

### Ruby {#Ruby}
```
public static final StructureTypeStandard Ruby
```


(Ruby; PDF 1.5) A side-note (annotation) written in a smaller text size and placed adjacent to the base text to which it refers. A Ruby element may also contain the RB, RT, and RP elements.

(Ruby) The wrapper around the entire ruby assembly. It shall contain one RB element followed by either an RT element or a three-element group consisting of RP, RT, and RP. Ruby elements and their content elements shall not break across multiple lines.

### RB {#RB}
```
public static final StructureTypeStandard RB
```


(Ruby base text) The full-size text to which the ruby annotation is applied. RB may contain text, other inline elements, or a mixture of both. It may have the RubyAlignattribute.

### RT {#RT}
```
public static final StructureTypeStandard RT
```


(Ruby annotation text) The smaller-size text that shall be placed adjacent to the ruby base text. It may contain text, other inline elements, or a mixture of both. It may have the RubyAlign and RubyPosition attributes.

### RP {#RP}
```
public static final StructureTypeStandard RP
```


(Ruby punctuation) Punctuation surrounding the ruby annotation text. It is used only when a ruby annotation cannot be properly formatted in a ruby style and instead is formatted as a normal comment, or when it is formatted as a warichu. It contains text (usually a single LEFT or RIGHT PARENTHESIS or similar bracketing character).

### Warichu {#Warichu}
```
public static final StructureTypeStandard Warichu
```


(Warichu; PDF 1.5) A comment or annotation in a smaller text size and formatted onto two smaller lines within the height of the containing text line and placed following (inline) the base text to which it refers. A Warichu element may also contain the WT and WP elements.

(Warichu) The wrapper around the entire warichu assembly. It may contain a three-element group consisting of WP, WT, and WP. Warichu elements (and their content elements) may wrap across multiple lines, according to the warichu breaking rules described in the Japanese Industrial Standard (JIS) X 4051-1995.

### WT {#WT}
```
public static final StructureTypeStandard WT
```


(Warichu text) The smaller-size text of a warichu comment that is formatted into two lines and placed between surrounding WP elements.

### WP {#WP}
```
public static final StructureTypeStandard WP
```


(Warichu punctuation) The punctuation that surrounds the WT text. It contains text (usually a single LEFT or RIGHT PARENTHESIS or similar bracketing character). According to JIS X 4051-1995, the parentheses surrounding a warichu may be converted to a SPACE (nominally 1/4 EM in width) at the discretion of the formatter.

### Figure {#Figure}
```
public static final StructureTypeStandard Figure
```


(Figure) An item of graphical content. Its placement may be specified with the Placement layout attribute.

### Formula {#Formula}
```
public static final StructureTypeStandard Formula
```


(Formula) A mathematical formula.

This structure type is useful only for identifying an entire content element as a formula. No standard structure types are defined for identifying individual components within the formula. From a formatting standpoint, the formula shall be treated similarly to a figure (structure type Figure).

### Form {#Form}
```
public static final StructureTypeStandard Form
```


(Form) A widget annotation representing an interactive form field.

### getTag() {#getTag--}
```
public final String getTag()
```


Gets tag name of  StructureElement .

**Returns:**
java.lang.String - Tag name of  StructureElement .
### getCategory() {#getCategory--}
```
public final StructureTypeCategory getCategory()
```


Gets category of Standard Structure Type.

**Returns:**
[StructureTypeCategory](../../com.aspose.pdf.tagged.logicalstructure/structuretypecategory) - Value: Category of Standard Structure Type.
### to_StructureTypeStandard(String tag) {#to-StructureTypeStandard-java.lang.String-}
```
public static StructureTypeStandard to_StructureTypeStandard(String tag)
```


Performs an explicit conversion from String to [StructureTypeStandard](../../com.aspose.pdf.tagged.logicalstructure/structuretypestandard).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | java.lang.String | The tag name. |

**Returns:**
[StructureTypeStandard](../../com.aspose.pdf.tagged.logicalstructure/structuretypestandard) - The result of the conversion.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - String that represents the current object.
### canBeAppended(StructureTypeStandard structureType) {#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-}
```
public final boolean canBeAppended(StructureTypeStandard structureType)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| structureType | [StructureTypeStandard](../../com.aspose.pdf.tagged.logicalstructure/structuretypestandard) |  |

**Returns:**
boolean
