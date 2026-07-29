---
title: "IOpenAIClient.WaitForAssistantMessageAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IOpenAIClient. تنتظر الرسالة الأولى من المساعد داخل خيط بشكل غير متزامن"
type: docs
weight: 430
url: /ar/net/aspose.pdf.ai/iopenaiclient/waitforassistantmessageasync/
---
## IOpenAIClient.WaitForAssistantMessageAsync method

ينتظر الرسالة الأولى من المساعد داخل خيط بشكل غير متزامن.

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرّف الخيط لمراقبة الرسالة الأولى من المساعد. |
| queryParameters | ThreadMessageListQueryParameters | معلمات استعلام اختيارية لتصفية قائمة الرسائل. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. نتيجة المهمة تحتوي على الرسالة الأولى من المساعد في الخيط.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف الخيط فارغًا أو null. |

### انظر أيضًا

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


