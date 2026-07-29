---
title: "OpenAIClient.GetRunsAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OpenAIClient. تسترجع قائمة من تشغيلات لخيط محدد بشكل غير متزامن"
type: docs
weight: 270
url: /ar/net/aspose.pdf.ai/openaiclient/getrunsasync/
---
## OpenAIClient.GetRunsAsync method

يسترجع قائمة بالتشغيلات لخيط محدد بشكل غير متزامن.

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرّف الخيط لاسترجاع تشغيلات منه. |
| queryParameters | RunListQueryParameters | معلمات استعلام اختيارية لتصفية قائمة التشغيلات. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. نتيجة المهمة تحتوي على قائمة من التشغيلات.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف الخيط فارغًا أو null. |

### انظر أيضًا

* class [RunListResponse](../../runlistresponse/)
* class [RunListQueryParameters](../../runlistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


