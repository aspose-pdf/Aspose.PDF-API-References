---
title: OpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تقوم بتحميل ملف بشكل غير متزامن إلى خادم OpenAI
type: docs
weight: 450
url: /ar/net/aspose.pdf.ai/openaiclient/uploadfileasync/
---
## طريقة OpenAIClient.UploadFileAsync

تقوم بتحميل ملف بشكل غير متزامن إلى خادم OpenAI.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| purpose | String | الغرض من تحميل الملف، وعادة ما يصف كيفية استخدام الملف. |
| fileName | String | اسم الملف المراد تحميله. |
| fileBytes | Byte[] | مصفوفة البايت التي تحتوي على بيانات الملف. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من تحميل الملف.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون غرض الملف فارغًا أو غير موجود. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون اسم الملف فارغًا أو غير موجود. |

### انظر أيضًا

* class [FileResponse](../../fileresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)