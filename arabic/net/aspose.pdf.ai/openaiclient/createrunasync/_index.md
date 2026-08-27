---
title: "OpenAIClient.CreateRunAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OpenAIClient. تنشئ تشغيلًا داخل خيط محدد بشكل غير متزامن"
type: docs
weight: 50
url: /ar/net/aspose.pdf.ai/openaiclient/createrunasync/
---
## OpenAIClient.CreateRunAsync method

ينشئ تشغيلًا داخل خيط محدد بشكل غير متزامن.

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرّف الخيط حيث سيتم إنشاء التشغيل. |
| runCreateRequest | RunCreateRequest | تفاصيل الطلب لإنشاء التشغيل. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. نتيجة المهمة تحتوي على الاستجابة من إنشاء التشغيل.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [AIClientException](../../aiclientexception/) | يُرمى عندما يكون معرّف الخيط فارغًا أو null. |

### انظر أيضًا

* class [RunResponse](../../runresponse/)
* class [RunCreateRequest](../../runcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


