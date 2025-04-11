---
title: OpenAIClient.GetRunsAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تسترجع قائمة بالتشغيلات لثريد محدد بشكل غير متزامن
type: docs
weight: 260
url: /ar/net/aspose.pdf.ai/openaiclient/getrunsasync/
---
## طريقة OpenAIClient.GetRunsAsync

تسترجع قائمة بالتشغيلات لثريد محدد بشكل غير متزامن.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرف الثريد لاسترجاع التشغيلات منه. |
| queryParameters | RunListQueryParameters | معلمات استعلام اختيارية لتصفية قائمة التشغيلات. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على قائمة بالتشغيلات.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون معرف الثريد فارغًا أو غير موجود. |

### انظر أيضًا

* class [RunListResponse](../../runlistresponse/)
* class [RunListQueryParameters](../../runlistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)