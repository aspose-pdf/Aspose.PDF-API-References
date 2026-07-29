---
title: "IOpenAIClient.DeleteAssistantAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IOpenAIClient. تحذف مساعدًا موجودًا بشكل غير متزامن"
type: docs
weight: 130
url: /ar/net/aspose.pdf.ai/iopenaiclient/deleteassistantasync/
---
## IOpenAIClient.DeleteAssistantAsync method

يحذف مساعدًا موجودًا بشكل غير متزامن.

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| assistantId | String | معرّف المساعد المراد حذفه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على حالة عملية الحذف.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرف المساعد null أو فارغ. |

### انظر أيضًا

* class [DeleteStatusResponse](../../deletestatusresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


