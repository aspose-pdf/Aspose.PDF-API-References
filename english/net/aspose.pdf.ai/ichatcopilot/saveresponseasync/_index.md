---
title: "IChatCopilot.SaveResponseAsync"
linktitle: "SaveResponseAsync"
articleTitle: "SaveResponseAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IChatCopilot method. Asynchronously saves the response for the given message to a PDF file."
type: docs
weight: 30
url: "/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/"
product_version: "26.9.0"
---
## SaveResponseAsync(string, string, Nullable<CancellationToken>) {#saveresponseasync}

Asynchronously saves the response for the given message to a PDF file.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | string | The input message for which the response is saved. |
| outputFileName | string | The name of the output PDF file to save the response. |
| cancellationToken | Nullable<CancellationToken> | The cancellation token (optional). |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

A task representing the asynchronous operation.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, [SaveFormat](../../../aspose.pdf.lowcode/saveformat/), Nullable<CancellationToken>) {#saveresponseasync_1}

Asynchronously saves the response for the given message to a file with specified format.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | string | The input message for which the response is saved. |
| outputFileName | string | The name of the output file to save the response. |
| saveFormat | SaveFormat | The format in which to save the response (PDF if not specified). |
| cancellationToken | Nullable<CancellationToken> | The cancellation token (optional). |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

A task representing the asynchronous operation.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List<string>, string, Nullable<CancellationToken>) {#saveresponseasync_2}

Asynchronously saves the responses for the given list of messages to a PDF file.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List<string> | The list of input messages for which responses are saved. |
| outputFileName | string | The name of the output PDF file to save the responses. |
| cancellationToken | Nullable<CancellationToken> | The cancellation token (optional). |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

A task representing the asynchronous operation.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List<string>, string, [SaveFormat](../../../aspose.pdf.lowcode/saveformat/), Nullable<CancellationToken>) {#saveresponseasync_3}

Asynchronously saves the responses for the given list of messages to a file with specified format.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List<string> | The list of input messages for which responses are saved. |
| outputFileName | string | The name of the output file to save the responses. |
| saveFormat | SaveFormat | The format in which to save the responses (PDF if not specified). |
| cancellationToken | Nullable<CancellationToken> | The cancellation token (optional). |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

A task representing the asynchronous operation.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

