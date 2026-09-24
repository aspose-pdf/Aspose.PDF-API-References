---
title: "OcrTextAbsorber Class"
linktitle: "OcrTextAbsorber"
articleTitle: "OcrTextAbsorber"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Ocr.OcrTextAbsorber class. Extracts plain text from PDF pages using OCR over the rendered page bitmap."
type: docs
weight: 30
url: "/net/aspose.pdf.ocr/ocrtextabsorber/"
keywords: "OcrTextAbsorber, Aspose.Pdf.Ocr, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## OcrTextAbsorber class

Extracts plain text from PDF pages using OCR over the rendered page bitmap.

```csharp
public sealed class OcrTextAbsorber
```

## Constructors

| Name | Description |
| --- | --- |
| [OcrTextAbsorber](./ocrtextabsorber/#constructor) | Initializes a new instance with default options. |
| [OcrTextAbsorber](./ocrtextabsorber/#constructor_1)(*[OcrTextRecognitionOptions](../../aspose.pdf.ocr/ocrtextrecognitionoptions/)*) | Initializes a new instance with the specified options. |

## Properties

| Name | Description |
| --- | --- |
| [Options](./options/) { get; } | Gets the recognition options. |
| [Text](./text/) { get; } | Gets the text recognized by the most recent `Visit` or `Visit` call. |

## Methods

| Name | Description |
| --- | --- |
| [Visit](./visit/)(*Document*) | Recognizes text on every page of the document, joined by `PageSeparator`. |
| [Visit](./visit/)(*Page*) | Recognizes text on the page. |

### See Also

* namespace [Aspose.Pdf.Ocr](../../aspose.pdf.ocr/)
* assembly [Aspose.PDF](../../)

