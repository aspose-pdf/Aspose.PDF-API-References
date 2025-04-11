---
title: OpenAIClient.GetFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تسترجع قائمة من الملفات بشكل غير متزامن بناءً على الغرض المحدد
type: docs
weight: 230
url: /ar/net/aspose.pdf.ai/openaiclient/getfilesasync/
---
## طريقة OpenAIClient.GetFilesAsync

تسترجع قائمة من الملفات بشكل غير متزامن بناءً على الغرض المحدد.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| purpose | String | اختياري. الغرض من الملفات التي يجب استرجاعها. إذا كان null، يتم استرجاع الملفات لجميع الأغراض. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على قائمة من الملفات.

### انظر أيضًا

* class [FileListResponse](../../filelistresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)