---
title: "IChatCopilot.GetResponseAsync"
linktitle: "GetResponseAsync"
articleTitle: "GetResponseAsync"
second_title: "Aspose.PDF for .NET API Reference"
description: "IChatCopilot method. Asynchronously gets a response for the given message."
type: docs
weight: 10
url: "/net/aspose.pdf.ai/ichatcopilot/getresponseasync/"
product_version: "26.9.0"
---
## GetResponseAsync(string, Nullable<CancellationToken>) {#getresponseasync}

Asynchronously gets a response for the given message.

```csharp
public Task<string> GetResponseAsync(string message, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | string | The input message for which a response is requested. |
| cancellationToken | Nullable<CancellationToken> | The cancellation token (optional). |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<string>

A task representing the asynchronous operation with the response string.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## GetResponseAsync(List<string>, Nullable<CancellationToken>) {#getresponseasync_1}

Asynchronously gets a response for the given list of messages.

```csharp
public Task<string> GetResponseAsync(List<string> messages, Nullable<CancellationToken> cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List<string> | The list of input messages for which responses are requested. |
| cancellationToken | Nullable<CancellationToken> | The cancellation token (optional). |

### Return Value

[Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)<string>

A task representing the asynchronous operation with the response string.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

