---
title: IOpenAIClient.GetAssistantsAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تسترجع قائمة بالمساعدين بشكل غير متزامن
type: docs
weight: 200
url: /ar/net/aspose.pdf.ai/iopenaiclient/getassistantsasync/
---
## طريقة IOpenAIClient.GetAssistantsAsync

تسترجع قائمة بالمساعدين بشكل غير متزامن.

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | معلمات استعلام اختيارية لتصفية قائمة المساعدين. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على قائمة بالمساعدين.

### انظر أيضًا

* class [AssistantListResponse](../../assistantlistresponse/)
* class [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)