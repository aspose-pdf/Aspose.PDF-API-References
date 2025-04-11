---
title: OpenAIClient.WaitForRunToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تنتظر حتى تكتمل عملية التشغيل داخل خيط بشكل غير متزامن
type: docs
weight: 470
url: /ar/net/aspose.pdf.ai/openaiclient/waitforruntocompleteasync/
---
## طريقة OpenAIClient.WaitForRunToCompleteAsync

تنتظر حتى تكتمل عملية التشغيل داخل خيط بشكل غير متزامن.

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرف الخيط الذي يحتوي على عملية التشغيل. |
| runId | String | معرف عملية التشغيل لمراقبتها حتى الاكتمال. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الحالة النهائية لعملية التشغيل.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف الخيط فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف عملية التشغيل فارغًا أو null. |

### انظر أيضًا

* class [RunResponse](../../runresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)