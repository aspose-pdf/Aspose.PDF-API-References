---
title: "TextFragmentAbsorber Class"
linktitle: "TextFragmentAbsorber"
articleTitle: "TextFragmentAbsorber"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.TextFragmentAbsorber class. Represents an absorber object of text fragments. Performs text search and provides access to search results via T..."
type: docs
weight: 560
url: "/net/aspose.pdf.text/textfragmentabsorber/"
keywords: "TextFragmentAbsorber, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextFragmentAbsorber class

Represents an absorber object of text fragments.
 Performs text search and provides access to search results via `TextFragments` collection.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Examples

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

## Constructors

| Name | Description |
| --- | --- |
| [TextFragmentAbsorber](./textfragmentabsorber/#constructor)() | Initializes a new instance of the [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) that performs search of all text segments of the document or page. |
| [TextFragmentAbsorber](./textfragmentabsorber/#constructor_1)(Regex) | Initializes a new instance of the [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) class for the specified System.Text.RegularExpressions.Regex class object. |
| [TextFragmentAbsorber](./textfragmentabsorber/#constructor_2)(string) | Initializes a new instance of the [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) class for the specified text phrase. |
| [TextFragmentAbsorber](./textfragmentabsorber/#constructor_3)(TextEditOptions) | Initializes a new instance of the [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) with text edit options, that performs search of all text segments of the document or page. |
| [TextFragmentAbsorber](./textfragmentabsorber/#constructor_4)(Regex, TextEditOptions) | Initializes a new instance of the [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) class for the specified text phrase and text edit options. |
| [TextFragmentAbsorber](./textfragmentabsorber/#constructor_5)(Regex, TextSearchOptions) | Initializes a new instance of the [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) class for the specified text phrase and text search options. |
| [TextFragmentAbsorber](./textfragmentabsorber/#constructor_6)(Regex[], TextSearchOptions) | Initializes a new instance of the [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) class for the specified text phrase and text search options. |
| [TextFragmentAbsorber](./textfragmentabsorber/#constructor_7)(string, TextEditOptions) | Initializes a new instance of the [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) class for the specified text phrase and text edit options. |
| [TextFragmentAbsorber](./textfragmentabsorber/#constructor_8)(string, TextSearchOptions) | Initializes a new instance of the [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) class for the specified text phrase and text search options. |
| [TextFragmentAbsorber](./textfragmentabsorber/#constructor_9)(string, TextSearchOptions, TextEditOptions) | Initializes a new instance of the [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) class for the specified text phrase, text search options and text edit options. |

## Properties

| Name | Description |
| --- | --- |
| [Errors](./errors/) { get; } | List of [`TextExtractionError`](../../aspose.pdf.text/textextractionerror/) objects. It contain information about errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance. |
| override [ExtractionOptions](./extractionoptions/) { get; set; } | Gets or sets text extraction options. |
| [HasErrors](./haserrors/) { get; } | Value indicates whether errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance. |
| [Phrase](./phrase/) { get; set; } | Gets or sets phrase that the [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) searches on the PDF document or page. |
| [RegexResults](./regexresults/) { get; } | Gets dictionary of search occurrences that are presented with System.Text.RegularExpressions.Regex class as key and [`TextFragment`](../../aspose.pdf.text/textfragment/) as value. |
| override [Text](./text/) { get; } | Gets extracted text that the [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) extracts on the PDF document or page. |
| [TextEditOptions](./texteditoptions/) { get; set; } | Gets or sets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [TextFragments](./textfragments/) { get; set; } | Gets collection of search occurrences that are presented with [`TextFragment`](../../aspose.pdf.text/textfragment/) objects. |
| [TextReplaceOptions](./textreplaceoptions/) { get; set; } | Gets or sets text replace options. The options define behavior when fragment text is replaced to more short/long. |
| [TextSearchOptions](./textsearchoptions/) { get; set; } | Gets or sets search options. The options enable search using regular expressions. |

## Methods

| Name | Description |
| --- | --- |
| [ApplyForAllFragments](./applyforallfragments/)(float) | Applies font size for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping. |
| [ApplyForAllFragments](./applyforallfragments/)(Font) | Applies font for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping. |
| [ApplyForAllFragments](./applyforallfragments/)(Font, float) | Applies font and size for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping. |
| [RemoveAllText](./removealltext/)(Document) | Removes all text from the document. |
| [RemoveAllText](./removealltext/)(Page) | Removes all text from the specified page. |
| [RemoveAllText](./removealltext/)(Page, Rectangle) | Removes text inside the specified rectangle from the specified page. |
| [Reset](./reset/)() | Clears TextFragments collection of this [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) object. |
| override [Visit](./visit/)(Document) | Performs search on the specified document. |
| override [Visit](./visit/)(Page) | Performs search on the specified page. |
| [Visit](./visit/)(XForm) | Performs search on the specified form object. |

## Remarks

The [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) object is basically used in text search scenario.
 When the search is completed the occurrences are represented with [`TextFragment`](../../aspose.pdf.text/textfragment/) objects that the `TextFragments` collection contains.
 The [`TextFragment`](../../aspose.pdf.text/textfragment/) object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).

### See Also

* class [TextAbsorber](../textabsorber/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

