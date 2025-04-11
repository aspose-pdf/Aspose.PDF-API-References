---
title: OpenAIClient.GetFileAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تسترجع تفاصيل ملف معين بشكل غير متزامن
type: docs
weight: 220
url: /ar/net/aspose.pdf.ai/openaiclient/getfileasync/
---
## طريقة OpenAIClient.GetFileAsync

تسترجع تفاصيل ملف معين بشكل غير متزامن.

```csharp
public Task<FileResponse> GetFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fileId | String | معرف الملف الذي سيتم استرجاعه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على تفاصيل الملف.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم رميها عندما يكون معرف الملف فارغًا أو غير موجود. |

### انظر أيضًا

* class [FileResponse](../../fileresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)