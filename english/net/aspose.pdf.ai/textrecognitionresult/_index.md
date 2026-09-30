---
title: "TextRecognitionResult Class"
linktitle: "TextRecognitionResult"
articleTitle: "TextRecognitionResult"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.TextRecognitionResult class. Represents the aggregated OCR results for a single source document."
type: docs
weight: 1180
url: "/net/aspose.pdf.ai/textrecognitionresult/"
keywords: "TextRecognitionResult, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextRecognitionResult class

Represents the aggregated OCR results for a single source document.

```csharp
public class TextRecognitionResult
```

## Constructors

| Name | Description |
| --- | --- |
| [TextRecognitionResult](./textrecognitionresult/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [OcrDetails](./ocrdetails/) { get; set; } | A list containing the detailed OCR results for each page of the document. For single-image files, this list will typically contain one OcrDetail entry with PageNumber = 1. |
| [OverallSuccess](./overallsuccess/) { get; set; } | Indicates if OCR was successful for ALL pages within this document. False if any OcrDetail in OcrDetails has Success = false. |
| [SourceIdentifier](./sourceidentifier/) { get; set; } | Identifier for the source file (e.g., the full path or a unique name). |
| [SummaryErrorMessage](./summaryerrormessage/) { get; set; } | A consolidated error message if OverallSuccess is false, or a summary if any page failed. Null if OverallSuccess is true. |
| [TotalUsage](./totalusage/) { get; set; } | Gets or sets the total usage statistics for processing this document (all pages). |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

