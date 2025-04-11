---
title: Class LlamaClient
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.AI.LlamaClient. تمثل عميلًا للتفاعل مع واجهة برمجة تطبيقات Llama
type: docs
weight: 700
url: /ar/net/aspose.pdf.ai/llamaclient/
---
## LlamaClient class

تمثل عميلًا للتفاعل مع واجهة برمجة تطبيقات Llama.

تمثل عميلًا للتفاعل مع واجهة برمجة تطبيقات Llama.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## Properties

| Name | Description |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | يحصل على أو يحدد تأخير التراجع بالثواني. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | يحصل على أو يحدد الحد الأقصى لعدد محاولات إعادة طلب HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | يحصل على أو يحدد فترة الاستطلاع بالثواني. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | يحصل على أو يحدد مهلة الاستطلاع بالثواني. |

## Methods

| Name | Description |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | ينشئ طلب إكمال دردشة في خدمة Llama. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | يتخلص من الموارد المستخدمة بواسطة [`AIClientBase`](../aiclientbase/). |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | يحصل على مثيل من [`ISummaryCopilot`](../isummarycopilot/) مع الخيارات المحددة. |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | ينشئ مثيلًا جديدًا من [`Builder`](../llamaclient.builder/) باستخدام مفتاح API المقدم. |

## Other Members

| Name | Description |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | فئة Builder لإنشاء مثيل من `LlamaClient`. |

### See Also

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)