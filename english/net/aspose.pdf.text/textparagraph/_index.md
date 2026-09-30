---
title: "TextParagraph Class"
linktitle: "TextParagraph"
articleTitle: "TextParagraph"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.TextParagraph class. Represents text paragraphs as multiline text object."
type: docs
weight: 600
url: "/net/aspose.pdf.text/textparagraph/"
keywords: "TextParagraph, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextParagraph class

Represents text paragraphs as multiline text object.

```csharp
public sealed class TextParagraph
```

## Examples

The example demonstrates how to create text paragraph object and append it to the Pdf page.

```csharp
Document doc = new Document(inFile);

Page page = (Page)doc.Pages[1];

// create text paragraph
TextParagraph paragraph = new TextParagraph();

// set the paragraph rectangle
paragraph.Rectangle = new Rectangle(100, 600, 200, 700);

// set word wrapping options
paragraph.FormattingOptions.WrapMode = TextFormattingOptions.WordWrapMode.ByWords;

// append string lines
paragraph.AppendLine("the quick brown fox jumps over the lazy dog");
paragraph.AppendLine("line2");
paragraph.AppendLine("line3");

// append the paragraph to the Pdf page with the TextBuilder
TextBuilder textBuilder = new TextBuilder(page);
textBuilder.AppendParagraph(paragraph);

// save Pdf document
doc.Save(outFile);
```

## Constructors

| Name | Description |
| --- | --- |
| [TextParagraph](./textparagraph/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [FirstLineIndent](./firstlineindent/) { get; set; } | Gets or sets subsequent lines indent value. If set to a non-zero value, it has an advantage over the FormattingOptions.SubsequentLinesIndent value. |
| [FormattingOptions](./formattingoptions/) { get; set; } | Gets or sets formatting options. |
| [HorizontalAlignment](./horizontalalignment/) { get; set; } | Gets or sets horizontal alignment for the text inside paragrph's `Rectangle`. |
| [Justify](./justify/) { get; set; } | Gets or sets value whether text is justified. |
| [Margin](./margin/) { get; set; } | Gets or sets the padding. |
| [Position](./position/) { get; set; } | Gets or sets position of the paragraph. |
| [Rectangle](./rectangle/) { get; set; } | Gets or sets rectangle of the paragraph. |
| [Rotation](./rotation/) { get; set; } | Gets or sets rotation angle in degrees. |
| [SubsequentLinesIndent](./subsequentlinesindent/) { get; set; } | Gets or sets subsequent lines indent value. If set to a non-zero value, it has an advantage over the FormattingOptions.SubsequentLinesIndent value. |
| [TextRectangle](./textrectangle/) { get; } | Gets rectangle of the text placed to the paragraph. |
| [VerticalAlignment](./verticalalignment/) { get; set; } | Gets or sets vertical alignment for the text inside paragrph's `Rectangle`. |

## Methods

| Name | Description |
| --- | --- |
| [AppendLine](./appendline/)(string) | Appends text line |
| [AppendLine](./appendline/)(TextFragment) | Appends text line with text state parameters. |
| [AppendLine](./appendline/)(string, float) | Appends text line. |
| [AppendLine](./appendline/)(string, TextState) | Appends text line with text state parameters. |
| [AppendLine](./appendline/)(TextFragment, TextState) | Appends text line with text state parameters. |
| [AppendLine](./appendline/)(string, TextState, float) | Appends text line with text state parameters |
| [AppendLine](./appendline/)(TextFragment, TextState, float) | Appends text line with text state parameters |
| [BeginEdit](./beginedit/)() | Begins the editing of the TextParagraph. |
| [EndEdit](./endedit/)() | Ends the editing of the TextParagraph. |

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

