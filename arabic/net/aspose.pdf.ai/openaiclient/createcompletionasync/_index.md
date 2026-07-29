---
title: "OpenAIClient.CreateCompletionAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OpenAIClient. تنشئ إكمالًا جديدًا بشكل غير متزامن"
type: docs
weight: 40
url: /ar/net/aspose.pdf.ai/openaiclient/createcompletionasync/
---
## OpenAIClient.CreateCompletionAsync method

ينشئ إكمالًا جديدًا بشكل غير متزامن.

```csharp
public Task<CompletionResponse> CreateCompletionAsync(
    CompletionCreateRequest completionCreateRequest, CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| completionCreateRequest | CompletionCreateRequest | كائن الطلب الذي يحتوي على تفاصيل إنشاء الإكمال. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إنشاء الإكمال.

### انظر أيضًا

* class [CompletionResponse](../../completionresponse/)
* class [CompletionCreateRequest](../../completioncreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


