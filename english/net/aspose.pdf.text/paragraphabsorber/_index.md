---
title: "ParagraphAbsorber Class"
linktitle: "ParagraphAbsorber"
articleTitle: "ParagraphAbsorber"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.ParagraphAbsorber class. Represents an absorber object of page structure objects such as sections and paragraphs. Performs search for section..."
type: docs
weight: 280
url: "/net/aspose.pdf.text/paragraphabsorber/"
keywords: "ParagraphAbsorber, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ParagraphAbsorber class

Represents an absorber object of page structure objects such as sections and paragraphs.
 Performs search for sections and paragraphs of text and provides access for rectangles and polydons that describes it in text coordinate space. 
 Also performs text segments search and provides access to search results via `!:TextFragments` collections grouped by structure elements.

```csharp
public class ParagraphAbsorber
```

## Constructors

| Name | Description |
| --- | --- |
| [ParagraphAbsorber](./paragraphabsorber/#constructor)() | Initializes a new instance of the [`ParagraphAbsorber`](../../aspose.pdf.text/paragraphabsorber/) that performs search for sections/paragraphs of the document or page. |
| [ParagraphAbsorber](./paragraphabsorber/#constructor_1)(int) | Initializes a new instance of the [`ParagraphAbsorber`](../../aspose.pdf.text/paragraphabsorber/) that performs search for sections/paragraphs of the document or page. |
| [ParagraphAbsorber](./paragraphabsorber/#constructor_2)(ParagraphAbsorberOptions) | Initializes a new instance of the [`ParagraphAbsorber`](../../aspose.pdf.text/paragraphabsorber/) that performs search for sections/paragraphs of the document or page with the specified parameters. |
| [ParagraphAbsorber](./paragraphabsorber/#constructor_3)(int, ParagraphAbsorberOptions) | Initializes a new instance of the [`ParagraphAbsorber`](../../aspose.pdf.text/paragraphabsorber/) that performs search for sections/paragraphs of the document or page with the specified parameters. |

## Properties

| Name | Description |
| --- | --- |
| [IsMulticolumnParagraphsAllowed](./ismulticolumnparagraphsallowed/) { get; set; } | Gets or sets value that indicates whether starting text lines of a next section may be treated as continuation of the last paragraph of a previous section. |
| [PageMarkups](./pagemarkups/) { get; } | Gets collection of [`PageMarkup`](../../aspose.pdf.text/pagemarkup/) that were absorbed. |
| [ParagraphAbsorberOptions](./paragraphabsorberoptions/) { get; set; } | Gets or sets the ParagraphAbsorberOptions. |
| [SectionsSearchDepth](./sectionssearchdepth/) { get; set; } | Gets or sets value that instructs how many times sequential searches for more fine elements of structure will be performed. Default search depth is 3. It means three searches for horizontally divided sections (headers, paragraphs etc) and three searches for vertically divided ones (columns). |
| [TextReplaceOptions](./textreplaceoptions/) { get; set; } | Gets or sets the TextReplaceOptions. |

## Methods

| Name | Description |
| --- | --- |
| [Visit](./visit/)(Document) | Performs search for sections and paragraphs on the specified [`Document`](../../aspose.pdf/document/). |
| [Visit](./visit/)(Page) | Performs search on the specified [`Page`](../../aspose.pdf/page/). |

## Remarks

When the search is completed the `PageMarkups` collection will contains [`PageMarkup`](../../aspose.pdf.text/pagemarkup/) objects that represents page structure by collections of [`MarkupSection`](../../aspose.pdf.text/markupsection/) and [`MarkupParagraph`](../../aspose.pdf.text/markupparagraph/).
 The [`TextFragment`](../../aspose.pdf.text/textfragment/) object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

