---
title: "LlamaClient Class"
linktitle: "LlamaClient"
articleTitle: "LlamaClient"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.AI.LlamaClient class. Represents a client for interacting with the Llama API."
type: docs
weight: 750
url: "/net/aspose.pdf.ai/llamaclient/"
keywords: "LlamaClient, Aspose.Pdf.AI, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## LlamaClient class

Represents a client for interacting with the Llama API.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, IAIClient
```

## Properties

| Name | Description |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Gets or sets the backoff delay in seconds. *(Inherited from AIClientBase)* |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Gets or sets the maximum number of HTTP request retries. *(Inherited from AIClientBase)* |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Gets or sets the polling interval in seconds. *(Inherited from AIClientBase)* |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Gets or sets the polling timeout in seconds. *(Inherited from AIClientBase)* |

## Methods

| Name | Description |
| --- | --- |
| [AssertDisposed](../../aspose.pdf.ai/aiclientbase/assertdisposed/) | Asserts whether the object has been disposed. *(Inherited from AIClientBase)* |
| [CreateCompletionAsync](./createcompletionasync/)(*LlamaChatCompletionRequest, Nullable<CancellationToken>*) | Creates a chat completion request in the Llama service. |
| [CreateWithApiKey](./createwithapikey/)(*string*) | Creates a new instance of `Builder` with the provided API key. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/) | Disposes of the resources used by the [`AIClientBase`](../../aspose.pdf.ai/aiclientbase/). *(Inherited from AIClientBase)* |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)(*bool*) | Disposes of the resources used by the [`AIClientBase`](../../aspose.pdf.ai/aiclientbase/). *(Inherited from AIClientBase)* |
| [GetSummaryCopilot](./getsummarycopilot/)(*ISummaryCopilotOptions<LlamaSummaryCopilotOptions>*) | Gets an instance of [`ISummaryCopilot`](../../aspose.pdf.ai/isummarycopilot/) with the specified options. |
| [HandleRequestAsync](../../aspose.pdf.ai/aiclientbase/handlerequestasync/)(*Func<Task<T0>>, Func<string, string>, Nullable<CancellationToken>*) | *(Inherited from AIClientBase)* |
| [PollForCompletionAsync](../../aspose.pdf.ai/aiclientbase/pollforcompletionasync/)(*Func<Task<IStatus>>, Nullable<CancellationToken>*) | Polls for completion asynchronously with a specified request delegate. *(Inherited from AIClientBase)* |
| [PollForCompletionAsync](../../aspose.pdf.ai/aiclientbase/pollforcompletionasync/)(*Func<Task<T0>>, Func<T0, bool>, Nullable<CancellationToken>*) | *(Inherited from AIClientBase)* |

## Fields

| Name | Description |
| --- | --- |
| [Disposed](../../aspose.pdf.ai/aiclientbase/disposed/) | *(Inherited from AIClientBase)* |
| [HttpClient](../../aspose.pdf.ai/aiclientbase/httpclient/) | *(Inherited from AIClientBase)* |

### See Also

* class [AIClientBase](../aiclientbase/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

