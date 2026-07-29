---
title: "OpenAIClient.GetVectorStoreFileAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OpenAIClient. تسترجع تفاصيل ملف محدد داخل مخزن المتجهات بشكل غير متزامن"
type: docs
weight: 350
url: /ar/net/aspose.pdf.ai/openaiclient/getvectorstorefileasync/
---
## OpenAIClient.GetVectorStoreFileAsync method

يسترجع تفاصيل ملف محدد داخل مخزن متجه بشكل غير متزامن.

```csharp
public Task<VectorStoreFileResponse> GetVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| vectorStoreId | String | معرّف مخزن المتجهات الذي يحتوي على الملف. |
| fileId | String | معرّف الملف المراد استرجاعه. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على تفاصيل الملف.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف مخزن المتجهات فارغًا أو null. |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرف الملف فارغًا أو null. |

### انظر أيضًا

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


