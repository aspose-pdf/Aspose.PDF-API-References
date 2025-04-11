---
title: Class LlamaClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaClient class. 代表与 Llama API 交互的客户端
type: docs
weight: 700
url: /zh/net/aspose.pdf.ai/llamaclient/
---
## LlamaClient class

代表与 Llama API 交互的客户端。

代表与 Llama API 交互的客户端。

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## Properties

| Name | Description |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | 获取或设置回退延迟（以秒为单位）。 |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | 获取或设置最大 HTTP 请求重试次数。 |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | 获取或设置轮询间隔（以秒为单位）。 |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | 获取或设置轮询超时（以秒为单位）。 |

## Methods

| Name | Description |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | 在 Llama 服务中创建聊天完成请求。 |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | 释放 [`AIClientBase`](../aiclientbase/) 使用的资源。 |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | 获取具有指定选项的 [`ISummaryCopilot`](../isummarycopilot/) 实例。 |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | 使用提供的 API 密钥创建 [`Builder`](../llamaclient.builder/) 的新实例。 |

## Other Members

| Name | Description |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | 用于创建 `LlamaClient` 实例的 Builder 类。 |

### See Also

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)