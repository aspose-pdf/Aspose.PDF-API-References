---
title: Class LlamaClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaClient class. Represents a client for interacting with the Llama API
type: docs
weight: 750
url: /net/aspose.pdf.ai/llamaclient/
---
## LlamaClient class

Represents a client for interacting with the Llama API.

Represents a client for interacting with the Llama API.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## Properties

| Name | Description |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Gets or sets the backoff delay in seconds. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Gets or sets the maximum number of HTTP request retries. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Gets or sets the polling interval in seconds. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Gets or sets the polling timeout in seconds. |

## Methods

| Name | Description |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Creates a chat completion request in the Llama service. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Disposes of the resources used by the [`AIClientBase`](../aiclientbase/). |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Gets an instance of [`ISummaryCopilot`](../isummarycopilot/) with the specified options. |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | Creates a new instance of [`Builder`](../llamaclient.builder/) with the provided API key. |

## Other Members

| Name | Description |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | Builder class for creating an instance of `LlamaClient`. |

### See Also

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


