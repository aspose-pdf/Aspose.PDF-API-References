---
title: Class ParagraphAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.ParagraphAbsorber class. Represents an absorber object of page structure objects such as sections and paragraphs. Performs search for sections and paragraphs of text and provides access for rectangles and polydons that describes it in text coordinate space. Also performs text segments search and provides access to search results via TextFragments collections grouped by structure elements
type: docs
weight: 7830
url: /net/aspose.pdf.text/paragraphabsorber/
---
## ParagraphAbsorber class

Represents an absorber object of page structure objects such as sections and paragraphs. Performs search for sections and paragraphs of text and provides access for rectangles and polydons that describes it in text coordinate space. Also performs text segments search and provides access to search results via !:TextFragments collections grouped by structure elements.

```csharp
public class ParagraphAbsorber
```

## Constructors

| Name | Description |
| --- | --- |
| [ParagraphAbsorber](paragraphabsorber/#constructor)() | Initializes a new instance of the `ParagraphAbsorber` that performs search for sections/paragraphs of the document or page. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_2)(int) | Initializes a new instance of the `ParagraphAbsorber` that performs search for sections/paragraphs of the document or page. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_1)(ParagraphAbsorberOptions) | Initializes a new instance of the `ParagraphAbsorber` that performs search for sections/paragraphs of the document or page with the specified parameters. |
| [ParagraphAbsorber](paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | Initializes a new instance of the `ParagraphAbsorber` that performs search for sections/paragraphs of the document or page with the specified parameters. |

## Properties

| Name | Description |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](../../aspose.pdf.text/paragraphabsorber/ismulticolumnparagraphsallowed/) { get; set; } | Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section. |
| [PageMarkups](../../aspose.pdf.text/paragraphabsorber/pagemarkups/) { get; } | Gets collection of [`PageMarkup`](../pagemarkup/) that were absorbed. |
| [ParagraphAbsorberOptions](../../aspose.pdf.text/paragraphabsorber/paragraphabsorberoptions/) { get; set; } | Gets or sets the ParagraphAbsorberOptions. |
| [SectionsSearchDepth](../../aspose.pdf.text/paragraphabsorber/sectionssearchdepth/) { get; set; } | Gets or sets value that instructs how many times sequential searches for more fine elements of structure will be performed. Default search depth is 3. It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns). |
| [TextReplaceOptions](../../aspose.pdf.text/paragraphabsorber/textreplaceoptions/) { get; set; } | Gets or sets the TextReplaceOptions. |

## Methods

| Name | Description |
| --- | --- |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit)(Document) | Performs search for sections and paragraphs on the specified [`Document`](../../aspose.pdf/document/). |
| [Visit](../../aspose.pdf.text/paragraphabsorber/visit/#visit_1)(Page) | Performs search on the specified [`Page`](../../aspose.pdf/page/). |

## Remarks

When the search is completed the [`PageMarkups`](./pagemarkups/) collection will contains [`PageMarkup`](../pagemarkup/) objects that represents page structure by collections of [`MarkupSection`](../markupsection/) and [`MarkupParagraph`](../markupparagraph/). The [`TextFragment`](../textfragment/) object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).

## Examples

The example demonstrates how to find first text segment of each paragraph on the first PDF document page and highlight it.

```csharp
// Open document
Document doc = new Document("input.pdf");

// Create ParagraphAbsorber object
ParagraphAbsorber absorber = new ParagraphAbsorber();

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Get markup object of first page
PageMarkup markup = absorber.PageMarkups[0];

// Loop through structure elements of the page text to find first text fragment of each paragraph
foreach (MarkupSection section in markup.Sections)
{
    foreach (MarkupParagraph paragraph in section.Paragraphs)
    {
        TextFragment fragment = paragraph.Fragments[0];
        // Update text properties
        fragment.TextState.BackgroundColor = Color.LightBlue;
    }
}

// Save document
doc.Save(GetOutputPath("output.pdf"));
```

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


