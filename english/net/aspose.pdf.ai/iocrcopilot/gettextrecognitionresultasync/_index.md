---
title: "IOcrCopilot.GetTextRecognitionResultAsync"
linktitle: "GetTextRecognitionResultAsync"
articleTitle: "GetTextRecognitionResultAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOcrCopilot method. Asynchronously retrieves text recognition results for the PDF documents and image files. The supported image types: PNG (.png), JPEG (.jp..."
type: docs
weight: 10
url: "/net/aspose.pdf.ai/iocrcopilot/gettextrecognitionresultasync/"
product_version: "26.9"
---
## IOcrCopilot.GetTextRecognitionResultAsync method

Asynchronously retrieves text recognition results for the PDF documents and image files.
 The supported image types: PNG (.png), JPEG (.jpeg and .jpg), WEBP (.webp), non-animated GIF (.gif).

```csharp
public Task<List<TextRecognitionResult>> GetTextRecognitionResultAsync(
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cancellationToken | Nullable`1 | An optional cancellation token to cancel the operation. |

### Return Value

A task that represents the asynchronous operation. The task result contains a list of [`TextRecognitionResult`](../../textrecognitionresult/).

### See Also

* class [TextRecognitionResult](../../textrecognitionresult/)
* interface [IOcrCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

