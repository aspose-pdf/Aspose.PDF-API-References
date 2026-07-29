---
title: "类 LlamaClient"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.LlamaClient 类。表示用于与 Llama API 交互的客户端。"
type: docs
weight: 750
url: /zh/net/aspose.pdf.ai/llamaclient/
---
## LlamaClient class

表示用于与 Llama API 交互的客户端。

表示用于与 Llama API 交互的客户端。

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | 获取或设置以秒为单位的退避延迟。 |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | 获取或设置 HTTP 请求重试的最大次数。 |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | 获取或设置以秒为单位的轮询间隔。 |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | 获取或设置以秒为单位的轮询超时。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | 在 Llama 服务中创建聊天完成请求。 |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | 释放由 [`AIClientBase`](../aiclientbase/) 使用的资源。 |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | 获取具有指定选项的[`ISummaryCopilot`](../isummarycopilot/)实例。 |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | 使用提供的 API 密钥创建 [`Builder`](../llamaclient.builder/) 的新实例。 |

## 其他成员

| 名称 | 描述 |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | 用于创建 `LlamaClient` 实例的 Builder 类。 |

### 另请参见

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


