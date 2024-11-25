---
title: IChatCopilot.GetResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: IChatCopilot method. Asynchronously gets a response for the given message
type: docs
weight: 20
url: /net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

Asynchronously gets a response for the given message.

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | String | The input message for which a response is requested. |
| cancellationToken | Nullable`1 | The cancellation token (optional). |

### Return Value

A task representing the asynchronous operation with the response string.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## GetResponseAsync(List&lt;string&gt;, CancellationToken?) {#getresponseasync}

Asynchronously gets a response for the given list of messages.

```csharp
public Task<string> GetResponseAsync(List<string> messages, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| messages | List`1 | The list of input messages for which responses are requested. |
| cancellationToken | Nullable`1 | The cancellation token (optional). |

### Return Value

A task representing the asynchronous operation with the response string.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


