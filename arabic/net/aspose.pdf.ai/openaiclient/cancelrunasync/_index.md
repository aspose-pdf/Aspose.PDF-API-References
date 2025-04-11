---
title: OpenAIClient.CancelRunAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تلغي عملية قائمة موجودة داخل خيط بشكل غير متزامن
type: docs
weight: 10
url: /ar/net/aspose.pdf.ai/openaiclient/cancelrunasync/
---
## طريقة OpenAIClient.CancelRunAsync

تلغي عملية قائمة موجودة داخل خيط بشكل غير متزامن.

```csharp
public Task<RunResponse> CancelRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرف الخيط الذي يحتوي على العملية المراد إلغاؤها. |
| runId | String | معرف العملية المراد إلغاؤها. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إلغاء العملية.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف الخيط فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف العملية فارغًا أو null. |

### انظر أيضًا

* class [RunResponse](../../runresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)