---
title: IOpenAIClient.GetThreadMessagesAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تسترجع قائمة بالرسائل لثريد محدد بشكل غير متزامن
type: docs
weight: 290
url: /ar/net/aspose.pdf.ai/iopenaiclient/getthreadmessagesasync/
---
## طريقة IOpenAIClient.GetThreadMessagesAsync

تسترجع قائمة بالرسائل لثريد محدد بشكل غير متزامن.

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرف الثريد لاسترجاع الرسائل منه. |
| queryParameters | ThreadMessageListQueryParameters | معلمات استعلام اختيارية لتصفية قائمة الرسائل. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على قائمة برسائل الثريد.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف الثريد فارغًا أو null. |

### انظر أيضًا

* class [ThreadMessageListResponse](../../threadmessagelistresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)