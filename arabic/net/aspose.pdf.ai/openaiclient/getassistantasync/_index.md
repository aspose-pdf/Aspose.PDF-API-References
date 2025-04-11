---
title: OpenAIClient.GetAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تسترجع تفاصيل مساعد معين بشكل غير متزامن
type: docs
weight: 190
url: /ar/net/aspose.pdf.ai/openaiclient/getassistantasync/
---
## طريقة OpenAIClient.GetAssistantAsync

تسترجع تفاصيل مساعد معين بشكل غير متزامن.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| assistantId | String | معرف المساعد الذي سيتم استرجاعه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على تفاصيل المساعد.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف المساعد فارغًا أو null. |

### انظر أيضًا

* class [AssistantResponse](../../assistantresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)