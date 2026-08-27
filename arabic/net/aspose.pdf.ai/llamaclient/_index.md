---
title: "الفئة LlamaClient"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "فئة Aspose.Pdf.AI.LlamaClient. تمثل عميلًا للتفاعل مع Llama API"
type: docs
weight: 750
url: /ar/net/aspose.pdf.ai/llamaclient/
---
## LlamaClient class

يمثل عميلًا للتفاعل مع واجهة برمجة تطبيقات Llama.

يمثل عميلًا للتفاعل مع واجهة برمجة تطبيقات Llama.

```csharp
public class LlamaClient : AIClientBase, ILlamaClient, ISummaryClient<LlamaSummaryCopilotOptions>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | يحصل أو يعيّن تأخير التراجع بالثواني. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | يحصل أو يعيّن الحد الأقصى لعدد محاولات إعادة طلب HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | يحصل أو يعيّن فترة الاستطلاع بالثواني. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | يحصل أو يعيّن مهلة الاستطلاع بالثواني. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateCompletionAsync](../../aspose.pdf.ai/llamaclient/createcompletionasync/)(LlamaChatCompletionRequest, CancellationToken?) | ينشئ طلب إكمال محادثة في خدمة Llama. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | يتخلص من الموارد المستخدمة بواسطة [`AIClientBase`](../aiclientbase/). |
| [GetSummaryCopilot](../../aspose.pdf.ai/llamaclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;LlamaSummaryCopilotOptions&gt;) | يحصل على نسخة من [`ISummaryCopilot`](../isummarycopilot/) مع الخيارات المحددة. |
| static [CreateWithApiKey](../../aspose.pdf.ai/llamaclient/createwithapikey/)(string) | ينشئ مثيلًا جديدًا من [`Builder`](../llamaclient.builder/) باستخدام مفتاح API المقدم. |

## الأعضاء الآخرين

| الاسم | الوصف |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/llamaclient.builder) | فئة Builder لإنشاء مثيل من `LlamaClient`. |

### انظر أيضًا

* class [AIClientBase](../aiclientbase/)
* interface [ILlamaClient](../illamaclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [LlamaSummaryCopilotOptions](../llamasummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


