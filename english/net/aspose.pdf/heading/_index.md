---
title: Class Heading
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Heading class. Represents heading
type: docs
weight: 4100
url: /net/aspose.pdf/heading/
---
## Heading class

Represents heading.

```csharp
public sealed class Heading : TextFragment
```

## Constructors

| Name | Description |
| --- | --- |
| [Heading](heading/)(int) | Initializes a new instance of the Cell class. |

## Properties

| Name | Description |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition/) { get; set; } | Gets text position for text, represented with [`TextFragment`](../../aspose.pdf.text/textfragment/) object. The YIndent of the Position structure represents baseline coordinate of the text fragment. |
| [DestinationPage](../../aspose.pdf/heading/destinationpage/) { get; set; } | Gets the destination page. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote/) { get; set; } | Gets or sets the paragraph end note.(for pdf generation only) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote/) { get; set; } | Gets or sets the paragraph foot note.(for pdf generation only) |
| [Form](../../aspose.pdf.text/textfragment/form/) { get; } | Gets form object that contains the TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment/) { get; set; } | Gets or sets a horizontal alignment of text fragment. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink/) { set; } | Sets the fragment hyperlink |
| [IsAutoSequence](../../aspose.pdf/heading/isautosequence/) { get; set; } | Gets the heading should be numered automatically. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gets or sets a paragraph is inline. Default is false.(for pdf generation) |
| [IsInList](../../aspose.pdf/heading/isinlist/) { get; set; } | Gets the heading should be in toc list. |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [Level](../../aspose.pdf/heading/level/) { get; set; } | Gets the level. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation) |
| [Page](../../aspose.pdf.text/textfragment/page/) { get; } | Gets page that contains the TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position/) { get; set; } | Gets or sets text position for text, represented with [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle/) { get; } | Gets rectangle of the TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions/) { get; } | Gets text replace options. The options define behavior when fragment text is replaced to more short/long. |
| [Segments](../../aspose.pdf.text/textfragment/segments/) { get; set; } | Gets text segments for current [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [StartNumber](../../aspose.pdf/heading/startnumber/) { get; set; } | Gets the heading start number. |
| [Style](../../aspose.pdf/heading/style/) { get; set; } | Gets or sets style. |
| [Text](../../aspose.pdf.text/textfragment/text/) { get; set; } | Gets or sets String text object that the [`TextFragment`](../../aspose.pdf.text/textfragment/) object represents. |
| [TextState](../../aspose.pdf.text/textfragment/textstate/) { get; } | Gets or sets text state for the text that [`TextFragment`](../../aspose.pdf.text/textfragment/) object represents. |
| [TocPage](../../aspose.pdf/heading/tocpage/) { get; set; } | Gets the page that contains this heading. |
| [Top](../../aspose.pdf/heading/top/) { get; set; } | Gets the top Y of this headings. |
| [UserLabel](../../aspose.pdf/heading/userlabel/) { get; set; } | Gets or sets user label. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment/) { get; set; } | Gets or sets a vertical alignment of text fragment. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount/) { get; set; } | Gets or sets wrap lines count for this paragraph(for pdf generation only) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/heading/clone/)() | Clone the heading. |
| override [CloneWithSegments](../../aspose.pdf/heading/clonewithsegments/)() | Clone the heading with all segments. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments/)(int, int) | Gets [`TextSegment`](../../aspose.pdf.text/textsegment/)(s) representing specified part of the [`TextFragment`](../../aspose.pdf.text/textfragment/) text. |

### See Also

* class [TextFragment](../../aspose.pdf.text/textfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


