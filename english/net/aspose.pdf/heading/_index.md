---
title: "Heading Class"
linktitle: "Heading"
articleTitle: "Heading"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Heading class. Represents heading."
type: docs
weight: 1090
url: "/net/aspose.pdf/heading/"
keywords: "Heading, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Heading class

Represents heading.

```csharp
public sealed class Heading : TextFragment
```

## Constructors

| Name | Description |
| --- | --- |
| [Heading](./heading/#constructor)(*int*) | Initializes a new instance of the Cell class. |

## Properties

| Name | Description |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Gets text position for text, represented with [`TextFragment`](../../aspose.pdf.text/textfragment/) object. *(Inherited from TextFragment)* |
| [DestinationPage](./destinationpage/) { get; set; } | Gets the destination page. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Gets or sets the paragraph end note.(for pdf generation only). *(Inherited from TextFragment)* |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Gets or sets the paragraph foot note.(for pdf generation only). *(Inherited from TextFragment)* |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Gets form object that contains the TextFragment. *(Inherited from TextFragment)* |
| [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Gets or sets a horizontal alignment of text fragment. *(Inherited from TextFragment)* |
| [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Sets the fragment hyperlink. *(Inherited from TextFragment)* |
| [IsAutoSequence](./isautosequence/) { get; set; } | Gets the heading should be numered automatically. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. *(Inherited from BaseParagraph)* |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gets or sets a paragraph is inline. *(Inherited from BaseParagraph)* |
| [IsInList](./isinlist/) { get; set; } | Gets the heading should be in toc list. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. *(Inherited from BaseParagraph)* |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. *(Inherited from BaseParagraph)* |
| [Level](./level/) { get; set; } | Gets the level. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation). *(Inherited from BaseParagraph)* |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Gets page that contains the TextFragment. *(Inherited from TextFragment)* |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Gets or sets text position for text, represented with [`TextFragment`](../../aspose.pdf.text/textfragment/) object. *(Inherited from TextFragment)* |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Gets rectangle of the TextFragment. *(Inherited from TextFragment)* |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Gets text replace options. The options define behavior when fragment text is replaced to more short/long. *(Inherited from TextFragment)* |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Gets text segments for current [`TextFragment`](../../aspose.pdf.text/textfragment/). *(Inherited from TextFragment)* |
| [StartNumber](./startnumber/) { get; set; } | Gets the heading start number. |
| [Style](./style/) { get; set; } | Gets or sets style. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Gets or sets `String` text object that the [`TextFragment`](../../aspose.pdf.text/textfragment/) object represents. *(Inherited from TextFragment)* |
| [TextEditOptions](../../aspose.pdf.text/textfragment/texteditoptions/) { get; set; } | Gets or sets text edit options. The options define special behavior when requested symbol cannot be written with font. *(Inherited from TextFragment)* |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Gets or sets text state for the text that [`TextFragment`](../../aspose.pdf.text/textfragment/) object represents. *(Inherited from TextFragment)* |
| [TocPage](./tocpage/) { get; set; } | Gets the page that contains this heading. |
| [Top](./top/) { get; set; } | Gets the top Y of this headings. |
| [UserLabel](./userlabel/) { get; set; } | Gets or sets user label. |
| [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Gets or sets a vertical alignment of text fragment. *(Inherited from TextFragment)* |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Gets or sets wrap lines count for this paragraph(for pdf generation only). *(Inherited from TextFragment)* |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex. *(Inherited from BaseParagraph)* |

## Methods

| Name | Description |
| --- | --- |
| [Clone](./clone/) | Clone the heading. |
| [CloneWithSegments](./clonewithsegments/) | Clone the heading with all segments. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(*int, int*) | Gets [`TextSegment`](../../aspose.pdf.text/textsegment/)(s) representing specified part of the [`TextFragment`](../../aspose.pdf.text/textfragment/) text. *(Inherited from TextFragment)* |

### See Also

* class [TextFragment](../../aspose.pdf.text/textfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

