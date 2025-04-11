---
title: OpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة OpenAIClient. تقوم بتشغيل المساعد مع threadId المحدد و runCreateRequest وتحصل على استجابة المساعد بشكل غير متزامن
type: docs
weight: 440
url: /ar/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/
---
## طريقة OpenAIClient.RunAndGetAssistantResponseAsync

تقوم بتشغيل المساعد مع threadId المحدد و runCreateRequest، وتحصل على استجابة المساعد بشكل غير متزامن.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرف الخيط. |
| runCreateRequest | RunCreateRequest | طلب إنشاء التشغيل. |
| cancellationToken | Nullable`1 | رمز إلغاء (اختياري). |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة مع سلسلة استجابة المساعد.

### انظر أيضًا

* class [RunCreateRequest](../../runcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)