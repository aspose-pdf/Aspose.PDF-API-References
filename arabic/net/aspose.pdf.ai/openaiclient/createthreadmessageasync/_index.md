---
title: OpenAIClient.CreateThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تنشئ رسالة جديدة داخل سلسلة بشكل غير متزامن
type: docs
weight: 80
url: /ar/net/aspose.pdf.ai/openaiclient/createthreadmessageasync/
---
## طريقة OpenAIClient.CreateThreadMessageAsync

تنشئ رسالة جديدة داخل سلسلة بشكل غير متزامن.

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرف السلسلة حيث ستُنشأ الرسالة. |
| threadMessageRequest | ThreadMessageCreateRequest | تفاصيل الطلب لإنشاء الرسالة. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إنشاء الرسالة.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف السلسلة فارغًا أو غير موجود. |

### انظر أيضًا

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)