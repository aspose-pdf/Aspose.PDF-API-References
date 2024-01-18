---
title: Class TextSegment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextSegment class. Represents segment of Pdf text
type: docs
weight: 8420
url: /net/aspose.pdf.text/textsegment/
---
## TextSegment class

Represents segment of Pdf text.

```csharp
public sealed class TextSegment
```

## Constructors

| Name | Description |
| --- | --- |
| [TextSegment](textsegment/#constructor)() | Creates TextSegment object. |
| [TextSegment](textsegment/#constructor_1)(string) | Creates TextSegment object. |

## Properties

| Name | Description |
| --- | --- |
| [BaselinePosition](../../aspose.pdf.text/textsegment/baselineposition/) { get; set; } | Gets text position for text, represented with `TextSegment` object. The YIndent of the Position structure represents baseline coordinate of the text segment. |
| [Characters](../../aspose.pdf.text/textsegment/characters/) { get; } | Gets collection of CharInfo objects that represent information on characters in the text segment. |
| [EndCharIndex](../../aspose.pdf.text/textsegment/endcharindex/) { get; } | Gets ending character index of current segment in the show text operator (Tj, TJ) segment. |
| [Hyperlink](../../aspose.pdf.text/textsegment/hyperlink/) { get; set; } | Gets or sets the segment hyperlink(for pdf generator). |
| [Position](../../aspose.pdf.text/textsegment/position/) { get; set; } | Gets text position for text, represented with `TextSegment` object. |
| [Rectangle](../../aspose.pdf.text/textsegment/rectangle/) { get; } | Gets rectangle of the TextSegment |
| [StartCharIndex](../../aspose.pdf.text/textsegment/startcharindex/) { get; } | Gets starting character index of current segment in the show text operator (Tj, TJ) segment. |
| [Text](../../aspose.pdf.text/textsegment/text/) { get; set; } | Gets or sets String text object that the `TextSegment` object represents. |
| [TextEditOptions](../../aspose.pdf.text/textsegment/texteditoptions/) { get; set; } | Gets or sets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [TextState](../../aspose.pdf.text/textsegment/textstate/) { get; set; } | Gets or sets text state for the text that `TextSegment` object represents. |

## Methods

| Name | Description |
| --- | --- |
| static [MyHtmlEncode](../../aspose.pdf.text/textsegment/myhtmlencode/)(string) | Encodes string as html. |

## Remarks

In a few words, `TextSegment` objects are children of [`TextFragment`](../textfragment/) object. In details: Text of pdf document in Pdf is represented by two basic objects: [`TextFragment`](../textfragment/) and `TextSegment` The differences between them is mostly context-dependent. Let's consider following scenario. User searches text "hello world" to operate with it, change it's properties, look etc.

```csharp
Document doc = new Document(docFile);
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
doc.Pages[1].Accept(absorber);
```

Phisycally pdf text's representation is very complex. The text "hello world" may consist of several phisycally independent text segments. The Aspose.Pdf text model basically establishes that [`TextFragment`](../textfragment/) object provides single logic operation set over physical `TextSegment` objects set that represent user's query. In text search scenario, [`TextFragment`](../textfragment/) is logical "hello world" text representation, and `TextSegment` object collection represents all physical segments that construct "hello world" text object. So, [`TextFragment`](../textfragment/) is close to logical text representation. And `TextSegment` is close to physical text representation. Obviously each `TextSegment` object may have it's own font, coloring, positioning properties. [`TextFragment`](../textfragment/) provides simple way to change text with it's properties: set font, set font size, set font color etc. Meanwhile `TextSegment` objects are accessible and users are able to operate with `TextSegment` objects independently.

## Examples

The example demonstrates how to change text color and font size of the text with [`TextState`](./textstate/) object of `TextSegment` object.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text segment of the first text occurrence
absorber.TextFragments[1].Segments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


