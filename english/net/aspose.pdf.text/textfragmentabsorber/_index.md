---
title: Class TextFragmentAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextFragmentAbsorber class. Represents an absorber object of text fragments. Performs text search and provides access to search results via TextFragments collection
type: docs
weight: 8320
url: /net/aspose.pdf.text/textfragmentabsorber/
---
## TextFragmentAbsorber class

Represents an absorber object of text fragments. Performs text search and provides access to search results via [`TextFragments`](./textfragments/) collection.

```csharp
public sealed class TextFragmentAbsorber : TextAbsorber
```

## Constructors

| Name | Description |
| --- | --- |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor)() | Initializes a new instance of the `TextFragmentAbsorber` that performs search of all text segments of the document or page. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_6)(Regex) | Initializes a new instance of the `TextFragmentAbsorber` class for the specified System.Text.RegularExpressions.Regex class object. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_2)(string) | Initializes a new instance of the `TextFragmentAbsorber` class for the specified text phrase. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_1)(TextEditOptions) | Initializes a new instance of the `TextFragmentAbsorber` with text edit options, that performs search of all text segments of the document or page. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_7)(Regex, TextEditOptions) | Initializes a new instance of the `TextFragmentAbsorber` class for the specified text phrase and text edit options. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_8)(Regex, TextSearchOptions) | Initializes a new instance of the `TextFragmentAbsorber` class for the specified text phrase and text search options. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_3)(string, TextEditOptions) | Initializes a new instance of the `TextFragmentAbsorber` class for the specified text phrase and text edit options. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_4)(string, TextSearchOptions) | Initializes a new instance of the `TextFragmentAbsorber` class for the specified text phrase and text search options. |
| [TextFragmentAbsorber](textfragmentabsorber/#constructor_5)(string, TextSearchOptions, TextEditOptions) | Initializes a new instance of the `TextFragmentAbsorber` class for the specified text phrase, text search options and text edit options. |

## Properties

| Name | Description |
| --- | --- |
| [Errors](../../aspose.pdf.text/textfragmentabsorber/errors/) { get; } | List of [`TextExtractionError`](../textextractionerror/) objects. It contain information about errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance. |
| override [ExtractionOptions](../../aspose.pdf.text/textfragmentabsorber/extractionoptions/) { get; set; } | Gets or sets text extraction options. |
| [HasErrors](../../aspose.pdf.text/textfragmentabsorber/haserrors/) { get; } | Value indicates whether errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance. |
| [Phrase](../../aspose.pdf.text/textfragmentabsorber/phrase/) { get; set; } | Gets or sets phrase that the `TextFragmentAbsorber` searches on the PDF document or page. |
| override [Text](../../aspose.pdf.text/textfragmentabsorber/text/) { get; } | Gets extracted text that the [`TextAbsorber`](../textabsorber/) extracts on the PDF document or page. |
| [TextEditOptions](../../aspose.pdf.text/textfragmentabsorber/texteditoptions/) { get; set; } | Gets or sets text edit options. The options define special behavior when requested symbol cannot be written with font. |
| [TextFragments](../../aspose.pdf.text/textfragmentabsorber/textfragments/) { get; set; } | Gets collection of search occurrences that are presented with [`TextFragment`](../textfragment/) objects. |
| [TextReplaceOptions](../../aspose.pdf.text/textfragmentabsorber/textreplaceoptions/) { get; set; } | Gets or sets text replace options. The options define behavior when fragment text is replaced to more short/long. |
| [TextSearchOptions](../../aspose.pdf.text/textfragmentabsorber/textsearchoptions/) { get; set; } | Gets or sets search options. The options enable search using regular expressions. |

## Methods

| Name | Description |
| --- | --- |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_2)(float) | Applies font size for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments)(Font) | Applies font for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping. |
| [ApplyForAllFragments](../../aspose.pdf.text/textfragmentabsorber/applyforallfragments/#applyforallfragments_1)(Font, float) | Applies font and size for all text fragments that were absorbed. It works faster than looping through the fragments if all fragments on the page(s) were absorbed. Otherwise it works similar with looping. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext)(Document) | Removes all text from the document. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_1)(Page) | Removes all text from the specified page. |
| [RemoveAllText](../../aspose.pdf.text/textfragmentabsorber/removealltext/#removealltext_2)(Page, Rectangle) | Removes text inside the specified rectangle from the specified page. |
| [Reset](../../aspose.pdf.text/textfragmentabsorber/reset/)() | Clears TextFragments collection of this `TextFragmentAbsorber` object. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit)(Document) | Performs search on the specified document. |
| override [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_1)(Page) | Performs search on the specified page. |
| [Visit](../../aspose.pdf.text/textfragmentabsorber/visit/#visit_2)(XForm) | Performs search on the specified form object. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/)(XForm) | Extracts text on the specified XForm. |

## Remarks

The `TextFragmentAbsorber` object is basically used in text search scenario. When the search is completed the occurrences are represented with [`TextFragment`](../textfragment/) objects that the [`TextFragments`](./textfragments/) collection contains. The [`TextFragment`](../textfragment/) object provides access to the search occurrence text, text properties, and allows to edit text and change the text state (font, font size, color etc).

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

### See Also

* class [TextAbsorber](../textabsorber/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


