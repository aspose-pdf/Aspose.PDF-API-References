---
title: "TextAbsorber Class"
linktitle: "TextAbsorber"
articleTitle: "TextAbsorber"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.TextAbsorber class. Represents an absorber object of a text. Performs text extraction and provides access to the result via Text object."
type: docs
weight: 410
url: "/net/aspose.pdf.text/textabsorber/"
keywords: "TextAbsorber, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## TextAbsorber class

Represents an absorber object of a text.
 Performs text extraction and provides access to the result via [`Text`](./text/) object.

```csharp
public class TextAbsorber
```

## Examples

The example demonstrates how to extract text on the first PDF document page.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;
```

## Constructors

| Name | Description |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | Initializes a new instance of the `TextAbsorber`. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | Initializes a new instance of the `TextAbsorber` with extraction options. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | Initializes a new instance of the `TextAbsorber` with extraction and text search options. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | Initializes a new instance of the `TextAbsorber` with text search options. |

## Properties

| Name | Description |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | List of [`TextExtractionError`](../textextractionerror/) objects. It contain information about errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | Gets or sets text extraction options. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | Value indicates whether errors were found during text extraction. Searching for errors will performed only if TextSearchOptions.LogTextExtractionErrors = true; And it may decrease performance. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | Gets extracted text that the `TextAbsorber` extracts on the PDF document or page. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | Gets or sets text search options. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Page) | Extracts text on the specified page |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(XForm) | Extracts text on the specified XForm. |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(Document) | Extracts text on the specified document |

## Remarks

The [`TextAbsorber`](../textabsorber/) object is used to extract text from a Pdf document or the document's page.

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

