---
title: "IOpenAIClient.ModifyThreadMessageAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IOpenAIClient. تعدل رسالة موجودة داخل خيط بشكل غير متزامن"
type: docs
weight: 390
url: /ar/net/aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/
---
## IOpenAIClient.ModifyThreadMessageAsync method

يعدل رسالة موجودة داخل خيط بشكل غير متزامن.

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرّف السلسلة التي تحتوي على الرسالة التي سيتم تعديلها. |
| threadMessageId | String | معرّف الرسالة التي سيتم تعديلها. |
| threadMessageModifyRequest | ThreadMessageModifyRequest | تفاصيل الطلب لتعديل الرسالة. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على الاستجابة من تعديل الرسالة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف الخيط فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم رمي الاستثناء عندما يكون معرّف رسالة الخيط null أو فارغ. |

### انظر أيضًا

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


