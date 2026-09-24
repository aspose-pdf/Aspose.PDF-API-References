---
title: "TextAbsorber Class"
linktitle: "TextAbsorber"
articleTitle: "TextAbsorber"
second_title: "Aspose.PDF for .NET"
description: "Represents an absorber object of a text. Performs text extraction and provides access to the result via object."
type: docs
weight: 410
url: "/net/aspose.pdf.text/textabsorber/"
keywords: "TextAbsorber, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextAbsorber class

Represents an absorber object of a text.
 Performs text extraction and provides access to the result via `Text` object.

```csharp
public class TextAbsorber
```

## Constructors

| Name | Description |
| --- | --- |
| [TextAbsorber](./textabsorber/#constructor) | Initializes a new instance of the [`TextAbsorber`](../../aspose.pdf.text/textabsorber/). |
| [TextAbsorber](./textabsorber/#constructor_1)(*[TextExtractionOptions](../../aspose.pdf.text/textextractionoptions/)*) | Initializes a new instance of the [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) with extraction options. |
| [TextAbsorber](./textabsorber/#constructor_2)(*[TextSearchOptions](../../aspose.pdf.text/textsearchoptions/)*) | Initializes a new instance of the [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) with text search options. |
| [TextAbsorber](./textabsorber/#constructor_3)(*[TextExtractionOptions](../../aspose.pdf.text/textextractionoptions/), [TextSearchOptions](../../aspose.pdf.text/textsearchoptions/)*) | Initializes a new instance of the [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) with extraction and text search options. |

## Properties

| Name | Description |
| --- | --- |
| [Errors](./errors/) { get; } | List of [`TextExtractionError`](../../aspose.pdf.text/textextractionerror/) objects. It contain information about errors were found during text extraction. |
| [ExtractionOptions](./extractionoptions/) { get; set; } | Gets or sets text extraction options. |
| [HasErrors](./haserrors/) { get; } | Value indicates whether errors were found during text extraction. |
| [Text](./text/) { get; } | Gets extracted text that the [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) extracts on the PDF document or page. |
| [TextSearchOptions](./textsearchoptions/) { get; set; } | Gets or sets text search options. |

## Methods

| Name | Description |
| --- | --- |
| [Visit](./visit/)(*Page*) | Extracts text on the specified page. |
| [Visit](./visit/)(*XForm*) | Extracts text on the specified XForm. |
| [Visit](./visit/)(*Document*) | Extracts text on the specified document. |

## Remarks

The [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) object is used to extract text from a Pdf document or the document's page.

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

