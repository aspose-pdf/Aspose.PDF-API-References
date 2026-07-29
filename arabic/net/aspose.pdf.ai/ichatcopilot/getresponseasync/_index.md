---
title: "IChatCopilot.GetResponseAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة IChatCopilot. تحصل بشكل غير متزامن على استجابة للرسالة المعطاة"
type: docs
weight: 20
url: /ar/net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

يحصل بشكل غير متزامن على استجابة للرسالة المعطاة.

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| رسالة | String | رسالة الإدخال التي يُطلب استجابة لها. |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة مع سلسلة الاستجابة.

### انظر أيضًا

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## GetResponseAsync(List&lt;string&gt;, CancellationToken?) {#getresponseasync}

يحصل بشكل غير متزامن على استجابة للقائمة المعطاة من الرسائل.

```csharp
public Task<string> GetResponseAsync(List<string> messages, 
    CancellationToken? cancellationToken = default)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| رسائل | List`1 | قائمة رسائل الإدخال التي يُطلب استجابات لها. |
| cancellationToken | Nullable`1 | رمز الإلغاء (اختياري). |

### قيمة الإرجاع

مهمة تمثل العملية غير المتزامنة مع سلسلة الاستجابة.

### انظر أيضًا

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


