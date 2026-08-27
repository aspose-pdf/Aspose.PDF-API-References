---
title: "OpenAIClient.GetFilesAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OpenAIClient. تسترجع قائمة بالملفات بشكل غير متزامن بناءً على الغرض المحدد"
type: docs
weight: 230
url: /ar/net/aspose.pdf.ai/openaiclient/getfilesasync/
---
## OpenAIClient.GetFilesAsync method

يسترجع قائمة بالملفات بشكل غير متزامن بناءً على الغرض المحدد.

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| purpose | String | اختياري. الغرض من الملفات التي سيتم استرجاعها. إذا كان null، يتم استرجاع الملفات لجميع الأغراض. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على قائمة بالملفات.

### انظر أيضًا

* class [FileListResponse](../../filelistresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


