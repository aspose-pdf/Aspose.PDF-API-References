---
title: IOpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة IOpenAIClient. تقوم بتشغيل المساعد باستخدام threadId المحدد و runCreateRequest وتحصل على استجابة المساعد بشكل غير متزامن
type: docs
weight: 410
url: /ar/net/aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/
---
## طريقة IOpenAIClient.RunAndGetAssistantResponseAsync

تقوم بتشغيل المساعد باستخدام threadId المحدد و runCreateRequest، وتحصل على استجابة المساعد بشكل غير متزامن.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | سلسلة | معرف الخيط. |
| runCreateRequest | RunCreateRequest | طلب إنشاء التشغيل. |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة مع سلسلة استجابة المساعد.

### انظر أيضًا

* class [RunCreateRequest](../../runcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)