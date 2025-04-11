---
title: OpenAIClient.GetThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تسترجع تفاصيل رسالة معينة ضمن سلسلة بشكل غير متزامن
type: docs
weight: 310
url: /ar/net/aspose.pdf.ai/openaiclient/getthreadmessageasync/
---
## طريقة OpenAIClient.GetThreadMessageAsync

تسترجع تفاصيل رسالة معينة ضمن سلسلة بشكل غير متزامن.

```csharp
public Task<ThreadMessageResponse> GetThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | سلسلة | معرف السلسلة التي تحتوي على الرسالة. |
| threadMessageId | سلسلة | معرف الرسالة التي سيتم استرجاعها. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على تفاصيل رسالة السلسلة.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف السلسلة فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف رسالة السلسلة فارغًا أو null. |

### انظر أيضًا

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)