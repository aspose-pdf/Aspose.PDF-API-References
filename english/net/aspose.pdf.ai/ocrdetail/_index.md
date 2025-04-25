---
title: Class OcrDetail
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.OcrDetail class. Represents the OCR result for a single page of a document or a single image file
type: docs
weight: 860
url: /net/aspose.pdf.ai/ocrdetail/
---
## OcrDetail class

Represents the OCR result for a single page of a document or a single image file.

```csharp
public class OcrDetail : IComparable<OcrDetail>
```

## Constructors

| Name | Description |
| --- | --- |
| [OcrDetail](ocrdetail/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [ErrorMessage](../../aspose.pdf.ai/ocrdetail/errormessage/) { get; set; } | An error message describing why OCR failed for this page, if Success is false. Null otherwise. |
| [ExtractedText](../../aspose.pdf.ai/ocrdetail/extractedtext/) { get; set; } | The extracted text content from the page. Null if Success is false or no text was found. |
| [PageNumber](../../aspose.pdf.ai/ocrdetail/pagenumber/) { get; set; } | The 1-based page number within the source document. For single-page images, this will always be 1. |
| [Success](../../aspose.pdf.ai/ocrdetail/success/) { get; set; } | Indicates whether the OCR extraction for this specific page was successful. |
| [Usage](../../aspose.pdf.ai/ocrdetail/usage/) { get; set; } | Gets or sets the usage statistics. |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../aspose.pdf.ai/ocrdetail/compareto/)(OcrDetail) | Compares the current OcrDetail instance with another OcrDetail object based on their PageNumber property. |

### See Also

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


