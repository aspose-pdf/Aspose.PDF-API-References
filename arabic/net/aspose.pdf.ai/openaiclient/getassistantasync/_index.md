---
title: "OpenAIClient.GetAssistantAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OpenAIClient. تسترجع تفاصيل مساعد محدد بشكل غير متزامن"
type: docs
weight: 190
url: /ar/net/aspose.pdf.ai/openaiclient/getassistantasync/
---
## OpenAIClient.GetAssistantAsync method

يسترجع تفاصيل مساعد محدد بشكل غير متزامن.

```csharp
public Task<AssistantResponse> GetAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| assistantId | String | معرّف المساعد المراد استرجاعه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على تفاصيل المساعد.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرف المساعد null أو فارغ. |

### انظر أيضًا

* class [AssistantResponse](../../assistantresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


