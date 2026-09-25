---
title: "OcrDetail Class"
linktitle: "OcrDetail"
articleTitle: "OcrDetail"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.OcrDetail class. Represents the OCR result for a single page of a document or a single image file."
type: docs
weight: 860
url: "/net/aspose.pdf.ai/ocrdetail/"
keywords: "OcrDetail, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## OcrDetail class

Represents the OCR result for a single page of a document or a single image file.

```csharp
public class OcrDetail
```

## Constructors

| Name | Description |
| --- | --- |
| [OcrDetail](./ocrdetail/#constructor) | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ErrorMessage](./errormessage/) { get; set; } | An error message describing why OCR failed for this page, if Success is false. Null otherwise. |
| [ExtractedText](./extractedtext/) { get; set; } | The extracted text content from the page. Null if Success is false or no text was found. |
| [PageNumber](./pagenumber/) { get; set; } | The 1-based page number within the source document. |
| [Success](./success/) { get; set; } | Indicates whether the OCR extraction for this specific page was successful. |
| [Usage](./usage/) { get; set; } | Gets or sets the usage statistics. |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](./compareto/)(*OcrDetail*) | Compares the current OcrDetail instance with another OcrDetail object based on their PageNumber property. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

