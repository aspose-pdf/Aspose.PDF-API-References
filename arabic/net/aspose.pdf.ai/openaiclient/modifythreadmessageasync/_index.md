---
title: OpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تعدل رسالة موجودة ضمن سلسلة بشكل غير متزامن
type: docs
weight: 420
url: /ar/net/aspose.pdf.ai/openaiclient/modifythreadmessageasync/
---
## طريقة OpenAIClient.ModifyThreadMessageAsync

تعدل رسالة موجودة ضمن سلسلة بشكل غير متزامن.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرف السلسلة التي تحتوي على الرسالة لتعديلها. |
| threadMessageId | String | معرف الرسالة لتعديلها. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | تفاصيل الطلب لتعديل الرسالة. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من تعديل الرسالة.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف السلسلة فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف رسالة السلسلة فارغًا أو null. |

### انظر أيضًا

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)