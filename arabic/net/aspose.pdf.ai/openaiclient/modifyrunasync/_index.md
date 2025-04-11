---
title: OpenAIClient.ModifyRunAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تعدل عملية موجودة ضمن خيط بشكل غير متزامن
type: docs
weight: 400
url: /ar/net/aspose.pdf.ai/openaiclient/modifyrunasync/
---
## طريقة OpenAIClient.ModifyRunAsync

تعدل عملية موجودة ضمن خيط بشكل غير متزامن.

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرف الخيط الذي يحتوي على العملية. |
| runId | String | معرف العملية التي سيتم تعديلها. |
| assistantModifyRequest | RunModifyRequest | تفاصيل الطلب لتعديل العملية. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من تعديل العملية.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف الخيط فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف العملية فارغًا أو null. |

### انظر أيضًا

* class [RunResponse](../../runresponse/)
* class [RunModifyRequest](../../runmodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)