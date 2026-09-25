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
| [CreateCompletionAsync](./createcompletionasync/)(*LlamaChatCompletionRequest, Nullable<CancellationToken>*) | Creates a chat completion request in the Llama service. |
| [CreateWithApiKey](./createwithapikey/)(*string*) | Creates a new instance of `Builder` with the provided API key. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/) | Disposes of the resources used by the [`AIClientBase`](../../aspose.pdf.ai/aiclientbase/). *(Inherited from AIClientBase)* |
| [GetSummaryCopilot](./getsummarycopilot/)(*ISummaryCopilotOptions<LlamaSummaryCopilotOptions>*) | Gets an instance of [`ISummaryCopilot`](../../aspose.pdf.ai/isummarycopilot/) with the specified options. |

### See Also

* class [AIClientBase](../aiclientbase/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

