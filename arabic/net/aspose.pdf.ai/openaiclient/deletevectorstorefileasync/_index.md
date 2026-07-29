---
title: "OpenAIClient.DeleteVectorStoreFileAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OpenAIClient. تحذف ملفًا داخل مخزن المتجهات بشكل غير متزامن"
type: docs
weight: 180
url: /ar/net/aspose.pdf.ai/openaiclient/deletevectorstorefileasync/
---
## OpenAIClient.DeleteVectorStoreFileAsync method

يحذف ملفًا داخل مخزن متجه بشكل غير متزامن.

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | String | معرّف مخزن المتجهات الذي يحتوي على الملف المراد حذفه. |
| fileId | String | معرّف الملف المراد حذفه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. يحتوي نتيجة المهمة على حالة عملية الحذف.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف مخزن المتجهات فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرف الملف فارغًا أو null. |

### انظر أيضًا

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


