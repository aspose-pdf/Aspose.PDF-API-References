---
title: "IOpenAIClient.GetThreadMessagesAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IOpenAIClient. تسترجع قائمة الرسائل لخيط محدد بشكل غير متزامن"
type: docs
weight: 290
url: /ar/net/aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/
---
## IOpenAIClient.GetThreadMessagesAsync method

يسترجع قائمة بالرسائل لخيط محدد بشكل غير متزامن.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرّف الخيط لاسترجاع الرسائل منه. |
| queryParameters | ThreadMessageListQueryParameters | معلمات استعلام اختيارية لتصفية قائمة الرسائل. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على قائمة من رسائل الخيط.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف الخيط فارغًا أو null. |

### انظر أيضًا

* class [ThreadMessageListResponse](../../threadmessagelistresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


