---
title: OpenAIClient.DeleteThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تحذف رسالة ضمن سلسلة بشكل غير متزامن
type: docs
weight: 160
url: /ar/net/aspose.pdf.ai/openaiclient/deletethreadmessageasync/
---
## طريقة OpenAIClient.DeleteThreadMessageAsync

تحذف رسالة ضمن سلسلة بشكل غير متزامن.

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | سلسلة | معرف السلسلة التي تحتوي على الرسالة المراد حذفها. |
| threadMessageId | سلسلة | معرف الرسالة المراد حذفها. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على حالة عملية الحذف.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف السلسلة فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف رسالة السلسلة فارغًا أو null. |

### انظر أيضًا

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)