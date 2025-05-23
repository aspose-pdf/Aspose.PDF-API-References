---
title: OpenAIClient.CreateThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تنشئ خيطًا جديدًا بشكل غير متزامن
type: docs
weight: 70
url: /ar/net/aspose.pdf.ai/openaiclient/createthreadasync/
---
## طريقة OpenAIClient.CreateThreadAsync

تنشئ خيطًا جديدًا بشكل غير متزامن.

```csharp
public Task<ThreadResponse> CreateThreadAsync(ThreadCreateRequest threadCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadCreateRequest | ThreadCreateRequest | كائن الطلب الذي يحتوي على تفاصيل إنشاء الخيط. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إنشاء الخيط.

### انظر أيضًا

* class [ThreadResponse](../../threadresponse/)
* class [ThreadCreateRequest](../../threadcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)