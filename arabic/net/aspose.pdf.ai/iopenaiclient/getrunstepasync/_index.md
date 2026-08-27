---
title: "IOpenAIClient.GetRunStepAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IOpenAIClient. تسترجع تفاصيل خطوة محددة داخل تشغيل بشكل غير متزامن"
type: docs
weight: 250
url: /ar/net/aspose.pdf.ai/iopenaiclient/getrunstepasync/
---
## IOpenAIClient.GetRunStepAsync method

يسترجع تفاصيل خطوة محددة داخل تشغيل بشكل غير متزامن.

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرّف الخيط الذي يحتوي على التشغيل. |
| runId | String | معرّف التشغيل الذي يحتوي على الخطوة. |
| runStepId | String | معرّف خطوة التشغيل للاسترجاع. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. نتيجة المهمة تحتوي على تفاصيل خطوة التشغيل.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف الخيط فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم رمي الاستثناء عندما يكون معرّف التشغيل null أو فارغ. |
| [AIClientException](../../aiclientexception/) | يتم رمي الاستثناء عندما يكون معرّف خطوة التشغيل null أو فارغ. |

### انظر أيضًا

* class [RunStepResponse](../../runstepresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


