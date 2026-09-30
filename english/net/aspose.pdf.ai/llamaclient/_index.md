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
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## Properties

| Name | Description |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Gets or sets the backoff delay in seconds. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Gets or sets the maximum number of HTTP request retries. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Gets or sets the polling interval in seconds. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Gets or sets the polling timeout in seconds. |

## Methods

| Name | Description |
| --- | --- |
| [CreateCompletionAsync](./createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Creates a chat completion request in the Llama service. |
| static [CreateWithApiKey](./createwithapikey/)(string) | Creates a new instance of `Builder` with the provided API key. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Disposes of the resources used by the [`AIClientBase`](../../aspose.pdf.ai/aiclientbase/). |
| [GetSummaryCopilot](./getsummarycopilot/)(ISummaryCopilotOptions<LlamaSummaryCopilotOptions>) | Gets an instance of [`ISummaryCopilot`](../../aspose.pdf.ai/isummarycopilot/) with the specified options. |

## Other Members

| Name | Description |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | Builder class for creating an instance of [`LlamaClient`](../../aspose.pdf.ai/llamaclient/). |

### See Also

* class [AIClientBase](../aiclientbase/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)

