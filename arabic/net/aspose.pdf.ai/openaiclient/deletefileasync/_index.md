---
title: "OpenAIClient.DeleteFileAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OpenAIClient. تحذف ملفًا محددًا بشكل غير متزامن"
type: docs
weight: 140
url: /ar/net/aspose.pdf.ai/openaiclient/deletefileasync/
---
## OpenAIClient.DeleteFileAsync method

يحذف ملفًا محددًا بشكل غير متزامن.

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileId | String | معرّف الملف المراد حذفه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على حالة عملية الحذف.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرف الملف فارغًا أو null. |

### انظر أيضًا

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


