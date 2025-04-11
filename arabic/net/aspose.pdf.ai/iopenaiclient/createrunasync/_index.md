---
title: IOpenAIClient.CreateRunAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تنشئ عملية ضمن خيط محدد بشكل غير متزامن
type: docs
weight: 50
url: /ar/net/aspose.pdf.ai/iopenaiclient/createrunasync/
---
## طريقة IOpenAIClient.CreateRunAsync

تنشئ عملية ضمن خيط محدد بشكل غير متزامن.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرف الخيط الذي ستُنشأ فيه العملية. |
| runCreateRequest | RunCreateRequest | تفاصيل الطلب لإنشاء العملية. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إنشاء العملية.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرف الخيط فارغًا أو غير موجود. |

### انظر أيضًا

* class [RunResponse](../../runresponse/)
* class [RunCreateRequest](../../runcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)