---
title: IOpenAIClient.CreateThreadAndRunAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تنشئ خيطًا وتشغيلًا ضمنه بشكل غير متزامن
type: docs
weight: 60
url: /ar/net/aspose.pdf.ai/iopenaiclient/createthreadandrunasync/
---
## طريقة IOpenAIClient.CreateThreadAndRunAsync

تنشئ خيطًا وتشغيلًا ضمنه بشكل غير متزامن.

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | تفاصيل الطلب لإنشاء الخيط والتشغيل. |
| cancellationToken | Nullable`1 | رمز لإلغاء العملية. |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة. تحتوي نتيجة المهمة على الاستجابة من إنشاء الخيط والتشغيل.

### انظر أيضًا

* class [RunResponse](../../runresponse/)
* class [RunThreadCreateRequest](../../runthreadcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)