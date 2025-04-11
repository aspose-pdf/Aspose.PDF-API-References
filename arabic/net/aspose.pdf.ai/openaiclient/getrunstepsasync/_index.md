---
title: OpenAIClient.GetRunStepsAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تسترجع قائمة بالخطوات لعملية معينة ضمن سلسلة بشكل غير متزامن
type: docs
weight: 280
url: /ar/net/aspose.pdf.ai/openaiclient/getrunstepsasync/
---
## طريقة OpenAIClient.GetRunStepsAsync

تسترجع قائمة بالخطوات لعملية معينة ضمن سلسلة بشكل غير متزامن.

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرف السلسلة التي تحتوي على العملية. |
| runId | String | معرف العملية لاسترجاع الخطوات منها. |
| queryParameters | RunStepListQueryParameters | معلمات استعلام اختيارية لتصفية قائمة خطوات العملية. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على قائمة خطوات العملية.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف السلسلة فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف العملية فارغًا أو null. |

### انظر أيضًا

* class [RunStepListResponse](../../runsteplistresponse/)
* class [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)