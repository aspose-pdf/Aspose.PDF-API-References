---
title: "IOpenAIClient.UploadFileAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IOpenAIClient. ترفع ملفًا بشكل غير متزامن إلى خادم OpenAI"
type: docs
weight: 420
url: /ar/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/
---
## IOpenAIClient.UploadFileAsync method

يرفع ملفًا بشكل غير متزامن إلى خادم OpenAI.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| purpose | String | الغرض من رفع الملف، عادةً ما يصف كيف سيُستخدم الملف. |
| fileName | String | اسم الملف المراد رفعه. |
| fileBytes | Byte[] | مصفوفة البايتات التي تحتوي على بيانات الملف. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على الاستجابة من رفع الملف.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون غرض الملف فارغًا أو غير مُحدد. |
| [AIClientException](../../aiclientexception/) | يتم رميه عندما يكون اسم الملف فارغًا أو غير محدد. |

### انظر أيضًا

* class [FileResponse](../../fileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


