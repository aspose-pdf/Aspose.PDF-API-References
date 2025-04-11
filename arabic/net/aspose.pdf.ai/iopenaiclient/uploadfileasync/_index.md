---
title: IOpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. يقوم بتحميل ملف بشكل غير متزامن إلى خادم OpenAI
type: docs
weight: 420
url: /ar/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/
---
## طريقة IOpenAIClient.UploadFileAsync

يقوم بتحميل ملف بشكل غير متزامن إلى خادم OpenAI.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| purpose | String | الغرض من تحميل الملف، عادةً ما يصف كيفية استخدام الملف. |
| fileName | String | اسم الملف المراد تحميله. |
| fileBytes | Byte[] | مصفوفة البايت التي تحتوي على بيانات الملف. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من تحميل الملف.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون غرض الملف فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يتم طرحه عندما يكون اسم الملف فارغًا أو null. |

### انظر أيضًا

* class [FileResponse](../../fileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)