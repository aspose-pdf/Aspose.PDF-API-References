---
title: "OpenAIClient.GetRunAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OpenAIClient. تسترجع تفاصيل تشغيل محدد داخل سلسلة بشكل غير متزامن"
type: docs
weight: 260
url: /ar/net/aspose.pdf.ai/openaiclient/getrunasync/
---
## OpenAIClient.GetRunAsync method

يسترجع تفاصيل تشغيل محدد داخل خيط بشكل غير متزامن.

```csharp
public Task<RunResponse> GetRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرّف الخيط الذي يحتوي على التشغيل. |
| runId | String | معرّف التشغيل المراد استرجاعه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على تفاصيل التشغيل.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف الخيط فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم رمي الاستثناء عندما يكون معرّف التشغيل null أو فارغ. |

### انظر أيضًا

* class [RunResponse](../../runresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


