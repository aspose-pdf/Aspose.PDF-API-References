---
title: "OpenAIClient.RunAndGetAssistantResponseAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة OpenAIClient. تشغّل المساعد باستخدام معرف السلسلة المحدد وطلب إنشاء التشغيل وتسترجع استجابة المساعد بشكل غير متزامن"
type: docs
weight: 450
url: /ar/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/
---
## OpenAIClient.RunAndGetAssistantResponseAsync method

يشغّل المساعد باستخدام معرف الخيط المحدد وطلب إنشاء التشغيل، ويحصل بشكل غير متزامن على استجابة المساعد.

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| threadId | String | معرّف السلسلة. |
| runCreateRequest | RunCreateRequest | طلب إنشاء التشغيل. |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة مع سلسلة استجابة المساعد.

### انظر أيضًا

* class [RunCreateRequest](../../runcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


