---
title: "IOcrCopilot.GetTextRecognitionResultAsync"
linktitle: "GetTextRecognitionResultAsync"
articleTitle: "GetTextRecognitionResultAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IOcrCopilot method. Asynchronously retrieves text recognition results for the PDF documents and image files. The supported image types: PNG (.png), JPEG (.jp..."
type: docs
weight: 10
url: "/net/aspose.pdf.ai/iocrcopilot/gettextrecognitionresultasync/"
product_version: "26.9.0"
---
## GetTextRecognitionResultAsync(Nullable<CancellationToken>) {#gettextrecognitionresultasync}

Asynchronously retrieves text recognition results for the PDF documents and image files.
 The supported image types: PNG (.png), JPEG (.jpeg and .jpg), WEBP (.webp), non-animated GIF (.gif).

```csharp
public Task<List<TextRecognitionResult>> GetTextRecognitionResultAsync(Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cancellationToken | Nullable<CancellationToken> | An optional cancellation token to cancel the operation. |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<[List](https://docs.oracle.com/javase/8/docs/api/java/util/List.html)<[TextRecognitionResult](../../../aspose.pdf.ai/textrecognitionresult/)>>

A task that represents the asynchronous operation. The task result contains a list of [`TextRecognitionResult`](../../../aspose.pdf.ai/textrecognitionresult/).

### See Also

* interface [IOcrCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

