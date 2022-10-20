---
title: TextFragment
second_title: Aspose.PDF for .NET API Reference
description: Represents fragment of Pdf text.
type: docs
weight: 7110
url: /net/aspose.pdf.text/textfragment/
---
## TextFragment class

Represents fragment of Pdf text.

```csharp
public class TextFragment : BaseParagraph
```

## Constructors

| Name | Description |
| --- | --- |
| [TextFragment](textfragment#constructor)() | Initializes new instance of the [`TextFragment`](../textfragment) object. |
| [TextFragment](textfragment#constructor_2)(string) | Creates [`TextFragment`](../textfragment) object with single [`TextSegment`](../textsegment) object inside. Specifies text string inside the segment. |
| [TextFragment](textfragment#constructor_1)(TabStops) | Initializes new instance of the [`TextFragment`](../textfragment) object with predefined [`TabStops`](../tabstops) positions. |
| [TextFragment](textfragment#constructor_3)(string, TabStops) | Creates [`TextFragment`](../textfragment) object with single [`TextSegment`](../textsegment) object inside and predefined [`TabStops`](../tabstops) positions. |

## Properties

| Name | Description |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textfragment/baselineposition) { get; set; } | Gets text position for text, represented with [`TextFragment`](../textfragment) object. The YIndent of the Position structure represents baseline coordinate of the text fragment. |
| [EndNote](../../aspose.pdf.text/textfragment/endnote) { get; set; } | Gets or sets the paragraph end note.(for pdf generation only) |
| [FootNote](../../aspose.pdf.text/textfragment/footnote) { get; set; } | Gets or sets the paragraph foot note.(for pdf generation only) |
| [Form](../../aspose.pdf.text/textfragment/form) { get; } | Gets form object that contains the TextFragment |
| override [HorizontalAlignment](../../aspose.pdf.text/textfragment/horizontalalignment) { get; set; } | Gets or sets a horizontal alignment of text fragment. |
| override [Hyperlink](../../aspose.pdf.text/textfragment/hyperlink) { set; } | Sets the fragment hyperlink |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Gets or sets a paragraph is inline. Default is false.(for pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation) |
| [Page](../../aspose.pdf.text/textfragment/page) { get; } | Gets page that contains the TextFragment |
| [Position](../../aspose.pdf.text/textfragment/position) { get; set; } | Gets or sets text position for text, represented with [`TextFragment`](../textfragment) object. |
| [Rectangle](../../aspose.pdf.text/textfragment/rectangle) { get; } | Gets rectangle of the TextFragment |
| [ReplaceOptions](../../aspose.pdf.text/textfragment/replaceoptions) { get; } | Gets text replace options. The options define behavior when fragment text is replaced to more short/long. |
| [Segments](../../aspose.pdf.text/textfragment/segments) { get; set; } | Gets text segments for current [`TextFragment`](../textfragment). |
| [Text](../../aspose.pdf.text/textfragment/text) { get; set; } | Gets or sets String text object that the [`TextFragment`](../textfragment) object represents. |
| [TextState](../../aspose.pdf.text/textfragment/textstate) { get; } | Gets or sets text state for the text that [`TextFragment`](../textfragment) object represents. |
| override [VerticalAlignment](../../aspose.pdf.text/textfragment/verticalalignment) { get; set; } | Gets or sets a vertical alignment of text fragment. |
| [WrapLinesCount](../../aspose.pdf.text/textfragment/wraplinescount) { get; set; } | Gets or sets wrap lines count for this paragraph(for pdf generation only) |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](../../aspose.pdf.text/textfragment/clone)() | Clone the fragment. |
| virtual [CloneWithSegments](../../aspose.pdf.text/textfragment/clonewithsegments)() | Clone the fragment with all segments. |
| [IsolateTextSegments](../../aspose.pdf.text/textfragment/isolatetextsegments)(int, int) | Gets [`TextSegment`](../textsegment)(s) representing specified part of the [`TextFragment`](../textfragment) text. |

### Remarks

In a few words, [`TextFragment`](../textfragment) object contains list of [`TextSegment`](../textsegment) objects. In details: Text of pdf document in Pdf is represented by two basic objects: [`TextFragment`](../textfragment) and [`TextSegment`](../textsegment) The differences between them is mostly context-dependent. Let's consider following scenario. User searches text "hello world" to operate with it, change it's properties, look etc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Phisycally pdf text's representation is very complex. The text "hello world" may consist of several phisycally independent text segments. The Aspose.Pdf text model basically establishes that [`TextFragment`](../textfragment) object provides single logic operation set over physical [`TextSegment`](../textsegment) objects set that represent user's query. In text search scenario, [`TextFragment`](../textfragment) is logical "hello world" text representation, and [`TextSegment`](../textsegment) object collection represents all physical segments that construct "hello world" text object. So, [`TextFragment`](../textfragment) is close to logical text representation. And [`TextSegment`](../textsegment) is close to physical text representation. Obviously each [`TextSegment`](../textsegment) object may have it's own font, coloring, positioning properties. [`TextFragment`](../textfragment) provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile [`TextSegment`](../textsegment) objects are accessible and users are able to operate with [`TextSegment`](../textsegment) objects independently. Note that changing TextFragment properties may change inner [`Segments`](./segments) collection because TextFragment is an aggregate object and it may rearrange internal segments or merge them into single segment. If your requirement is to leave the [`Segments`](./segments) collection unchanged, please change inner segments individually.

### Examples

The example demonstrates how to find text on the first PDF document page and replace the text and it's font.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change text and font of the first text occurrence
absorber.TextFragments[1].Text = "hi world";
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* class [BaseParagraph](../../aspose.pdf/baseparagraph)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
