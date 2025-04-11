---
title: IOpenAIClient.GetRunStepsAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تسترجع قائمة بالخطوات لتشغيل محدد ضمن سلسلة بشكل غير متزامن
type: docs
weight: 260
url: /ar/net/aspose.pdf.ai/iopenaiclient/getrunstepsasync/
---
## IOpenAIClient.GetRunStepsAsync method

تسترجع قائمة بالخطوات لتشغيل محدد ضمن سلسلة بشكل غير متزامن.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| threadId | String | معرف السلسلة التي تحتوي على التشغيل. |
| runId | String | معرف التشغيل لاسترجاع الخطوات منه. |
| queryParameters | RunStepListQueryParameters | معلمات استعلام اختيارية لتصفية قائمة خطوات التشغيل. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### Return Value

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على قائمة خطوات التشغيل.

### Exceptions

| exception | condition |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحها عندما يكون معرف السلسلة فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحها عندما يكون معرف التشغيل فارغًا أو null. |

### See Also

* class [RunStepListResponse](../../runsteplistresponse/)
* class [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)