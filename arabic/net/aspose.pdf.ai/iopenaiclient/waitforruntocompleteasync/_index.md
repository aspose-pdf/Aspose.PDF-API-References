---
title: "IOpenAIClient.WaitForRunToCompleteAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IOpenAIClient. تنتظر تشغيلًا ليكتمل داخل خيط بشكل غير متزامن"
type: docs
weight: 440
url: /ar/net/aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/
---
## IOpenAIClient.WaitForRunToCompleteAsync method

ينتظر إكمال تشغيل داخل خيط بشكل غير متزامن.

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرّف الخيط الذي يحتوي على التشغيل. |
| runId | String | معرّف التشغيل لمراقبته حتى الانتهاء. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على الحالة النهائية للتشغيل.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف الخيط فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم رمي الاستثناء عندما يكون معرّف التشغيل null أو فارغ. |

### انظر أيضًا

* class [RunResponse](../../runresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


