---
title: OpenAIClient.GetRunStepAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تسترجع تفاصيل خطوة معينة ضمن عملية تشغيل بشكل غير متزامن
type: docs
weight: 270
url: /ar/net/aspose.pdf.ai/openaiclient/getrunstepasync/
---
## طريقة OpenAIClient.GetRunStepAsync

تسترجع تفاصيل خطوة معينة ضمن عملية تشغيل بشكل غير متزامن.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرف الخيط الذي يحتوي على عملية التشغيل. |
| runId | String | معرف عملية التشغيل التي تحتوي على الخطوة. |
| runStepId | String | معرف خطوة التشغيل التي سيتم استرجاعها. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على تفاصيل خطوة التشغيل.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف الخيط فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف عملية التشغيل فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف خطوة التشغيل فارغًا أو null. |

### انظر أيضًا

* class [RunStepResponse](../../runstepresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)