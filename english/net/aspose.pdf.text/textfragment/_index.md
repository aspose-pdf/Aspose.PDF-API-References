---
title: "TextFragment Class"
linktitle: "TextFragment"
articleTitle: "TextFragment"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.TextFragment class. Represents fragment of Pdf text."
type: docs
weight: 550
url: "/net/aspose.pdf.text/textfragment/"
keywords: "TextFragment, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextFragment class

Represents fragment of Pdf text.

```csharp
public class TextFragment : BaseParagraph
```

## Constructors

| Name | Description |
| --- | --- |
| [TextFragment](./textfragment/#constructor) | Initializes new instance of the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [TextFragment](./textfragment/#constructor_1)(*[TabStops](../../aspose.pdf.text/tabstops/)*) | Initializes new instance of the [`TextFragment`](../../aspose.pdf.text/textfragment/) object with predefined [`TabStops`](../../aspose.pdf.text/tabstops/) positions. |
| [TextFragment](./textfragment/#constructor_2)(*string*) | Creates [`TextFragment`](../../aspose.pdf.text/textfragment/) object with single [`TextSegment`](../../aspose.pdf.text/textsegment/) object inside. |
| [TextFragment](./textfragment/#constructor_3)(*string, [TabStops](../../aspose.pdf.text/tabstops/)*) | Creates [`TextFragment`](../../aspose.pdf.text/textfragment/) object with single [`TextSegment`](../../aspose.pdf.text/textsegment/) object inside and predefined [`TabStops`](../../aspose.pdf.text/tabstops/) positions. |

## Properties

| Name | Description |
| --- | --- |
| [BaselinePosition](./baselineposition/) { get; set; } | Gets text position for text, represented with [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [EndNote](./endnote/) { get; set; } | Gets or sets the paragraph end note.(for pdf generation only). |
| [FootNote](./footnote/) { get; set; } | Gets or sets the paragraph foot note.(for pdf generation only). |
| [Form](./form/) { get; } | Gets form object that contains the TextFragment. |
| [HorizontalAlignment](./horizontalalignment/) { get; set; } | Gets or sets a horizontal alignment of text fragment. |
| [Hyperlink](./hyperlink/) { set; } | Sets the fragment hyperlink. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. *(Inherited from BaseParagraph)* |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gets or sets a paragraph is inline. *(Inherited from BaseParagraph)* |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. *(Inherited from BaseParagraph)* |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. *(Inherited from BaseParagraph)* |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation). *(Inherited from BaseParagraph)* |
| [Page](./page/) { get; } | Gets page that contains the TextFragment. |
| [Position](./position/) { get; set; } | Gets or sets text position for text, represented with [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [Rectangle](./rectangle/) { get; } | Gets rectangle of the TextFragment. |
| [ReplaceOptions](./replaceoptions/) { get; } | Gets text replace options. The options define behavior when fragment text is replaced to more short/long. |
| [Segments](./segments/) { get; set; } | Gets text segments for current [`TextFragment`](../../aspose.pdf.text/textfragment/). |
| [Text](./text/) { get; set; } | Gets or sets `String` text object that the [`TextFragment`](../../aspose.pdf.text/textfragment/) object represents. |
| [TextEditOptions](./texteditoptions/) { get; set; } | Gets or sets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [TextState](./textstate/) { get; } | Gets or sets text state for the text that [`TextFragment`](../../aspose.pdf.text/textfragment/) object represents. |
| [VerticalAlignment](./verticalalignment/) { get; set; } | Gets or sets a vertical alignment of text fragment. |
| [WrapLinesCount](./wraplinescount/) { get; set; } | Gets or sets wrap lines count for this paragraph(for pdf generation only). |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex. *(Inherited from BaseParagraph)* |

## Methods

| Name | Description |
| --- | --- |
| [Clone](./clone/) | Clone the fragment. |
| [CloneWithSegments](./clonewithsegments/) | Clone the fragment with all segments. |
| [IsolateTextSegments](./isolatetextsegments/)(*int, int*) | Gets [`TextSegment`](../../aspose.pdf.text/textsegment/)(s) representing specified part of the [`TextFragment`](../../aspose.pdf.text/textfragment/) text. |

## Remarks

In a few words, [`TextFragment`](../../aspose.pdf.text/textfragment/) object contains list of [`TextSegment`](../../aspose.pdf.text/textsegment/) objects.
 
 In details:
 Text of pdf document in `Pdf` is represented by two basic objects: [`TextFragment`](../../aspose.pdf.text/textfragment/) and [`TextSegment`](../../aspose.pdf.text/textsegment/)
 
 The differences between them is mostly context-dependent.
 
 Let's consider following scenario. User searches text "hello world" to operate with it, change it's properties, look etc.
 
 Document doc = new Document(docFile);
 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
 doc.Pages[1].Accept(absorber);
 
 Phisycally pdf text's representation is very complex.
 The text "hello world" may consist of several phisycally independent text segments.
 
 The Aspose.Pdf text model basically establishes that [`TextFragment`](../../aspose.pdf.text/textfragment/) object
 provides single logic operation set over physical [`TextSegment`](../../aspose.pdf.text/textsegment/) objects set that represent user's query.
 
 In text search scenario, [`TextFragment`](../../aspose.pdf.text/textfragment/) is logical "hello world" text representation,
 and [`TextSegment`](../../aspose.pdf.text/textsegment/) object collection represents all physical segments that construct "hello world" text object.
 
 So, [`TextFragment`](../../aspose.pdf.text/textfragment/) is close to logical text representation.
 And [`TextSegment`](../../aspose.pdf.text/textsegment/) is close to physical text representation.
 
 Obviously each [`TextSegment`](../../aspose.pdf.text/textsegment/) object may have it's own font, coloring, positioning properties.
 
 [`TextFragment`](../../aspose.pdf.text/textfragment/) provides simple way to change text with it's properties: set font, set font size, set font color etc.
 Meanwhile [`TextSegment`](../../aspose.pdf.text/textsegment/) objects are accessible and users are able to operate with [`TextSegment`](../../aspose.pdf.text/textsegment/) objects independently.
 
 Note that changing TextFragment properties may change inner `Segments` collection because TextFragment is an aggregate object 
 and it may rearrange internal segments or merge them into single segment.
 If your requirement is to leave the `Segments` collection unchanged, please change inner segments individually.

### See Also

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

