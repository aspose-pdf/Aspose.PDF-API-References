---
title: "TextSegment Class"
linktitle: "TextSegment"
articleTitle: "TextSegment"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.TextSegment class. Represents segment of Pdf text."
type: docs
weight: 670
url: "/net/aspose.pdf.text/textsegment/"
keywords: "TextSegment, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextSegment class

Represents segment of Pdf text.

```csharp
public sealed class TextSegment
```

## Constructors

| Name | Description |
| --- | --- |
| [TextSegment](./textsegment/#constructor) | Creates TextSegment object. |
| [TextSegment](./textsegment/#constructor_1)(*string*) | Creates TextSegment object. |

## Properties

| Name | Description |
| --- | --- |
| [BaselinePosition](./baselineposition/) { get; set; } | Gets text position for text, represented with [`TextSegment`](../../aspose.pdf.text/textsegment/) object. |
| [Characters](./characters/) { get; } | Gets collection of CharInfo objects that represent information on characters in the text segment. |
| [EndCharIndex](./endcharindex/) { get; } | Gets ending character index of current segment in the show text operator (Tj, TJ) segment. |
| [Hyperlink](./hyperlink/) { get; set; } | Gets or sets the segment hyperlink(for pdf generator). |
| [Position](./position/) { get; set; } | Gets text position for text, represented with [`TextSegment`](../../aspose.pdf.text/textsegment/) object. |
| [Rectangle](./rectangle/) { get; } | Gets rectangle of the TextSegment. |
| [StartCharIndex](./startcharindex/) { get; } | Gets starting character index of current segment in the show text operator (Tj, TJ) segment. |
| [Text](./text/) { get; set; } | Gets or sets `String` text object that the [`TextSegment`](../../aspose.pdf.text/textsegment/) object represents. |
| [TextEditOptions](./texteditoptions/) { get; set; } | Gets or sets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [TextState](./textstate/) { get; set; } | Gets or sets text state for the text that [`TextSegment`](../../aspose.pdf.text/textsegment/) object represents. |

## Methods

| Name | Description |
| --- | --- |
| [MyHtmlEncode](./myhtmlencode/)(*string*) | Encodes string as html. |

## Remarks

In a few words, [`TextSegment`](../../aspose.pdf.text/textsegment/) objects are children of [`TextFragment`](../../aspose.pdf.text/textfragment/) object.
 
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

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

