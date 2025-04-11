---
title: Class LlamaClient
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.LlamaClient sınıfı. Llama API'si ile etkileşimde bulunmak için bir istemciyi temsil eder.
type: docs
weight: 700
url: /tr/net/aspose.pdf.ai/llamaclient/
---
## LlamaClient sınıfı

Llama API'si ile etkileşimde bulunmak için bir istemciyi temsil eder.

Llama API'si ile etkileşimde bulunmak için bir istemciyi temsil eder.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Geri çekilme gecikmesini saniye cinsinden alır veya ayarlar. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | HTTP isteklerinin maksimum yeniden deneme sayısını alır veya ayarlar. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Anket aralığını saniye cinsinden alır veya ayarlar. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Anket zaman aşımını saniye cinsinden alır veya ayarlar. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | Llama hizmetinde bir sohbet tamamlama isteği oluşturur. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | [`AIClientBase`](../aiclientbase/) tarafından kullanılan kaynakları serbest bırakır. |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | Belirtilen seçeneklerle [`ISummaryCopilot`](../isummarycopilot/) örneğini alır. |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | Sağlanan API anahtarı ile [`Builder`](../llamaclient.builder/) sınıfının yeni bir örneğini oluşturur. |

## Diğer Üyeler

| İsim | Açıklama |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | `LlamaClient` örneği oluşturmak için Builder sınıfı. |

### Ayrıca Bakınız

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)